local ScreenGui = Instance.new("ScreenGui")
local MainHub = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local text = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local yield = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local slapbattlegui = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local disaster = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_6 = Instance.new("UICorner")
local text_2 = Instance.new("TextLabel")
local UICorner_7 = Instance.new("UICorner")
local aimbot = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local admin = Instance.new("TextLabel")
local UICorner_9 = Instance.new("UICorner")
local admin_2 = Instance.new("TextLabel")
local UICorner_10 = Instance.new("UICorner")


ScreenGui.Parent = game.CoreGui

MainHub.Name = "MainHub"
MainHub.Parent = ScreenGui
MainHub.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MainHub.Position = UDim2.new(0.226267874, 0, 0.39538464, 0)
MainHub.Size = UDim2.new(0, 371, 0, 294)
MainHub.Active = true
MainHub.Draggable = true

UICorner.Parent = MainHub

text.Name = "text"
text.Parent = MainHub
text.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
text.BorderColor3 = Color3.fromRGB(0, 0, 0)
text.Position = UDim2.new(0.811576843, 0, 0.894557834, 0)
text.Size = UDim2.new(0, 69, 0, 31)
text.Font = Enum.Font.SourceSans
text.Text = "Dark Hub"
text.TextColor3 = Color3.fromRGB(255, 255, 0)
text.TextScaled = true
text.TextSize = 14.000
text.TextWrapped = true

UICorner_2.Parent = text

yield.Name = "yield"
yield.Parent = MainHub
yield.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
yield.Position = UDim2.new(0.335376084, 0, 0.129272252, 0)
yield.Size = UDim2.new(0, 91, 0, 33)
yield.Font = Enum.Font.SourceSans
yield.Text = "Infinite Yield FE"
yield.TextColor3 = Color3.fromRGB(85, 170, 0)
yield.TextSize = 14.000
yield.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
end)

UICorner_3.Parent = yield

slapbattlegui.Name = "slapbattlegui"
slapbattlegui.Parent = MainHub
slapbattlegui.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
slapbattlegui.Position = UDim2.new(0.0146213789, 0, 0.15449369, 0)
slapbattlegui.Size = UDim2.new(0, 88, 0, 33)
slapbattlegui.Font = Enum.Font.SourceSans
slapbattlegui.Text = "Slap Battles Gui"
slapbattlegui.TextColor3 = Color3.fromRGB(85, 170, 0)
slapbattlegui.TextSize = 14.000
slapbattlegui.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/dizyhvh/slap_battles_gui/main/0.lua"))()
end)

UICorner_4.Parent = slapbattlegui

disaster.Name = "disaster"
disaster.Parent = MainHub
disaster.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
disaster.Position = UDim2.new(0.0143703315, 0, 0.266091049, 0)
disaster.Size = UDim2.new(0, 94, 0, 33)
disaster.Font = Enum.Font.SourceSans
disaster.Text = "Disaster Gui"
disaster.TextColor3 = Color3.fromRGB(85, 170, 0)
disaster.TextSize = 14.000
disaster.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/9NLK7/93qjoadnlaknwldk/main/main'))()
end)

UICorner_5.Parent = disaster

TextLabel.Parent = MainHub
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.Position = UDim2.new(0.00904977415, 0, 0.0184399858, 0)
TextLabel.Size = UDim2.new(0, 94, 0, 33)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Scripts"
TextLabel.TextColor3 = Color3.fromRGB(85, 255, 0)
TextLabel.TextSize = 14.000

UICorner_6.Parent = TextLabel

text_2.Name = "text"
text_2.Parent = MainHub
text_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
text_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
text_2.Position = UDim2.new(0.013733157, 0, 0.863945484, 0)
text_2.Size = UDim2.new(0, 131, 0, 40)
text_2.Font = Enum.Font.SourceSans
text_2.Text = "Dc: semfmgEBMM"
text_2.TextColor3 = Color3.fromRGB(255, 255, 0)
text_2.TextScaled = true
text_2.TextSize = 14.000
text_2.TextWrapped = true

UICorner_7.Parent = text_2

aimbot.Name = "aimbot"
aimbot.Parent = MainHub
aimbot.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
aimbot.Position = UDim2.new(0.663966, 0, 0.15384616, 0)
aimbot.Size = UDim2.new(0, 94, 0, 33)
aimbot.Font = Enum.Font.SourceSans
aimbot.Text = "Owl Hub"
aimbot.TextColor3 = Color3.fromRGB(85, 170, 0)
aimbot.TextSize = 14.000
aimbot.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)

UICorner_8.Parent = aimbot

admin.Name = "admin"
admin.Parent = MainHub
admin.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
admin.Position = UDim2.new(0.328802735, 0, 0.0184399858, 0)
admin.Size = UDim2.new(0, 94, 0, 33)
admin.Font = Enum.Font.SourceSans
admin.Text = "Admin Scripts"
admin.TextColor3 = Color3.fromRGB(85, 255, 0)
admin.TextSize = 14.000

UICorner_9.Parent = admin

admin_2.Name = "admin"
admin_2.Parent = MainHub
admin_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
admin_2.Position = UDim2.new(0.66572994, 0, 0.0184399858, 0)
admin_2.Size = UDim2.new(0, 94, 0, 33)
admin_2.Font = Enum.Font.SourceSans
admin_2.Text = "Aimbot Script"
admin_2.TextColor3 = Color3.fromRGB(85, 255, 0)
admin_2.TextSize = 14.000

UICorner_10.Parent = admin_2
