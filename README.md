<!-- HEADER -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/helloalt12/helloalt12/banner">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/helloalt12/helloalt12/banner">
  <img alt="Header" src="https://raw.githubusercontent.com/helloalt12/helloalt12/main/assets/header-light.png">
</picture>

# 👋 Hi, I'm **helloalt12**
### 🔥 Roblox Scripter • Luau Developer • Systems Engineer

I develop **clean, modular, and scalable gameplay systems** for Roblox using Luau, ModuleScript architecture, and a Rojo-based workflow.  
Focused on maintainable code, professional structure, and high-efficiency systems.

---

# 🎮 Roblox Development Skills

### 🧠 Core Scripting
- RemoteEvents & RemoteFunctions  
- Character / physics gameplay  
- OOP patterns (constructors, metatables)  
- DataStore & ProfileService  
- UI scripting, transitions & animations  
- Systems logic & state machines  
- Optimization, code cleanup & refactoring  

### 🔧 Tools & Workflow
- Rojo + Visual Studio Code  
- GitHub version control  
- Roblox Studio Team Create  
- Luau type checking  
- Modular architecture patterns  
- Automated project structure  

---

# 🎬 Portfolio Video Showcase  
> Here are **6 professional scripting showcases**, demonstrating UI systems, gameplay mechanics, frameworks, and modular tools.

---

### 🎥 **1. UI Animation System — Smooth Transitions & Components**  
[![UI Animation Demo](https://img.youtube.com/vi/VIDEO_ID_1/maxresdefault.jpg)](https://youtu.be/VIDEO_ID_1)

---

### 🎥 **2. Ability / Combat System — Effects, Timing, Server Sync**  
[![Combat System Demo](https://img.youtube.com/vi/VIDEO_ID_2/maxresdefault.jpg)](https://youtu.be/VIDEO_ID_2)

---

### 🎥 **3. Custom Inventory System — Drag, Drop, Slot Logic**  
[![Inventory Demo](https://img.youtube.com/vi/VIDEO_ID_3/maxresdefault.jpg)](https://youtu.be/VIDEO_ID_3)

---

### 🎥 **4. NPC System — Movement, Detection, Behavior Logic**  
[![NPC System Demo](https://img.youtube.com/vi/VIDEO_ID_4/maxresdefault.jpg)](https://youtu.be/VIDEO_ID_4)

---

### 🎥 **5. Data & Progression System — Saving, Loading, Stats**  
[![Data System Demo](https://img.youtube.com/vi/VIDEO_ID_5/maxresdefault.jpg)](https://youtu.be/VIDEO_ID_5)

---

### 🎥 **6. UI Framework / Utility Toolkit — Modules & Reusable Functions**  
[![Toolkit Demo](https://img.youtube.com/vi/VIDEO_ID_6/maxresdefault.jpg)](https://youtu.be/VIDEO_ID_6)

---

# 🚀 Featured Systems

### 🧩 **UI Framework**
A reusable UI architecture that supports animation controllers, easing functions, transitions, and component logic.

### ⚙️ **Utility Toolkit**
Includes signal modules, state managers, module loaders, automated controllers, and helper utilities.

### 🎮 **Gameplay Systems**
Combat logic, cooldown systems, VFX timing, physics mechanics, and character interactions.

---

# 🧪 Code Samples (Professional)

### 🟦 OOP Pattern — Clean & Reusable
```lua
local Class = {}
Class.__index = Class

function Class.new(config)
    return setmetatable({
        Value = config.Value or 0
    }, Class)
end

function Class:Set(v)
    self.Value = v
end

function Class:Increment()
    self.Value += 1
end

return Class
