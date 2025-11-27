<!-- HEADER -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/helloalt12/helloalt12/main/assets/header-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/helloalt12/helloalt12/main/assets/header-light.png">
    <img alt="Header" src="https://raw.githubusercontent.com/helloalt12/helloalt12/main/assets/header-light.png" width="100%">
  </picture>
</p>

<!-- NAME -->
<h1 align="center">👋 Hi, I'm <strong>helloalt12</strong></h1>
<h3 align="center">🔥 Roblox Scripter • Luau Developer • Systems Engineer</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Luau-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Editor-VSCode-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/Framework-Rojo-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/GitHub-Automated-black?style=for-the-badge">
</p>

---

# 🚀 About Me
I create **clean, scalable, and modular gameplay systems** for Roblox using professional development workflows like **Rojo**, **VSCode**, **Git**, and strongly typed Luau.

My focus:
- ⚡ High-performance systems  
- 🧩 Modular architecture  
- 🔁 Reusable frameworks  
- ✔️ Professional project structure  

---

# 🎮 Roblox Development Skills

### 🧠 Core Scripting
- RemoteEvents & RemoteFunctions  
- Character physics & gameplay  
- OOP (constructors, metatables, inheritance)  
- DataStore + ProfileService  
- UI logic, animations & tween frameworks  
- System logic & state machines  
- Optimization & refactoring  

### 🔧 Tools & Workflow
- Rojo + Visual Studio Code  
- GitHub versioning  
- Type-checked Luau  
- ModuleScript architectures  
- Automated directory structure  

---

# 🎬 Portfolio Video Showcase  
> **6 high-quality showcases** featuring gameplay systems, UI frameworks, and tools.

---

# 🎞️ **Showcase Grid**
<table>
<tr>
<td>

### 🎥 UI Animation System  
<a href="https://youtu.be/VIDEO_ID_1">
  <img src="https://img.youtube.com/vi/9A8sQZDRn5o/maxresdefault.jpg" width="100%">
</a>

</td>
<td>

### 🎥 Combat / Ability System  
<a href="https://youtu.be/VIDEO_ID_2">
  <img src="https://img.youtube.com/vi/VIDEO_ID_2/maxresdefault.jpg" width="100%">
</a>

</td>
</tr>

<tr>
<td>

### 🎥 Inventory System  
<a href="https://youtu.be/VIDEO_ID_3">
  <img src="https://img.youtube.com/vi/VIDEO_ID_3/maxresdefault.jpg" width="100%">
</a>

</td>
<td>

### 🎥 NPC AI System  
<a href="https://youtu.be/VIDEO_ID_4">
  <img src="https://img.youtube.com/vi/VIDEO_ID_4/maxresdefault.jpg" width="100%">
</a>

</td>
</tr>

<tr>
<td>

### 🎥 Data & Progression  
<a href="https://youtu.be/VIDEO_ID_5">
  <img src="https://img.youtube.com/vi/VIDEO_ID_5/maxresdefault.jpg" width="100%">
</a>

</td>
<td>

### 🎥 UI Framework / Toolkit  
<a href="https://youtu.be/VIDEO_ID_6">
  <img src="https://img.youtube.com/vi/VIDEO_ID_6/maxresdefault.jpg" width="100%">
</a>

</td>
</tr>
</table>

---

# 🧩 Featured Systems

### 🧩 **UI Framework**
Reusable UI engine with:
- animation controllers  
- easing functions  
- transition states  
- scalable component logic  

### ⚙️ **Utility Toolkit**
Includes:
- Signal modules  
- State managers  
- Class builders  
- Module loaders  
- Automated service controllers  

### 🎮 **Gameplay Systems**
- Combat logic  
- Cooldowns  
- Timed VFX  
- Movement mechanics  
- Interaction systems  

---

# 🧪 Code Sample — **Professional OOP Pattern**
```lua
local Class = {}
Class.__index = Class

function Class.new(config)
    return setmetatable({
        Value = config.Value or 0
    }, Class)
end

function Class:Set(newValue)
    self.Value = newValue
end

function Class:Increment()
    self.Value += 1
end

return Class
