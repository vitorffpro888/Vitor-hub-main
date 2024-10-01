-- Vitor Hub: Script Avançado para Blox Fruits no Roblox
-- Funções: Auto Farm, Auto Quest, Auto Raid, entre outras.

local VitorHub = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local AutoFarmToggle = Instance.new("TextButton")
local AutoQuestToggle = Instance.new("TextButton")
local AutoRaidToggle = Instance.new("TextButton")
-- Adicione mais botões para outras funções aqui

-- Configurações da GUI
VitorHub.Name = "VitorHub"
VitorHub.Parent = game.CoreGui
VitorHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainFrame.Name = "MainFrame"
MainFrame.Parent = VitorHub
MainFrame.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
MainFrame.Position = UDim2.new(0.5, -150, 0.5, -200)
MainFrame.Size = UDim2.new(0, 300, 0, 400)
MainFrame.Draggable = true

Title.Name = "Title"
Title.Parent = MainFrame
Title.BackgroundColor3 = Color3.fromRGB(255, 165, 0)
Title.Size = UDim2.new(1, 0, 0.1, 0)
Title.Font = Enum.Font.SourceSansBold
Title.Text = "Vitor Hub"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextScaled = true

-- Botão Auto Farm
AutoFarmToggle.Name = "AutoFarmToggle"
AutoFarmToggle.Parent = MainFrame
AutoFarmToggle.BackgroundColor3 = Color3.fromRGB(255, 165, 0)
AutoFarmToggle.Position = UDim2.new(0.05, 0, 0.15, 0)
AutoFarmToggle.Size = UDim2.new(0.9, 0, 0.1, 0)
AutoFarmToggle.Font = Enum.Font.SourceSans
AutoFarmToggle.Text = "Auto Farm: Off"
AutoFarmToggle.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoFarmToggle.TextScaled = true

-- Botão Auto Quest
AutoQuestToggle.Name = "AutoQuestToggle"
AutoQuestToggle.Parent = MainFrame
AutoQuestToggle.BackgroundColor3 = Color3.fromRGB(255, 165, 0)
AutoQuestToggle.Position = UDim2.new(0.05, 0, 0.3, 0)
AutoQuestToggle.Size = UDim2.new(0.9, 0, 0.1, 0)
AutoQuestToggle.Font = Enum.Font.SourceSans
AutoQuestToggle.Text = "Auto Quest: Off"
AutoQuestToggle.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoQuestToggle.TextScaled = true

-- Botão Auto Raid
