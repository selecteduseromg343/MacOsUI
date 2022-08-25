

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local TextLabel_5 = Instance.new("TextLabel")
local UICorner_6 = Instance.new("UICorner")
local ScrollingFrame = Instance.new("ScrollingFrame")
local slbg = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local katana = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local gun = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local gun_2 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local User = Instance.new("Frame")
local TextLabel_6 = Instance.new("TextLabel")
local ImageLabel = Instance.new("ImageLabel")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local UICorner_11 = Instance.new("UICorner")
local UserName = Instance.new("TextLabel")
local TextLabel_7 = Instance.new("TextLabel")
local UICorner_12 = Instance.new("UICorner")



ScreenGui.Parent = game.CoreGui

Main.Name = "Main"
Main.Parent = ScreenGui
Main.Active = true
Main.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
Main.Position = UDim2.new(0.132603407, 0, 0.311111152, 0)
Main.Size = UDim2.new(0, 579, 0, 296)

UICorner.Parent = Main

TextButton.Parent = UICorner
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0.519464731, 0, 0.515873015, 0)
TextButton.Size = UDim2.new(0, 102, 0, 32)
TextButton.Font = Enum.Font.SourceSans
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(85, 255, 127)
TextLabel.Position = UDim2.new(0.0114707211, 0, -0.00023172982, 0)
TextLabel.Size = UDim2.new(0, 120, 0, 28)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Dark MacOs RedEdition"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UICorner_2.Parent = TextLabel

TextLabel_2.Parent = Main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
TextLabel_2.Position = UDim2.new(-0.000309603172, 0, 0.767391801, 0)
TextLabel_2.Size = UDim2.new(0, 83, 0, 66)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Rank: Paid"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

UICorner_3.Parent = TextLabel_2

TextLabel_3.Parent = Main
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
TextLabel_3.Position = UDim2.new(0.968523979, 0, -0.00643244945, 0)
TextLabel_3.Size = UDim2.new(0, 17, 0, 15)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = ""
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

UICorner_4.Parent = TextLabel_3

TextLabel_4.Parent = Main
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 101)
TextLabel_4.Position = UDim2.new(0.939082086, 0, -0.00643244945, 0)
TextLabel_4.Size = UDim2.new(0, 17, 0, 15)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = ""
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 14.000

UICorner_5.Parent = TextLabel_4

TextLabel_5.Parent = Main
TextLabel_5.BackgroundColor3 = Color3.fromRGB(85, 170, 0)
TextLabel_5.Position = UDim2.new(0.911367357, 0, -0.00643244945, 0)
TextLabel_5.Size = UDim2.new(0, 17, 0, 15)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = ""
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextSize = 14.000

UICorner_6.Parent = TextLabel_5

ScrollingFrame.Parent = Main
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
ScrollingFrame.Position = UDim2.new(0.724488556, 0, 0.111908361, 0)
ScrollingFrame.Size = UDim2.new(0, 159, 0, 262)

slbg.Name = "slbg"
slbg.Parent = ScrollingFrame
slbg.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
slbg.Position = UDim2.new(0.182236373, 0, 0.0054151509, 0)
slbg.Size = UDim2.new(0, 101, 0, 31)
slbg.Font = Enum.Font.SourceSans
slbg.Text = "Slap Battles Gui"
slbg.TextColor3 = Color3.fromRGB(0, 0, 0)
slbg.TextSize = 14.000
slbg.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/dizyhvh/slap_battles_gui/main/0.lua"))()
end)

UICorner_7.Parent = slbg

katana.Name = "katana"
katana.Parent = ScrollingFrame
katana.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
katana.Position = UDim2.new(0.187329561, 0, 0.0812274218, 0)
katana.Size = UDim2.new(0, 101, 0, 31)
katana.Font = Enum.Font.SourceSans
katana.Text = "Katana"
katana.TextColor3 = Color3.fromRGB(0, 0, 0)
katana.TextSize = 14.000
katana.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/yt-flix/katana/main/katanalua", true))()
end)

UICorner_8.Parent = katana

gun.Name = "gun"
gun.Parent = ScrollingFrame
gun.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
gun.Position = UDim2.new(0.182225525, 0, 0.161834031, 0)
gun.Size = UDim2.new(0, 104, 0, 25)
gun.Font = Enum.Font.SourceSans
gun.Text = "FE BlockGUN"
gun.TextColor3 = Color3.fromRGB(0, 0, 0)
gun.TextSize = 14.000
gun.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/selecteduseromg343/qweqweqw/main/README.md"))()
end)

UICorner_9.Parent = gun

gun_2.Name = "gun"
gun_2.Parent = ScrollingFrame
gun_2.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
gun_2.Position = UDim2.new(0.182225525, 0, 0.226023227, 0)
gun_2.Size = UDim2.new(0, 104, 0, 25)
gun_2.Font = Enum.Font.SourceSans
gun_2.Text = "BackdoorScanner"
gun_2.TextColor3 = Color3.fromRGB(0, 0, 0)
gun_2.TextSize = 14.000
gun_2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/iK4oS/backdoor.exe/master/source.lua"))()
end)
UICorner_10.Parent = gun_2

User.Name = "User"
User.Parent = Main
User.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
User.BackgroundTransparency = 1.000
User.Position = UDim2.new(0.0116202151, 0, 0.0250829905, 0)
User.Size = UDim2.new(0.974331021, 0, 0.19487755, 0)

TextLabel_6.Parent = User
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Position = UDim2.new(0.261616588, 0, 1.95829165, 0)
TextLabel_6.Size = UDim2.new(0.429446965, 0, 0.281868786, 0)
TextLabel_6.Font = Enum.Font.GothamBold
TextLabel_6.Text = "Welcome to Dark FE MacOs!"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.TextScaled = true
TextLabel_6.TextSize = 14.000
TextLabel_6.TextWrapped = true

ImageLabel.Parent = User
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.Position = UDim2.new(0.422551334, 0, 0.514768839, 0)
ImageLabel.Size = UDim2.new(0.113955028, 0, 1.06547868, 0)
ImageLabel.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UIAspectRatioConstraint.Parent = ImageLabel

UICorner_11.CornerRadius = UDim.new(1, 0)
UICorner_11.Parent = ImageLabel

UserName.Name = "UserName"
UserName.Parent = User
UserName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
UserName.BackgroundTransparency = 1.000
UserName.Position = UDim2.new(0.320317179, 0, 1.60092103, 0)
UserName.Size = UDim2.new(0.31083709, 0, 0.373517364, 0)
UserName.Font = Enum.Font.GothamBold
UserName.Text = "Name"
UserName.TextColor3 = Color3.fromRGB(255, 255, 255)
UserName.TextScaled = true
UserName.TextSize = 14.000
UserName.TextWrapped = true

TextLabel_7.Parent = Main
TextLabel_7.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
TextLabel_7.Position = UDim2.new(0.16951412, 0, 0.905405402, 0)
TextLabel_7.Size = UDim2.new(0, 321, 0, 26)
TextLabel_7.Font = Enum.Font.SourceSans
TextLabel_7.Text = "Version 1.8.5.3 MacOs"
TextLabel_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_7.TextSize = 14.000

UICorner_12.Parent = TextLabel_7

-- Scripts:

local function DXCL_fake_script() -- User.LocalScript 
	local script = Instance.new('LocalScript', User)

	local frame = script.Parent
	
	local player = game.Players.LocalPlayer
	
	local userId = player.UserId
	
	frame.UserName.Text = "Hey ".."@"..player.Name.. "!"
end
coroutine.wrap(DXCL_fake_script)()
