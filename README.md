local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local AIMButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local ESPButton = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local INFButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local PowerButton = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local PowerButton_2 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local SpeedButton = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local SpeedButton_2 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local infinytyviButton = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local timeButton = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(46, 32, 54)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.3282516, 0, 0.176108927, 0)
Frame.Size = UDim2.new(0, 467, 0, 264)
Frame.Visible = false

UICorner.CornerRadius = UDim.new(0, 5)
UICorner.Parent = Frame

UIGradient.Offset = Vector2.new(1, 1)
UIGradient.Rotation = 124
UIGradient.Parent = Frame

AIMButton.Name = "AIMButton"
AIMButton.Parent = Frame
AIMButton.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
AIMButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
AIMButton.BorderSizePixel = 0
AIMButton.Position = UDim2.new(0.259100646, 0, 0.49926272, 0)
AIMButton.Size = UDim2.new(0, 94, 0, 50)
AIMButton.Font = Enum.Font.FredokaOne
AIMButton.Text = "AIM BOT"
AIMButton.TextColor3 = Color3.fromRGB(0, 0, 0)
AIMButton.TextSize = 13.000

UICorner_2.Parent = AIMButton

ESPButton.Name = "ESPButton"
ESPButton.Parent = Frame
ESPButton.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
ESPButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ESPButton.BorderSizePixel = 0
ESPButton.Position = UDim2.new(0.0278372597, 0, 0.49926272, 0)
ESPButton.Size = UDim2.new(0, 94, 0, 50)
ESPButton.Font = Enum.Font.FredokaOne
ESPButton.Text = "ESP"
ESPButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ESPButton.TextSize = 13.000

UICorner_3.Parent = ESPButton

INFButton.Name = "INFButton"
INFButton.Parent = Frame
INFButton.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
INFButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
INFButton.BorderSizePixel = 0
INFButton.Position = UDim2.new(0.0278372597, 0, 0.734853327, 0)
INFButton.Size = UDim2.new(0, 94, 0, 50)
INFButton.Font = Enum.Font.FredokaOne
INFButton.Text = "InfinitiJump"
INFButton.TextColor3 = Color3.fromRGB(0, 0, 0)
INFButton.TextSize = 13.000

UICorner_4.Parent = INFButton

PowerButton.Name = "PowerButton"
PowerButton.Parent = Frame
PowerButton.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
PowerButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
PowerButton.BorderSizePixel = 0
PowerButton.Position = UDim2.new(0.259100646, 0, 0.278355449, 0)
PowerButton.Size = UDim2.new(0, 94, 0, 50)
PowerButton.Font = Enum.Font.FredokaOne
PowerButton.Text = "Jump defalt"
PowerButton.TextColor3 = Color3.fromRGB(0, 0, 0)
PowerButton.TextSize = 13.000

UICorner_5.Parent = PowerButton

PowerButton_2.Name = "PowerButton"
PowerButton_2.Parent = Frame
PowerButton_2.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
PowerButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
PowerButton_2.BorderSizePixel = 0
PowerButton_2.Position = UDim2.new(0.0278372597, 0, 0.278355449, 0)
PowerButton_2.Size = UDim2.new(0, 94, 0, 50)
PowerButton_2.Font = Enum.Font.FredokaOne
PowerButton_2.Text = "PowerJump"
PowerButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
PowerButton_2.TextSize = 13.000

UICorner_6.Parent = PowerButton_2

SpeedButton.Name = "SpeedButton"
SpeedButton.Parent = Frame
SpeedButton.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
SpeedButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
SpeedButton.BorderSizePixel = 0
SpeedButton.Position = UDim2.new(0.0278372597, 0, 0.0392117351, 0)
SpeedButton.Size = UDim2.new(0, 94, 0, 50)
SpeedButton.Font = Enum.Font.FredokaOne
SpeedButton.Text = "Speed"
SpeedButton.TextColor3 = Color3.fromRGB(0, 0, 0)
SpeedButton.TextSize = 20.000

UICorner_7.Parent = SpeedButton

SpeedButton_2.Name = "SpeedButton"
SpeedButton_2.Parent = Frame
SpeedButton_2.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
SpeedButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
SpeedButton_2.BorderSizePixel = 0
SpeedButton_2.Position = UDim2.new(0.259100646, 0, 0.0392117351, 0)
SpeedButton_2.Size = UDim2.new(0, 94, 0, 50)
SpeedButton_2.Font = Enum.Font.FredokaOne
SpeedButton_2.Text = "Speed Defalt"
SpeedButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
SpeedButton_2.TextSize = 13.000

UICorner_8.Parent = SpeedButton_2

infinytyviButton.Name = "infinytyviButton"
infinytyviButton.Parent = Frame
infinytyviButton.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
infinytyviButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
infinytyviButton.BorderSizePixel = 0
infinytyviButton.Position = UDim2.new(0.259100646, 0, 0.734853327, 0)
infinytyviButton.Size = UDim2.new(0, 94, 0, 50)
infinytyviButton.Font = Enum.Font.FredokaOne
infinytyviButton.Text = "InfinitiVield"
infinytyviButton.TextColor3 = Color3.fromRGB(0, 0, 0)
infinytyviButton.TextSize = 13.000

UICorner_9.Parent = infinytyviButton

timeButton.Name = "timeButton"
timeButton.Parent = Frame
timeButton.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
timeButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
timeButton.BorderSizePixel = 0
timeButton.Position = UDim2.new(0.495092094, 0, 0.734853327, 0)
timeButton.Size = UDim2.new(0, 216, 0, 50)
timeButton.Font = Enum.Font.FredokaOne
timeButton.Text = "Time"
timeButton.TextColor3 = Color3.fromRGB(0, 0, 0)
timeButton.TextSize = 13.000

UICorner_10.Parent = timeButton

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.490809441, 0, 0.0354430377, 0)
ImageLabel.Size = UDim2.new(0, 221, 0, 161)
ImageLabel.Image = "http://www.roblox.com/asset/?id=77163394425184"

TextLabel.Parent = ImageLabel
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.208144799, 0, 0.0372670814, 0)
TextLabel.Size = UDim2.new(0, 83, 0, 41)
TextLabel.Font = Enum.Font.Fondamento
TextLabel.Text = "DIE"
TextLabel.TextColor3 = Color3.fromRGB(111, 0, 0)
TextLabel.TextSize = 62.000

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(42, 40, 40)
TextButton.BackgroundTransparency = 0.250
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.414906591, 0, 0.965405405, -10)
TextButton.Size = UDim2.new(0, 200, 0, 23)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "closed"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

UICorner_11.CornerRadius = UDim.new(2, 0)
UICorner_11.Parent = TextButton

-- Scripts:

local function GDQWV_fake_script() -- AIMButton.LocalScript 
	local script = Instance.new('LocalScript', AIMButton)

	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Aimbot-V3/main/src/Aimbot.lua"))()
	ExunysDeveloperAimbot()
	end)
end
coroutine.wrap(GDQWV_fake_script)()
local function QQQQG_fake_script() -- ESPButton.LocalScript 
	local script = Instance.new('LocalScript', ESPButton)

	script.Parent.MouseButton1Click:Connect(function()
		while wait(0.5) do
			for i, childrik in ipairs(workspace:GetDescendants()) do
				if childrik:FindFirstChild("Humanoid") then
					if not childrik:FindFirstChild("EspBox") then
						if childrik ~= game.Players.LocalPlayer.Character then
							local esp = Instance.new("BoxHandleAdornment",childrik)
							esp.Adornee = childrik
							esp.ZIndex = 0
							esp.Size = Vector3.new(4, 5, 1)
							esp.Transparency = 0.65
							esp.Color3 = Color3.fromRGB(255,48,48)
							esp.AlwaysOnTop = true
							esp.Name = "EspBox"
						end
					end
				end
			end
		end
	end)
end
coroutine.wrap(QQQQG_fake_script)()
local function ZGRYWGM_fake_script() -- INFButton.LocalScript 
	local script = Instance.new('LocalScript', INFButton)

	script.Parent.MouseButton1Click:Connect(function()
		local Player = game:GetService'Players'.LocalPlayer;
		local UIS = game:GetService'UserInputService';
	
		_G.JumpHeight = 50;
	
		function Action(Object, Function) if Object ~= nil then Function(Object); end end
	
		UIS.InputBegan:connect(function(UserInput)
			if UserInput.UserInputType == Enum.UserInputType.Keyboard and UserInput.KeyCode == Enum.KeyCode.Space then
				Action(Player.Character.Humanoid, function(self)
					if self:GetState() == Enum.HumanoidStateType.Jumping or self:GetState() == Enum.HumanoidStateType.Freefall then
						Action(self.Parent.HumanoidRootPart, function(self)
							self.Velocity = Vector3.new(0, _G.JumpHeight, 0);
						end)
					end
				end)
			end
		end)
	end)
end
coroutine.wrap(ZGRYWGM_fake_script)()
local function FVXD_fake_script() -- PowerButton.LocalScript 
	local script = Instance.new('LocalScript', PowerButton)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.JumpHeight = 7.2
	end)
end
coroutine.wrap(FVXD_fake_script)()
local function WSDXMRD_fake_script() -- PowerButton_2.LocalScript 
	local script = Instance.new('LocalScript', PowerButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.JumpHeight = 50
	end)
end
coroutine.wrap(WSDXMRD_fake_script)()
local function PZLJVDV_fake_script() -- SpeedButton.LocalScript 
	local script = Instance.new('LocalScript', SpeedButton)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
	end)
end
coroutine.wrap(PZLJVDV_fake_script)()
local function HZGZRK_fake_script() -- SpeedButton_2.LocalScript 
	local script = Instance.new('LocalScript', SpeedButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
	end)
end
coroutine.wrap(HZGZRK_fake_script)()
local function ZLZTTI_fake_script() -- infinytyviButton.LocalScript 
	local script = Instance.new('LocalScript', infinytyviButton)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/DarkNetworks/Infinite-Yield/main/latest.lua'))()
	end)
end
coroutine.wrap(ZLZTTI_fake_script)()
local function RDYSW_fake_script() -- timeButton.LocalScript 
	local script = Instance.new('LocalScript', timeButton)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/yofriendfromschool1/Sky-Hub/main/SkyHub.txt"))()
	end)
end
coroutine.wrap(RDYSW_fake_script)()
local function BONTH_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.Frame.Visible == false then
			script.Parent.Parent.Frame.Visible = true
		else
			script.Parent.Parent.Frame.Visible = false
		end
	end)
end
coroutine.wrap(BONTH_fake_script)()
