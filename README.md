-- carregar biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

-- Aviso ao executar
Fluent:Notify({ Title = "Executado!", Content = "CARL HUB SCRIPTS" })

local Window = Fluent:CreateWindow({
    Title = "Carl hub" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

-- Parágrafos
Tabs.Main:AddParagraph({ Title = "EXECUTADO", Content = "SCRIPT EXECUTADO" })

-- Botões
Tabs.Main:AddButton({ Title = "Rael hub", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt")() end })
Tabs.Main:AddButton({ Title = "BROOKHAVEN", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/BROOKHAVEN-GUI-/main/METAB", true))() end })
Tabs.Main:AddButton({ Title = "EQ CARL", Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/eQA4nfcw"))() end })
Tabs.Main:AddButton({ Title = "CENTRAL BR", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptCentral-br/SCU/refs/heads/main/sc.md",true))() end })
Tabs.Main:AddButton({ Title = "SANDER X CARL", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/NormalSS.lua'))() end })
Tabs.Main:AddButton({ Title = "G HUB CARL", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBV14XZ/main/Ghub_Main_Loader.txt"))() end })
Tabs.Main:AddButton({ Title = "CARL HUB OLD", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/carlosdaniel987/Carl-hub-novo/refs/heads/main/README.md")() end })

-- Sliders
local Slider = Tabs.Main:AddSlider("Voar", {
        Title = "Voar",
        Description = "O player podera voa",
        Default = 2,
        Min = 0,
        Max = 5,
        Rounding = 1,
        Callback = function(Value)
            print("Voar mudou para:", Value)
        end
    })
    



-- carregar biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

-- Aviso ao executar
Fluent:Notify({ Title = "Executado!", Content = "GHOST777 FOI EXECUTADO" })

local Window = Fluent:CreateWindow({
    Title = "GHOST777" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

-- Parágrafos
Tabs.Main:AddParagraph({ Title = "EXECUTADO", Content = "SCRIPT EXECUTADO" })

-- Botões
Tabs.Main:AddButton({ Title = "Rael hub", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt")() end })
Tabs.Main:AddButton({ Title = "BROOKHAVEN", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/BROOKHAVEN-GUI-/main/METAB", true))() end })
Tabs.Main:AddButton({ Title = "EQ CARL", Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/eQA4nfcw"))() end })
Tabs.Main:AddButton({ Title = "CENTRAL BR", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptCentral-br/SCU/refs/heads/main/sc.md",true))() end })
Tabs.Main:AddButton({ Title = "SANDER X CARL", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/NormalSS.lua'))() end })
Tabs.Main:AddButton({ Title = "G HUB CARL", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBV14XZ/main/Ghub_Main_Loader.txt"))() end })
Tabs.Main:AddButton({ Title = "CARL HUB OLD", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/carlosdaniel987/Carl-hub-novo/refs/heads/main/README.md")() end })

-- Sliders
local Slider = Tabs.Main:AddSlider("Voar", {
        Title = "Voar",
        Description = "O player podera voa",
        Default = 2,
        Min = 0,
        Max = 5,
        Rounding = 1,
        Callback = function(Value)
            print("Voar mudou para:", Value)
        end
    })
    
    -- Games
    local Games = Window:NewTab("Games🎮")
local GamesSection = Games:NewSection("Games")


GamesSection:NewButton("🏠Brookhaven🏠", "", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
end)

GamesSection:NewButton("🔪MM2🔪", "", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/MM2%20Admin%20Panel'),true))()
end)

GamesSection:NewButton("Bedwars🛌", "", function()
    	loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()	
end)

GamesSection:NewButton("Prison Life", "", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/iZ64yzjE'))()
end)

GamesSection:NewButton("💪Muscle Legends💪", "", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/harisiskandar178/Roblox-Script/main/Muscle%20Legend"))()
end)

GamesSection:NewButton("Break In", "", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nikita365/Break-In-Story-/main/Break%20In%20Story%20Hub"))()
end)

GamesSection:NewButton("Nico's Nextbots", "", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/NicoNextBots", true))()
end)

GamesSection:NewButton("Doors👁", "", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/Doors"))()
end)

GamesSection:NewButton("Evade", "", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/Evade"))()
end)

GamesSection:NewButton("Rainbow Friends", "", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JNHHGaming/Rainbow-Friends/main/Rainbow%20Friends"))()
end)

-- Admin
GamesSection:NewButton("Slap Battles", "", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/TheScriptMaster1/ScriptMaster-Hub/main/scriptmasterhub.lua')))()
end)

GamesSection:NewButton("Cook Burgers", "", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/YUqvvEAB')))()
end)
local Admins = Window:NewTab("Admins")
local AdminsSection = Admins:NewSection("Admins")

AdminsSection:NewButton("Infinite Yield", nil, function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

AdminsSection:NewButton("CMD-X", nil, function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source", true))()
end)

AdminsSection:NewButton("Fates Admin", nil, function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
end)

-- keyboard
MiscSection:NewButton("Keyboard", nil, function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
end)

-- Credits
local Credits = Window:NewTab("Credits")
local CreditsSection = Credits:NewSection("Credits")


CreditsSection:NewLabel("Made by Carlos")
CreditsSection:NewLabel("Derik_ Roblox Account: derikmicael321")
CreditsSection:NewLabel("scripter_ follow Roblox Account: pedroalyra")
