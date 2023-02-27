noclip = false
game:GetService('RunService').Stepped:Connect(function()
	if noclip then
		game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		
	end
end)

local p = game.Players.LocalPlayer
local mo = p:GetMouse()

mo.KeyDown:Connect(function(k)
	if k == 'e' then
		noclip = not noclip
		p.Character.Humanoid:ChangeState(11)
	end
end)
