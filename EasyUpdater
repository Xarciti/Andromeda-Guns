local path = game.StarterPack --replace this with the path to your guns
for i,v in pairs(path:GetChildren()) do
	if v:FindFirstChild("gunclass") then
		local server = v.server
		local newserver = workspace.server
		
		newserver = server.Parent
		
		server.Other.Parent = newserver
	end
end
