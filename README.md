-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local ScriptGuiMain = Instance.new("Frame")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local close = Instance.new("ImageButton")
local remove = Instance.new("ImageButton")
local Frame_2 = Instance.new("Frame")
local Frame_3 = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local Frame_4 = Instance.new("Frame")
local PlayerImage = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")
local UICorner_2 = Instance.new("UICorner")
local Avisador = Instance.new("TextLabel")
local PlayerName = Instance.new("TextLabel")
local PlayerName_2 = Instance.new("TextLabel")
local ImageLabel_2 = Instance.new("ImageLabel")
local UICorner_3 = Instance.new("UICorner")
local PlayerName_3 = Instance.new("TextLabel")
local Script1Frame = Instance.new("Frame")
local minomgui = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Bloxfruit = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local infinityyield = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local silentaimpl = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Monkeyadmin = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local Redadmin = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local spammfoda = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local rangesword = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local raceclicker = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local Petsim2 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local silentaimpl_2 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local silentaimpl_3 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local shindolife = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local yourbizzarre = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local roghoul = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local demonfall = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local beeswarm = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local projectslayer = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local Script2Frame = Instance.new("Frame")
local navigate_before = Instance.new("ImageButton")
local OpenButton = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local Shadow = Instance.new("Frame")
local UICorner_23 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer("loaded  | Made by Gab & Shadow", "All")


ScriptGuiMain.Name = "ScriptGuiMain"
ScriptGuiMain.Parent = ScreenGui
ScriptGuiMain.Active = true
ScriptGuiMain.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
ScriptGuiMain.BorderColor3 = Color3.fromRGB(12, 12, 12)
ScriptGuiMain.Position = UDim2.new(0.204224333, 0, 0.282855332, 0)
ScriptGuiMain.Size = UDim2.new(0, 617, 0, 466)
ScriptGuiMain.Visible = false
ScriptGuiMain.Draggable = true

Frame.Parent = ScriptGuiMain
Frame.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Frame.BorderColor3 = Color3.fromRGB(34, 34, 34)
Frame.Position = UDim2.new(0, 0, 0.0987124443, 0)
Frame.Size = UDim2.new(0, 617, 0, 0)

TextLabel.Parent = ScriptGuiMain
TextLabel.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
TextLabel.BorderColor3 = Color3.fromRGB(13, 13, 13)
TextLabel.Size = UDim2.new(0, 172, 0, 31)
TextLabel.Font = Enum.Font.FredokaOne
TextLabel.Text = "Shadow & Gab"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

close.Name = "close"
close.Parent = ScriptGuiMain
close.BackgroundTransparency = 1.000
close.LayoutOrder = 4
close.Position = UDim2.new(0.959481359, 0, 0, 0)
close.Size = UDim2.new(0, 25, 0, 25)
close.ZIndex = 2
close.Image = "rbxassetid://3926305904"
close.ImageRectOffset = Vector2.new(284, 4)
close.ImageRectSize = Vector2.new(24, 24)
close.MouseButton1Down:connect(function()
	ScriptGuiMain.Visible = false
	OpenButton.Visible = true
end)

remove.Name = "remove"
remove.Parent = ScriptGuiMain
remove.BackgroundTransparency = 1.000
remove.Position = UDim2.new(0.899513781, 0, 0.00643776823, 0)
remove.Size = UDim2.new(0, 25, 0, 25)
remove.ZIndex = 2
remove.Image = "rbxassetid://3926307971"
remove.ImageRectOffset = Vector2.new(884, 284)
remove.ImageRectSize = Vector2.new(36, 36)

Frame_2.Parent = ScriptGuiMain
Frame_2.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Frame_2.BorderColor3 = Color3.fromRGB(34, 34, 34)
Frame_2.Position = UDim2.new(0.71961081, 0, 0.113733903, 0)
Frame_2.Size = UDim2.new(9.99999975e-05, 0, 0.884000003, 0)

Frame_3.Parent = ScriptGuiMain
Frame_3.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Frame_3.BorderColor3 = Color3.fromRGB(12, 12, 12)
Frame_3.Position = UDim2.new(0.732676804, 0, 0.180257514, 0)
Frame_3.Size = UDim2.new(0, 164, 0, 382)

TextLabel_2.Parent = ScriptGuiMain
TextLabel_2.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
TextLabel_2.BorderColor3 = Color3.fromRGB(13, 13, 13)
TextLabel_2.Position = UDim2.new(0.730956256, 0, 0.113733903, 0)
TextLabel_2.Size = UDim2.new(0, 164, 0, 31)
TextLabel_2.Font = Enum.Font.FredokaOne
TextLabel_2.Text = "Admin's List"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

Frame_4.Parent = ScriptGuiMain
Frame_4.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Frame_4.BorderColor3 = Color3.fromRGB(34, 34, 34)
Frame_4.Position = UDim2.new(0.0129659642, 0, 0.392703861, 0)
Frame_4.Size = UDim2.new(0, 435, 0, 0)

PlayerImage.Name = "PlayerImage"
PlayerImage.Parent = ScriptGuiMain
PlayerImage.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
PlayerImage.BorderColor3 = Color3.fromRGB(12, 12, 12)
PlayerImage.Position = UDim2.new(0, 0, 0.113733903, 0)
PlayerImage.Size = UDim2.new(0, 83, 0, 83)
PlayerImage.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner.CornerRadius = UDim.new(10, 66)
UICorner.Parent = PlayerImage

ImageLabel.Parent = ScriptGuiMain
ImageLabel.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
ImageLabel.BorderColor3 = Color3.fromRGB(12, 12, 12)
ImageLabel.Position = UDim2.new(0.730956256, 0, 0.180257514, 0)
ImageLabel.Size = UDim2.new(0, 55, 0, 52)
ImageLabel.Image = "rbxassetid://11892687290"

UICorner_2.CornerRadius = UDim.new(10, 66)
UICorner_2.Parent = ImageLabel

Avisador.Name = "Avisador"
Avisador.Parent = ScriptGuiMain
Avisador.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Avisador.BorderColor3 = Color3.fromRGB(13, 13, 13)
Avisador.Position = UDim2.new(0.181523502, 0, 0.113733903, 0)
Avisador.Size = UDim2.new(0, 174, 0, 31)
Avisador.Font = Enum.Font.FredokaOne
Avisador.Text = "Welcome To Shadow & Gab,"
Avisador.TextColor3 = Color3.fromRGB(255, 255, 255)
Avisador.TextScaled = true
Avisador.TextSize = 14.000
Avisador.TextWrapped = true

PlayerName.Name = "PlayerName"
PlayerName.Parent = ScriptGuiMain
PlayerName.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
PlayerName.BorderColor3 = Color3.fromRGB(13, 13, 13)
PlayerName.Position = UDim2.new(0.181523502, 0, 0.201716736, 0)
PlayerName.Size = UDim2.new(0, 172, 0, 31)
PlayerName.Font = Enum.Font.FredokaOne
PlayerName.Text = "darckgames0103"
PlayerName.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.TextScaled = true
PlayerName.TextSize = 14.000
PlayerName.TextWrapped = true

PlayerName_2.Name = "PlayerName"
PlayerName_2.Parent = ScriptGuiMain
PlayerName_2.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
PlayerName_2.BorderColor3 = Color3.fromRGB(13, 13, 13)
PlayerName_2.Position = UDim2.new(0.816855729, 0, 0.201716736, 0)
PlayerName_2.Size = UDim2.new(0, 113, 0, 36)
PlayerName_2.Font = Enum.Font.FredokaOne
PlayerName_2.Text = "darckgames0103"
PlayerName_2.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerName_2.TextScaled = true
PlayerName_2.TextSize = 14.000
PlayerName_2.TextWrapped = true

ImageLabel_2.Parent = ScriptGuiMain
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
ImageLabel_2.BorderColor3 = Color3.fromRGB(12, 12, 12)
ImageLabel_2.Position = UDim2.new(0.730956256, 0, 0.351931334, 0)
ImageLabel_2.Size = UDim2.new(0, 55, 0, 52)
ImageLabel_2.Image = "rbxassetid://11892692933"

UICorner_3.CornerRadius = UDim.new(10, 66)
UICorner_3.Parent = ImageLabel_2

PlayerName_3.Name = "PlayerName"
PlayerName_3.Parent = ScriptGuiMain
PlayerName_3.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
PlayerName_3.BorderColor3 = Color3.fromRGB(13, 13, 13)
PlayerName_3.Position = UDim2.new(0.828200996, 0, 0.369098723, 0)
PlayerName_3.Size = UDim2.new(0, 106, 0, 37)
PlayerName_3.Font = Enum.Font.FredokaOne
PlayerName_3.Text = "GAB_LEALZINHO"
PlayerName_3.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerName_3.TextScaled = true
PlayerName_3.TextSize = 14.000
PlayerName_3.TextWrapped = true

Script1Frame.Name = "Script1Frame"
Script1Frame.Parent = ScriptGuiMain
Script1Frame.Active = true
Script1Frame.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Script1Frame.BorderColor3 = Color3.fromRGB(12, 12, 12)
Script1Frame.Position = UDim2.new(0, 0, 0.412017167, 0)
Script1Frame.Size = UDim2.new(0, 418, 0, 274)

minomgui.Name = "minom gui"
minomgui.Parent = Script1Frame
minomgui.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
minomgui.Position = UDim2.new(-0.000519275665, 0, -0.00227227807, 0)
minomgui.Size = UDim2.new(0, 125, 0, 29)
minomgui.Font = Enum.Font.FredokaOne
minomgui.Text = "Minom gui"
minomgui.TextColor3 = Color3.fromRGB(255, 255, 255)
minomgui.TextSize = 26.000
minomgui.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/darckgames0103/jjjjjjjjjjjjjj/main/README.md"))();
end)

UICorner_4.CornerRadius = UDim.new(0, 9)
UICorner_4.Parent = minomgui

Bloxfruit.Name = "Blox fruit"
Bloxfruit.Parent = Script1Frame
Bloxfruit.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Bloxfruit.Position = UDim2.new(0.378877968, 0, -0.00576529838, 0)
Bloxfruit.Size = UDim2.new(0, 125, 0, 29)
Bloxfruit.Font = Enum.Font.FredokaOne
Bloxfruit.Text = "Blox fruit"
Bloxfruit.TextColor3 = Color3.fromRGB(255, 255, 255)
Bloxfruit.TextSize = 19.000

UICorner_5.CornerRadius = UDim.new(0, 9)
UICorner_5.Parent = Bloxfruit

infinityyield.Name = "infinity yield"
infinityyield.Parent = Script1Frame
infinityyield.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
infinityyield.Position = UDim2.new(0.729658782, 0, -0.00293524563, 0)
infinityyield.Size = UDim2.new(0, 128, 0, 33)
infinityyield.Font = Enum.Font.FredokaOne
infinityyield.Text = "infinity yield"
infinityyield.TextColor3 = Color3.fromRGB(255, 255, 255)
infinityyield.TextSize = 19.000
infinityyield.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))();
end)

UICorner_6.CornerRadius = UDim.new(0, 9)
UICorner_6.Parent = infinityyield

silentaimpl.Name = "silent aim pl"
silentaimpl.Parent = Script1Frame
silentaimpl.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
silentaimpl.Position = UDim2.new(-0.00108076632, 0, 0.170602083, 0)
silentaimpl.Size = UDim2.new(0, 125, 0, 29)
silentaimpl.Font = Enum.Font.FredokaOne
silentaimpl.Text = "Silent aim"
silentaimpl.TextColor3 = Color3.fromRGB(255, 255, 255)
silentaimpl.TextSize = 26.000
silentaimpl.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/cracked13/silentic/main/README.md"))()
end)
UICorner_7.CornerRadius = UDim.new(0, 9)
UICorner_7.Parent = silentaimpl

Monkeyadmin.Name = "Monkey admin"
Monkeyadmin.Parent = Script1Frame
Monkeyadmin.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Monkeyadmin.Position = UDim2.new(0.34341678, 0, 0.170602053, 0)
Monkeyadmin.Size = UDim2.new(0, 132, 0, 29)
Monkeyadmin.Font = Enum.Font.FredokaOne
Monkeyadmin.Text = "Monkey Admin"
Monkeyadmin.TextColor3 = Color3.fromRGB(255, 255, 255)
Monkeyadmin.TextSize = 26.000
Monkeyadmin.MouseButton1Down:connect(function()
	
loadstring(game:HttpGet("https://raw.githubusercontent.com/nullity6/Monkey-Admin/main/Source"))()
end)

UICorner_8.CornerRadius = UDim.new(0, 9)
UICorner_8.Parent = Monkeyadmin

Redadmin.Name = "Red admin"
Redadmin.Parent = Script1Frame
Redadmin.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Redadmin.Position = UDim2.new(-1.67638063e-08, 0, 0.331186175, 0)
Redadmin.Size = UDim2.new(0, 143, 0, 29)
Redadmin.Font = Enum.Font.FredokaOne
Redadmin.Text = "Red admin"
Redadmin.TextColor3 = Color3.fromRGB(255, 255, 255)
Redadmin.TextSize = 21.000
Redadmin.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/darckgames0103/aaaaaaaaaaaaaaaaaaaaaa/main/README.md"))()
end)

UICorner_9.CornerRadius = UDim.new(0, 9)
UICorner_9.Parent = Redadmin

spammfoda.Name = "spamm foda"
spammfoda.Parent = Script1Frame
spammfoda.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
spammfoda.Position = UDim2.new(0.754900217, 0, 0.170602068, 0)
spammfoda.Size = UDim2.new(0, 106, 0, 29)
spammfoda.Font = Enum.Font.FredokaOne
spammfoda.Text = "Spam (pl)"
spammfoda.TextColor3 = Color3.fromRGB(255, 255, 255)
spammfoda.TextSize = 26.000
rangesword.MouseButton1Down:connect(function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/cracked13/da/main/README.md"))()
end)

UICorner_10.CornerRadius = UDim.new(0, 9)
UICorner_10.Parent = spammfoda

rangesword.Name = "range  *sword*"
rangesword.Parent = Script1Frame
rangesword.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
rangesword.Position = UDim2.new(0.376909614, 0, 0.334835678, 0)
rangesword.Size = UDim2.new(0, 114, 0, 29)
rangesword.Font = Enum.Font.FredokaOne
rangesword.Text = "Range  *sword*"
rangesword.TextColor3 = Color3.fromRGB(255, 255, 255)
rangesword.TextSize = 19.000
rangesword.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/cracked13/srange/main/README.md"))()

end)

UICorner_11.CornerRadius = UDim.new(0, 9)
UICorner_11.Parent = rangesword

raceclicker.Name = "race clicker"
raceclicker.Parent = Script1Frame
raceclicker.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
raceclicker.Position = UDim2.new(0.699876308, 0, 0.334835678, 0)
raceclicker.Size = UDim2.new(0, 125, 0, 29)
raceclicker.Font = Enum.Font.FredokaOne
raceclicker.Text = "Race Clicker"
raceclicker.TextColor3 = Color3.fromRGB(255, 255, 255)
raceclicker.TextSize = 19.000

UICorner_12.CornerRadius = UDim.new(0, 9)
UICorner_12.Parent = raceclicker

Petsim2.Name = "Pet sim 2"
Petsim2.Parent = Script1Frame
Petsim2.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Petsim2.Position = UDim2.new(0.0167463943, 0, 0.491770118, 0)
Petsim2.Size = UDim2.new(0, 143, 0, 29)
Petsim2.Font = Enum.Font.FredokaOne
Petsim2.Text = "Pet Simulator x"
Petsim2.TextColor3 = Color3.fromRGB(255, 255, 255)
Petsim2.TextSize = 19.000

UICorner_13.CornerRadius = UDim.new(0, 9)
UICorner_13.Parent = Petsim2

silentaimpl_2.Name = "silent aim pl"
silentaimpl_2.Parent = Script1Frame
silentaimpl_2.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
silentaimpl_2.Position = UDim2.new(-0.00108076632, 0, 0.170602083, 0)
silentaimpl_2.Size = UDim2.new(0, 125, 0, 29)
silentaimpl_2.Font = Enum.Font.FredokaOne
silentaimpl_2.Text = "Silent aim"
silentaimpl_2.TextColor3 = Color3.fromRGB(255, 255, 255)
silentaimpl_2.TextSize = 26.000
silentaimpl_2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/cracked13/silentic/main/README.md"))()
end)

UICorner_14.CornerRadius = UDim.new(0, 9)
UICorner_14.Parent = silentaimpl_2

silentaimpl_3.Name = "silent aim pl"
silentaimpl_3.Parent = Script1Frame
silentaimpl_3.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
silentaimpl_3.Position = UDim2.new(-0.00108076632, 0, 0.170602083, 0)
silentaimpl_3.Size = UDim2.new(0, 125, 0, 29)
silentaimpl_3.Font = Enum.Font.FredokaOne
silentaimpl_3.Text = "Silent aim"
silentaimpl_3.TextColor3 = Color3.fromRGB(255, 255, 255)
silentaimpl_3.TextSize = 26.000
silentaimpl_3.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/cracked13/silentic/main/README.md"))()
end)

UICorner_15.CornerRadius = UDim.new(0, 9)
UICorner_15.Parent = silentaimpl_3

shindolife.Name = "shindo life"
shindolife.Parent = Script1Frame
shindolife.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
shindolife.Position = UDim2.new(0.736842096, 0, 0.780091465, 0)
shindolife.Size = UDim2.new(0, 135, 0, 29)
shindolife.Font = Enum.Font.FredokaOne
shindolife.Text = "shindo life"
shindolife.TextColor3 = Color3.fromRGB(255, 255, 255)
shindolife.TextSize = 21.000

UICorner_16.CornerRadius = UDim.new(0, 9)
UICorner_16.Parent = shindolife

yourbizzarre.Name = "your bizzarre"
yourbizzarre.Parent = Script1Frame
yourbizzarre.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
yourbizzarre.Position = UDim2.new(0.368421018, 0, 0.780091405, 0)
yourbizzarre.Size = UDim2.new(0, 143, 0, 29)
yourbizzarre.Font = Enum.Font.FredokaOne
yourbizzarre.Text = "your bizzarre adventure"
yourbizzarre.TextColor3 = Color3.fromRGB(255, 255, 255)
yourbizzarre.TextSize = 13.000

UICorner_17.CornerRadius = UDim.new(0, 9)
UICorner_17.Parent = yourbizzarre

roghoul.Name = "ro ghoul"
roghoul.Parent = Script1Frame
roghoul.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
roghoul.Position = UDim2.new(0.0191387236, 0, 0.780091405, 0)
roghoul.Size = UDim2.new(0, 143, 0, 29)
roghoul.Font = Enum.Font.FredokaOne
roghoul.Text = "ro ghoul"
roghoul.TextColor3 = Color3.fromRGB(255, 255, 255)
roghoul.TextSize = 21.000

UICorner_18.CornerRadius = UDim.new(0, 9)
UICorner_18.Parent = roghoul

demonfall.Name = "demonfall"
demonfall.Parent = Script1Frame
demonfall.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
demonfall.Position = UDim2.new(0.0167464018, 0, 0.637755632, 0)
demonfall.Size = UDim2.new(0, 143, 0, 29)
demonfall.Font = Enum.Font.FredokaOne
demonfall.Text = "Demonfall"
demonfall.TextColor3 = Color3.fromRGB(255, 255, 255)
demonfall.TextSize = 21.000

UICorner_19.CornerRadius = UDim.new(0, 9)
UICorner_19.Parent = demonfall

beeswarm.Name = "bee swarm"
beeswarm.Parent = Script1Frame
beeswarm.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
beeswarm.Position = UDim2.new(0.433014363, 0, 0.488120556, 0)
beeswarm.Size = UDim2.new(0, 143, 0, 29)
beeswarm.Font = Enum.Font.FredokaOne
beeswarm.Text = "bee swarm"
beeswarm.TextColor3 = Color3.fromRGB(255, 255, 255)
beeswarm.TextSize = 21.000

UICorner_20.CornerRadius = UDim.new(0, 9)
UICorner_20.Parent = beeswarm

projectslayer.Name = "project slayer"
projectslayer.Parent = Script1Frame
projectslayer.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
projectslayer.Position = UDim2.new(0.38516742, 0, 0.645054817, 0)
projectslayer.Size = UDim2.new(0, 143, 0, 29)
projectslayer.Font = Enum.Font.FredokaOne
projectslayer.Text = "project slayer"
projectslayer.TextColor3 = Color3.fromRGB(255, 255, 255)
projectslayer.TextSize = 21.000

UICorner_21.CornerRadius = UDim.new(0, 9)
UICorner_21.Parent = projectslayer

Script2Frame.Name = "Script2Frame"
Script2Frame.Parent = ScriptGuiMain
Script2Frame.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Script2Frame.BorderColor3 = Color3.fromRGB(12, 12, 12)
Script2Frame.Position = UDim2.new(0.0129659642, 0, 0.392703801, 0)
Script2Frame.Size = UDim2.new(0, 412, 0, 281)
Script2Frame.Visible = false

navigate_before.Name = "navigate_before"
navigate_before.Parent = Script2Frame
navigate_before.BackgroundTransparency = 1.000
navigate_before.LayoutOrder = 12
navigate_before.Position = UDim2.new(1, 0, 0.791701555, 0)
navigate_before.Size = UDim2.new(0, 22, 0, 25)
navigate_before.ZIndex = 2
navigate_before.Image = "rbxassetid://3926305904"
navigate_before.ImageRectOffset = Vector2.new(244, 284)
navigate_before.ImageRectSize = Vector2.new(36, 36)

OpenButton.Name = "OpenButton"
OpenButton.Parent = ScreenGui
OpenButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
OpenButton.BorderSizePixel = 0
OpenButton.Position = UDim2.new(0.0150188105, 0, 0.675957918, 0)
OpenButton.Size = UDim2.new(0, 180, 0, 45)
OpenButton.ZIndex = 2
OpenButton.Font = Enum.Font.Unknown
OpenButton.Text = ""
OpenButton.TextColor3 = Color3.fromRGB(255, 255, 255)
OpenButton.TextScaled = true
OpenButton.TextSize = 14.000
OpenButton.TextWrapped = true
OpenButton.MouseButton1Down:connect(function()
	ScriptGuiMain.Visible = true
	OpenButton.Visible = false
end)

UICorner_22.CornerRadius = UDim.new(1, 0)
UICorner_22.Parent = OpenButton

Shadow.Name = "Shadow"
Shadow.Parent = OpenButton
Shadow.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
Shadow.BorderColor3 = Color3.fromRGB(34, 34, 34)
Shadow.BorderSizePixel = 0
Shadow.Size = UDim2.new(1, 0, 1, 4)
Shadow.Style = Enum.FrameStyle.DropShadow

UICorner_23.CornerRadius = UDim.new(1, 0)
UICorner_23.Parent = Shadow

TextLabel_3.Parent = OpenButton
TextLabel_3.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.555555582, 0, 0.433333337, 0)
TextLabel_3.Size = UDim2.new(1, -20, 1, -20)
TextLabel_3.ZIndex = 2
TextLabel_3.Font = Enum.Font.Unknown
TextLabel_3.Text = "Open"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

-- Scripts:

local function MZKF_fake_script() -- ScriptGuiMain.LocalScript 
	local script = Instance.new('LocalScript', ScriptGuiMain)

	local frame = script.Parent
	
	
	
	local player = game.Players.LocalPlayer
	
	
	
	local userId = player.UserId
	
	local thumbType = Enum.ThumbnailType.AvatarBust
	
	local thumbSize = Enum.ThumbnailSize.Size420x420
	
	local content, isReady = game.Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
	
	local player = game.Players.LocalPlayer
	if player.Name == "darckgames0103" then
		frame.Avisador.Text = "Welcome To Shadow & Gab, Owner Shadow"
	elseif player.Name == "GAB_LEALZINHO" then
		frame.Avisador.Text = "Welcome To Shadow & Gab, Owner Gab"
	else
		frame.Avisador.Text = "Welcome To Shadow & Gab,"
	end
	
	
	
	frame.PlayerImage.Image = content
	
	frame.PlayerName.Text = player.Name
end
coroutine.wrap(MZKF_fake_script)()
