## Starting A Library
  By Xheptc
```lua
local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/Unknownkellymc1/Libraries/main/Oxy/source.lua", true))() -- finds the site raw
```
## Booting A Window
```lua
local Window = Lib:Create();--creates main lib
local WhiteText = "Oxy" -- A Name Of Window At First Left
local BlackText = "Hub" -- A Plus Name Of Window At Second Right
```

## Creating A Tab
```lua
local MainTab = Window:CreateSection("A") -- Create Section makes new tab
```

## Creating A Label
```lua
MainTab:CreateLabel("A") -- 1 Label Text
```

## Creating A Button
```lua
MainTab:CreateButton("a","Print", function() -- 1 (Button Info) 2 (Button Text)
   print("ImHottie")
end)
```

## Creating A Toggle
```lua
MainTab:CreateToggle("Prints State", function(state) --1 (Toggle Info) / state = on or off
   print(state)
end)
```

## Creating A TextBox
```lua
MainTab:CreateTextBox("YayFucker", "Fucking Yes", function(val) -- 1 (TextBox Info) 2 (TextBox PlaceHolder) / val = textbox text
   print(val)
end)
```

## Creating A Slider
```lua
MainTab:CreateSlider(16, 500, "Walkspeed", function(val) -- 1 (Min Value) 2 (Max Value) 3 (Slider Info)
   game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = val
end)
```

## Creating A Keybind <PC>
```lua
MainTab:CreateKeyBind("Opens or Closes UI", Enum.KeyCode.F, function() --1 (Keybind info); 2 default keybind
   Lib:CloseOpen()  -- closes or opens on F click
end)
```

### Destroy A Library
```lua
Lib:Destroy()
```
### A ITS ALL MADE BY XHEPTC
Please Dont Judge





