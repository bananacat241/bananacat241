local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Banana Cat", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

 

local Tab = Window:MakeTab({

Name = "script blox fruit",

Icon = "rbxassetid://4483345998",

PremiumOnly = false

})

 

Tab:AddButton({

Name = "alchemy hub",

Callback = function()

loadstring(game:HttpGet("https://luable.netlify.app/AlchemyHub/Luncher.script"))()

      print("button pressed")

  end    

})

 

 

Tab:AddButton({

Name = "FTS Hub",

Callback = function()

loadstring(game:HttpGet(('https://raw.githubusercontent.com/Tulam2000/FTS-HUB/main/FTS%20x%20Hub')))()

      print("button pressed")

  end    

})

 

local Tab = Window:MakeTab({

Name = "Project slayers",

Icon = "rbxassetid://4483345998",

PremiumOnly = false

})

 

Tab:AddButton({

Name = "Oni hub",

Callback = function()

loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/01471f12f9adfd4537f4cc0b3b7bba14.lua"))()

      print("button pressed")

  end    

})

 

Tab:AddButton({

Name = "Nuke Hub",

Callback = function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/NukeVsCity/Scripts2023/main/projslayerthingy', true))()

      print("button pressed")

  end    

})

 

local Tab = Window:MakeTab({

Name = "King Legacy",

Icon = "rbxassetid://4483345998",

PremiumOnly = false

})

 

Tab:AddButton({

Name = "adel hub kaitun",

Callback = function()

repeat wait() until game:IsLoaded() getgenv().Settings = { ['Haki'] = true, -- Auto Turn On Haki ['Ken'] = true, -- Auto Turn On Ken ['Weapon'] = 'Combat', -- Select Weapon ["MethodFarm"] = "Above", -- Method Farm ['Farm'] = true, -- Auto Farm ["Distance"] = 7, -- Distance Farm Mob ['NewWorld'] = true, -- Auto New World ['TableSaveStats'] = { ['Melee'] = true, -- Auto Stats Melee ['Defense'] = true, -- Auto Stats Defense ['Devil Fruit'] = false, -- Auto Stats Devil Fruit ['Sword'] = false, -- Auto Stats Sword }, ['StatsCap'] = 1, -- Recommend Set 1 ['BoostFps'] = true, -- Boost Fps ['AutoRejoin'] = true, -- Auto Rejoin When Kick ['BringDF'] = true, -- Auto Bring DF ['SelectDF'] = 'WolfWolf', -- Select DF ['AutoSniperDF'] = true, -- Auto Sniper DF ['DFEsp'] = false, -- DF Esp ['PlrEsp'] = false, -- Player Esp ['SelectSkill'] = { -- Select Skill ['X'] = true, ['Z'] = true, ['V'] = true, ['C'] = true, ['B'] = true, ['E'] = true }, ['AutoSkillFarm'] = true, -- Auto Skill When Farm ['SelectItem'] = { -- Select Items ['AuthenticMace'] = true, ['Saber'] = true, ['MomBlade'] = true, ['HellSword'] = true, ['PhoenixBlade'] = true }, ['Sword'] = true, -- Auto Sword ['Start Auto Sword At Level'] = '1', -- Auto Start Sword At Level ['SeaKing'] = true, -- Auto Sea King ['SeaKingHop'] = false, -- Auto Sea King Hop ['ChestSeaKing'] = true, -- Auto Chest Sea King ['GhostShip'] = true, -- Auto Ghost Ship ['GhostShipHop'] = false, -- Auto Ghost Ship Hop ['DashNoCD'] = false, -- Dash No Cooldown ['GeppoInf'] = false, -- Geppo Inf ['ChooseMode'] = nil, -- Choose Mode Dungoen ['AutoDungoen'] = false, -- Auto Dungoen ['SaveHealth'] = false, -- Save Health If You Low Health ['SaveSettings'] = true, -- Save Settings } loadstring(game:HttpGet("https://raw.githubusercontent.com/AdelOnTheTop/Adel-Hub/main/Main.lua"))()

      print("button pressed")

  end    

})
