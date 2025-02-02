-- biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

-- janela principal

local Window = Fluent:CreateWindow({
    Title = "Cael Hub" .. Fluent.Version,
    SubTitle = "by Cael",
    TabWidth = 160,
    Size = UDim2.fromOffset(580, 460),
    Acrylic = true, -- The blur may be detectable, setting this to false disables blur entirely
    Theme = "Dark",
    MinimizeKey = Enum.KeyCode.LeftControl -- Used when theres no MinimizeKeybind
})

-- Abas

local Tabs = {
    Descricao = Window:AddTab({ Title = "Descrição", Icon = "" }),
    Insta = Window:AddTab({ Title = "Instagram", Icon = "" }),
    Youtube = Window:AddTab({ Title = "YouTube", Icon = "" }),
    Insta da muie = Window:AddTab({ Title = "Instagram da minha mulher", Icon = "" }),
    Discord= Window:AddTab({ Title = "Discord", Icon = "" }),
    Main = Window:AddTab({ Title = "Inicio" }),
    Settings = Window:AddTab({ Title = "Configurações", Icon = "settings" })
}

-- notificacao

Fluent:Notify({ Title = "Notificação", Content = "script executado com sucesso " })
Fluent:Notify({ Title = "Diga-me no Instagram", Content = "Eai ja está conectado nas redes sociais do cael?" })
Fluent:Notify({ Title = "Instagram", Content = "Siga no Instagram (carlosdanielsilv708" })
Fluent:Notify({ Title = "keys dos Scripts", Content = "Key:Graciasporseleccionarnos, Key:</>FaseTesting" })
Fluent:Notify({ Title = "Leia", Content = "Fase de teste⚠️" })
Fluent:Notify({ Title = "Leia", Content = "Se quiser que eu faça um script pra você fale comigo não cobro nada👍" })
Fluent:Notify({ Title = "Cael hub", Content = "Como que eu comecei a criar scripts? eu tava bebendo ai me veio uma vontade de criar um script so que eu não sabia 
como que criava ai eu fui e procurei e achei ate hoje tou criando esses script" })
    
-- paragrafo

    Tabs.Main:AddParagraph({
        Title = "Cael hub",
        Content = "começando no ramo de script 👍"
    })
    Tabs.Youtube:AddParagraph({
        Title = "Meu YouTube",
        Content = "(CaelHub)"
    })
    Tabs.Insta da muie:AddParagraph({
        Title = "Insta da mulher se não acha vai tar na minha bio do insta",
        Content = "ana_gabriela_1344848"
    
-- botao

Tabs.Main:AddButton({ Title = "shadow", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/xscripts7/XScripts/refs/heads/XScript/ShadowHub", true))() end })
Tabs.keys:AddButton({ Title = "dopamina", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Dopamina-Hub-17894"))() end })
Tabs.keys:AddButton({ Title = "Cael sky", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/yofriendfromschool1/Sky-Hub/main/SkyHub.txt"))()end })
Tabs.Main:AddButton({ Title = "sander X", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/New.lua'))() end })
Tabs.Main:AddButton({ Title = "carl hub versão beta", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/carlosdaniel987/Carlos/refs/heads/main/README.md"))() end })
Tabs.bons:AddButton({ Title = "Sirius", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Sirius-7420"))() end })
Tabs.Main:AddButton({ Title = "Sander X 341", Callback = function() loadstring(game:HttpGet(('https://raw.githubusercontent.com/kigredns/sander341/main/sanderx341')))() end })
