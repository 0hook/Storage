# Roblox Assets Collection

A comprehensive repository of resources for Roblox custom experiences, development, and modifications.

## 📂 Repository Contents

### 🎮 Lua Scripts

- **Skyboxes.lua** - Collection of custom skybox textures with IDs
- **Models.lua** - Library of 3D models with asset IDs and positioning data

### 🎨 Visual Assets

- **Tracers/** - Visual effects for projectile tracing and highlights
- **Imgs/** - Utility images and textures
- **Fonts/** - Custom fonts with TTF, TXT, and JSON variants

### 🔊 Audio Assets

- **HitSounds/** - Collection of hit confirmation sounds in MP3 format

## 🔧 Usage Guide

### Lua Scripts

```lua
local Skyboxes = require("Skyboxes")
local skyboxSet = Skyboxes["Vaporwave"] -- Access a specific skybox set

local Models = require("Models")
local modelData = Models["Tank"] -- Get model asset ID and offset
```

### Implementing Tracers

Tracer images can be used with Roblox's beam effects or custom rendering.

### Fonts

Each font includes:

- TTF file - Original font file
- TXT file - Base64 encoded variant
- JSON file - Font metadata for integration

### Sound Implementation

```lua
local sound = Instance.new("Sound")
sound.SoundId = "rbxassetid://[YOUR_SOUND_ID]"
sound.Parent = workspace
sound:Play()
```

## 📋 Asset Categories

### Skyboxes

- Default, Vaporwave, Redshift, Desert, Minecraft, Space Wave, Dark Night, and more

### Models

- Vehicles, Characters, Furniture, Buildings, Decorations, and Memes

### Tracers

- Lightning, Beam, Energy, Electro, DNA, and more

### HitSounds

- Game sounds (TF2, Minecraft, COD)
- Effect sounds (Beep, Bonk, Metal)
- Meme sounds

## ⚠️ Important Note

This repository is intended for educational purposes only. Use these assets responsibly and respect the terms of service of Roblox.

## 📝 Organization

Assets are organized by type to make finding and implementing resources easier:

```
Repository
├── Lua/           - Lua scripts and data files
├── Tracers/       - Visual beam/tracer effects
├── HitSounds/     - Audio files for hit confirmation
├── Fonts/         - Custom font files
└── Imgs/          - Miscellaneous images
```

## 🔄 Updates

New assets are added regularly. Check back often for updates!
