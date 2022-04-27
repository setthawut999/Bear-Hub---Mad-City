local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Bear Hub", "Sentinel")

local Tab = Window:NewTab("Mad City")
local Section = Tab:NewSection("Menu")

Section:NewButton("AutoFarm", "Bear Hub", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Eazvy/Mad-City-Advanced-Autofarm/main/Autofarm.lua"))()
end)
