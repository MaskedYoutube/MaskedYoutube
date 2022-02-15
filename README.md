-- Made By Masked with honor.

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local title = Instance.new("TextLabel")
local BUTTONBUTTON = Instance.new("TextButton")
local CLOSE = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
local OPENMAIN = Instance.new("Frame")
local OPEN = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(255, 74, 42)
main.Position = UDim2.new(0.408879727, 0, 0.335319161, 0)
main.Size = UDim2.new(0, 450, 0, 280)
main.Visible = false
main.Active = true
main.Draggable = true

title.Name = "title"
title.Parent = main
title.BackgroundColor3 = Color3.fromRGB(95, 67, 255)
title.Position = UDim2.new(0, 0, -0.153571442, 0)
title.Size = UDim2.new(0, 450, 0, 42)
title.Font = Enum.Font.SciFi
title.Text = "Someone's HACK   GUI "
title.TextColor3 = Color3.fromRGB(0, 0, 0)
title.TextSize = 14.000
NAMEOFBUTTONHERE.MouseButton1Down:connect(function()
	Scripthere
end)

BUTTONBUTTON.Name = "BUTTON BUTTON"
BUTTONBUTTON.Parent = main
BUTTONBUTTON.BackgroundColor3 = Color3.fromRGB(34, 255, 71)
BUTTONBUTTON.BorderColor3 = Color3.fromRGB(9, 15, 53)
BUTTONBUTTON.Size = UDim2.new(0, 200, 0, 50)
BUTTONBUTTON.Font = Enum.Font.GothamBold
BUTTONBUTTON.Text = "HORROR MUSIC"
BUTTONBUTTON.TextColor3 = Color3.fromRGB(0, 0, 0)
BUTTONBUTTON.TextSize = 14.000
BUTTONBUTTON.MouseButton1Down:connect(function()
	Scripthere
end)

CLOSE.Name = "CLOSE"
CLOSE.Parent = main
CLOSE.BackgroundColor3 = Color3.fromRGB(255, 51, 174)
CLOSE.Position = UDim2.new(0.888888776, 0, -0.150000006, 0)
CLOSE.Size = UDim2.new(0, 50, 0, 42)
CLOSE.Font = Enum.Font.SourceSans
CLOSE.Text = "X"
CLOSE.TextColor3 = Color3.fromRGB(0, 0, 0)
CLOSE.TextScaled = true
CLOSE.TextSize = 14.000
CLOSE.TextWrapped = true
	close.MouseButton1Down:connect(function()
	main.Visible = false
	openmain.Visible = true
end)

TextButton.Parent = main
TextButton.BackgroundColor3 = Color3.fromRGB(255, 79, 48)
TextButton.Position = UDim2.new(0.675271034, 0, 0.342978746, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.GothamBold
TextButton.Text = "GOD MODE"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000
NAMEOFBUTTONHERE.MouseButton1Down:connect(function()
	Scripthere
end)

OPENMAIN.Name = "OPENMAIN"
OPENMAIN.Parent = ScreenGui
OPENMAIN.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OPENMAIN.Position = UDim2.new(0.119772844, 0, 0.3506383, 0)
OPENMAIN.Size = UDim2.new(0, 109, 0, 42)
OPENMAIN.Active = true
OPENMAIN.Draggable = true
NAMEOFBUTTONHERE.MouseButton1Down:connect(function()
	Scripthere
end)

OPEN.Name = "OPEN"
OPEN.Parent = OPENMAIN
OPEN.BackgroundColor3 = Color3.fromRGB(255, 62, 62)
OPEN.Position = UDim2.new(-0.00114899129, 0, -0.017460227, 0)
OPEN.Size = UDim2.new(0, 111, 0, 43)
OPEN.Font = Enum.Font.GothamBold
OPEN.Text = "OPEN"
OPEN.TextColor3 = Color3.fromRGB(0, 0, 0)
OPEN.TextSize = 15.000
OPEN.TextWrapped = true
OPEN.MouseButton1Down:connect(function()
	OPENMAIN.Visible = false
	main.Visible = true
end)

