
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK

--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK
--CLIENT SETTINGS DO NOT LEAK

getgenv().x9 = {
    ['Whitelist'] = {
        ['LuaKey'] = "Place ur luarmor key here",
    },
    ['Configuration'] = {
        ['Checks'] = {
            ['Auto Mute Boombox'] = false,
            ['Auto Low GFX'] = false,
            ['Esp Box'] = false,
        },
        ['Loader'] = {
            ['Enabled'] = false,
        }
    },
    ['Silent Aim'] = {
        ['Enabled'] = true,
        ['Targetting'] = {
            ['Keybind Enabled'] = false,
            ['Keybind'] = "P",
        },
        ['Checks'] = {
            ['Wall'] = true,
            ['KO'] = true,
            ['Death'] = true,
            ['Picked'] = true,
        },
        ['Config'] = {
            ['Hit Chance'] = 100,
            ['Points'] = {
                ['Point'] = "HumanoidRootPart",
                ['Point Offset'] = 0,
                ['Nearest Part'] = true,
                ['Nearest Point'] = true,
            },
            ['Velocity'] = {
                ['Prediction'] = 0.129,
                ['Anti Ground Shots'] = true,
            }
        },
    },
    ['Cam Lock'] = {
        ['Enabled'] = true,
        ['Prediction'] = 0.9,
        ['Key'] = "C",
        ['Notify'] = true,
        ['Point'] = "HumanoidRootPart",
        ['Point Offset'] = 0,
        ['Nearest Part'] = true,
        ['Nearest Point'] = true,
        ['Dot'] = false,
        ['Smoothness'] = {
            ['Enabled'] = true,
            ['Value'] = 0.01
        },
        ['Flags'] = {
            ['Unlock On KO'] = true,
            ['Unlock Outside FOV'] = false,
            ['Unlock Behind Wall'] = false,
        },
        ['Shake'] = {
            ['Enabled'] = false,
            ['X'] = 5,
            ['Y'] = 5,
            ['Z'] = 5
        }
    },
    ['Weapon Modifications'] = { 
        ['Enabled'] = false,
        ['Double Barrel'] = {
            ['FOV'] = true, 
            ['Prediction'] = true, 
            ['Smoothness'] = true, 
            ['Hit Chance'] = true,
                ['Close Detection'] = 16,    ['Close FOV'] = 55,    ['Close Prediction'] = 0.13,    ['Close Smoothness'] = 0.013,    ['Close Hit Chance'] = 100,
                ['Mid Detection'] = 42,      ['Mid FOV'] = 35,      ['Mid Prediction'] = 0.127,      ['Mid Smoothness'] = 0.016,      ['Mid Hit Chance'] = 100,
                ['Far Detection'] = 100,     ['Far FOV'] = 2,      ['Far Prediction'] = 0.122,              ['Far Smoothness'] = 0.021,      ['Far Hit Chance'] = 100,
        },
        ['Revolver'] = {
            ['FOV'] = true, 
            ['Prediction'] = true, 
            ['Smoothness'] = true, 
            ['Hit Chance'] = true,
                ['Close Detection'] = 16,    ['Close FOV'] = 46,    ['Close Prediction'] = 0.1343536753,    ['Close Smoothness'] = 0.01,    ['Close Hit Chance'] = 100,
                ['Mid Detection'] = 42,      ['Mid FOV'] = 32,      ['Mid Prediction'] = 0.1266543456,      ['Mid Smoothness'] = 0.013,      ['Mid Hit Chance'] = 100,
                ['Far Detection'] = 100,     ['Far FOV'] = 27,      ['Far Prediction'] = 0.12,              ['Far Smoothness'] = 0.022,      ['Far Hit Chance'] = 100,
        },
        ['Tactical Shotgun'] = {
            ['FOV'] = true, 
            ['Prediction'] = true, 
            ['Smoothness'] = true, 
            ['Hit Chance'] = true,
                ['Close Detection'] = 16,    ['Close FOV'] = 50,    ['Close Prediction'] = 0.1343536753,    ['Close Smoothness'] = 0.007,    ['Close Hit Chance'] = 100,
                ['Mid Detection'] = 42,      ['Mid FOV'] = 32,      ['Mid Prediction'] = 0.1276543456,      ['Mid Smoothness'] = 0.01,      ['Mid Hit Chance'] = 100,
                ['Far Detection'] = 100,     ['Far FOV'] = 30,      ['Far Prediction'] = 0.12,              ['Far Smoothness'] = 0.03,      ['Far Hit Chance'] = 100,
        },
        ['Shotgun'] = {
            ['FOV'] = true, 
            ['Prediction'] = true, 
            ['Smoothness'] = true, 
            ['Hit Chance'] = true,
                ['Close Detection'] = 16,    ['Close FOV'] = 50,    ['Close Prediction'] = 0.1343536753,    ['Close Smoothness'] = 0.015,    ['Close Hit Chance'] = 100,
                ['Mid Detection'] = 42,      ['Mid FOV'] = 32,      ['Mid Prediction'] = 0.1296543456,      ['Mid Smoothness'] = 0.02,      ['Mid Hit Chance'] = 100,
                ['Far Detection'] = 100,     ['Far FOV'] = 33,      ['Far Prediction'] = 0.12,              ['Far Smoothness'] = 0.01,      ['Far Hit Chance'] = 100,
        },
        ['Rifle'] = {
            ['FOV'] = true, 
            ['Prediction'] = true, 
            ['Smoothness'] = true, 
            ['Hit Chance'] = true,
                ['Close Detection'] = 16,    ['Close FOV'] = 30,    ['Close Prediction'] = 0.1343536753,    ['Close Smoothness'] = 0.01,    ['Close Hit Chance'] = 100,
                ['Mid Detection'] = 42,      ['Mid FOV'] = 32,      ['Mid Prediction'] = 0.1296543456,      ['Mid Smoothness'] = 0.023,      ['Mid Hit Chance'] = 100,
                ['Far Detection'] = 100,     ['Far FOV'] = 33,      ['Far Prediction'] = 0.12,              ['Far Smoothness'] = 0.3,      ['Far Hit Chance'] = 100,
        }
    },
    ['Resolver'] = {
        ['Enabled'] = false,
        ['Method'] = "Delta",
    },
    ['Global'] = {
        ['Auto Prediction'] = false,
    },
    ['Checks'] = {
        ['Visible Check'] = true,
        ['K.O Check'] = true,
        ['Crew Check'] = false
    },
    ['Drawings Thug'] = {
        ['Dot'] = {
            ['Visible'] = false,
            ['Filled'] = false,
            ['Size'] = 5,
            ['Thickness'] = 1,
            ['Transparency'] = 1,
            ['Color'] = Color3.fromRGB(112, 2, 2)
        },
        ['Circle'] = {
            ['Silent'] = {
                ['Visible'] = false,
                ['Stick'] = false,
                ['Filled'] = false,
                ['Size'] = 9,
                ['Thickness'] = 1,
                ['Transparency'] = 1,
                ['Color'] = Color3.fromRGB(1, 1, 1)
            },
            ['Aimbot'] = {
                ['Visible'] = false,
                ['Filled'] = false,
                ['Size'] = 32,
                ['Thickness'] = 1,
                ['Transparency'] = 1,
                ['Color'] = Color3.fromRGB(1, 1, 1)
            }
        }
    },
    ['Panic'] = {
        ['Enabled'] = false, 
        ['KeyBind'] = "M",
    },
    ['Airshot'] = {
        ['Enabled'] = false,
        ['Point'] = "LowerTorso"
    },
    ['MemorySpoofer'] = {
        ["MemSpoofer"] = true, 
        ["Minimum"] = 800, 
        ["Maximum"] = 950, 
    },  
    ['Options'] = {
        ['Headless'] = true,
        ['Korblox'] = true,
    },
    ['Fps_Unlocker'] = {
        ['Enabled'] = false,
        ['Cap'] = 999,
    },
    ['Macro'] = {
        ['Enabled'] = true,
        ['Bind'] = "X",
        ['Abuse'] = true,
        ['Speed'] = 1,
    }
}


script_key = getgenv().x9.Whitelist.LuaKey


local Players = game:GetService("Players")
local RunService = game:GetService("RunService")
local Workspace = game:GetService("Workspace")
local Gui = game:GetService("GuiService")

local SilentTarget = nil
local CamlockTarget = nil
local PredictionValue = 0.133
local LocalPlayer = Players.LocalPlayer
local Mouse = LocalPlayer:GetMouse()
local CurrentCamera = Workspace.CurrentCamera
local v3 = Vector3
local CF = CFrame
local v2 = Vector2
local closestsilentbodypart = "HumanoidRootPart"
local closestcamlockpart = "HumanoidRootPart"


function notify(text) 
    game:GetService("StarterGui"):SetCore("SendNotification",{
        Title = "x9",
        Text = text, 
        Duration = 5,
    })
end

if x9.Configuration.Loader.Enabled then 
    local cam = workspace.CurrentCamera
    local x = cam.ViewportSize.X
    local y = cam.ViewportSize.Y
    local newx = math.floor(x * 0.5)
    local newy = math.floor(y * 0.5)

    local SpashScreen = Instance.new("ScreenGui")
    local Image = Instance.new("ImageLabel")
    SpashScreen.Name = "SpashScreen"
    SpashScreen.Parent = game.CoreGui
    SpashScreen.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
    Image.Name = "Image"
    Image.Parent = SpashScreen
    Image.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    Image.BackgroundTransparency = 1
    Image.Position = UDim2.new(0, newx, 0, newy)
    Image.Size = UDim2.new(0, 825, 0, 377)
    Image.Image = "rbxassetid://1"
    Image.ImageTransparency = 1
    Image.AnchorPoint = v2.new(0.5,0.5)

    local Blur = Instance.new("BlurEffect")
    Blur.Parent = game.Lighting
    Blur.Size = 0
    Blur.Name = math.random(1,123123)

    local function gui(last, sex, t, s, inorout)
        local TI = TweenInfo.new(t or 1, s or Enum.EasingStyle.Sine, Enum.EasingDirection.InOut)
        local Tweening = game:GetService("TweenService"):Create(last, TI, sex)
        Tweening:Play()
    end

    gui(Image, {ImageTransparency = 0},0.3)
    gui(Blur, {Size = 20},0.3)
    wait(3)
    gui(Image, {ImageTransparency = 1},0.3)
    gui(Blur, {Size = 0},0.3)
    wait(0.3)
end


if not LPH_OBFUSCATED and not LPH_JIT_ULTRA then
    LPH_NO_VIRTUALIZE = function(f) return f end
end




local Line = Drawing.new("Line") 
Line.Visible = false 
Line.Thickness = 0 
Line.Transparency = 1 
Line.Radius = 5 
Line.Color = Color3.new(1,1,1)

local Circle = Drawing.new("Circle")
Circle.Transparency = x9['Drawings Thug'].Circle.Silent.Transparency
Circle.Radius = x9['Drawings Thug'].Circle.Silent.Size
Circle.Visible = x9['Drawings Thug'].Circle.Silent.Visible
Circle.Color = x9['Drawings Thug'].Circle.Silent.Color
Circle.Thickness = x9['Drawings Thug'].Circle.Silent.Thickness
Circle.Filled = x9['Drawings Thug'].Circle.Silent.Filled

local Circle2 = Drawing.new("Circle")
Circle2.Transparency = x9['Drawings Thug'].Circle.Aimbot.Transparency
Circle2.Radius = x9['Drawings Thug'].Circle.Aimbot.Size * 3
Circle2.Visible = x9['Drawings Thug'].Circle.Aimbot.Visible
Circle2.Color = x9['Drawings Thug'].Circle.Aimbot.Color
Circle2.Thickness = x9['Drawings Thug'].Circle.Aimbot.Thickness
Circle2.Filled = x9['Drawings Thug'].Circle.Aimbot.Filled



local Vis1 = Drawing.new("Circle")
Vis1.Filled = x9['Drawings Thug'].Dot.Filled
Vis1.Visible = false
Vis1.Thickness = x9['Drawings Thug'].Dot.Thickness
Vis1.Transparency = x9['Drawings Thug'].Dot.Transparency
Vis1.Radius = x9['Drawings Thug'].Dot.Size
Vis1.Color = x9['Drawings Thug'].Dot.Color

local Vis2 = Drawing.new("Circle")
Vis2.Filled = true
Vis2.Visible = false
Vis2.Thickness = 1
Vis2.Transparency = 1
Vis2.Radius = 5
Vis2.Color = Color3.new(1,1,1)

OnScreen = function(Object)
    local _, screen = CurrentCamera:WorldToScreenPoint(Object.Position)
    return screen
end


RayCastCheck = function(Part, PartDescendant)
    local Character = LocalPlayer.Character or LocalPlayer.CharacterAdded.Wait(LocalPlayer.CharacterAdded)
    local Origin = CurrentCamera.CFrame.Position

    local RayCastParams = RaycastParams.new()
    RayCastParams.FilterType = Enum.RaycastFilterType.Blacklist
    RayCastParams.FilterDescendantsInstances = {Character, CurrentCamera}

    local Result = Workspace.Raycast(Workspace, Origin, Part.Position - Origin, RayCastParams)
    
    if (Result) then
        local PartHit = Result.Instance
        local Visible = (not PartHit or Instance.new("Part").IsDescendantOf(PartHit, PartDescendant))
        
        return Visible
    end
    return false
end

Alive = function(Plr)
    if Plr and Plr.Character and Plr.Character:FindFirstChild("HumanoidRootPart") ~= nil and Plr.Character:FindFirstChild("Humanoid") ~= nil and Plr.Character:FindFirstChild("Head") ~= nil then
        return true
    end
    return false
end


GetMagnitudeFromMouse = function(Part)
    local PartPos, OnScreen = CurrentCamera:WorldToScreenPoint(Part.Position)
    if OnScreen then
        local Magnitude = (v2.new(PartPos.X, PartPos.Y) - v2.new(Mouse.X, Mouse.Y)).Magnitude
        return Magnitude
    end
    return math.huge
end

GetPrediction = function() 
    if x9['Global']['Auto Prediction'] then 

        local PingStats = game:GetService("Stats").Network.ServerStatsItem["Data Ping"]:GetValueString()
        local Value = tostring(PingStats)
        local PingValue = Value:split(" ")
        local PingNumber = tonumber(PingValue[1])

        if PingNumber < 130 then
            return tonumber(PingNumber / 1000 + 0.037)
        else
            return tonumber(PingNumber / 1000 + 0.033)
        end
    else
        return tonumber(x9['Silent Aim'].Config.Velocity.Prediction)
    end
end

if x9.Configuration.Checks['Auto Low GFX'] then
    for _,v in pairs(workspace:GetDescendants()) do
    if v.ClassName == "Part"
    or v.ClassName == "SpawnLocation"
    or v.ClassName == "WedgePart"
    or v.ClassName == "Terrain"
    or v.ClassName == "MeshPart" then
    v.Material = "Plastic"
    end
end
end



if x9.Configuration.Checks['Auto Mute Boombox'] == true then 
    for i,v in pairs(game.Players:GetChildren()) do 
        if v.Name ~= game.Players.LocalPlayer.Name then 
            if game.Players:FindFirstChild(v.Name) then 
                repeat wait() until v.Character
                for i,x in pairs(v.Character:GetDescendants()) do
                    if x:IsA("Sound") and x.Playing == true then
                        x.Playing = false
                    end
                end
            end
        end
    end
end

local function velocityCalculation(SilentTarget)
    if x9['Silent Aim'].Enabled then
        if SilentTarget and SilentTarget.Character.HumanoidRootPart then
            local currentPosition = SilentTarget.Character.HumanoidRootPart.Position
            local currentTime = tick() 
            wait(0.0035)
            
            local newPosition = SilentTarget.Character.HumanoidRootPart.Position
            local newTime = tick()
            local timeInterval = (newTime-currentTime)
            local newVelocity = (newPosition-currentPosition)/timeInterval
            
            currentPosition = newPosition
            currentTime = newTime
            return newVelocity
        end
    end
end



FindCrew = function(Player)
    if Player:FindFirstChild("DataFolder") and Player.DataFolder:FindFirstChild("Information") and Player.DataFolder.Information:FindFirstChild("Crew") and LocalPlayer:FindFirstChild("DataFolder") and LocalPlayer.DataFolder:FindFirstChild("Information") and LocalPlayer.DataFolder.Information:FindFirstChild("Crew") then
        if LocalPlayer.DataFolder.Information:FindFirstChild("Crew").Value ~= nil and Player.DataFolder.Information:FindFirstChild("Crew").Value ~= nil and Player.DataFolder.Information:FindFirstChild("Crew").Value ~= "" and LocalPlayer.DataFolder.Information:FindFirstChild("Crew").Value ~= "" then 
            return true
        end
    end
    return false
end

GetGunName = function(Name)
    local split = string.split(string.split(Name, "[")[2], "]")[1]
    return split
end

GetCurrentWeaponName = function()
    if LocalPlayer.Character and LocalPlayer.Character:FindFirstChildWhichIsA("Tool") then
       local Tool =  LocalPlayer.Character:FindFirstChildWhichIsA("Tool")
       if string.find(Tool.Name, "%[") and string.find(Tool.Name, "%]") and not string.find(Tool.Name, "Wallet") and not string.find(Tool.Name, "Phone") then
          return GetGunName(Tool.Name)
       end
    end
    return nil
end

WTS = function(Object)
    local ObjectVector = CurrentCamera:WorldToScreenPoint(Object.Position)
    return v2.new(ObjectVector.X, ObjectVector.Y)
end

Filter = function(obj)
    if (obj:IsA('BasePart')) then
        return true
    end
end

mousePosv2 = function()
    return v2.new(Mouse.X, Mouse.Y) 
end

IsOnScreen2 = function(Object)
    local IsOnScreen = CurrentCamera:WorldToScreenPoint(Object.Position)
    return IsOnScreen
end

FilterObjs = function(Object)
    if string.find(Object.Name, "Gun") then
        return
    end
    if table.find({"Part", "MeshPart", "BasePart"}, Object.ClassName) then
        return true
    end
end


GetClosestBodyPart = function()
    local character = SilentTarget.Character
    local ClosestDistance = 1 / 0
    local BodyPart = nil
    if (character and character:GetChildren()) then
        for _, x in next, character:GetChildren() do
            if FilterObjs(x) and IsOnScreen2(x) then
                local Distance = (WTS(x) - v2.new(Mouse.X, Mouse.Y)).Magnitude
                    if (Distance < ClosestDistance) then
                        ClosestDistance = Distance
                        BodyPart = x
                    end
            end
        end
    end
    if x9['Silent Aim'].Config.Points['Nearest Part'] then 
        closestsilentbodypart = tostring(BodyPart)
    else
        closestsilentbodypart = x9['Silent Aim'].Config.Points.Point
    end

end

GetClosestBodyPart2 = function()
    local character = CamlockTarget.Character
    local ClosestDistance = 1 / 0
    local BodyPart = nil
    if (character and character:GetChildren()) then
        for _, x in next, character:GetChildren() do
            if FilterObjs(x) and IsOnScreen2(x) then
                local Distance = (WTS(x) - v2.new(Mouse.X, Mouse.Y)).Magnitude
                    if (Distance < ClosestDistance) then
                        ClosestDistance = Distance
                        BodyPart = x
                    end
            end
        end
    end
    if x9['Cam Lock']['Nearest Part'] then 
        closestcamlockpart = tostring(BodyPart)
    else
        closestcamlockpart = x9['Cam Lock'].Point
    end
end

UpdateFOV = function()
    Circle.Transparency = x9['Drawings Thug'].Circle.Silent.Transparency
    Circle.Radius = x9['Drawings Thug'].Circle.Silent.Size 
    Circle.Visible = x9['Drawings Thug'].Circle.Silent.Visible
    Circle.Color = x9['Drawings Thug'].Circle.Silent.Color
    Circle.Thickness = x9['Drawings Thug'].Circle.Silent.Thickness
    Circle.Filled = x9['Drawings Thug'].Circle.Silent.Filled
end

UpdateFOV2 = function()
    Circle2.Transparency = x9['Drawings Thug'].Circle.Aimbot.Transparency
    Circle2.Radius = x9['Drawings Thug'].Circle.Aimbot.Size 
    Circle2.Visible = x9['Drawings Thug'].Circle.Aimbot.Visible
    Circle2.Color = x9['Drawings Thug'].Circle.Aimbot.Color
    Circle2.Thickness = x9['Drawings Thug'].Circle.Aimbot.Thickness
    Circle2.Filled = x9['Drawings Thug'].Circle.Aimbot.Filled
    Circle2.Position = Vector2.new(Mouse.X, Mouse.Y + (game:GetService("GuiService"):GetGuiInset().Y))
end


CalculateChance = function(Percentage)
    Percentage = math.floor(Percentage)
    local chance = math.floor(Random.new().NextNumber(Random.new(), 0, 1) * 100) / 100

    return chance < Percentage / 100
end

GetClosestPlayer = function()
    local Target = nil
    local Closest = math.huge

    local HitChance = CalculateChance(x9['Silent Aim'].Config['Hit Chance'])

    if not HitChance then
        return nil
    end

    for _, v in pairs(Players:GetPlayers()) do
        if v.Character and v ~= LocalPlayer and v.Character:FindFirstChild("HumanoidRootPart") then
            if not OnScreen(v.Character.HumanoidRootPart) then 
                continue
            end
            if x9.Checks['Visible Check'] and not RayCastCheck(v.Character.HumanoidRootPart, v.Character) then 
                continue 
            end
            if x9.Checks['K.O Check'] and v.Character:FindFirstChild("BodyEffects") then
                local KoCheck 
                if game.PlaceId == 7242996350 or game.PlaceId == 12884917481 then 
                    KoCheck = v.Character.BodyEffects:FindFirstChild("KO").Value
                else
                    KoCheck = v.Character.BodyEffects:FindFirstChild("K.O").Value
                end
                local Grabbed = v.Character:FindFirstChild("GRABBING_CONSTRAINT") ~= nil
                if KoCheck or Grabbed then
                    continue
                end
            end
            if x9.Checks['Crew Check'] and FindCrew(v) and v.DataFolder.Information:FindFirstChild("Crew").Value == LocalPlayer.DataFolder.Information:FindFirstChild("Crew").Value then
                continue
            end

            local Distance = GetMagnitudeFromMouse(v.Character.HumanoidRootPart)

            if (Distance < Closest and Circle.Radius + 10 > Distance) then
                Closest = Distance
                Target = v
            end
        end
    end

    SilentTarget = Target
end

GetClosestPlayer2 = function()
    local Target = nil
    local Closest = math.huge

    for _, v in pairs(Players:GetPlayers()) do
        if v.Character and v ~= LocalPlayer and v.Character:FindFirstChild("HumanoidRootPart") then
            if not OnScreen(v.Character.HumanoidRootPart) then 
                continue 
            end
            if x9.Checks['Visible Check'] and not RayCastCheck(v.Character.HumanoidRootPart, v.Character) then 
                continue 
            end
            if x9.Checks['K.O Check'] and v.Character:FindFirstChild("BodyEffects") then
                local KoCheck 
                if game.PlaceId == 7242996350 or game.PlaceId == 12884917481 then 
                    KoCheck = v.Character.BodyEffects:FindFirstChild("KO").Value
                else
                    KoCheck = v.Character.BodyEffects:FindFirstChild("K.O").Value
                end
                local Grabbed = v.Character:FindFirstChild("GRABBING_CONSTRAINT") ~= nil
                if KoCheck or Grabbed then
                    continue
                end
            end
            if x9.Checks['Crew Check'] and FindCrew(v) and v.DataFolder.Information:FindFirstChild("Crew").Value == LocalPlayer.DataFolder.Information:FindFirstChild("Crew").Value then
                continue
            end

            local Distance = GetMagnitudeFromMouse(v.Character.HumanoidRootPart)

            if (Distance < Closest and Circle2.Radius + 10 > Distance) then
                Closest = Distance
                Target = v
            end
        end
    end

    CamlockTarget = Target
end

function checkifplayer(obj) 
    if game.Players:FindFirstChild(obj.Name) then 
        return true
    else
        return false
    end
end

LocalPlayer.Character.ChildAdded:Connect(function(Weapon)
    if x9['Weapon Modifications'].Enabled == true then
        local dis = (LocalPlayer.Character.HumanoidRootPart.Position - SilentTarget.Character.HumanoidRootPart.Position).Magnitude
        if SilentTarget then
            if Weapon.Name == "[Double-Barrel SG]" then
                if x9['Weapon Modifications']['Double Barrel'].FOV == true and x9['Weapon Modifications']['Double Barrel'].Prediction == true and x9['Weapon Modifications']['Double Barrel'].Smoothness == true and x9['Weapon Modifications']['Double Barrel']['Hit Chance'] == true then
                    if dis < x9['Weapon Modifications']['Double Barrel']['Close Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications']['Double Barrel']['Close FOV'] * 3
                        x9['Silent Aim']['Hit Chance'] = x9['Weapon Modifications']['Double Barre']['Close Hit Chance']
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications']['Tactical Shotgun']['Close Prediction']
                    elseif dis < x9['Weapon Modifications']['Double Barrel']['Mid Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications']['Double Barrel']['Mid FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications']['Double Barrel']['Mid Prediction']
                        x9['Silent Aim']['Hit Chance'] = x9['Weapon Modifications']['Double Barrel']['Close Hit Chance']
                    elseif dis < x9['Weapon Modifications']['Double Barrel']['Far Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications']['Double Barrel']['Far FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications']['Double Barrel']['Far Prediction']
                        x9['Silent Aim']['Hit Chance'] = x9['Weapon Modifications']['Double Barrel']['Close Hit Chance']
                    end
                end
            end
            if Weapon.Name == "[Revolver]" then
                if x9['Weapon Modifications'].Revolver.FOV == true and x9['Weapon Modifications'].Revolver.Prediction == true and x9['Weapon Modifications'].Revolver.Smoothness == true and x9['Weapon Modifications'].Revolver['Hit Chance'] == true then
                    if dis < x9['Weapon Modifications'].Revolver['Close Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications'].Revolver['Close FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications'].Revolver['Close Prediction']
                        x9['Silent Aim']['Hit Chance'] = x9['Weapon Modifications'].Revolver['Close Hit Chance']
                    elseif dis < x9['Weapon Modifications'].Revolver['Mid Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications'].Revolver['Mid FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications'].Revolver['Mid Prediction']
                        x9['Silent Aim']['Hit Chance'] = x9['Weapon Modifications'].Revolver['Mid Hit Chance']
                    elseif dis < x9['Weapon Modifications'].Revolver['Far Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications'].Revolver['Far FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications'].Revolver['Far Prediction']                        
                        x9['Silent Aim']['Hit Chance'] = x9['Weapon Modifications'].Revolver['Far Hit Chance']
                    end
                end
            end
            if Weapon.Name == "[TacticalShotgun]" then
                if x9['Weapon Modifications']['Tactical Shotgun'].FOV == true and x9['Weapon Modifications']['Tactical Shotgun'].Prediction == true and x9['Weapon Modifications']['Tactical Shotgun'].Smoothness == true and x9['Weapon Modifications']['Tactical Shotgun']['Hit Chance'] == true then
                    if dis < x9['Weapon Modifications']['Tactical Shotgun']['Close Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications']['Tactical Shotgun']['Close FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications']['Tactical Shotgun']['Close Prediction']
                        x9['Silent Aim']['Hit Chance'] = x9['Weapon Modifications']['Tactical Shotgun']['Close Hit Chance']
                    elseif dis < x9['Weapon Modifications']['Tactical Shotgun']['Mid Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications']['Tactical Shotgun']['Mid FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications']['Tactical Shotgun']['Mid Prediction']
                        x9['Silent Aim']['Hit Chance'] = x9['Weapon Modifications']['Tactical Shotgun']['Close Hit Chance']
                    elseif dis < x9['Weapon Modifications']['Tactical Shotgun']['Far Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications']['Tactical Shotgun']['Far FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications']['Tactical Shotgun']['Far Prediction']
                        x9['Silent Aim']['Hit Chance'] = x9['Weapon Modifications']['Tactical Shotgun']['Close Hit Chance']
                    end
                end
            end
            if Weapon.Name == "[Rifle]" then
                if x9['Weapon Modifications'].Rifle.FOV == true and x9['Weapon Modifications'].Rifle.Prediction == true and x9['Weapon Modifications'].Rifle.Smoothness == true then
                    if dis < x9['Weapon Modifications'].Rifle['Close Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications'].Rifle['Close FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction =
                            x9['Weapon Modifications']['Tactical Shotgun']['Close Prediction']
                    elseif dis < x9['Weapon Modifications'].Rifle['Mid Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications'].Rifle['Mid FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications'].Rifle['Mid Prediction']
                    elseif dis < x9['Weapon Modifications'].Rifle['Far Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications'].Rifle['Far FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications'].Rifle['Far Prediction']
                    end
                end
            end
            if Weapon.Name == "[Shotgun]" then
                if x9['Weapon Modifications'].Shotgun.FOV == true and x9['Weapon Modifications'].Shotgun.Prediction == true and x9['Weapon Modifications'].Shotgun.Smoothness == true then
                    if dis < x9['Weapon Modifications'].Shotgun['Close Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications'].Shotgun['Close FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction =
                            x9['Weapon Modifications']['Tactical Shotgun']['Close Prediction']
                    elseif dis < x9['Weapon Modifications'].Shotgun['Mid Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications'].Shotgun['Mid FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications'].Shotgun['Mid Prediction']
                    elseif dis < x9['Weapon Modifications'].Shotgun['Far Detection'] then
                        x9['Drawings Thug'].Circle.Silent.Size = x9['Weapon Modifications'].Shotgun['Far FOV'] * 3
                        x9['Silent Aim'].Config.Velocity.Prediction = x9['Weapon Modifications'].Shotgun['Far Prediction']
            
                    end
                end
            end
        end
    end
end)



function GetClosestPointOfPart(Part)
    local mouseray = Mouse.UnitRay
    mouseray = mouseray.Origin + (mouseray.Direction * (Part.Position - mouseray.Origin).Magnitude)
    local point =
        (mouseray.Y >= (Part.Position - Part.Size / 2).Y and mouseray.Y <= (Part.Position + Part.Size / 2).Y) and
            (Part.Position + v3.new(0, -Part.Position.Y + mouseray.Y, 0)) or Part.Position
    local check = RaycastParams.new()
    check.FilterType = Enum.RaycastFilterType.Whitelist
    check.FilterDescendantsInstances = {Part}
    local ray = game:GetService("Workspace"):Raycast(mouseray, (point - mouseray), check)
    if ray then
        return ray.Position
    else
        return Mouse.Hit.Position
    end
end

RunService.Heartbeat:Connect(function()
    UpdateFOV()
    UpdateFOV2()
    x9['Cam Lock'].Prediction = GetPrediction()
    if x9['Silent Aim'].Enabled then 
        GetClosestPlayer()
        if x9['Silent Aim'].Config.Points['Nearest Part'] and SilentTarget then 
            GetClosestBodyPart()
        end
    end
    if x9['Cam Lock'].Enabled then
        GetClosestPlayer()
        if x9['Cam Lock']['Nearest Part'] and CamlockTarget then 
            GetClosestBodyPart2()
        end
    end
end)

RunService.RenderStepped:Connect(function()
    if x9['Drawings Thug'].Circle.Silent.Stick and SilentTarget ~= nil and (SilentTarget.Character) then
        local Vector, OnScreen = CurrentCamera:WorldToViewportPoint(SilentTarget.Character[x9['Silent Aim'].Config.Points.Point].Position)
        Circle.Position = Vector2.new(Vector.X, Vector.Y)
        Circle.Position = Vector2.new(Vector.X, Vector.Y)
    else
        Circle.Position = Vector2.new(Mouse.X, Mouse.Y + (game:GetService("GuiService"):GetGuiInset().Y))
        Circle.Position = Vector2.new(Mouse.X, Mouse.Y + (game:GetService("GuiService"):GetGuiInset().Y))
    end
end)

RunService.RenderStepped:Connect(function()
    if true and SilentTarget ~= nil and (SilentTarget.Character) then
        local Vector, OnScreen = CurrentCamera:WorldToViewportPoint(SilentTarget.Character[x9['Silent Aim'].Config.Points.Point].Position)
        Line.Visible = true
        Line.From = Vector2.new(Mouse.X, Mouse.Y + (game:GetService("GuiService"):GetGuiInset().Y))
        Line.To = Vector2.new(Vector.X, Vector.Y)
    else
        Line.Visible = false
    end
end)

local txt1 = true
RunService.RenderStepped:Connect(function()
    if txt1 and SilentTarget ~= nil and (SilentTarget.Character) then
        local Vector, OnScreen = CurrentCamera:WorldToViewportPoint(SilentTarget.Character[x9['Silent Aim'].Config.Points.Point].Position)
        txt.Visible = true
        txt.Position = Vector2.new(Vector.X, Vector.Y)
    else
        txt.Visible = false
    end
end)



RunService.Heartbeat:Connect(function()
    if x9['Silent Aim'].Enabled and x9['Silent Aim'].Dot and SilentTarget then 
        local targetbone
        if x9.Airshot.Enabled then
            if SilentTarget.Character.Humanoid.Jump == true then
                targetbone = SilentTarget.Character[x9.Airshot.Point]
            else
                targetbone = SilentTarget.Character[closestsilentbodypart]
            end
        else
            targetbone = SilentTarget.Character[x9['Silent Aim'].Config.Points.Point]
        end
        local TargetCF = targetbone.Position
        if x9['Silent Aim'].Config.Points['Nearest Point'] then
            TargetCF = GetClosestPointOfPart(targetbone)
        end
        local Prediction
        if not x9.Resolver.Enabled then 
            Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + targetbone.Velocity * x9['Silent Aim'].Config.Velocity.Prediction
        else
            if x9.Resolver.Method == "MoveDirection" then 
                Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + SilentTarget.Character.Humanoid.MoveDirection * x9['Silent Aim'].Config.Velocity.Prediction * 16
            elseif x9.Resolver.Method == "Delta"  then
                Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + velocityCalculation(SilentTarget) * x9['Silent Aim'].Config.Velocity.Prediction 
            elseif x9.Resolver.Method == "No Prediction" then
                Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0)
            elseif x9.Resolver.Method == "Underground" then
                targetbone.Velocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                targetbone.AssemblyLinearVelocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + targetbone.Velocity * x9['Silent Aim'].Config.Velocity.Prediction
            end
        end
        Vis1.Position = CurrentCamera:WorldToViewportPoint(Prediction)
        Vis1.Visible = x9['Drawings Thug'].Dot.Visible
    else
        Vis1.Visible = false
    end 
    if x9['Cam Lock'].Enabled and x9['Cam Lock'].Dot and CamlockTarget then 
        local targetbone
        local shake = v3.new(0,0,0)
        if x9.Airshot.Enabled then
            if CamlockTarget.Character.Humanoid.Jump == true then
                targetbone = CamlockTarget.Character[x9.Airshot.Config.Points.Point]
            else
                targetbone = CamlockTarget.Character[closestcamlockpart]
            end
        else
            targetbone = CamlockTarget.Character[x9['Cam Lock'].Config.Points.Point]
        end
        local TargetCF = targetbone.Position
        if x9['Cam Lock']['Nearest Point'] then
            TargetCF = GetClosestPointOfPart(targetbone)
        end
        if x9['Cam Lock'].Shake.Enabled then 
            shake = v3.new(
                math.random(-x9['Cam Lock'].Shake.X, x9['Cam Lock'].Shake.X),
                math.random(-x9['Cam Lock'].Shake.Y, x9['Cam Lock'].Shake.Y),
                math.random(-x9['Cam Lock'].Shake.Z, x9['Cam Lock'].Shake.Z)
            ) * 0.1
        end
        local Prediction
        if not x9.Resolver.Enabled then 
            Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + targetbone.Velocity * x9['Cam Lock'].Prediction + shake
        else
            if x9.Resolver.Method == "MoveDirection" then 
                Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + CamlockTarget.Character.Humanoid.MoveDirection * x9['Cam Lock'].Prediction + shake * 16  
            elseif x9.Resolver.Method == "Delta"  then
                Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + velocityCalculation(CamlockTarget) * x9['Cam Lock'].Prediction + shake 
            elseif x9.Resolver.Method == "No Prediction"  then
                Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + shake 
            elseif x9.Resolver.Method == "Underground"  then
                targetbone.Velocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                targetbone.AssemblyLinearVelocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + targetbone.Velocity * x9['Cam Lock'].Prediction + shake
            end
        end
        Vis2.Position = CurrentCamera:WorldToViewportPoint(Prediction)
        Vis2.Visible = true
    else
        Vis2.Visible = false
    end 
end)


local speeding = false
Mouse.KeyDown:Connect(function(Key)
    if Key == (string.lower(x9.Macro.Bind)) and x9.Macro.Abuse == false then
        if x9.Macro.Enabled then
            speeding = not speeding
            if speeding == true then
                repeat task.wait(x9.Macro.Speed / 100)
                game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                task.wait(x9.Macro.Speed / 100)
                game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                task.wait(x9.Macro.Speed / 100)
                game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                task.wait(x9.Macro.Speed / 100)
                game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                task.wait(x9.Macro.Speed / 100)
                until speeding == false
            end
        end
    end
end)


Mouse.KeyDown:Connect(function(Key)
    if Key == (string.lower(x9.Macro.Bind)) and x9.Macro.Abuse == true then
        if x9.Macro.Enabled  then
            SpeedGlitch = not SpeedGlitch
            if SpeedGlitch == true then
                repeat task.wait(x9.Macro.Speed / 100)
                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                    task.wait(x9.Macro.Speed / 100)
                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                    task.wait(x9.Macro.Speed / 100)
                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                    task.wait(x9.Macro.Speed / 100)
                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                    task.wait(x9.Macro.Speed / 100)
                until SpeedGlitch == false
            end
        end
    end
end)

Mouse.KeyDown:Connect(function(Key)
    local Keybind = x9['Silent Aim'].Targetting.Keybind:lower()
    if (Key == Keybind) then
        if x9['Silent Aim'].Targetting['Keybind Enabled'] then 
            if x9['Silent Aim'].Enabled == true then 
                x9['Silent Aim'].Enabled = false
                notify("Silent aim disabled.")
            else
                x9['Silent Aim'].Enabled = true
                notify("Silent aim enabled.")
            end
        end
    end
end)

local function GetArgs()
    if game.PlaceId == 2788229376 or game.PlaceId == 4106313503 then
        return "UpdateMousePosI"
    elseif game.PlaceId == 5602055394 or game.PlaceId == 7951883376 then
        return "MousePos"
    elseif game.PlaceId == 10100958808 or game.PlaceId == 12645617354 or game.PlaceId == 14171242539 or game.PlaceId == 14412436145 or game.PlaceId == 14412355918 or game.PlaceId == 14413720089 then
        return "MOUSE"
    else
        return "UpdateMousePosI"
    end
end


local function GetEvent()
    for _, v in pairs(game.ReplicatedStorage:GetChildren()) do
        if v.Name == "MainEvent" or v.Name == "Bullets" or v.Name == ".gg/untitledhood" or v.Name == "Remote" or v.Name == "MAINEVENT" then
            return v
        end
    end
end

game.Players.LocalPlayer.Character.ChildAdded:Connect(LPH_NO_VIRTUALIZE(function(tool)
    if tool:IsA("Tool") then
        tool.Activated:Connect(function()
            if x9['Silent Aim'].Enabled then
                if SilentTarget ~= nil then
                    local targetbone
                    if x9.Airshot.Enabled then
                        if SilentTarget.Character.Humanoid.Jump == true then
                            targetbone = SilentTarget.Character[x9.Airshot.Config.Points.Point]
                        else
                            targetbone = SilentTarget.Character[closestsilentbodypart]
                        end
                    else
                        targetbone = SilentTarget.Character[x9['Silent Aim'].Config.Points.Point]
                    end
                    local TargetCF = targetbone.Position
                    if x9['Silent Aim'].Config.Points['Nearest Point'] then
                        TargetCF = GetClosestPointOfPart(targetbone)
                    end
                    local Prediction
                    if not x9.Resolver.Enabled then 
                        Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + targetbone.Velocity * x9['Silent Aim'].Config.Velocity.Prediction
                    else
                        if x9.Resolver.Method == "MoveDirection" then 
                            Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + SilentTarget.Character.Humanoid.MoveDirection * x9['Silent Aim'].Config.Velocity.Prediction * 16
                        elseif x9.Resolver.Method == "Delta"  then
                            Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + velocityCalculation(SilentTarget) * x9['Silent Aim'].Config.Velocity.Prediction 
                        elseif x9.Resolver.Method == "No Prediction" then
                            Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0)
                        elseif x9.Resolver.Method == "Underground" then
                            targetbone.Velocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                            targetbone.AssemblyLinearVelocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                            Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + targetbone.Velocity * x9['Silent Aim'].Config.Velocity.Prediction
                        end
                    end
                    GetEvent():FireServer(GetArgs(), Prediction)
                end
            end
        end)
    end
end))
    
game.Players.LocalPlayer.CharacterAdded:Connect(LPH_NO_VIRTUALIZE(function(Character)
    Character.ChildAdded:Connect(function(tool)
        if tool:IsA("Tool") then
            tool.Activated:Connect(function()
                if x9['Silent Aim'].Enabled then
                    if SilentTarget ~= nil then
                        local targetbone
                        if x9.Airshot.Enabled then
                            if SilentTarget.Character.Humanoid.Jump == true then
                                targetbone = SilentTarget.Character[x9.Airshot.Config.Points.Point]
                            else
                                targetbone = SilentTarget.Character[closestsilentbodypart]
                            end
                        else
                            targetbone = SilentTarget.Character[x9['Silent Aim'].Config.Points.Point]
                        end
                        local TargetCF = targetbone.Position
                        if x9['Silent Aim'].Config.Points['Nearest Point'] then
                            TargetCF = GetClosestPointOfPart(targetbone)
                        end
                        local Prediction
                        if not x9.Resolver.Enabled then 
                            Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + targetbone.Velocity * x9['Silent Aim'].Config.Velocity.Prediction
                        else
                            if x9.Resolver.Method == "MoveDirection" then 
                                Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + SilentTarget.Character.Humanoid.MoveDirection * x9['Silent Aim'].Config.Velocity.Prediction * 16
                            elseif x9.Resolver.Method == "Delta"  then
                                Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + velocityCalculation(SilentTarget) * x9['Silent Aim'].Config.Velocity.Prediction 
                            elseif x9.Resolver.Method == "No Prediction" then
                                Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0)
                            elseif x9.Resolver.Method == "Underground" then
                                targetbone.Velocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                                targetbone.AssemblyLinearVelocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                                Prediction = TargetCF + v3.new(0,x9['Silent Aim'].Config.Points['Point Offset'],0) + targetbone.Velocity * x9['Silent Aim'].Config.Velocity.Prediction
                            end
                        end
                        GetEvent():FireServer(GetArgs(), Prediction)
                    end
                end
            end)
        end
    end)
end))

local targeting = false

Mouse.KeyDown:Connect(function(Key)
    local Keybind = x9['Cam Lock'].Key:lower()
    if (Key == Keybind) then
        if x9['Cam Lock'].Enabled == true then 
            if targeting == false then 
                GetClosestPlayer2()
                if CamlockTarget ~= nil then 
                    targeting = true
                    if x9['Cam Lock'].Notify then 
                        notify("target: "..tostring(CamlockTarget))
                    end
                else
                
                    if x9['Cam Lock'].Notify then 
                        notify("null")
                    end
                end
            else
                targeting = false
                CamlockTarget = nil
                if x9['Cam Lock'].Notify then 
                    notify("off")
                end
            end
        end
    end
end)


game:GetService("RunService").RenderStepped:Connect(function()
    if x9['Cam Lock'].Flags['Unlock Outside FOV'] and CamlockTarget and CamlockTarget.Character and CamlockTarget.Character:FindFirstChild(closestcamlockpart) then
        if Circle2.Radius <
            (v2.new(
                CurrentCamera:WorldToScreenPoint(CamlockTarget.Character.HumanoidRootPart.Position).X,
                CurrentCamera:WorldToScreenPoint(CamlockTarget.Character.HumanoidRootPart.Position).Y
            ) - v2.new(Mouse.X, Mouse.Y)).Magnitude
         then
            CamlockTarget = nil
            targeting = false
        end
    end
    if x9['Cam Lock'].Flags['Unlock On KO'] == true and CamlockTarget ~= nil and CamlockTarget.Character and CamlockTarget.Character:FindFirstChild(closestcamlockpart) then
        if CamlockTarget.Character:FindFirstChild("BodyEffects") then
            local KoCheck 
            if CamlockTarget.Character.BodyEffects:FindFirstChild("KO") then 
                KoCheck = CamlockTarget.Character.BodyEffects:FindFirstChild("KO").Value
            elseif CamlockTarget.Character.BodyEffects:FindFirstChild("K.O") then
                KoCheck = CamlockTarget.Character.BodyEffects:FindFirstChild("K.O").Value
            end
            
            if KoCheck then
                CamlockTarget = nil   
                targeting = false
                if x9['Cam Lock'].Notify then 
                    notify("Target Knocked, Unlocked.")
                end
            end
        end
    end
    if x9['Cam Lock'].Flags['Unlock Behind Wall'] == true and CamlockTarget ~= nil and CamlockTarget.Character and CamlockTarget.Character:FindFirstChild(closestcamlockpart) then
        if not RayCastCheck(CamlockTarget.Character[closestcamlockpart], CamlockTarget.Character) then 
            CamlockTarget = nil   
            targeting = false
            if x9['Cam Lock'].Notify then 
                notify("Target Behind Wall, Unlocked.")
            end
        end
    end
    if x9['Cam Lock'].Enabled and CamlockTarget and CamlockTarget.Character and CamlockTarget.Character:FindFirstChild(x9['Cam Lock'].Point) then 
        if targeting == true then
            local targetbone
            local shake = v3.new(0,0,0)
            if x9.Airshot.Enabled then
                if CamlockTarget.Character.Humanoid.Jump == true then
                    targetbone = CamlockTarget.Character[x9.Airshot['Point']]
                else
                    targetbone = CamlockTarget.Character[closestcamlockpart]
                end
            else
                targetbone = CamlockTarget.Character[x9['Cam Lock'].Point]
            end
            local TargetCF = targetbone.Position
            if x9['Cam Lock']['Nearest Point'] then
                TargetCF = GetClosestPointOfPart(targetbone)
            end

            if x9['Cam Lock'].Shake.Enabled then 
                shake = v3.new(
                    math.random(-x9['Cam Lock'].Shake.X, x9['Cam Lock'].Shake.X),
                    math.random(-x9['Cam Lock'].Shake.Y, x9['Cam Lock'].Shake.Y),
                    math.random(-x9['Cam Lock'].Shake.Z, x9['Cam Lock'].Shake.Z)
                ) * 0.1
            end
            local Prediction
            if not x9.Resolver.Enabled then 
                Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + targetbone.Velocity * x9['Cam Lock'].Prediction + shake
            else
                if x9.Resolver.Method == "MoveDirection" then 
                    Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + CamlockTarget.Character.Humanoid.MoveDirection * x9['Cam Lock'].Prediction + shake * 16  
                elseif x9.Resolver.Method == "Delta"  then
                    Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + velocityCalculation(CamlockTarget) * x9['Cam Lock'].Prediction + shake 
                elseif x9.Resolver.Method == "No Prediction"  then
                    Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + shake 
                elseif x9.Resolver.Method == "Underground"  then
                    targetbone.Velocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                    targetbone.AssemblyLinearVelocity = v3.new(targetbone.Velocity.X, 0, targetbone.Velocity.Z)
                    Prediction = TargetCF + v3.new(0,x9['Cam Lock']['Point Offset'],0) + targetbone.Velocity * x9['Cam Lock'].Prediction + shakeP
                end
            end
            local Main = CF.new(CurrentCamera.CFrame.p, Prediction)
            if x9['Cam Lock'].Smoothness.Enabled then 
                CurrentCamera.CFrame = CurrentCamera.CFrame:Lerp(Main, x9['Cam Lock'].Smoothness.Value, "Exponential", Enum.EasingDirection.InOut)
            else
                CurrentCamera.CFrame = CurrentCamera.CFrame:Lerp(Main, 1, "Exponential", Enum.EasingDirection.InOut)
            end
        end
    end
end)

-- // fps made by dex
if getgenv().x9.Fps_Unlocker.Enabled == true then
    setfpscap(getgenv().x9.Fps_Unlocker.Cap)
else
    setfpscap(999)
end
--

-- // headless


if getgenv().x9.Options.Headless == false then
    game.Players.LocalPlayer.Character.Head.Transparency = 1
    for i,v in pairs(game.Players.LocalPlayer.Character.Head:GetChildren()) do
         if (v:IsA("Decal")) then
              v.Transparency = 1
         end
    end
end
--

-- // korblox
if getgenv().x9.Options.Korblox == false then
     local ply = game.Players.LocalPlayer
     local chr = ply.Character
     chr.RightLowerLeg.MeshId = "902942093"
     chr.RightLowerLeg.Transparency = "1"
     chr.RightUpperLeg.MeshId = "http://www.roblox.com/asset/?id=902942096"
     chr.RightUpperLeg.TextureID = "http://roblox.com/asset/?id=902843398"
     chr.RightFoot.MeshId = "902942089"
     chr.RightFoot.Transparency = "1"
     game.Players.LocalPlayer.Character.Humanoid.Jump = false
     wait(1)
end
