--carregar Biblioteca Kavos Ui
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()


--Janela principal
local Window = Library.CreateLib("Satox Hub 1.0.0", "Sentinel")
local Tab = Window:NewTab("Home🏠")

local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "ScreenGui"
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

local Toggle = Instance.new("Satox")
Toggle.Name = "Satox"
Toggle.Parent = ScreenGui
Toggle.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Toggle.Position = UDim2.new(0, 0, 0.454706937, 0)
Toggle.Size = UDim2.new(0, 90, 0, 38)
Toggle.Font = Enum.Font.SourceSans
Toggle.Text = "Satox"
Toggle.TextColor3 = Color3.fromRGB(248, 248, 248)
Toggle.TextSize = 28.000
Toggle.Draggable = true
Toggle.MouseButton1Click:connect(function()
    Library:ToggleUI()
end)

local Corner = Instance.new("UICorner")
Corner.Name = "Corner"
Corner.Parent = Satox


local Section = Tab:NewSection("Scripts Brook")
Section:NewButton("Antates Hub (Boris)🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/BorisLua/AntaresHubSuaMaeNaMinhaCama/0.5.1/AntaresHubWorking.lua"))()
end)
Section:NewButton("Em Breve🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMae17/NewIceHub/main/Brookhaven"))()
end)
Section:NewButton("Igor Premium🖥️", "Executar Script", function()
https://raw.githubusercontent.com/igormsqq/ORION-BL/main/KEYSYS
end)
Section:NewButton("Juanko Hub🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://pastebin.com/raw/d5BS5qiX"))()
end)
Section:NewButton("Unfair hub🖥️", "Executar Script", function()
 loadstring(game:HttpGet(('https://raw.githubusercontent.com/rblxscriptsnet/unfair/main/rblxhub.lua'),true))()
end)
Section:NewButton("Barra de admin🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://freenote.biz/raw/Rk3INLZtUF",true))()
end)
Section:NewButton("Drop tools🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://pastebin.com/raw/Ctqjmtkv", true))()
end)




local Tab = Window:NewTab("Main🧬")
local Section = Tab:NewSection("Main Config")
Section:NewTextBox("WalkSpeed","Speed", function(txt)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end)
Section:NewTextBox("JumpPower","Jump", function(txt)
game.Players.LocalPlayer.Character.Humanoid.JumpPower = txt
end)
Section:NewToggle("Hitbox🍁", "info" ,function(state)
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Update-script-hitbox-9326"))()
end)
Section:NewToggle("ESP🍁", "info" ,function(state)
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-3d-Box-ESP-5346"))()
end)
local Tab = Window:NewTab("Trolling🤷")
local Section = Tab:NewSection("All Kills") 
Section:NewButton("Fling all🔪(pegue sofa)", "Executar Script", function()
 loadstring(game:HttpGet("https://pastebin.com/raw/zqyDSUWX"))()
  local args = {
    [1] = "PickingTools",
    [2] = "Couch"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Too1l"):InvokeServer(unpack(args))
end)
local Section = Tab:NewSection("Flings")
Section:NewButton("Kill Troll(Pegue sofá)🌟", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/KillTrollByDefense.dev/main/Troll.lua"))()
end) 
Section:NewButton("Void(pegue a pessoa no sofá)🌟", "Executar Script", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Void'))()
end)
local Tab = Window:NewTab("others💥")
local Section = Tab:NewSection("GUIS|HUBS")
Section:NewButton("OrangeX🍊", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/ImJosh66/OrangeX-Hub-V3-Rel/main/OrangeX%20V3%20Milvan.txt"))()
end)
Section:NewButton("Gigachead🗿", "Executar Script", function()
 loadstring(game:HttpGet('https://raw.githubusercontent.com/OWJBWKQLAISH/GigaChad-Hub/main/Gigachad%20Hub%20V4'))()
end)
Section:NewButton("Game Hub🎮", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/TakeModzz/Games-Hub-Script/main/Games%20Hub%20(Always%20updated)"))()
end)
Section:NewButton("Rainbow Hub🌈", "Executar Script", function()
 loadstring(game:HttpGet("https://pastebin.com/raw/AivNBdLk"))()
end)
Section:NewButton("Pendulum Hub🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Tescalus/Pendulum-Hubs-Source/main/Pendulum%20Hub%20V5.lua"))()
end)
Section:NewButton("invisible Hub🖥️", "Executar Script", function()
 loadstring(game:HttpGet('https://pastebin.com/raw/AYtzGEPb'))()
end)
Section:NewButton("Turtle Spy🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://pastebin.com/raw/BDhSQqUU", true))()
end)
Section:NewButton("Fe Fling🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://paste.ee/r/NTtmf", true))()
end)
Section:NewButton("Keyboard🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/GGH52lan/GGH52lan/main/keyboard.txt"))()
end)
Section:NewButton("GhostHub🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-X-Ghost-Hub-X-7595"))()
end)
Section:NewButton("BACKDOOR.EXE🖥️", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/iK4oS/backdoor.exe/master/source.lua"))()
end)
local Section = Tab:NewSection("Scripts")
Section:NewButton("Nameless ADMIN🍪", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
end)
Section:NewButton("Fly Gui🪽", "Executar Script", function()
 loadstring(game:HttpGet("https://pastebin.com/raw/y7GnniTi",true))()
end)
Section:NewButton("Em Breve", "ButtonInfo", function()
 
   print("Clicked")
end)

local Tab = Window:NewTab("Carros🚘")
local Section = Tab:NewSection("Velocidade Overboard")
Section:NewTextBox("Overboard","Speed", function(txt)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end)
local Section = Tab:NewSection("Velocidade Bicicleta")
Section:NewTextBox("Bicicleta","Speed", function(txt)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end)
local Section = Tab:NewSection("Velocidade Skate")
Section:NewTextBox("Skate","Speed", function(txt)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end)
local Section = Tab:NewSection("Outros")
Section:NewButton("Vehicle Fly", "Executar Script", function()
 loadstring(game:HttpGet("https://pastebin.com/raw/MHE1cbWF"))()
end)
local Tab = Window:NewTab("Avatar👔") 
local Section = Tab:NewSection("Catalogue")
Section:NewButton("HeadLess🎃", "Executar Script", function()
 -- services
local players = game:GetService("Players")
local starterGui = game:GetService("StarterGui")
-- objects
local player = players.LocalPlayer
local character = player.Character
local humanoid = character:FindFirstChildWhichIsA("Humanoid")
local head, torso = character:FindFirstChild("Head"), character:FindFirstChild("UpperTorso")
local resetBindable = Instance.new("BindableEvent")
-- variables
local destroyFunc, resetBindableConnection = character.Destroy, nil
-- main
-- initializes the permadeath
player.Character = nil
player.Character = character
task.wait(players.RespawnTime + .05)

humanoid.BreakJointsOnDeath = false
humanoid:SetStateEnabled(Enum.HumanoidStateType.Dead, false)
if humanoid.RigType == Enum.HumanoidRigType.R15 then
   task.defer(destroyFunc, (head.Neck))
end
task.defer(destroyFunc, head) -- and we destroy the head

resetBindableConnection = resetBindable.Event:Connect(function()
   starterGui:SetCore("ResetButtonCallback", true)
   resetBindableConnection:Disconnect()

   if player.Character == character then
       character:Destroy()
       local daModel = Instance.new("Model")
       local _daModelHumanoid = Instance.new("Humanoid")
       _daModelHumanoid.Parent = daModel
       player.Character = daModel

       task.delay(players.RespawnTime, destroyFunc, daModel)
   else
       player.Character:BreakJoints()
   end
end)
starterGui:SetCore("ResetButtonCallback", resetBindable)

--fixed for synapse
end)
Section:NewButton("Korblox And Headless🎃👖", "Executar Script", function()
loadstring(game:HttpGet(('https://gist.githubusercontent.com/Gogogamer61/5ce96262b57aa9b2e88cee7b41c68baa/raw/5f8bc97994f2bdfea0cd60f2371495c45ac7d2f4/Headless%2520Script'),true))()
end)
Section:NewButton("Look Assustador", "Executar Script", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Ghostplayer%20Outfit'))()
end)
local Section = Tab:NewSection("Animations")
Section:NewButton("Fe emotes all🤹", "Executar Script", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FEmotesGui/main/FEmotesGui.lua", true))()
end)
Section:NewButton("Animation Hub(FE)💓", "Executar Script", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FEAnimationGui/main/FEAnimationGui.lua", true))() 
end)
local Tab = Window:NewTab("itens💐") 
local Section = Tab:NewSection("itens Visuais")
Section:NewButton("Sofá✨", "Executar Script", function()
local args = {
    [1] = "PickingTools",
    [2] = "Couch"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Too1l"):InvokeServer(unpack(args))
end)
Section:NewButton("itens-Im Patrick✨", "Executar Script", function()
 loadstring(game:HttpGet(('https://pastefy.app/VYIAk3o1/raw'),true))()
end)
Section:NewButton("ClickTP🛠️", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/KptHadesBlair/main/Bao.lua"))()
end)
Section:NewButton("F3X🛠️", "Executar Script", function()
 loadstring(game:GetObjects("rbxassetid://6695644299")[1].Source)()
end)
Section:NewButton("Btools🛠️", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/PqpHadesBlair/main/Bao.lua"))()
end)
local Tab = Window:NewTab("Misc☎️") 
local Section = Tab:NewSection("Scripts")
Section:NewButton("Shiftlock🔒", "Executar Script", function()
 loadstring(game:HttpGet("https://scriptblox.com/raw/Baseplate-Universal-Script-Permanent-Shift-Lock-6924"))()
end)
Section:NewButton("infinite Yield👾", "Executar Script", function()
 loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
Section:NewButton("Infinite Jump🌪️", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/SerpenteXByHadesBlair/main/Bao.lua"))()
end)
Section:NewButton("ernergizer hub⚡", "Executar Script", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/ErnegizerHubBySla/main/KKK.lua"))()
end)
Section:NewButton("Telescopio⚡", "Executar Script", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Telescope'))()
end)
Section:NewButton("Portal⚡(Agora funciona)", "Executar Script", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Portal'))()
end)
