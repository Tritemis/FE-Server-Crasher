-- be R15 and wear layered clothing
for _,y in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
    if y:IsA("Motor6D") and y.Name ~= "Neck" then
        local x = y.Parent
        y:Destroy()
        x.CFrame = CFrame.new(9e9 * _,9e9* _,9e9*_)
        wait()
    end
end
