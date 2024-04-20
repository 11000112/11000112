-- Gui to Lua
-- Version: 3.2

-- Instances:

local ZAZOLHUB = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local joinzazolhub = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local hh = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local joinzazolhub_2 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")
local f = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")

--Properties:

ZAZOLHUB.Name = "ZAZOL HUB"
ZAZOLHUB.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ZAZOLHUB.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ZAZOLHUB
Frame.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.239401489, 0, 0.244416878, 0)
Frame.Size = UDim2.new(0, 674, 0, 400)

UICorner.CornerRadius = UDim.new(0.100000001, 5)
UICorner.Parent = Frame

joinzazolhub.Name = "join zazol hub"
joinzazolhub.Parent = Frame
joinzazolhub.BackgroundColor3 = Color3.fromRGB(121, 121, 121)
joinzazolhub.BorderColor3 = Color3.fromRGB(0, 0, 0)
joinzazolhub.BorderSizePixel = 0
joinzazolhub.Position = UDim2.new(0.0459940657, 0, 0.075000003, 0)
joinzazolhub.Size = UDim2.new(0, 214, 0, 66)
joinzazolhub.Font = Enum.Font.Gotham
joinzazolhub.Text = "join zazol hub"
joinzazolhub.TextColor3 = Color3.fromRGB(0, 0, 0)
joinzazolhub.TextSize = 14.000

UICorner_2.CornerRadius = UDim.new(0.100000001, 5)
UICorner_2.Parent = joinzazolhub

hh.Name = "hh"
hh.Parent = Frame
hh.BackgroundColor3 = Color3.fromRGB(121, 121, 121)
hh.BorderColor3 = Color3.fromRGB(0, 0, 0)
hh.BorderSizePixel = 0
hh.Position = UDim2.new(0.0459940657, 0, 0.319999993, 0)
hh.Size = UDim2.new(0, 214, 0, 66)
hh.Font = Enum.Font.Gotham
hh.Text = "chat bypass"
hh.TextColor3 = Color3.fromRGB(0, 0, 0)
hh.TextSize = 14.000

UICorner_3.CornerRadius = UDim.new(0.100000001, 5)
UICorner_3.Parent = hh

joinzazolhub_2.Name = "join zazol hub"
joinzazolhub_2.Parent = Frame
joinzazolhub_2.BackgroundColor3 = Color3.fromRGB(121, 121, 121)
joinzazolhub_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
joinzazolhub_2.BorderSizePixel = 0
joinzazolhub_2.Position = UDim2.new(0.390207708, 0, 0.075000003, 0)
joinzazolhub_2.Size = UDim2.new(0, 214, 0, 66)
joinzazolhub_2.Font = Enum.Font.Gotham
joinzazolhub_2.Text = "join lalol hub"
joinzazolhub_2.TextColor3 = Color3.fromRGB(0, 0, 0)
joinzazolhub_2.TextSize = 14.000

UICorner_4.CornerRadius = UDim.new(0.100000001, 5)
UICorner_4.Parent = joinzazolhub_2

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(145, 145, 145)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.41246292, 0, 0.272500008, 0)
TextBox.Size = UDim2.new(0, 377, 0, 181)
TextBox.Font = Enum.Font.Kalam
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

TextButton.Parent = TextBox
TextButton.BackgroundColor3 = Color3.fromRGB(139, 139, 139)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.225464195, 0, 1.22099447, 0)
TextButton.Size = UDim2.new(0, 146, 0, 55)
TextButton.Font = Enum.Font.Fondamento
TextButton.Text = "Execute"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

f.Name = "f"
f.Parent = Frame
f.BackgroundColor3 = Color3.fromRGB(121, 121, 121)
f.BorderColor3 = Color3.fromRGB(0, 0, 0)
f.BorderSizePixel = 0
f.Position = UDim2.new(0.0459940657, 0, 0.589999974, 0)
f.Size = UDim2.new(0, 214, 0, 66)
f.Font = Enum.Font.Gotham
f.Text = "infinite yield"
f.TextColor3 = Color3.fromRGB(0, 0, 0)
f.TextSize = 14.000

UICorner_5.CornerRadius = UDim.new(0.100000001, 5)
UICorner_5.Parent = f

-- Scripts:

local function CBPXX_fake_script() -- joinzazolhub.Script 
	local script = Instance.new('Script', joinzazolhub)

	script.Parent.MouseButton1Click:Connect(function()
	local copy = "https://discord.gg/XfjNpVYB"
	setclipboard(tostring(copy)) 
	end)
	
end
coroutine.wrap(CBPXX_fake_script)()
local function PMDTLE_fake_script() -- hh.Script 
	local script = Instance.new('Script', hh)

	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Synergy-Networks/products/main/BetterBypasser/loader.lua",true))()
	end)
end
coroutine.wrap(PMDTLE_fake_script)()
local function XZZBLO_fake_script() -- joinzazolhub_2.Script 
	local script = Instance.new('Script', joinzazolhub_2)

	script.Parent.MouseButton1Click:Connect(function()
	local copy = "https://discord.gg/ux3xBqvm"
	setclipboard(tostring(copy)) 
	end)
	
end
coroutine.wrap(XZZBLO_fake_script)()
local function UEPFSO_fake_script() -- TextButton.Script 
	local script = Instance.new('Script', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(script.Parent.Parent.Text)
	end)
end
coroutine.wrap(UEPFSO_fake_script)()
local function ZFRT_fake_script() -- f.Script 
	local script = Instance.new('Script', f)

	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
	end)
end
coroutine.wrap(ZFRT_fake_script)()
local function KGKOS_fake_script() -- Frame.Drag Gui Script 
	local script = Instance.new('LocalScript', Frame)

	function dragify(Main)
	dragToggle = nil
	dragSpeed = 0.95 -- You can edit this.
	dragInput = nil
	dragStart = nil
	dragPos = nil
	
	function updateInput(input)
	Delta = input.Position - dragStart
	Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	game:GetService("TweenService"):Create(Main, TweenInfo.new(.25), {Position = Position}):Play()
	end
	
	Main.InputBegan:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then
	dragToggle = true
	dragStart = input.Position
	startPos = Main.Position
	input.Changed:Connect(function()
	if (input.UserInputState == Enum.UserInputState.End) then
	dragToggle = false
	end
	end)
	end
	end)
	
	Main.InputChanged:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
	dragInput = input
	end
	end)
	
	game:GetService("UserInputService").InputChanged:Connect(function(input)
	if (input == dragInput and dragToggle) then
	updateInput(input)
	end
	end)
	end
	
	dragify(script.Parent)
end
coroutine.wrap(KGKOS_fake_script)()
