# Perf Boost

A Fabric mod for Minecraft 1.21.10 that adds a toggleable performance stats HUD and an optional **performance mode** that temporarily lowers graphics settings to improve FPS. All changes from performance mode are reverted when you turn it off.

---

## What this mod does

**Stats HUD** — A small overlay in the top-right (toggle with **P**) showing:
- FPS and frame time  
- RAM usage  
- Entity and chunk counts  
- Ping (multiplayer)  
- CPU usage and temperature (when available on your system)

**Performance mode** — Toggle with **O**. When **on**, the mod temporarily applies these changes to boost FPS:
- **Graphics**: set to Fast  
- **Particles**: set to Minimal, and active particles are capped at 2,000  
- **Render distance**: 8 chunks  
- **Simulation distance**: 6 chunks  
- **Entity distance scaling**: 0.5  
- **Ambient occlusion**: off  
- **Entity shadows**: off  
- **Biome blend**: 0  

When you turn performance mode **off**, your previous settings are restored. Nothing is saved to your options file; it only affects the current session.

---

## Why use it

- See FPS, RAM, and other stats at a glance without leaving the game.  
- Get a quick FPS boost in busy areas (e.g. lots of entities or particles) by pressing **O**; turn it off when you leave.  
- Keybinds are rebindable under **Perf Boost** in Options → Controls.

---

## Requirements and keybinds

- **Minecraft**: 1.21.10 (Fabric).  
- **Fabric Loader** and **Fabric API** are required.  
- **Toggle Perf HUD**: default **P**.  
- **Toggle Performance Mode**: default **O**.

## Screenshots

**Performance HUD** (press P to toggle)

![Perf Boost HUD](https://raw.githubusercontent.com/Omymobie/Perf-Boost/main/src/main/resources/assets/perfboost/hud.png)

**Keybinds in Settings**

![Perf Boost keybinds](https://raw.githubusercontent.com/Omymobie/Perf-Boost/main/src/main/resources/assets/perfboost/settings.png)

## License

MIT
