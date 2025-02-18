for _, v in pairs(game:GetService("Workspace"):GetChildren()) do
    if v:IsA("Model") and v:FindFirstChild("WaveTime") then
        v.WaveTime.Value = 1
    end
end
