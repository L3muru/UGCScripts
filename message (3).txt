local args = {
    [1] = "x18B",
    [2] = "D"
}

game:GetService("ReplicatedStorage"):WaitForChild("BL_DataRemoteEvent"):FireServer(unpack(args))
wait()
local args = {
    [1] = {
        [1] = "\6",
        [2] = {
            [1] = "ingredients",
            [2] = "add",
            [3] = math.huge,
            [4] = true
        },
        [3] = "\19",
        [4] = {
            [1] = "current",
            [2] = "add",
            [3] = math.huge,
            [4] = true
        }
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("BL_DataRemoteEvent"):FireServer(unpack(args))
wait(1)
local args = {
    [1] = "x18B",
    [2] = "C"
}

game:GetService("ReplicatedStorage"):WaitForChild("BL_DataRemoteEvent"):FireServer(unpack(args))
wait()
local args = {
    [1] = {
        [1] = "#",
        [2] = {
            [1] = {
                ["duration"] = 13211111180,
                ["currency"] = "coins",
                ["amount"] = math.huge
            }
        }
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("BL_DataRemoteEvent"):FireServer(unpack(args))
wait(1)
local args = {
    [1] = "x18B",
    [2] = "A"
}

game:GetService("ReplicatedStorage"):WaitForChild("BL_DataRemoteEvent"):FireServer(unpack(args))
wait()
local args = {
    [1] = {
        [1] = "\6",
        [2] = {
            [1] = "totalDoors",
            [2] = "add",
            [3] = math.huge
        },
        [3] = "\6",
        [4] = {
            [1] = "lapsRecord",
            [2] = "new",
            [3] = math.huge
        },
        [5] = "\7",
        [6] = {
            [1] = "newScore",
            [2] =  math.huge
        }
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("BL_DataRemoteEvent"):FireServer(unpack(args))
wait(1)
local args = {
    [1] = "x18B",
    [2] = "F"
}

game:GetService("ReplicatedStorage"):WaitForChild("BL_DataRemoteEvent"):FireServer(unpack(args))
wait()
local args = {
    [1] = {
        [1] = "\6",
        [2] = {
            [1] = "codes",
            [2] = "used",
            [3] = "bamboooo"
        },
        [3] = "\20",
        [4] = {
            [1] = {
                ["amount"] = math.huge,
                ["msg"] = "You got x1 Spin!",
                ["currency"] = "spin",
                ["Code"] = "bamboooo"
            }
        }
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("BL_DataRemoteEvent"):FireServer(unpack(args))