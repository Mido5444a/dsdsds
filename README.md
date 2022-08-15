--Made By Mido

local Megaloge = Instance.new("ScreenGui")
local LoginFrame = Instance.new("Frame")
local logintitle = Instance.new("TextLabel")
local username = Instance.new("TextBox")
local password = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")
local MadeByMido = Instance.new("TextLabel")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local PrisonLife = Instance.new("TextButton")
local jailbreack = Instance.new("TextButton")
local ADMIN = Instance.new("TextButton")
local Made = Instance.new("TextLabel")

--Properties:

Megaloge.Name = "Mega  loge"
Megaloge.Parent = game.CoreGui
Megaloge.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

LoginFrame.Name = "LoginFrame"
LoginFrame.Parent = Megaloge
LoginFrame.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
LoginFrame.Position = UDim2.new(0.359591544, 0, 0.145476773, 0)
LoginFrame.Size = UDim2.new(0, 346, 0, 421)
LoginFrame.Active = true
LoginFrame.Draggable = true 


logintitle.Name = "login title"
logintitle.Parent = LoginFrame
logintitle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
logintitle.LayoutOrder = 1
logintitle.Size = UDim2.new(0, 346, 0, 50)
logintitle.Font = Enum.Font.Highway
logintitle.Text = "Welcome Screen"
logintitle.TextColor3 = Color3.fromRGB(255, 255, 255)
logintitle.TextScaled = true
logintitle.TextSize = 14.000
logintitle.TextWrapped = true

username.Name = "username"
username.Parent = LoginFrame
username.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
username.Position = UDim2.new(0.0953757241, 0, 0.292161524, 0)
username.Size = UDim2.new(0, 279, 0, 50)
username.Font = Enum.Font.SourceSans
username.Text = "Username"
username.TextColor3 = Color3.fromRGB(255, 255, 255)
username.TextScaled = true
username.TextSize = 14.000
username.TextWrapped = true

password.Name = "password"
password.Parent = LoginFrame
password.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
password.Position = UDim2.new(0.0953757241, 0, 0.484560579, 0)
password.Size = UDim2.new(0, 279, 0, 50)
password.Font = Enum.Font.SourceSans
password.Text = "Password"
password.TextColor3 = Color3.fromRGB(255, 255, 255)
password.TextScaled = true
password.TextSize = 14.000
password.TextWrapped = true

TextButton.Parent = LoginFrame
TextButton.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
TextButton.Position = UDim2.new(0.208092496, 0, 0.679334879, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Login"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true
TextButton.MouseButton1Click:Connect(function()
	if username.Text == "PKS" and password.Text == "Mido" then
		LoginFrame.Visible = false
		Frame.Visible = true
	end
end)

MadeByMido.Name = "Made By Mido"
MadeByMido.Parent = LoginFrame
MadeByMido.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
MadeByMido.LayoutOrder = 1
MadeByMido.Position = UDim2.new(0, 0, 0.881235182, 0)
MadeByMido.Size = UDim2.new(0, 346, 0, 50)
MadeByMido.Font = Enum.Font.Oswald
MadeByMido.Text = "Made By Mido"
MadeByMido.TextColor3 = Color3.fromRGB(255, 255, 255)
MadeByMido.TextScaled = true
MadeByMido.TextSize = 14.000
MadeByMido.TextWrapped = true

Frame.Parent = Megaloge
Frame.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Frame.LayoutOrder = 1
Frame.Position = UDim2.new(0.329686344, 0, 0.216381416, 0)
Frame.Size = UDim2.new(0, 466, 0, 378)
Frame.Visible = false
Frame.Active = true
Frame.Draggable = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
TextLabel.Size = UDim2.new(0, 466, 0, 50)
TextLabel.Font = Enum.Font.Highway
TextLabel.Text = "Free.Hax"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

PrisonLife.Name = "Prison Life"
PrisonLife.Parent = Frame
PrisonLife.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
PrisonLife.Position = UDim2.new(0, 0, 0.238095239, 0)
PrisonLife.Size = UDim2.new(0, 466, 0, 50)
PrisonLife.Font = Enum.Font.Bangers
PrisonLife.Text = "Prison Life"
PrisonLife.TextColor3 = Color3.fromRGB(255, 255, 255)
PrisonLife.TextScaled = true
PrisonLife.TextSize = 14.000
PrisonLife.TextWrapped = true
PrisonLife.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/XTheMasterX/Scripts/Main/PrisonLife'),true))()
end)

jailbreack.Name = "jailbreack"
jailbreack.Parent = Frame
jailbreack.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
jailbreack.Position = UDim2.new(0, 0, 0.465608478, 0)
jailbreack.Size = UDim2.new(0, 466, 0, 50)
jailbreack.Font = Enum.Font.Bangers
jailbreack.Text = "jailbreack"
jailbreack.TextColor3 = Color3.fromRGB(255, 255, 255)
jailbreack.TextScaled = true
jailbreack.TextSize = 14.000
jailbreack.TextWrapped = true
jailbreack.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/KuriWasTaken/MonkeyScripts/main/JailMonkey.lua"))()
end)

ADMIN.Name = "ADMIN"
ADMIN.Parent = Frame
ADMIN.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ADMIN.Position = UDim2.new(0, 0, 0.677248716, 0)
ADMIN.Size = UDim2.new(0, 466, 0, 50)
ADMIN.Font = Enum.Font.Bangers
ADMIN.Text = "Admin"
ADMIN.TextColor3 = Color3.fromRGB(255, 255, 255)
ADMIN.TextScaled = true
ADMIN.TextSize = 14.000
ADMIN.TextWrapped = true
ADMIN.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

Made.Name = "Made"
Made.Parent = Frame
Made.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Made.Position = UDim2.new(0, 0, 0.867724895, 0)
Made.Size = UDim2.new(0, 466, 0, 50)
Made.Font = Enum.Font.Oswald
Made.Text = "Made By Mido"
Made.TextColor3 = Color3.fromRGB(255, 255, 255)
Made.TextScaled = true
Made.TextSize = 14.000
Made.TextWrapped = true
