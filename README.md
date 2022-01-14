local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua%22))()
local Window = Library.CreateLib("1DAY HUB", "DarkTheme")

local Tab = Window:NewTab("TP")
local Section = Tab:NewSection("TP MODE")


Section:NewButton("port town", "1DAY Handsome", function()
   game.Players.LocalPlayer.chaeracter.HumanoidRootPart.CFrame = CFrame.new(-281.306549, 6.75574493, 5329.99121, -0.978672624, 0, -0.205426171, 0, 1, 0, 0.205426171, 0, -0.978672624)
end
