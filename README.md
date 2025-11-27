<!-- HEADER AUTO THEME -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/helloalt12/helloalt12/main/assets/header-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/helloalt12/helloalt12/main/assets/header-light.png">
  <img alt="Header" src="https://raw.githubusercontent.com/helloalt12/helloalt12/main/assets/header-light.png">
</picture>

# 👋 Hi, I'm **helloalt12**
### 🔥 Roblox Scripter • Luau Developer • Systems Engineer

I build **clean, modular, and scalable Roblox systems** using Luau, OOP patterns, and Rojo workflow.  
Focused on performance, maintainability, and professional project structure.

---

# 🎮 **Roblox Development Skills**
### **Core Scripting**
- ✔️ Luau Scripting (modules, OOP, patterns)
- ✔️ RemoteEvents / RemoteFunctions
- ✔️ DataStore & ProfileService
- ✔️ Custom systems (mechanics, tools, UI logic)
- ✔️ Server–Client architecture

### **Tools & Workflow**
- ✔️ Rojo (VSCode workflow)
- ✔️ Git/GitHub versioning
- ✔️ Roblox Studio Team Create
- ✔️ Typing Luau + Linting
- ✔️ ModuleScript architecture

### **Extras**
- ✔️ UI Scripting
- ✔️ TweenService / Effects
- ✔️ Optimization & Refactoring
- ✔️ Asset automation

---

# 🚀 **Featured Projects**

### 🔹 **⚽ GoalKeeper System**
Multi–script system that controls goalkeeper AI, physics, animations, and ball tracking.

**Tech Used:** Luau, OOP, Rojo, ModuleScript  
**Highlights:**
- Intelligent save logic
- Modular & maintainable
- Server-client synced
- Configurable difficulty

---

### 🔹 **🧩 Custom UI Framework**
Lightweight UI handler for buttons, animations, popups, and transitions.

**Tech Used:** TweenService, ModuleScript  
**Highlights:**
- Reusable components  
- Dynamic style control  
- Clean and scalable  

---

### 🔹 **🔧 Roblox Utility Tools**
Small tools that improve the development experience.

Examples:
- Signal module  
- State manager  
- UI animator  
- Custom event bus  

---

# 📂 **Code Samples (Mini Showcase)**

### **🔥 Clean Module Pattern**
```lua
local Module = {}
Module.__index = Module

function Module.new()
    return setmetatable({
        Value = 0
    }, Module)
end

function Module:Increment()
    self.Value += 1
end

return Module
