local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("Tool Tower defense", "BloodTheme")

local Tab = Window:NewTab("Sorry:(")

local Section = Tab:NewSection("Sorry but i will wait untill skibidi toilet")

local Section = Tab:NewSection("Will get update so i will make scripts")

local Section = Tab:NewSection("for another games and sorry agin:(")

local Tab = Window:NewTab("Free Gamepass/Badges")

local Section = Tab:NewSection("Free Gamepass/Badges")

Section:NewButton("Unlock Gamepass/Badges", "ButtonInfo", function()
    if game.CreatorType == Enum.CreatorType.User then
game.Players.LocalPlayer.UserId = game.CreatorId
end
if game.CreatorType == Enum.CreatorType.Group then
game.Players.LocalPlayer.UserId = game:GetService("GroupService"):GetGroupInfoAsync(game.CreatorId).Owner.Id
end
end)

local Tab = Window:NewTab("Main(Free Characters)")

local Section = Tab:NewSection("Main(Free Characters)")

Section:NewButton("BoxCutter", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "BoxCutter"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end

end)

Section:NewButton("BottleThrower", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "BottleThrower"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end

end)

Section:NewButton("Painter", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Painter"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("HealingStand", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "HealingStand"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("BaseFixer", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "BaseFixer"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Builder", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Builder"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Explorer", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Explorer"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Farm", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Farm"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Shotgunner", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Shotgunner"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("LeafBlower", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "LeafBlower"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Miner", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Miner"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Commander", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Commander"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Mechanic", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Mechanic"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Sniper", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Sniper"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("PressureWasher", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "PressureWasher"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("RepairShop", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "RepairShop"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("SolarBlaster", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "SolarBlaster"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("DJ", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "DJ"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Welder", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Welder"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("WaterDispenser", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "WaterDispenser"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Enforcer", "ButtonInfo", function()
   local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Enforcer"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Flamethrower", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Flamethrower"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Minigunner", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Minigunner"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Driller", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Driller"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("CandyCaneLauncher", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "CandyCaneLauncher"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Snowballer", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Snowballer"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)

Section:NewButton("Guard", "ButtonInfo", function()
    local function getHeadPosition()
    local player = game.Players.LocalPlayer
    local character = player.Character
    if character then
        local humanoid = character:FindFirstChild("Humanoid")
        if humanoid then
            local head = character:FindFirstChild("Head")
            if head then
                return head.Position
            end
        end
    end
    return nil
end

local headPosition = getHeadPosition()
if headPosition then
    local A_1 = "Guard"
    local A_2 = CFrame.new(headPosition)
    local Event = game:GetService("ReplicatedStorage").Functions.SpawnTower
    Event:InvokeServer(A_1, A_2)
end
end)
