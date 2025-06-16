local Hack = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local UICorner = Instance.new("UICorner")
local VisualButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_8 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_9 = Instance.new("UICorner")
local TextButton_6 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local DFF = Instance.new("TextLabel")
local UICorner_11 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_12 = Instance.new("UICorner")
local TextButton_7 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local AimTriggerButton = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local Frame_3 = Instance.new("Frame")
local TextButton_8 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local UICorner_16 = Instance.new("UICorner")

--Properties:

Hack.Name = "Hack"
Hack.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Hack.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = Hack
Frame.BackgroundColor3 = Color3.fromRGB(67, 8, 97)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.151456311, 0, 0.229102165, 0)
Frame.Size = UDim2.new(0, 407, 0, 346)
Frame.Visible = false
Frame.ZIndex = 0

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(39, 39, 39))}
UIGradient.Rotation = -180
UIGradient.Parent = Frame

UICorner.Parent = Frame

VisualButton.Name = "VisualButton"
VisualButton.Parent = Frame
VisualButton.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
VisualButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
VisualButton.BorderSizePixel = 0
VisualButton.Position = UDim2.new(0.0147822052, 0, 0.0173410401, 0)
VisualButton.Size = UDim2.new(0, 124, 0, 32)
VisualButton.Font = Enum.Font.Fondamento
VisualButton.Text = "ESP - Visual"
VisualButton.TextColor3 = Color3.fromRGB(255, 255, 255)
VisualButton.TextSize = 14.000

UICorner_2.Parent = VisualButton

Frame_2.Parent = VisualButton
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BackgroundTransparency = 1.000
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.0079326015, 0, 1.0625, 0)
Frame_2.Size = UDim2.new(0, 406, 0, 274)

TextButton.Parent = Frame_2
TextButton.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0, 0, 0.655102789, 0)
TextButton.Size = UDim2.new(0, 200, 0, 34)
TextButton.Font = Enum.Font.DenkOne
TextButton.Text = "FreeCam = Shift+p"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

UICorner_3.Parent = TextButton

TextButton_2.Parent = Frame_2
TextButton_2.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0, 0, 0.497038126, 0)
TextButton_2.Size = UDim2.new(0, 200, 0, 34)
TextButton_2.Font = Enum.Font.DenkOne
TextButton_2.Text = " Sky = +"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

UICorner_4.Parent = TextButton_2

TextButton_3.Parent = Frame_2
TextButton_3.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0, 0, 0.345278651, 0)
TextButton_3.Size = UDim2.new(0, 200, 0, 34)
TextButton_3.Font = Enum.Font.DenkOne
TextButton_3.Text = "Big head"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000

UICorner_5.Parent = TextButton_3

TextButton_4.Parent = Frame_2
TextButton_4.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0, 0, 0.0417595319, 0)
TextButton_4.Size = UDim2.new(0, 200, 0, 34)
TextButton_4.Font = Enum.Font.DenkOne
TextButton_4.Text = "ESP"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 14.000

UICorner_6.Parent = TextButton_4

TextButton_5.Parent = Frame_2
TextButton_5.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0, 0, 0.194486856, 0)
TextButton_5.Size = UDim2.new(0, 200, 0, 34)
TextButton_5.Font = Enum.Font.DenkOne
TextButton_5.Text = "ESP Head"
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextSize = 14.000

UICorner_7.Parent = TextButton_5

TextLabel.Parent = Frame_2
TextLabel.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0, 0, 0.959999979, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 34)
TextLabel.Font = Enum.Font.DenkOne
TextLabel.Text = "Transperancy View"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

UICorner_8.Parent = TextLabel

TextLabel_2.Parent = TextLabel
TextLabel_2.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(1.03499997, 0, -0.010587804, 0)
TextLabel_2.Size = UDim2.new(0, 55, 0, 34)
TextLabel_2.Font = Enum.Font.DenkOne
TextLabel_2.Text = "OFF"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

UICorner_9.Parent = TextLabel_2

TextButton_6.Parent = Frame_2
TextButton_6.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextButton_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0.68041873, 0, 0.807272732, 0)
TextButton_6.Size = UDim2.new(0, 35, 0, 34)
TextButton_6.Font = Enum.Font.DenkOne
TextButton_6.Text = ""
TextButton_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.TextSize = 14.000

UICorner_10.Parent = TextButton_6

DFF.Name = "DFF"
DFF.Parent = Frame_2
DFF.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
DFF.BorderColor3 = Color3.fromRGB(0, 0, 0)
DFF.BorderSizePixel = 0
DFF.Position = UDim2.new(-0.00246305414, 0, 0.807272732, 0)
DFF.Size = UDim2.new(0, 200, 0, 34)
DFF.Font = Enum.Font.DenkOne
DFF.Text = "FOV"
DFF.TextColor3 = Color3.fromRGB(0, 0, 0)
DFF.TextSize = 14.000

UICorner_11.Parent = DFF

TextLabel_3.Parent = DFF
TextLabel_3.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(1.03499997, 0, -0.010587804, 0)
TextLabel_3.Size = UDim2.new(0, 55, 0, 34)
TextLabel_3.Font = Enum.Font.DenkOne
TextLabel_3.Text = "OFF"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

UICorner_12.Parent = TextLabel_3

TextButton_7.Parent = Frame_2
TextButton_7.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextButton_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(0.68041873, 0, 0.959999979, 0)
TextButton_7.Size = UDim2.new(0, 35, 0, 34)
TextButton_7.Font = Enum.Font.DenkOne
TextButton_7.Text = ""
TextButton_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.TextSize = 14.000

UICorner_13.Parent = TextButton_7

AimTriggerButton.Name = "AimTriggerButton"
AimTriggerButton.Parent = Frame
AimTriggerButton.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
AimTriggerButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
AimTriggerButton.BorderSizePixel = 0
AimTriggerButton.Position = UDim2.new(0.346477538, 0, 0.0173410401, 0)
AimTriggerButton.Size = UDim2.new(0, 124, 0, 32)
AimTriggerButton.Font = Enum.Font.Fondamento
AimTriggerButton.Text = "AimTrigger"
AimTriggerButton.TextColor3 = Color3.fromRGB(255, 255, 255)
AimTriggerButton.TextSize = 14.000

UICorner_14.Parent = AimTriggerButton

Frame_3.Parent = AimTriggerButton
Frame_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_3.BackgroundTransparency = 1.000
Frame_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.BorderSizePixel = 0
Frame_3.Position = UDim2.new(-1.04851902, 0, 1.0625, 0)
Frame_3.Size = UDim2.new(0, 406, 0, 259)
Frame_3.Visible = false

TextButton_8.Parent = Frame_3
TextButton_8.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
TextButton_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.BorderSizePixel = 0
TextButton_8.Position = UDim2.new(0, 0, 0.0438006185, 0)
TextButton_8.Size = UDim2.new(0, 200, 0, 34)
TextButton_8.Font = Enum.Font.DenkOne
TextButton_8.Text = "AimBot"
TextButton_8.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.TextSize = 14.000

UICorner_15.Parent = TextButton_8

TextLabel_4.Parent = Frame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
TextLabel_4.BackgroundTransparency = 0.700
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.678132653, 0, 0.0173410401, 0)
TextLabel_4.Size = UDim2.new(0, 123, 0, 32)
TextLabel_4.Font = Enum.Font.Fondamento
TextLabel_4.Text = "Legit Hack"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 28.000

UICorner_16.Parent = TextLabel_4

-- Scripts:

local function CCILYCQ_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		--Converted with ttyyuu12345's model to script plugin v4
		function sandbox(var,func)
			local env = getfenv(func)
			local newenv = setmetatable({},{
				__index = function(self,k)
					if k=="script" then
						return var
					else
						return env[k]
					end
				end,
			})
			setfenv(func,newenv)
			return func
		end
		cors = {}
		mas = Instance.new("Model",game:GetService("Lighting"))
		LocalScript0 = Instance.new("LocalScript")
		LocalScript0.Name = "FreeCamera"
		LocalScript0.Parent = mas
		table.insert(cors,sandbox(LocalScript0,function()
			-----------------------------------------------------------------------
			-- Freecam
			-- Cinematic free camera for spectating and video production.
			------------------------------------------------------------------------
	
			local pi    = math.pi
			local abs   = math.abs
			local clamp = math.clamp
			local exp   = math.exp
			local rad   = math.rad
			local sign  = math.sign
			local sqrt  = math.sqrt
			local tan   = math.tan
	
			local ContextActionService = game:GetService("ContextActionService")
			local Players = game:GetService("Players")
			local RunService = game:GetService("RunService")
			local StarterGui = game:GetService("StarterGui")
			local UserInputService = game:GetService("UserInputService")
	
			local LocalPlayer = Players.LocalPlayer
			if not LocalPlayer then
				Players:GetPropertyChangedSignal("LocalPlayer"):Wait()
				LocalPlayer = Players.LocalPlayer
			end
	
			local Camera = workspace.CurrentCamera
			workspace:GetPropertyChangedSignal("CurrentCamera"):Connect(function()
				local newCamera = workspace.CurrentCamera
				if newCamera then
					Camera = newCamera
				end
			end)
	
			------------------------------------------------------------------------
	
			local TOGGLE_INPUT_PRIORITY = Enum.ContextActionPriority.Low.Value
			local INPUT_PRIORITY = Enum.ContextActionPriority.High.Value
			local FREECAM_MACRO_KB = {Enum.KeyCode.LeftShift, Enum.KeyCode.P}
	
			local NAV_GAIN = Vector3.new(1, 1, 1)*64
			local PAN_GAIN = Vector2.new(0.75, 1)*8
			local FOV_GAIN = 300
	
			local PITCH_LIMIT = rad(90)
	
			local VEL_STIFFNESS = 1.5
			local PAN_STIFFNESS = 1.0
			local FOV_STIFFNESS = 4.0
	
			------------------------------------------------------------------------
	
			local Spring = {} do
				Spring.__index = Spring
	
				function Spring.new(freq, pos)
					local self = setmetatable({}, Spring)
					self.f = freq
					self.p = pos
					self.v = pos*0
					return self
				end
	
				function Spring:Update(dt, goal)
					local f = self.f*2*pi
					local p0 = self.p
					local v0 = self.v
	
					local offset = goal - p0
					local decay = exp(-f*dt)
	
					local p1 = goal + (v0*dt - offset*(f*dt + 1))*decay
					local v1 = (f*dt*(offset*f - v0) + v0)*decay
	
					self.p = p1
					self.v = v1
	
					return p1
				end
	
				function Spring:Reset(pos)
					self.p = pos
					self.v = pos*0
				end
			end
	
			------------------------------------------------------------------------
	
			local cameraPos = Vector3.new()
			local cameraRot = Vector2.new()
			local cameraFov = 0
	
			local velSpring = Spring.new(VEL_STIFFNESS, Vector3.new())
			local panSpring = Spring.new(PAN_STIFFNESS, Vector2.new())
			local fovSpring = Spring.new(FOV_STIFFNESS, 0)
	
			------------------------------------------------------------------------
	
			local Input = {} do
				local thumbstickCurve do
					local K_CURVATURE = 2.0
					local K_DEADZONE = 0.15
	
					local function fCurve(x)
						return (exp(K_CURVATURE*x) - 1)/(exp(K_CURVATURE) - 1)
					end
	
					local function fDeadzone(x)
						return fCurve((x - K_DEADZONE)/(1 - K_DEADZONE))
					end
	
					function thumbstickCurve(x)
						return sign(x)*clamp(fDeadzone(abs(x)), 0, 1)
					end
				end
	
				local gamepad = {
					ButtonX = 0,
					ButtonY = 0,
					DPadDown = 0,
					DPadUp = 0,
					ButtonL2 = 0,
					ButtonR2 = 0,
					Thumbstick1 = Vector2.new(),
					Thumbstick2 = Vector2.new(),
				}
	
				local keyboard = {
					W = 0,
					A = 0,
					S = 0,
					D = 0,
					E = 0,
					Q = 0,
					U = 0,
					H = 0,
					J = 0,
					K = 0,
					I = 0,
					Y = 0,
					Up = 0,
					Down = 0,
					LeftShift = 0,
					RightShift = 0,
				}
	
				local mouse = {
					Delta = Vector2.new(),
					MouseWheel = 0,
				}
	
				local NAV_GAMEPAD_SPEED  = Vector3.new(1, 1, 1)
				local NAV_KEYBOARD_SPEED = Vector3.new(1, 1, 1)
				local PAN_MOUSE_SPEED    = Vector2.new(1, 1)*(pi/64)
				local PAN_GAMEPAD_SPEED  = Vector2.new(1, 1)*(pi/8)
				local FOV_WHEEL_SPEED    = 1.0
				local FOV_GAMEPAD_SPEED  = 0.25
				local NAV_ADJ_SPEED      = 0.75
				local NAV_SHIFT_MUL      = 0.25
	
				local navSpeed = 1
	
				function Input.Vel(dt)
					navSpeed = clamp(navSpeed + dt*(keyboard.Up - keyboard.Down)*NAV_ADJ_SPEED, 0.01, 4)
	
					local kGamepad = Vector3.new(
						thumbstickCurve(gamepad.Thumbstick1.x),
						thumbstickCurve(gamepad.ButtonR2) - thumbstickCurve(gamepad.ButtonL2),
						thumbstickCurve(-gamepad.Thumbstick1.y)
					)*NAV_GAMEPAD_SPEED
	
					local kKeyboard = Vector3.new(
						keyboard.D - keyboard.A + keyboard.K - keyboard.H,
						keyboard.E - keyboard.Q + keyboard.I - keyboard.Y,
						keyboard.S - keyboard.W + keyboard.J - keyboard.U
					)*NAV_KEYBOARD_SPEED
	
					local shift = UserInputService:IsKeyDown(Enum.KeyCode.LeftShift) or UserInputService:IsKeyDown(Enum.KeyCode.RightShift)
	
					return (kGamepad + kKeyboard)*(navSpeed*(shift and NAV_SHIFT_MUL or 1))
				end
	
				function Input.Pan(dt)
					local kGamepad = Vector2.new(
						thumbstickCurve(gamepad.Thumbstick2.y),
						thumbstickCurve(-gamepad.Thumbstick2.x)
					)*PAN_GAMEPAD_SPEED
					local kMouse = mouse.Delta*PAN_MOUSE_SPEED
					mouse.Delta = Vector2.new()
					return kGamepad + kMouse
				end
	
				function Input.Fov(dt)
					local kGamepad = (gamepad.ButtonX - gamepad.ButtonY)*FOV_GAMEPAD_SPEED
					local kMouse = mouse.MouseWheel*FOV_WHEEL_SPEED
					mouse.MouseWheel = 0
					return kGamepad + kMouse
				end
	
				do
					local function Keypress(action, state, input)
						keyboard[input.KeyCode.Name] = state == Enum.UserInputState.Begin and 1 or 0
						return Enum.ContextActionResult.Sink
					end
	
					local function GpButton(action, state, input)
						gamepad[input.KeyCode.Name] = state == Enum.UserInputState.Begin and 1 or 0
						return Enum.ContextActionResult.Sink
					end
	
					local function MousePan(action, state, input)
						local delta = input.Delta
						mouse.Delta = Vector2.new(-delta.y, -delta.x)
						return Enum.ContextActionResult.Sink
					end
	
					local function Thumb(action, state, input)
						gamepad[input.KeyCode.Name] = input.Position
						return Enum.ContextActionResult.Sink
					end
	
					local function Trigger(action, state, input)
						gamepad[input.KeyCode.Name] = input.Position.z
						return Enum.ContextActionResult.Sink
					end
	
					local function MouseWheel(action, state, input)
						mouse[input.UserInputType.Name] = -input.Position.z
						return Enum.ContextActionResult.Sink
					end
	
					local function Zero(t)
						for k, v in pairs(t) do
							t[k] = v*0
						end
					end
	
					function Input.StartCapture()
						ContextActionService:BindActionAtPriority("FreecamKeyboard", Keypress, false, INPUT_PRIORITY,
							Enum.KeyCode.W, Enum.KeyCode.U,
							Enum.KeyCode.A, Enum.KeyCode.H,
							Enum.KeyCode.S, Enum.KeyCode.J,
							Enum.KeyCode.D, Enum.KeyCode.K,
							Enum.KeyCode.E, Enum.KeyCode.I,
							Enum.KeyCode.Q, Enum.KeyCode.Y,
							Enum.KeyCode.Up, Enum.KeyCode.Down
						)
						ContextActionService:BindActionAtPriority("FreecamMousePan",          MousePan,   false, INPUT_PRIORITY, Enum.UserInputType.MouseMovement)
						ContextActionService:BindActionAtPriority("FreecamMouseWheel",        MouseWheel, false, INPUT_PRIORITY, Enum.UserInputType.MouseWheel)
						ContextActionService:BindActionAtPriority("FreecamGamepadButton",     GpButton,   false, INPUT_PRIORITY, Enum.KeyCode.ButtonX, Enum.KeyCode.ButtonY)
						ContextActionService:BindActionAtPriority("FreecamGamepadTrigger",    Trigger,    false, INPUT_PRIORITY, Enum.KeyCode.ButtonR2, Enum.KeyCode.ButtonL2)
						ContextActionService:BindActionAtPriority("FreecamGamepadThumbstick", Thumb,      false, INPUT_PRIORITY, Enum.KeyCode.Thumbstick1, Enum.KeyCode.Thumbstick2)
					end
	
					function Input.StopCapture()
						navSpeed = 1
						Zero(gamepad)
						Zero(keyboard)
						Zero(mouse)
						ContextActionService:UnbindAction("FreecamKeyboard")
						ContextActionService:UnbindAction("FreecamMousePan")
						ContextActionService:UnbindAction("FreecamMouseWheel")
						ContextActionService:UnbindAction("FreecamGamepadButton")
						ContextActionService:UnbindAction("FreecamGamepadTrigger")
						ContextActionService:UnbindAction("FreecamGamepadThumbstick")
					end
				end
			end
	
			local function GetFocusDistance(cameraFrame)
				local znear = 0.1
				local viewport = Camera.ViewportSize
				local projy = 2*tan(cameraFov/2)
				local projx = viewport.x/viewport.y*projy
				local fx = cameraFrame.rightVector
				local fy = cameraFrame.upVector
				local fz = cameraFrame.lookVector
	
				local minVect = Vector3.new()
				local minDist = 512
	
				for x = 0, 1, 0.5 do
					for y = 0, 1, 0.5 do
						local cx = (x - 0.5)*projx
						local cy = (y - 0.5)*projy
						local offset = fx*cx - fy*cy + fz
						local origin = cameraFrame.p + offset*znear
						local part, hit = workspace:FindPartOnRay(Ray.new(origin, offset.unit*minDist))
						local dist = (hit - origin).magnitude
						if minDist > dist then
							minDist = dist
							minVect = offset.unit
						end
					end
				end
	
				return fz:Dot(minVect)*minDist
			end
	
			------------------------------------------------------------------------
	
			local function StepFreecam(dt)
				local vel = velSpring:Update(dt, Input.Vel(dt))
				local pan = panSpring:Update(dt, Input.Pan(dt))
				local fov = fovSpring:Update(dt, Input.Fov(dt))
	
				local zoomFactor = sqrt(tan(rad(70/2))/tan(rad(cameraFov/2)))
	
				cameraFov = clamp(cameraFov + fov*FOV_GAIN*(dt/zoomFactor), 1, 120)
				cameraRot = cameraRot + pan*PAN_GAIN*(dt/zoomFactor)
				cameraRot = Vector2.new(clamp(cameraRot.x, -PITCH_LIMIT, PITCH_LIMIT), cameraRot.y%(2*pi))
	
				local cameraCFrame = CFrame.new(cameraPos)*CFrame.fromOrientation(cameraRot.x, cameraRot.y, 0)*CFrame.new(vel*NAV_GAIN*dt)
				cameraPos = cameraCFrame.p
	
				Camera.CFrame = cameraCFrame
				Camera.Focus = cameraCFrame*CFrame.new(0, 0, -GetFocusDistance(cameraCFrame))
				Camera.FieldOfView = cameraFov
			end
	
			------------------------------------------------------------------------
	
			local PlayerState = {} do
				local mouseIconEnabled
				local cameraSubject
				local cameraType
				local cameraFocus
				local cameraCFrame
				local cameraFieldOfView
				local screenGuis = {}
				local coreGuis = {
					Backpack = true,
					Chat = true,
					Health = true,
					PlayerList = true,
				}
				local setCores = {
					BadgesNotificationsActive = true,
					PointsNotificationsActive = true,
				}
	
				-- Save state and set up for freecam
				function PlayerState.Push()
					for name in pairs(coreGuis) do
						coreGuis[name] = StarterGui:GetCoreGuiEnabled(Enum.CoreGuiType[name])
						StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType[name], false)
					end
					for name in pairs(setCores) do
						setCores[name] = StarterGui:GetCore(name)
						StarterGui:SetCore(name, false)
					end
					local playergui = LocalPlayer:FindFirstChildOfClass("PlayerGui")
					if playergui then
						for _, gui in pairs(playergui:GetChildren()) do
							if gui:IsA("ScreenGui") and gui.Enabled then
								screenGuis[#screenGuis + 1] = gui
								gui.Enabled = false
							end
						end
					end
	
					cameraFieldOfView = Camera.FieldOfView
					Camera.FieldOfView = 70
	
					cameraType = Camera.CameraType
					Camera.CameraType = Enum.CameraType.Custom
	
					cameraSubject = Camera.CameraSubject
					Camera.CameraSubject = nil
	
					cameraCFrame = Camera.CFrame
					cameraFocus = Camera.Focus
	
					mouseIconEnabled = UserInputService.MouseIconEnabled
					UserInputService.MouseIconEnabled = false
	
					mouseBehavior = UserInputService.MouseBehavior
					UserInputService.MouseBehavior = Enum.MouseBehavior.Default
				end
	
				-- Restore state
				function PlayerState.Pop()
					for name, isEnabled in pairs(coreGuis) do
						StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType[name], isEnabled)
					end
					for name, isEnabled in pairs(setCores) do
						StarterGui:SetCore(name, isEnabled)
					end
					for _, gui in pairs(screenGuis) do
						if gui.Parent then
							gui.Enabled = true
						end
					end
	
					Camera.FieldOfView = cameraFieldOfView
					cameraFieldOfView = nil
	
					Camera.CameraType = cameraType
					cameraType = nil
	
					Camera.CameraSubject = cameraSubject
					cameraSubject = nil
	
					Camera.CFrame = cameraCFrame
					cameraCFrame = nil
	
					Camera.Focus = cameraFocus
					cameraFocus = nil
	
					UserInputService.MouseIconEnabled = mouseIconEnabled
					mouseIconEnabled = nil
	
					UserInputService.MouseBehavior = mouseBehavior
					mouseBehavior = nil
				end
			end
	
			local function StartFreecam()
				local cameraCFrame = Camera.CFrame
				cameraRot = Vector2.new(cameraCFrame:toEulerAnglesYXZ())
				cameraPos = cameraCFrame.p
				cameraFov = Camera.FieldOfView
	
				velSpring:Reset(Vector3.new())
				panSpring:Reset(Vector2.new())
				fovSpring:Reset(0)
	
				PlayerState.Push()
				RunService:BindToRenderStep("Freecam", Enum.RenderPriority.Camera.Value, StepFreecam)
				Input.StartCapture()
			end
	
			local function StopFreecam()
				Input.StopCapture()
				RunService:UnbindFromRenderStep("Freecam")
				PlayerState.Pop()
			end
	
			------------------------------------------------------------------------
	
			do
				local enabled = false
	
				local function ToggleFreecam()
					if enabled then
						StopFreecam()
					else
						StartFreecam()
					end
					enabled = not enabled
				end
	
				local function CheckMacro(macro)
					for i = 1, #macro - 1 do
						if not UserInputService:IsKeyDown(macro[i]) then
							return
						end
					end
					ToggleFreecam()
				end
	
				local function HandleActivationInput(action, state, input)
					if state == Enum.UserInputState.Begin then
						if input.KeyCode == FREECAM_MACRO_KB[#FREECAM_MACRO_KB] then
							CheckMacro(FREECAM_MACRO_KB)
						end
					end
					return Enum.ContextActionResult.Pass
				end
	
				ContextActionService:BindActionAtPriority("FreecamToggle", HandleActivationInput, false, TOGGLE_INPUT_PRIORITY, FREECAM_MACRO_KB[#FREECAM_MACRO_KB])
			end
		end))
		for i,v in pairs(mas:GetChildren()) do
			v.Parent = game:GetService("Players").LocalPlayer.PlayerGui
			pcall(function() v:MakeJoints() end)
		end
		mas:Destroy()
		for i,v in pairs(cors) do
			spawn(function()
				pcall(v)
			end)
		end
	end)
end
coroutine.wrap(CCILYCQ_fake_script)()
local function AVJZGG_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		sky = Instance.new("Sky",game:GetService("Lighting"))
		sky.SkyboxBk = "rbxassetid://654808887"
		sky.SkyboxFt = "rbxassetid://654808760"
		sky.SkyboxLf = "rbxassetid://654809248"
		sky.SkyboxRt = "rbxassetid://654809043"
		sky.SkyboxUp = "rbxassetid://654808635"
	end)
end
coroutine.wrap(AVJZGG_fake_script)()
local function OOBWL_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		local SelectPart = "Head"
		local HBSizeX = 14
		local HBSizeY = 14
		local HBSizeZ = 14
		local HBTrans = 0.3
	
		local PurpleColor = BrickColor.new("Really red")
	
		local hitboxlist1 = {}
	
		local RunService = game:GetService("RunService")  
	
		task.spawn(function ()
			while wait(0.1) do
				for v, i in pairs(workspace:GetChildren()) do
					if i:FindFirstChild("HumanoidRootPart") and not i:FindFirstChild("Fake1") then
						local FakeHead = Instance.new("Part", i)
						FakeHead.CFrame = i.Head.CFrame
						FakeHead.Name = SelectPart
						FakeHead.Size = Vector3.new(HBSizeX, HBSizeY, HBSizeZ)
						FakeHead.Anchored = true
						FakeHead.CanCollide = false
						FakeHead.Transparency = HBTrans
						FakeHead.BrickColor = PurpleColor
						local subndom = Instance.new("Part", i)
						subndom.Name = "Fake1"
						table.insert(hitboxlist1, FakeHead)
						table.insert(hitboxlist1, subndom)
						for d, obj in ipairs(hitboxlist1) do
							print(i, obj) 
						end
					end
				end
			end
		end)
	end)
end
coroutine.wrap(OOBWL_fake_script)()
local function XBWFZE_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		local BoxESP = {}
		function BoxESP.Create(Player)
			local Box = Drawing.new("Square")
			Box.Visible = false
			Box.Color = Color3.fromRGB(255, 255, 255)
			Box.Filled = true
			Box.Transparency = 0.40
			Box.Thickness = 1
	
			local Updater
	
			local function UpdateBox()
				if Player and Player:IsA("Model") and Player:FindFirstChild("HumanoidRootPart") and Player:FindFirstChild("Head") then
					local Target2dPosition, IsVisible = workspace.CurrentCamera:WorldToViewportPoint(Player.HumanoidRootPart.Position)
					local scale_factor = 1 / (Target2dPosition.Z * math.tan(math.rad(workspace.CurrentCamera.FieldOfView * 0.5)) * 2) * 100
					local width, height = math.floor(30 * scale_factor), math.floor(30 * scale_factor)
					Box.Visible = IsVisible
					Box.Size = Vector2.new(width, height)
					Box.Position = Vector2.new(Target2dPosition.X - Box.Size.X / 2, Target2dPosition.Y - Box.Size.Y / 2)
				else
					Box.Visible = false
					if not Player then
						Box:Remove()
						Updater:Disconnect()
					end
				end
			end
	
			Updater = game:GetService("RunService").RenderStepped:Connect(UpdateBox)
	
			return Box
		end
	
		local Boxes = {}
	
		local function EnableBoxESP()
			for _, Player in pairs(game:GetService("Workspace"):GetChildren()) do
				if Player:IsA("Model") and Player:FindFirstChild("HumanoidRootPart") and Player:FindFirstChild("Head") then
					local Box = BoxESP.Create(Player)
					table.insert(Boxes, Box)
				end
			end
		end
	
		game.Workspace.DescendantAdded:Connect(function(i)
			if i:IsA("Model") and i:FindFirstChild("HumanoidRootPart") and i:FindFirstChild("Head") then
				local Box = BoxESP.Create(i)
				table.insert(Boxes, Box)
			end
		end)
	
		EnableBoxESP()
	end)
end
coroutine.wrap(XBWFZE_fake_script)()
local function JFVHAZ_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
		local BoxESP = {}
		function BoxESP.Create(Player)
			local Box = Drawing.new("Square")
			Box.Visible = false
			Box.Color = Color3.fromRGB(255, 0, 4)
			Box.Filled = true
			Box.Transparency = 0.30
			Box.Thickness = 1
	
			local Updater
	
			local function UpdateBox()
				if Player and Player:IsA("Model") and Player:FindFirstChild("Head") and Player:FindFirstChild("Head") then
					local Target2dPosition, IsVisible = workspace.CurrentCamera:WorldToViewportPoint(Player.Head.Position)
					local scale_factor = 1 / (Target2dPosition.Z * math.tan(math.rad(workspace.CurrentCamera.FieldOfView * 0.5)) * 2) * 100
					local width, height = math.floor(12 * scale_factor), math.floor(12 * scale_factor)
					Box.Visible = IsVisible
					Box.Size = Vector2.new(width, height)
					Box.Position = Vector2.new(Target2dPosition.X - Box.Size.X / 2, Target2dPosition.Y - Box.Size.Y / 2)
				else
					Box.Visible = false
					if not Player then
						Box:Remove()
						Updater:Disconnect()
					end
				end
			end
	
			Updater = game:GetService("RunService").RenderStepped:Connect(UpdateBox)
	
			return Box
		end
	
		local Boxes = {}
	
		local function EnableBoxESP()
			for _, Player in pairs(game:GetService("Workspace"):GetChildren()) do
				if Player:IsA("Model") and Player:FindFirstChild("Head") and Player:FindFirstChild("Head") then
					local Box = BoxESP.Create(Player)
					table.insert(Boxes, Box)
				end
			end
		end
	
		game.Workspace.DescendantAdded:Connect(function(i)
			if i:IsA("Model") and i:FindFirstChild("Head") and i:FindFirstChild("Head") then
				local Box = BoxESP.Create(i)
				table.insert(Boxes, Box)
			end
		end)
	
		EnableBoxESP()
	end)
end
coroutine.wrap(JFVHAZ_fake_script)()
local function ZRDDPQ_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.new(0,255,0) then
			 script.Parent.BackgroundColor3 = Color3.new(255, 0, 0)
			script.Parent.Parent.DFF.TextLabel.Text = "OFF"
				_G.FOVChangerConnection = _G.FOVChangerConnection or nil
	
				if _G.FOVChangerConnection then
					_G.FOVChangerConnection:Disconnect()
					_G.FOVChangerConnection = nil
				end
	
				local camera = workspace.Camera
	
				_G.FOVChangerConnection = camera:GetPropertyChangedSignal("FieldOfView"):Connect(function()
					if camera.FieldOfView ~= 70 then
						camera.FieldOfView = 70
					end
				end)
	
				camera.FieldOfView = 70
	    else
			script.Parent.BackgroundColor3 = Color3.new(0,255,0)
			script.Parent.Parent.DFF.TextLabel.Text = "ON"
			_G.FOVChangerConnection = _G.FOVChangerConnection or nil
	
			if _G.FOVChangerConnection then
				_G.FOVChangerConnection:Disconnect()
				_G.FOVChangerConnection = nil
			end
	
			local camera = workspace.Camera
	
			_G.FOVChangerConnection = camera:GetPropertyChangedSignal("FieldOfView"):Connect(function()
				if camera.FieldOfView ~= 100 then
					camera.FieldOfView = 100
				end
			end)
	
			camera.FieldOfView = 100
	    end
	end)
end
coroutine.wrap(ZRDDPQ_fake_script)()
local function ORKQU_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.new(0,255,0) then
			 script.Parent.BackgroundColor3 = Color3.new(255, 0, 0)
			script.Parent.Parent.TextLabel.TextLabel.Text = "OFF"
			workspace.Const.Ignore.FPSArms.Fake.c_LeftLowerArm.BrickColor = BrickColor.new("Earth green")
			workspace.Const.Ignore.FPSArms.Fake.c_LeftLowerArm.Transparency = 0
			workspace.Const.Ignore.FPSArms.Fake.c_RightLowerArm.BrickColor = BrickColor.new("Earth green")
			workspace.Const.Ignore.FPSArms.Fake.c_RightLowerArm.Transparency = 0
			workspace.Const.Ignore.FPSArms.RightLowerArm.BrickColor = BrickColor.new("Earth green")
			workspace.Const.Ignore.FPSArms.RightLowerArm.Transparency = 0
			workspace.Const.Ignore.FPSArms.RightHand.BrickColor = BrickColor.new("Earth green")
			workspace.Const.Ignore.FPSArms.RightHand.Transparency = 0
	    else
			  script.Parent.BackgroundColor3 = Color3.new(0,255,0)
			script.Parent.Parent.TextLabel.TextLabel.Text = "ON"
			workspace.Const.Ignore.FPSArms.Fake.c_LeftLowerArm.BrickColor = BrickColor.new("Really red")
			workspace.Const.Ignore.FPSArms.Fake.c_LeftLowerArm.Transparency = 0.5
			workspace.Const.Ignore.FPSArms.Fake.c_RightLowerArm.BrickColor = BrickColor.new("Really red")
			workspace.Const.Ignore.FPSArms.Fake.c_RightLowerArm.Transparency = 0.5
			workspace.Const.Ignore.FPSArms.RightLowerArm.BrickColor = BrickColor.new("Really red")
			workspace.Const.Ignore.FPSArms.RightLowerArm.Transparency = 0.5
			workspace.Const.Ignore.FPSArms.RightHand.BrickColor = BrickColor.new("Really red")
			workspace.Const.Ignore.FPSArms.RightHand.Transparency = 0.5
	    end
	end)
end
coroutine.wrap(ORKQU_fake_script)()
local function QSCPEKG_fake_script() -- VisualButton.LocalScript 
	local script = Instance.new('LocalScript', VisualButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Frame.Visible == false then
			script.Parent.Frame.Visible = true
			script.Parent.Parent.AimTriggerButton.Frame.Visible = false
		else
			script.Parent.Frame.Visible = false
		end
	end)
end
coroutine.wrap(QSCPEKG_fake_script)()
local function MMNNYO_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	script.Parent.MouseButton1Click:Connect(function()
		local circle = Drawing.new("Circle")
		circle.Visible = true
		circle.Radius = 30
		circle.Color = Color3.fromRGB(11, 210, 255)
		circle.Transparency = 1
		circle.Thickness = 1
		circle.Position = Vector2.new(workspace.CurrentCamera.ViewportSize.X/2, workspace.CurrentCamera.ViewportSize.Y/2)
		local smoothFactor = 2
		local function getHeadScreenPosition(character)
			local head = character:FindFirstChild("Head")
			if head then
				local screenPos, visible = workspace.CurrentCamera:WorldToViewportPoint(head.Position)
				return Vector2.new(screenPos.X, screenPos.Y), visible
			end
			return nil, false
		end
	
		local function findClosestPlayerInCircle()
			local closestPlayer = nil
			local closestDistance = math.huge
			local mousePos = circle.Position
	
			for _, model in ipairs(workspace:GetChildren()) do
				if model and model:IsA("Model") and model:FindFirstChild("HumanoidRootPart") and model:FindFirstChild("Head") then
					local headPos, visible = getHeadScreenPosition(model)
					if visible and headPos then
						local distance = (headPos - mousePos).Magnitude
						if distance <= circle.Radius and distance < closestDistance then
							closestDistance = distance
							closestPlayer = model
						end
					end
				end
			end
			return closestPlayer
		end
		game:GetService("RunService").RenderStepped:Connect(function()
			circle.Position = Vector2.new(workspace.CurrentCamera.ViewportSize.X/2, workspace.CurrentCamera.ViewportSize.Y/2)
	
			if game:GetService("UserInputService"):IsMouseButtonPressed(Enum.UserInputType.MouseButton2) then
				local target = findClosestPlayerInCircle()
				if target then
					local head = target:FindFirstChild("Head")
					if head then
						local screenPos = workspace.CurrentCamera:WorldToViewportPoint(head.Position)
						local targetPos = Vector2.new(screenPos.X, screenPos.Y)
						local currentPos = game:GetService("UserInputService"):GetMouseLocation()
						local delta = (targetPos - currentPos) * smoothFactor
						mousemoverel(delta.X, delta.Y)
					end
				end
			end
		end)
	end)
end
coroutine.wrap(MMNNYO_fake_script)()
local function DJDGAW_fake_script() -- AimTriggerButton.LocalScript 
	local script = Instance.new('LocalScript', AimTriggerButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Frame.Visible == false then
			script.Parent.Frame.Visible = true
			script.Parent.Parent.VisualButton.Frame.Visible = false
		else
			script.Parent.Frame.Visible = false
		end
	end)
end
coroutine.wrap(DJDGAW_fake_script)()
local function TNHJFVN_fake_script() -- Frame.Drag 
	local script = Instance.new('LocalScript', Frame)

	local parent: Frame = script.Parent
	parent.Draggable = true
	parent.Selectable = true
	parent.Active = true
end
coroutine.wrap(TNHJFVN_fake_script)()
local function LGZEDYI_fake_script() -- Hack.LocalScript 
	local script = Instance.new('LocalScript', Hack)

	local userInputService = game:GetService("UserInputService")
	
	userInputService.InputBegan:Connect(function(input, gameProcessedEvent)
		if input.UserInputType == Enum.UserInputType.Keyboard then
			if input.KeyCode == Enum.KeyCode.RightAlt then
				if script.Parent.Frame.Visible == true then
					script.Parent.Frame.Visible = false
				else
					script.Parent.Frame.Visible = true
				end
			end
		end
	end)
end
coroutine.wrap(LGZEDYI_fake_script)()
