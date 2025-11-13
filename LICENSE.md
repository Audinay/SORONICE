--SORONICE
--https://discord.gg/S3GpUTKm
--Appelez-moi pour tout problème
--Toujours en création

local ScreenGui = Instance.new("ScreenGui")
local PopUp_FRM = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local Button = Instance.new("TextButton")
local UIGradient_2 = Instance.new("UIGradient")
local UICorner_2 = Instance.new("UICorner")
local Button_2 = Instance.new("TextButton")
local UIGradient_3 = Instance.new("UIGradient")
local UICorner_3 = Instance.new("UICorner")
local Button_3 = Instance.new("TextButton")
local UIGradient_4 = Instance.new("UIGradient")
local UICorner_4 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UITextSizeConstraint = Instance.new("UITextSizeConstraint")
local TextLabel_2 = Instance.new("TextLabel")
local Button_4 = Instance.new("TextButton")
local UIGradient_5 = Instance.new("UIGradient")
local UICorner_5 = Instance.new("UICorner")
local Button_5 = Instance.new("TextButton")
local UIGradient_6 = Instance.new("UIGradient")
local UICorner_6 = Instance.new("UICorner")
local Button_6 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local UIGradient_7 = Instance.new("UIGradient")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

PopUp_FRM.Name = "PopUp_FRM"
PopUp_FRM.Parent = ScreenGui
PopUp_FRM.BackgroundColor3 = Color3.fromRGB(147, 147, 147)
PopUp_FRM.BorderColor3 = Color3.fromRGB(0, 0, 0)
PopUp_FRM.BorderSizePixel = 0
PopUp_FRM.Position = UDim2.new(0.035796687, 0, 0.142337754, 0)
PopUp_FRM.Size = UDim2.new(0.252932549, 0, 0.741124272, 0)
PopUp_FRM.Visible = false

UICorner.Parent = PopUp_FRM

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Rotation = -79.94999694824219
UIGradient.Parent = PopUp_FRM

Button.Name = "Button"
Button.Parent = PopUp_FRM
Button.BackgroundColor3 = Color3.fromRGB(147, 147, 147)
Button.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button.BorderSizePixel = 0
Button.Position = UDim2.new(0.0856152847, 0, 0.119545974, 0)
Button.Size = UDim2.new(0.823188484, 0, 0.117717139, 0)
Button.Font = Enum.Font.Unknown
Button.Text = "..."
Button.TextColor3 = Color3.fromRGB(0, 0, 0)
Button.TextScaled = true
Button.TextSize = 14.000
Button.TextWrapped = true

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(98, 98, 98)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_2.Rotation = -90
UIGradient_2.Parent = Button

UICorner_2.Parent = Button

Button_2.Name = "Button"
Button_2.Parent = PopUp_FRM
Button_2.BackgroundColor3 = Color3.fromRGB(147, 147, 147)
Button_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button_2.BorderSizePixel = 0
Button_2.Position = UDim2.new(0.0786053985, 0, 0.708624959, 0)
Button_2.Size = UDim2.new(0.823188424, 0, 0.0990509093, 0)
Button_2.Font = Enum.Font.Unknown
Button_2.Text = "..."
Button_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Button_2.TextScaled = true
Button_2.TextSize = 14.000
Button_2.TextWrapped = true

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(98, 98, 98)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_3.Rotation = -90
UIGradient_3.Parent = Button_2

UICorner_3.Parent = Button_2

Button_3.Name = "Button"
Button_3.Parent = PopUp_FRM
Button_3.BackgroundColor3 = Color3.fromRGB(147, 147, 147)
Button_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button_3.BorderSizePixel = 0
Button_3.Position = UDim2.new(0.0856153667, 0, 0.42773506, 0)
Button_3.Size = UDim2.new(0.823188424, 0, 0.101717524, 0)
Button_3.Font = Enum.Font.Unknown
Button_3.Text = "..."
Button_3.TextColor3 = Color3.fromRGB(0, 0, 0)
Button_3.TextScaled = true
Button_3.TextSize = 14.000
Button_3.TextWrapped = true

UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(98, 98, 98)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_4.Rotation = -90
UIGradient_4.Parent = Button_3

UICorner_4.Parent = Button_3

TextLabel.Parent = PopUp_FRM
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0827169642, 0, -0.0885196775, 0)
TextLabel.Size = UDim2.new(0.808695674, 0, 0.169660673, 0)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "SORONICE"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UITextSizeConstraint.Parent = TextLabel
UITextSizeConstraint.MaxTextSize = 85

TextLabel_2.Parent = PopUp_FRM
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.228677154, 0, 0.866645992, 0)
TextLabel_2.Size = UDim2.new(0.527536213, 0, 0.107052006, 0)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "..."
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

Button_4.Name = "Button"
Button_4.Parent = PopUp_FRM
Button_4.BackgroundColor3 = Color3.fromRGB(147, 147, 147)
Button_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button_4.BorderSizePixel = 0
Button_4.Position = UDim2.new(0.0856153667, 0, 0.566158056, 0)
Button_4.Size = UDim2.new(0.823188424, 0, 0.101717524, 0)
Button_4.Font = Enum.Font.Unknown
Button_4.Text = "..."
Button_4.TextColor3 = Color3.fromRGB(0, 0, 0)
Button_4.TextScaled = true
Button_4.TextSize = 14.000
Button_4.TextWrapped = true

UIGradient_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(98, 98, 98)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_5.Rotation = -90
UIGradient_5.Parent = Button_4

UICorner_5.Parent = Button_4

Button_5.Name = "Button"
Button_5.Parent = PopUp_FRM
Button_5.BackgroundColor3 = Color3.fromRGB(147, 147, 147)
Button_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button_5.BorderSizePixel = 0
Button_5.Position = UDim2.new(0.0821103826, 0, 0.281968415, 0)
Button_5.Size = UDim2.new(0.823188424, 0, 0.0990509093, 0)
Button_5.Font = Enum.Font.Unknown
Button_5.Text = "..."
Button_5.TextColor3 = Color3.fromRGB(0, 0, 0)
Button_5.TextScaled = true
Button_5.TextSize = 14.000
Button_5.TextWrapped = true

UIGradient_6.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(98, 98, 98)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_6.Rotation = -90
UIGradient_6.Parent = Button_5

UICorner_6.Parent = Button_5

Button_6.Name = "Button"
Button_6.Parent = ScreenGui
Button_6.BackgroundColor3 = Color3.fromRGB(85, 255, 119)
Button_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button_6.BorderSizePixel = 0
Button_6.Position = UDim2.new(0.46238181, 0, 0.0257852823, 0)
Button_6.Size = UDim2.new(0, 80, 0, 50)
Button_6.Font = Enum.Font.SourceSansBold
Button_6.Text = "Admin"
Button_6.TextColor3 = Color3.fromRGB(255, 255, 255)
Button_6.TextScaled = true
Button_6.TextSize = 100.000
Button_6.TextStrokeTransparency = 1.110
Button_6.TextWrapped = true

UICorner_7.Parent = Button_6

UIGradient_7.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(108, 191, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_7.Rotation = -90
UIGradient_7.Parent = Button_6

-- Scripts:

local function DYAKSJ_fake_script() -- Button.InfiniteJumpButton 
	local script = Instance.new('LocalScript', Button)

	local button = script.Parent
	local Players = game:GetService("Players")
	local UserInputService = game:GetService("UserInputService")
	
	local infiniteJumpEnabled = false
	local jumpConnection = nil
	
	local function enableInfiniteJump()
	    if jumpConnection then return end
	    jumpConnection = UserInputService.JumpRequest:Connect(function()
	        local player = Players.LocalPlayer
	        local character = player.Character or player.CharacterAdded:Wait()
	        local humanoid = character:FindFirstChildOfClass("Humanoid")
	        if humanoid then
	            humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	        end
	    end)
	end
	
	local function disableInfiniteJump()
	    if jumpConnection then
	        jumpConnection:Disconnect()
	        jumpConnection = nil
	    end
	end
	
	button.MouseButton1Click:Connect(function()
	    infiniteJumpEnabled = not infiniteJumpEnabled
	    if infiniteJumpEnabled then
	        enableInfiniteJump()
	        button.Text = "Infinite Jump "
	    else
	        disableInfiniteJump()
	        button.Text = "Infinite Jump "
	    end
	end)
	
	-- Optional: Set initial button text
	button.Text = "Infinite Jump "
	
	
end
coroutine.wrap(DYAKSJ_fake_script)()
local function PUOKK_fake_script() -- Button.Tween 
	local script = Instance.new('LocalScript', Button)

	--// This is a hover & click effect, i suggest you test this on pc. because it requires a mouse for hovering over the button.
	
	local btn = script.Parent
	local TS = game:GetService("TweenService")
	
	local origSize = btn.Size
	local hoverScl = 1.1
	local clickScl = 0.9
	local tInfo = TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut)
	
	local function makeTween(scl)
		local newSize = UDim2.new(
			origSize.X.Scale * scl,
			origSize.X.Offset * scl,
			origSize.Y.Scale * scl,
			origSize.Y.Offset * scl
		)
		return TS:Create(btn, tInfo, {Size = newSize})
	end
	
	btn.MouseEnter:Connect(function()
		makeTween(hoverScl):Play()
	end)
	
	btn.MouseLeave:Connect(function()
		makeTween(1):Play()
	end)
	
	btn.MouseButton1Click:Connect(function()
		local shrink = makeTween(clickScl)
		local reset = makeTween(1)
		shrink:Play()
		shrink.Completed:Connect(function()
			reset:Play()
		end)
	end)
end
coroutine.wrap(PUOKK_fake_script)()
local function HSWH_fake_script() -- Button_2.Tween 
	local script = Instance.new('LocalScript', Button_2)

	--// This is a hover & click effect, i suggest you test this on pc. because it requires a mouse for hovering over the button.
	
	local btn = script.Parent
	local TS = game:GetService("TweenService")
	
	local origSize = btn.Size
	local hoverScl = 1.1
	local clickScl = 0.9
	local tInfo = TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut)
	
	local function makeTween(scl)
		local newSize = UDim2.new(
			origSize.X.Scale * scl,
			origSize.X.Offset * scl,
			origSize.Y.Scale * scl,
			origSize.Y.Offset * scl
		)
		return TS:Create(btn, tInfo, {Size = newSize})
	end
	
	btn.MouseEnter:Connect(function()
		makeTween(hoverScl):Play()
	end)
	
	btn.MouseLeave:Connect(function()
		makeTween(1):Play()
	end)
	
	btn.MouseButton1Click:Connect(function()
		local shrink = makeTween(clickScl)
		local reset = makeTween(1)
		shrink:Play()
		shrink.Completed:Connect(function()
			reset:Play()
		end)
	end)
end
coroutine.wrap(HSWH_fake_script)()
local function ERRTND_fake_script() -- Button_2.FlyButton 
	local script = Instance.new('LocalScript', Button_2)

	local button = script.Parent
	local Players = game:GetService("Players")
	local UserInputService = game:GetService("UserInputService")
	local flyEnabled = false
	local flyConnection = nil
	local moveDirection = Vector3.new()
	local bodyVelocity = nil
	
	local function getCharacter()
	    local player = Players.LocalPlayer
	    return player.Character or player.CharacterAdded:Wait()
	end
	
	local function enableFly()
	    local character = getCharacter()
	    local humanoid = character:FindFirstChildOfClass("Humanoid")
	    if not humanoid then return end
	    humanoid.PlatformStand = true
	
	    local rootPart = character:FindFirstChild("HumanoidRootPart")
	    if not rootPart then return end
	
	    bodyVelocity = Instance.new("BodyVelocity")
	    bodyVelocity.MaxForce = Vector3.new(1e5, 1e5, 1e5)
	    bodyVelocity.Velocity = Vector3.new()
	    bodyVelocity.Parent = rootPart
	
	    flyConnection = UserInputService.InputBegan:Connect(function(input, processed)
	        if processed then return end
	        if input.KeyCode == Enum.KeyCode.W then
	            moveDirection = Vector3.new(0, 0, -1)
	        elseif input.KeyCode == Enum.KeyCode.S then
	            moveDirection = Vector3.new(0, 0, 1)
	        elseif input.KeyCode == Enum.KeyCode.A then
	            moveDirection = Vector3.new(-1, 0, 0)
	        elseif input.KeyCode == Enum.KeyCode.D then
	            moveDirection = Vector3.new(1, 0, 0)
	        elseif input.KeyCode == Enum.KeyCode.Space then
	            moveDirection = Vector3.new(0, 1, 0)
	        elseif input.KeyCode == Enum.KeyCode.LeftControl then
	            moveDirection = Vector3.new(0, -1, 0)
	        end
	    end)
	
	    UserInputService.InputEnded:Connect(function(input)
	        if input.KeyCode == Enum.KeyCode.W or input.KeyCode == Enum.KeyCode.S or
	           input.KeyCode == Enum.KeyCode.A or input.KeyCode == Enum.KeyCode.D or
	           input.KeyCode == Enum.KeyCode.Space or input.KeyCode == Enum.KeyCode.LeftControl then
	            moveDirection = Vector3.new()
	        end
	    end)
	
	    -- Update velocity every frame
	    local runService = game:GetService("RunService")
	    bodyVelocity.Velocity = Vector3.new()
	    bodyVelocity._updateConn = runService.RenderStepped:Connect(function()
	        if bodyVelocity and rootPart then
	            local cam = workspace.CurrentCamera
	            local dir = moveDirection
	            -- Move relative to camera direction
	            local moveVec = Vector3.new()
	            if dir.Z ~= 0 then
	                moveVec = moveVec + cam.CFrame.LookVector * dir.Z
	            end
	            if dir.X ~= 0 then
	                moveVec = moveVec + cam.CFrame.RightVector * dir.X
	            end
	            if dir.Y ~= 0 then
	                moveVec = moveVec + Vector3.new(0, dir.Y, 0)
	            end
	            bodyVelocity.Velocity = moveVec.Unit * 50
	        end
	    end)
	end
	
	local function disableFly()
	    local character = getCharacter()
	    local humanoid = character:FindFirstChildOfClass("Humanoid")
	    if humanoid then
	        humanoid.PlatformStand = false
	    end
	    local rootPart = character:FindFirstChild("HumanoidRootPart")
	    if bodyVelocity then
	        if bodyVelocity._updateConn then
	            bodyVelocity._updateConn:Disconnect()
	        end
	        bodyVelocity:Destroy()
	        bodyVelocity = nil
	    end
	    if flyConnection then
	        flyConnection:Disconnect()
	        flyConnection = nil
	    end
	    moveDirection = Vector3.new()
	end
	
	button.MouseButton1Click:Connect(function()
	    flyEnabled = not flyEnabled
	    if flyEnabled then
	        enableFly()
			button.Text = "kill"
	    else
	        disableFly()
			button.Text = "kill"
	    end
	end)
	
	button.Text = "kill"
	
	
end
coroutine.wrap(ERRTND_fake_script)()
local function BHIB_fake_script() -- Button_3.NoclipButton 
	local script = Instance.new('LocalScript', Button_3)

	local button = script.Parent
	local Players = game:GetService("Players")
	
	local noclipEnabled = false
	local noclipConnection = nil
	
	local function setNoclip(enabled)
	    local player = Players.LocalPlayer
	    local character = player.Character or player.CharacterAdded:Wait()
	    for i, part in character:GetChildren() do
	        if part:IsA("BasePart") then
	            part.CanCollide = not enabled
	        end
	    end
	end
	
	local function enableNoclip()
	    if noclipConnection then return end
	    noclipConnection = game:GetService("RunService").Stepped:Connect(function()
	        setNoclip(true)
	    end)
	end
	
	local function disableNoclip()
	    if noclipConnection then
	        noclipConnection:Disconnect()
	        noclipConnection = nil
	    end
	    setNoclip(false)
	end
	
	button.MouseButton1Click:Connect(function()
	    noclipEnabled = not noclipEnabled
	    if noclipEnabled then
	        enableNoclip()
	        button.Text = "Noclip: ON"
	    else
	        disableNoclip()
	        button.Text = "Noclip: OFF"
	    end
	end)
	
	button.Text = "Noclip: OFF"
	
	
end
coroutine.wrap(BHIB_fake_script)()
local function GWTC_fake_script() -- Button_3.Tween 
	local script = Instance.new('LocalScript', Button_3)

	--// This is a hover & click effect, i suggest you test this on pc. because it requires a mouse for hovering over the button.
	
	local btn = script.Parent
	local TS = game:GetService("TweenService")
	
	local origSize = btn.Size
	local hoverScl = 1.1
	local clickScl = 0.9
	local tInfo = TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut)
	
	local function makeTween(scl)
		local newSize = UDim2.new(
			origSize.X.Scale * scl,
			origSize.X.Offset * scl,
			origSize.Y.Scale * scl,
			origSize.Y.Offset * scl
		)
		return TS:Create(btn, tInfo, {Size = newSize})
	end
	
	btn.MouseEnter:Connect(function()
		makeTween(hoverScl):Play()
	end)
	
	btn.MouseLeave:Connect(function()
		makeTween(1):Play()
	end)
	
	btn.MouseButton1Click:Connect(function()
		local shrink = makeTween(clickScl)
		local reset = makeTween(1)
		shrink:Play()
		shrink.Completed:Connect(function()
			reset:Play()
		end)
	end)
end
coroutine.wrap(GWTC_fake_script)()
local function KVMMY_fake_script() -- TextLabel_2.ShowFPS 
	local script = Instance.new('LocalScript', TextLabel_2)

	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local frameCount = 0
	local fps = 0
	
	-- Count frames every RenderStepped
	RunService.RenderStepped:Connect(function()
	    frameCount = frameCount + 1
	end)
	
	-- Update FPS every second
	while true do
	    task.wait(1)
	    fps = frameCount
	    frameCount = 0
	    textLabel.Text = "FPS: " .. fps
	end
	
	
end
coroutine.wrap(KVMMY_fake_script)()
local function PFFGA_fake_script() -- Button_4.RedCharacterButton 
	local script = Instance.new('LocalScript', Button_4)

	local button = script.Parent
	local Players = game:GetService("Players")
	
	local function setCharacterRed()
	    local player = Players.LocalPlayer
	    local character = player.Character or player.CharacterAdded:Wait()
	    for i, part in character:GetChildren() do
	        if part:IsA("BasePart") then
	            part.Color = Color3.new(1, 0, 0)
	        end
	    end
	end
	
	button.MouseButton1Click:Connect(function()
	    setCharacterRed()
	end)
	
	button.Text = "Mettre en rouge"
	
	
end
coroutine.wrap(PFFGA_fake_script)()
local function FWNDXR_fake_script() -- Button_4.Tween 
	local script = Instance.new('LocalScript', Button_4)

	--// This is a hover & click effect, i suggest you test this on pc. because it requires a mouse for hovering over the button.
	
	local btn = script.Parent
	local TS = game:GetService("TweenService")
	
	local origSize = btn.Size
	local hoverScl = 1.1
	local clickScl = 0.9
	local tInfo = TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut)
	
	local function makeTween(scl)
		local newSize = UDim2.new(
			origSize.X.Scale * scl,
			origSize.X.Offset * scl,
			origSize.Y.Scale * scl,
			origSize.Y.Offset * scl
		)
		return TS:Create(btn, tInfo, {Size = newSize})
	end
	
	btn.MouseEnter:Connect(function()
		makeTween(hoverScl):Play()
	end)
	
	btn.MouseLeave:Connect(function()
		makeTween(1):Play()
	end)
	
	btn.MouseButton1Click:Connect(function()
		local shrink = makeTween(clickScl)
		local reset = makeTween(1)
		shrink:Play()
		shrink.Completed:Connect(function()
			reset:Play()
		end)
	end)
end
coroutine.wrap(FWNDXR_fake_script)()
local function PBEYRM_fake_script() -- Button_5.Tween 
	local script = Instance.new('LocalScript', Button_5)

	--// This is a hover & click effect, i suggest you test this on pc. because it requires a mouse for hovering over the button.
	
	local btn = script.Parent
	local TS = game:GetService("TweenService")
	
	local origSize = btn.Size
	local hoverScl = 1.1
	local clickScl = 0.9
	local tInfo = TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut)
	
	local function makeTween(scl)
		local newSize = UDim2.new(
			origSize.X.Scale * scl,
			origSize.X.Offset * scl,
			origSize.Y.Scale * scl,
			origSize.Y.Offset * scl
		)
		return TS:Create(btn, tInfo, {Size = newSize})
	end
	
	btn.MouseEnter:Connect(function()
		makeTween(hoverScl):Play()
	end)
	
	btn.MouseLeave:Connect(function()
		makeTween(1):Play()
	end)
	
	btn.MouseButton1Click:Connect(function()
		local shrink = makeTween(clickScl)
		local reset = makeTween(1)
		shrink:Play()
		shrink.Completed:Connect(function()
			reset:Play()
		end)
	end)
end
coroutine.wrap(PBEYRM_fake_script)()
local function CVNMT_fake_script() -- Button_5.FlyScriptLoaderOnButtonClick 
	local script = Instance.new('LocalScript', Button_5)

	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
	    -- WARNING: loadstring and HttpGet are not available in standard Roblox games!
	    -- This code will only work in exploit environments or with special permissions.
	    local success, err = pcall(function()
	        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	    end)
	    if not success then
	        warn("Failed to execute FlyScript: " .. tostring(err))
	    end
	end)
	
	
end
coroutine.wrap(CVNMT_fake_script)()
local function QNNITOU_fake_script() -- Button_5.SetButtonNameToFly 
	local script = Instance.new('LocalScript', Button_5)

	local button = script.Parent
	button.Text = "fly"
	
	
end
coroutine.wrap(QNNITOU_fake_script)()
local function CANDS_fake_script() -- Button_6.TogglePopUpVisibility 
	local script = Instance.new('LocalScript', Button_6)

	local button = script.Parent
	local screenGui = button.Parent
	local popUp = screenGui:FindFirstChild("PopUp_FRM")
	local TweenService = game:GetService("TweenService")
	
	local isVisible = false
	
	-- Store the original position of PopUp_FRM
	local originalPosition
	local offscreenPosition
	local tweenTime = 0.4
	
	if popUp then
	    originalPosition = popUp.Position
	    -- Move offscreen by increasing Y scale (moves down, but keeps X unchanged)
	    offscreenPosition = UDim2.new(originalPosition.X.Scale, originalPosition.X.Offset, originalPosition.Y.Scale + 1, originalPosition.Y.Offset)
	    popUp.Visible = false
	    popUp.Position = offscreenPosition
	end
	
	button.MouseButton1Click:Connect(function()
	    if not popUp then return end
	    isVisible = not isVisible
	
	    if isVisible then
	        popUp.Visible = true
	        -- Animate upwards to original position, set upright
	        local tweenUp = TweenService:Create(popUp, TweenInfo.new(tweenTime, Enum.EasingStyle.Quad, Enum.EasingDirection.Out), {Position = originalPosition, Rotation = 0})
	        tweenUp:Play()
	    else
	        -- Animate downwards (offscreen), then hide
	        local tweenDown = TweenService:Create(popUp, TweenInfo.new(tweenTime, Enum.EasingStyle.Quad, Enum.EasingDirection.In), {Position = offscreenPosition})
	        tweenDown:Play()
	        tweenDown.Completed:Connect(function()
	            popUp.Visible = false
	        end)
	    end
	end)
	
	
end
coroutine.wrap(CANDS_fake_script)()
