![RobloxStudioBeta_YY5pypWTj6](https://github.com/user-attachments/assets/2295f92b-feea-4119-9820-48d61324bc9a)
# FluentPlus - Enhanced Roblox UI Library

A modified and enhanced version of [Fluent](https://github.com/dawid-scripts/Fluent) with additional features and improvements.

## ✨ Features Added

- **🎨 Extended Theme Collection** - Much more themes available
- **🔍 Element Search** - Search functionality across all modules and elements  
- **🖱️ Interface Toggle Button** - Fixed and improved for both PC and mobile
- **🎯 Icon Support** - Icons for sections, window title and tabs using Lucide icon system
- **🐛 Bug Fixes** - Various stability and performance improvements
- **📃 Open Source** - This version have full source code in one script

## 📦 Installation

- Beta
```lua
local Fluent = loadstring(Game:HttpGet("https://raw.githubusercontent.com/discoart/FluentPlus/refs/heads/main/Beta.lua"))()
```

- Stable
```lua
local Fluent = loadstring(Game:HttpGet("https://raw.githubusercontent.com/discoart/FluentPlus/refs/heads/main/release.lua"))()
```

## 🚀 Quick Start

```lua
-- Create window
local Window = Fluent:CreateWindow({
    Title = "My Script",
    SubTitle = "Enhanced UI",
    Size = UDim2.fromOffset(580, 460),
    Acrylic = true,
    Theme = "Dark"
})

-- Create tab with icon
local Tab = Window:AddTab({ Title = "Main", Icon = "settings" })

-- Create section with icon
local Section = Tab:AddSection("Configuration", "cog")
```

## 🎨 Available Themes

Dark, Darker, AMOLED, Light, Balloon, SoftCream, Aqua, Amethyst, Rose, Midnight, Forest, Sunset, Ocean, Emerald, Sapphire, Cloud, Grape, Bloody

## 📄 License

Based on the original [Fluent](https://github.com/dawid-scripts/Fluent) library.
