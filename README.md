local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local AutoFarmButton = Instance.new("TextButton")
local AutoV4Button = Instance.new("TextButton")
local AutoSeaFarmButton = Instance.new("TextButton")

ScreenGui.Name = "ABSOLUTE HUB"
ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
Frame.Position = UDim2.new(0.5, -100, 0.5, -100)
Frame.Size = UDim2.new(0, 200, 0, 200)

AutoFarmButton.Parent = Frame
AutoFarmButton.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
AutoFarmButton.Size = UDim2.new(0, 180, 0, 40)
AutoFarmButton.Position = UDim2.new(0, 10, 0, 10)
AutoFarmButton.Text = "Auto Farm"
AutoFarmButton.MouseButton1Click:Connect(function()
    print("Auto Farm ativado")
    -- Código de auto farm aqui
end)

AutoV4Button.Parent = Frame
AutoV4Button.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
AutoV4Button.Size = UDim2.new(0, 180, 0, 40)
AutoV4Button.Position = UDim2.new(0, 10, 0, 60)
AutoV4Button.Text = "Auto V4"
AutoV4Button.MouseButton1Click:Connect(function()
    print("Auto V4 ativado")
    -- Código de auto V4 aqui
end)

AutoSeaFarmButton.Parent = Frame
AutoSeaFarmButton.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
AutoSeaFarmButton.Size = UDim2.new(0, 180, 0, 40)
AutoSeaFarmButton.Position = UDim2.new(0, 10, 0, 110)
AutoSeaFarmButton.Text = "Auto Farm Sea"
AutoSeaFarmButton.MouseButton1Click:Connect(function()
    print("Auto Farm Sea ativado")
    -- Código de auto farm sea aqui
end)
