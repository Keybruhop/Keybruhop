local args = {
    [1] = 200,
    [4] = Vector3.new(-0.14105062186717987, -0.45068278908729553, -0.8814702033996582)
}

game:GetService("ReplicatedStorage").Packages.Knit.Services.BallService.RE.Shoot:FireServer(unpack(args))
