

local level = game:GetService("Players").LocalPlayer.Data.Level.Value
local char = game:GetService("Players").LocalPlayer.Character


if level <= 15 then
    char.HumanoidRootPart.Position = CFrame.new(1058.83984, 16.3627472, 1548.58472)
end
