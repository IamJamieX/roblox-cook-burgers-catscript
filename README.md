# roblox-cook-burgers-catscript
local cat = workspace:FindFirstChild("Cats"):FindFirstChild("Cat")
local destination = workspace:FindFirstChild("Restaurant"):FindFirstChild("Grill"):FindFirstChild("Grill")
local catClone  = cat:Clone()
catClone.Parent = workspace
catClone:FindFirstChild("Body").CFrame = destination.CFrame + Vector3.new(0, 2, 0)
