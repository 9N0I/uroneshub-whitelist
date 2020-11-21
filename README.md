-- Gui to Lua
-- Version: 3.2

-- Instances:

local UronesHubScreen = Instance.new("ScreenGui")
local UronesHub = Instance.new("ImageLabel")
local UronesHub_2 = Instance.new("TextLabel")
local WhitelistKey = Instance.new("TextBox")
local TextBox_Roundify_4px = Instance.new("ImageLabel")
local LoadBarFrame = Instance.new("ImageLabel")
local LoadBar = Instance.new("ImageLabel")
local EnterKey = Instance.new("TextButton")
local TextButton_Roundify_4px = Instance.new("ImageLabel")
local Icon = Instance.new("ImageButton")
local LineRGB = Instance.new("ImageLabel")
local EnterKeyOFF = Instance.new("TextLabel")
local TextLabel_Roundify_4px = Instance.new("ImageLabel")
local Icon_2 = Instance.new("ImageButton")
local Notify = Instance.new("ImageLabel")
local TextNotify = Instance.new("TextLabel")
local Close = Instance.new("ImageButton")

--Properties:

UronesHubScreen.Name = "UronesHubScreen"
UronesHubScreen.Parent = game.CoreGui

UronesHub.Name = "UronesHub"
UronesHub.Parent = UronesHubScreen
UronesHub.Active = true
UronesHub.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
UronesHub.BackgroundTransparency = 1.000
UronesHub.Position = UDim2.new(0.390977442, 0, 0.330804259, 0)
UronesHub.Size = UDim2.new(0, 289, 0, 161)
UronesHub.Image = "rbxassetid://3570695787"
UronesHub.ImageColor3 = Color3.fromRGB(20, 20, 20)
UronesHub.ScaleType = Enum.ScaleType.Slice
UronesHub.SliceCenter = Rect.new(100, 100, 100, 100)
UronesHub.SliceScale = 0.040

UronesHub_2.Name = "UronesHub"
UronesHub_2.Parent = UronesHub
UronesHub_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
UronesHub_2.BackgroundTransparency = 1.000
UronesHub_2.Position = UDim2.new(0.384083033, 0, 0.0434782691, 0)
UronesHub_2.Size = UDim2.new(0, 68, 0, 18)
UronesHub_2.Font = Enum.Font.SourceSansSemibold
UronesHub_2.Text = "URONES HUB "
UronesHub_2.TextColor3 = Color3.fromRGB(247, 22, 56)
UronesHub_2.TextSize = 14.000

WhitelistKey.Name = "WhitelistKey"
WhitelistKey.Parent = UronesHub
WhitelistKey.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
WhitelistKey.BackgroundTransparency = 1.000
WhitelistKey.BorderColor3 = Color3.fromRGB(45, 45, 45)
WhitelistKey.BorderSizePixel = 0
WhitelistKey.Position = UDim2.new(0.0242214538, 0, 0.316770196, 0)
WhitelistKey.Size = UDim2.new(0, 276, 0, 23)
WhitelistKey.ZIndex = 2
WhitelistKey.Font = Enum.Font.SourceSansSemibold
WhitelistKey.PlaceholderText = "WHITELIST KEY . . ."
WhitelistKey.Text = ""
WhitelistKey.TextColor3 = Color3.fromRGB(255, 255, 255)
WhitelistKey.TextSize = 14.000

TextBox_Roundify_4px.Name = "TextBox_Roundify_4px"
TextBox_Roundify_4px.Parent = WhitelistKey
TextBox_Roundify_4px.Active = true
TextBox_Roundify_4px.AnchorPoint = Vector2.new(0.5, 0.5)
TextBox_Roundify_4px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox_Roundify_4px.BackgroundTransparency = 1.000
TextBox_Roundify_4px.Position = UDim2.new(0.5, 0, 0.5, 0)
TextBox_Roundify_4px.Selectable = true
TextBox_Roundify_4px.Size = UDim2.new(1, 0, 1, 0)
TextBox_Roundify_4px.Image = "rbxassetid://3570695787"
TextBox_Roundify_4px.ImageColor3 = Color3.fromRGB(45, 45, 45)
TextBox_Roundify_4px.ScaleType = Enum.ScaleType.Slice
TextBox_Roundify_4px.SliceCenter = Rect.new(100, 100, 100, 100)
TextBox_Roundify_4px.SliceScale = 0.040

LoadBarFrame.Name = "LoadBarFrame"
LoadBarFrame.Parent = UronesHub
LoadBarFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LoadBarFrame.BackgroundTransparency = 1.000
LoadBarFrame.Position = UDim2.new(0.0242214538, 0, 0.521739125, 0)
LoadBarFrame.Size = UDim2.new(0, 276, 0, 11)
LoadBarFrame.Image = "rbxassetid://3570695787"
LoadBarFrame.ImageColor3 = Color3.fromRGB(10, 10, 10)
LoadBarFrame.ScaleType = Enum.ScaleType.Slice
LoadBarFrame.SliceCenter = Rect.new(100, 100, 100, 100)
LoadBarFrame.SliceScale = 0.040

LoadBar.Name = "LoadBar"
LoadBar.Parent = LoadBarFrame
LoadBar.Active = true
LoadBar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LoadBar.BackgroundTransparency = 1.000
LoadBar.Position = UDim2.new(0.0200000703, 0, 0.450001121, 0)
LoadBar.Size = UDim2.new(0, 0, 0, 2)
LoadBar.Image = "rbxassetid://3570695787"
LoadBar.ScaleType = Enum.ScaleType.Slice
LoadBar.SliceCenter = Rect.new(100, 100, 100, 100)
LoadBar.SliceScale = 0.040

EnterKey.Name = "EnterKey"
EnterKey.Parent = UronesHub
EnterKey.BackgroundColor3 = Color3.fromRGB(170, 255, 255)
EnterKey.BackgroundTransparency = 1.000
EnterKey.BorderColor3 = Color3.fromRGB(255, 170, 127)
EnterKey.BorderSizePixel = 0
EnterKey.Position = UDim2.new(0.0242214538, 0, 0.66459626, 0)
EnterKey.Size = UDim2.new(0, 276, 0, 23)
EnterKey.ZIndex = 2
EnterKey.Font = Enum.Font.SourceSansBold
EnterKey.Text = "ENTER KEY"
EnterKey.TextColor3 = Color3.fromRGB(0, 0, 0)
EnterKey.TextSize = 14.000

TextButton_Roundify_4px.Name = "TextButton_Roundify_4px"
TextButton_Roundify_4px.Parent = EnterKey
TextButton_Roundify_4px.Active = true
TextButton_Roundify_4px.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_4px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_4px.BackgroundTransparency = 1.000
TextButton_Roundify_4px.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_4px.Selectable = true
TextButton_Roundify_4px.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_4px.Image = "rbxassetid://3570695787"
TextButton_Roundify_4px.ImageColor3 = Color3.fromRGB(247, 22, 56)
TextButton_Roundify_4px.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_4px.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_4px.SliceScale = 0.040

Icon.Name = "Icon"
Icon.Parent = EnterKey
Icon.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Icon.BackgroundTransparency = 1.000
Icon.Position = UDim2.new(0.894927561, 0, 0.0434782617, 0)
Icon.Size = UDim2.new(0, 20, 0, 20)
Icon.ZIndex = 2
Icon.Image = "rbxassetid://3926305904"
Icon.ImageColor3 = Color3.fromRGB(0, 0, 0)
Icon.ImageRectOffset = Vector2.new(84, 204)
Icon.ImageRectSize = Vector2.new(36, 36)

LineRGB.Name = "LineRGB"
LineRGB.Parent = UronesHub
LineRGB.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineRGB.BackgroundTransparency = 1.000
LineRGB.Position = UDim2.new(0.0207612459, 0, 0.211180121, 0)
LineRGB.Size = UDim2.new(0, 276, 0, 1)
LineRGB.Image = "rbxassetid://3570695787"
LineRGB.ScaleType = Enum.ScaleType.Slice
LineRGB.SliceCenter = Rect.new(100, 100, 100, 100)
LineRGB.SliceScale = 0.040

EnterKeyOFF.Name = "EnterKeyOFF"
EnterKeyOFF.Parent = UronesHub
EnterKeyOFF.Active = true
EnterKeyOFF.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
EnterKeyOFF.BackgroundTransparency = 1.000
EnterKeyOFF.BorderColor3 = Color3.fromRGB(35, 35, 35)
EnterKeyOFF.BorderSizePixel = 0
EnterKeyOFF.Position = UDim2.new(0.0240000002, 0, 0.665000021, 0)
EnterKeyOFF.Size = UDim2.new(0, 276, 0, 0)
EnterKeyOFF.Visible = false
EnterKeyOFF.ZIndex = 2
EnterKeyOFF.Font = Enum.Font.SourceSansBold
EnterKeyOFF.Text = ""
EnterKeyOFF.TextColor3 = Color3.fromRGB(0, 0, 0)
EnterKeyOFF.TextSize = 14.000

TextLabel_Roundify_4px.Name = "TextLabel_Roundify_4px"
TextLabel_Roundify_4px.Parent = EnterKeyOFF
TextLabel_Roundify_4px.Active = true
TextLabel_Roundify_4px.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_Roundify_4px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_Roundify_4px.BackgroundTransparency = 1.000
TextLabel_Roundify_4px.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_Roundify_4px.Size = UDim2.new(1, 0, 1, 0)
TextLabel_Roundify_4px.Image = "rbxassetid://3570695787"
TextLabel_Roundify_4px.ImageColor3 = Color3.fromRGB(35, 35, 35)
TextLabel_Roundify_4px.ScaleType = Enum.ScaleType.Slice
TextLabel_Roundify_4px.SliceCenter = Rect.new(100, 100, 100, 100)
TextLabel_Roundify_4px.SliceScale = 0.040

Icon_2.Name = "Icon"
Icon_2.Parent = EnterKeyOFF
Icon_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Icon_2.BackgroundTransparency = 1.000
Icon_2.Position = UDim2.new(0.894927561, 0, 0.0434782617, 0)
Icon_2.Size = UDim2.new(0, 20, 0, 20)
Icon_2.ZIndex = 2
Icon_2.Image = "rbxassetid://3926305904"
Icon_2.ImageColor3 = Color3.fromRGB(0, 0, 0)
Icon_2.ImageRectOffset = Vector2.new(84, 204)
Icon_2.ImageRectSize = Vector2.new(36, 36)

Notify.Name = "Notify"
Notify.Parent = UronesHubScreen
Notify.Active = true
Notify.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Notify.BackgroundTransparency = 1.000
Notify.Position = UDim2.new(0.391000003, 0, -1, 0)
Notify.Size = UDim2.new(0, 289, 0, 61)
Notify.Image = "rbxassetid://3570695787"
Notify.ImageColor3 = Color3.fromRGB(20, 20, 20)
Notify.ScaleType = Enum.ScaleType.Slice
Notify.SliceCenter = Rect.new(100, 100, 100, 100)
Notify.SliceScale = 0.040

TextNotify.Name = "TextNotify"
TextNotify.Parent = Notify
TextNotify.Active = true
TextNotify.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextNotify.BackgroundTransparency = 1.000
TextNotify.Position = UDim2.new(0.152249128, 0, 0.377049178, 0)
TextNotify.Size = UDim2.new(0, 200, 0, 15)
TextNotify.Font = Enum.Font.SourceSansSemibold
TextNotify.Text = "YOU NEED TO FIND KEY IN DISCORD"
TextNotify.TextColor3 = Color3.fromRGB(255, 255, 255)
TextNotify.TextSize = 14.000

Close.Name = "Close"
Close.Parent = Notify
Close.BackgroundTransparency = 1.000
Close.Position = UDim2.new(0.913494825, 0, 0.0655737668, 0)
Close.Size = UDim2.new(0, 19, 0, 19)
Close.ZIndex = 2
Close.Image = "rbxassetid://3926305904"
Close.ImageColor3 = Color3.fromRGB(247, 22, 56)
Close.ImageRectOffset = Vector2.new(284, 4)
Close.ImageRectSize = Vector2.new(24, 24)

-- Scripts:
	local script = Instance.new('LocalScript', UronesHubScreen)

	local UronesHub = script.Parent.UronesHub
	local WhitelistKey = script.Parent.UronesHub.WhitelistKey
	local EnterKey = script.Parent.UronesHub.EnterKey
	local LoadBarFrame = script.Parent.UronesHub.LoadBarFrame
	local LoadBar = script.Parent.UronesHub.LoadBarFrame.LoadBar
	local UronesHub1 = script.Parent.UronesHub.UronesHub
	local LineRGB = script.Parent.UronesHub.LineRGB
	local Icon = script.Parent.UronesHub.EnterKey.Icon
	local EnterKeyOFF = script.Parent.UronesHub.EnterKeyOFF
	local Notify = script.Parent.Notify
	local CloseNotify = script.Parent.Notify.Close
	local TextNotify = script.Parent.Notify.TextNotify
	local EnterKey2 = script.Parent.UronesHub.EnterKey.TextButton_Roundify_4px
	
	CloseNotify.MouseButton1Down:Connect(function()
		Notify:TweenSize(UDim2.new(0, 289,0, 0), "Out", "Sine", 0.5)
		CloseNotify.Visible = false
		TextNotify.Visible = false
		wait(2)
		UronesHub:Destroy()
		Notify:Destroy()
	end)
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.2, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local colourDarkTween = tweenService:Create(EnterKey2, tweenInfo, {ImageColor3 = Color3.fromRGB(247, 22, 56)})
	local colourBrightTween = tweenService:Create(EnterKey2, tweenInfo, {ImageColor3 = Color3.fromRGB(170, 14, 40)})
	local colourDefaultTween = tweenService:Create(EnterKey2, tweenInfo, {ImageColor3 = Color3.fromRGB(247, 22, 56)})
	
	EnterKey.MouseEnter:Connect(function()
		isHovering = true
	
		colourBrightTween:Play()
	end)
	
	EnterKey.MouseLeave:Connect(function()
		
		isHovering = false
	
		colourDefaultTween:Play()
	end)
	
	EnterKey.MouseButton1Down:Connect(function()
		colourDarkTween:Play()
	end)
	
	EnterKey.MouseButton1Down:Connect(function()
		if WhitelistKey.Text == ("URONES-HUB-IS-FREE") then
			wait(0.1)
			EnterKey:TweenSize(UDim2.new(0, 276,0, 0), "Out", "Sine", 0.5)
			EnterKey.Text = ("")
			Icon.Visible = false
			wait(1)
			EnterKeyOFF:TweenSize(UDim2.new(0, 276,0, 23), "Out", "Sine", 0.5)
			EnterKeyOFF.Visible = true
			EnterKeyOFF.Icon.Visible = true
			EnterKeyOFF.Text = ("ENTER KEY")
			wait(0.1)
			WhitelistKey.Text = ("Verifylied Players")
			LoadBar:TweenSize(UDim2.new(0, 20,0, 2))
			wait(1)
			WhitelistKey.Text = ("Verifylied Players.")
			LoadBar:TweenSize(UDim2.new(0, 30,0, 2))
			wait(1)
			WhitelistKey.Text = ("Verifylied Players..")
			wait(1)
			WhitelistKey.Text = ("Check Version")
			LoadBar:TweenSize(UDim2.new(0, 50,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Version.")
			LoadBar:TweenSize(UDim2.new(0, 60,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Version..")
			wait(1)
			WhitelistKey.Text = ("Check Function")
			LoadBar:TweenSize(UDim2.new(0, 70,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Function.")
			LoadBar:TweenSize(UDim2.new(0, 80,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Function..")
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key")
			LoadBar:TweenSize(UDim2.new(0, 90,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key.")
			LoadBar:TweenSize(UDim2.new(0, 120,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key..")
			LoadBar:TweenSize(UDim2.new(0, 150,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key.")
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key")
			LoadBar:TweenSize(UDim2.new(0, 190,0, 2))
			wait(1)
			WhitelistKey.Text = ("Correct Key!")
			LoadBar:TweenSize(UDim2.new(0, 265,0, 2))
			LoadBar.ImageColor3 = Color3.new(0.333333, 1, 0.498039)
			wait(0.1)
			EnterKeyOFF:TweenSize(UDim2.new(0, 276,0, 0), "Out", "Sine", 0.5)
			EnterKeyOFF.Text = ("")
			EnterKeyOFF.Icon.Visible = false
			wait(1)
			EnterKey:TweenSize(UDim2.new(0, 276,0, 23), "Out", "Sine", 0.5)
			EnterKey.Text = ("ENTER KEY")
			EnterKey.Visible = true
			Icon.Visible = true
			wait(1)
			UronesHub:TweenSize(UDim2.new(0, 289,0, 0), "Out", "Sine", 0.5)
			EnterKeyOFF.Visible = false
			EnterKey.Visible = false
			LineRGB.Visible = false
			Icon.Visible = false
			UronesHub1.Visible = false
			WhitelistKey.Visible = false
			LoadBarFrame.Visible = false
			LoadBar.Visible = false
			wait(1)
			loadstring(game:HttpGet(('https://raw.githubusercontent.com/9N0I/urones-hub/main/README.md'),true))()
			wait(1)
			print("SCRIPT LOAD.")
			wait(1)
			print("Version : 09.001")
			wait(1)
			print("DISCORD : VcSZWyT4Yv ")
		else
			EnterKey:TweenSize(UDim2.new(0, 276,0, 0), "Out", "Sine", 0.5)
			EnterKey.Text = ("")
			Icon.Visible = false
			wait(1)
			EnterKeyOFF:TweenSize(UDim2.new(0, 276,0, 23), "Out", "Sine", 0.5)
			EnterKeyOFF.Visible = true
			EnterKeyOFF.Icon.Visible = true
			EnterKeyOFF.Text = ("ENTER KEY")
			wait(0.1)
			WhitelistKey.Text = ("Verifylied Players")
			LoadBar:TweenSize(UDim2.new(0, 20,0, 2))
			wait(1)
			WhitelistKey.Text = ("Verifylied Players.")
			LoadBar:TweenSize(UDim2.new(0, 30,0, 2))
			wait(1)
			WhitelistKey.Text = ("Verifylied Players..")
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key")
			LoadBar:TweenSize(UDim2.new(0, 90,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key.")
			LoadBar:TweenSize(UDim2.new(0, 120,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key..")
			LoadBar:TweenSize(UDim2.new(0, 150,0, 2))
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key.")
			wait(1)
			WhitelistKey.Text = ("Check Whitelist Key")
			LoadBar:TweenSize(UDim2.new(0, 190,0, 2))
			wait(1)
			WhitelistKey.Text = ("InCorrect Key!")
			LoadBar:TweenSize(UDim2.new(0, 265,0, 2))
			LoadBar.ImageColor3 = Color3.new(1, 0.133333, 0.145098)
			wait(0.1)
			EnterKeyOFF:TweenSize(UDim2.new(0, 276,0, 0), "Out", "Sine", 0.5)
			EnterKeyOFF.Text = ("")
			EnterKeyOFF.Icon.Visible = false
			wait(1)
			EnterKey:TweenSize(UDim2.new(0, 276,0, 23), "Out", "Sine", 0.5)
			EnterKey.Text = ("ENTER KEY")
			EnterKey.Visible = true
			Icon.Visible = true
			wait(1)
			UronesHub:TweenSize(UDim2.new(0, 289,0, 0), "Out", "Sine", 0.5)
			EnterKeyOFF.Visible = false
			EnterKey.Visible = false
			LineRGB.Visible = false
			Icon.Visible = false
			UronesHub1.Visible = false
			WhitelistKey.Visible = false
			LoadBarFrame.Visible = false
			LoadBar.Visible = false
			wait(0.1)
			Notify:TweenPosition(UDim2.new(0.391, 0, 0.0001, 0), "Out", "Back", 1)
			wait(1)
			loadstring(game:HttpGet(('https://raw.githubusercontent.com/9N0I/urones-hub/main/README.md'),true))()
			print("YOU CAN FIND A KEY IN THIS DISCORD")
			wait(1)
			print("DISCORD : VcSZWyT4Yv ")
		end
	end)
	
	function zigzag(X) return math.acos(math.cos(X*math.pi))/math.pi end
	
	counter = 0
	
	while wait(0.01)do
		LineRGB.ImageColor3 = Color3.fromHSV(zigzag(counter),1,1)
	
		counter = counter + 0.01
	end
