local player = game.Players.LocalPlayer
local character = player.Character
local humanoid = character:WaitForChild("Humanoid")

-- Enable flying
humanoid:ChangeState(Enum.HumanoidStateType.Flying)
