local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
getgenv().Theme = "Synapse"
--[[
    LightTheme
    DarkTheme
    GrapeTheme
    BloodTheme 
    Ocean
    Midnight
    Sentinel  
    Synapse
]]  
local Window = Library.CreateLib("Easy Hub v0.18 (Beta)", getgenv().Theme) 
local Tab = Window:NewTab("Main") 
local Section = Tab:NewSection("Main The Easy Hub Official(PayMent)")
Section:NewTextBox("Character speed", "Type in a number to make the speed u want", function(txt)
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end)
Section:NewSlider("speed but slider", "Yo", 500, 0, function(speed)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = speed
end)
Section:NewButton("Infinite yield", "alot of better", function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
Section:NewKeybind("Toggle ui", "makes the gui invisible, press again to make it visible", Enum.KeyCode.RightAlt, function()
	Library:ToggleUI()
end)
Section:NewButton("Easy Hub", "Op Than Other dh", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/6EF04163"))()
end)
Section:NewButton("Ftf Script", "WARNING DONT USE OTHER GAME", function()
    loadstring(game:HttpGet("https://nns4.me/scripts/loader.lua"))()
end)
Section:NewToggle("Speed", "Speed 60 jumpower 100", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 90
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 100
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
    end
end)
Section:NewButton("Keyboard", "ITS IMPORTANT FOR IT!!", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
end)
Section:NewButton("2 Flee The Facility", "2nd ver", function()
   loadstring(game:HttpGet("https://polarsblade.xyz/Hub/FleeTheFacility.txt"))()
end)
Section:NewButton("3 Flee the Facility", "Num 3", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/NexIsHot/Lunar/main/FTF.lua",true))()
end)
Section:NewButton("1 Toilet Tower Defense", "Not Patched *Mobile*", function()
   loadstring(game:HttpGet('https://raw.githubusercontent.com/ou1z/Roblox-Scripts/master/InputRecorder.lua'))()
end)
Section:NewButton("2 Toilet Tower Defense", "Not Patched *Mobile*", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/toilet"))()
end)

Section:NewToggle("Testing", "Testing", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 160
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 160
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
    end
end)

Section:NewTextBox("Jumppower", "ITS BROKEN", function(txt)
game.Players.LocalPlayer.Character.Humanoid.JumpPower = txt
end)
Section:NewButton("1 RagDoll", "Ver 1 *PATCHED NIGGA Mobile*", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/i4mitty/MysteryHub/main/MysteryHub%20-%20Ragdoll%20Engine.lua"))()
end)
Section:NewButton("Nyula", "sex porn shit", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/nyulachan/nyula/main/nyula", true))()
end)
Section:NewButton("Q TOOL FOR DH", "FUCK CUM WHITE", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/scripthubekitten/qtoolv3/main/qtoolv3", true))()
end)
Section:NewButton("BLAZED LOCK", "its good to use", function()
   loadstring(game:HttpGet('https://angxlzz.dev/blazed.lua'))()
end)
Section:NewButton("The mimic script", "", function()
    print("Clicked")
end)
Section:NewButton("1 The Mimic", "Ver 1 *Mobile*", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Nicuse/FrightenedHub/main/Loader.lua",  true))()
end)
Section:NewButton("NA ADMIN", "Vip ver", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
end)
Section:NewButton("Jailbreak script", "Ver 1 *Mobile idk if its patched*", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/KuriWasTaken/MonkeyScripts/main/JailMonkey.lua"))()
end)
Section:NewButton("Auto rob jailbreak", "Ver 2 *idk if its patched but mobile*", function()
   loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/5d4b0843f800d5dcac07568e18190b7e.lua"))()
end)
Section:NewButton("IV ADMIN", ".", function()
   loadstring(game:HttpGet('https://raw.githubusercontent.com/BloodyBurns/Hex/main/Iv%20Admin%20v2.lua'))()
end)
local Tab = Window:NewTab("Car Delearship Tycoon") 
local Section = Tab:NewSection("VROOM!!!")

Section:NewButton("1 Car Delearship tycoon", ".", function()
   loadstring(game:HttpGet("https://astronomic.vercel.app"))()
end)
Section:NewButton("2 Car Delearship tycoon", ".", function()
   loadstring(game:HttpGet('https://raw.githubusercontent.com/ToraIsMe/ToraIsMe/main/0CarDealership'))()
end)
Section:NewButton("3 Car Delearship tycoon", ".", function()
  loadstring(game:HttpGet("https://scriptblox.com/raw/NEW-CAR!-Car-Dealership-Tycoon-Auto-Drive-5068"))()
end)
