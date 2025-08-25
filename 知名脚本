local NotificationHolder = loadstring(game:HttpGet("https://raw.githubusercontent.com/BocusLuke/UI/main/STX/Module.Lua"))()
local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/BocusLuke/UI/main/STX/Client.Lua"))()

print("反挂机开启")
		local vu = game:GetService("VirtualUser")
		game:GetService("Players").LocalPlayer.Idled:connect(function()
		   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		   wait(1)
		   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		end)

local Sound = Instance.new("Sound")
        Sound.Parent = game.SoundService
        Sound.SoundId = "rbxassetid://4590662766"
        Sound.Volume = 3
        Sound.PlayOnRemove = true
        Sound:Destroy()

local WindUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/CNHM/asg/refs/heads/main/wind%20ui.lua"))()
local Tab = Window:Tab({
    Title = "知名脚本",
    Icon = "code",
    Locked = false,
})

local Button = Tab:Button({
    Title = "xa",
    Desc = "",
    Locked = false,
    Callback = function()
    loadstring(game:HttpGet("https://raw.gitcode.com/Xingtaiduan/Scripts/raw/main/Loader.lua"))()
    end
})

local Button = Tab:Button({
    Title = "皮脚本",
    Desc = "",
    Locked = false,
    Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/xiaopi77/xiaopi77/main/QQ1002100032-Roblox-Pi-script.lua"))()
    end
})

local Button = Tab:Button({
    Title = "霜溺",
    Desc = "",
    Locked = false,
    Callback = function()
    loadstring(game:loadstring(game:HttpGet("https://raw.githubusercontent.com/ShenJiaoBen/ShenJiaoBen/main/King-------------Script.txt"))()
    end
})
