# FootPong ⚽

A football-themed Pong clone — my first original game, built without following a tutorial.

**Engine:** Godot 4.6  
**Language:** GDScript  
**Platform:** Windows, Android (export preset ready)

## 🎮 Gameplay

Classic Pong with a football twist. Control your paddle on the left, score goals past the defender on the right.

| Action | Player 1 | Player 2 (Defender) |
|--------|----------|---------------------|
| Move up | W | ↑ |
| Move down | S | ↓ |

- Real-time score tracking (HUD)
- Ball respawn timer between goals
- Pause menu with shader effect

## 🛠️ What I learned

- Godot scene structure (scenes, nodes, scripts)
- Input mapping and `InputEventKey`
- Signal connections (`body_entered`, timers)
- UI/HUD with `CanvasLayer`
- Exporting to Android

## 🏗️ Project structure

```
FootPong/
├── Scenes/     # Main, menus, ball, players
├── Script/     # GDScript files
├── Assets/     # Sprites, fonts
├── Shader/     # Pause menu shader
└── project.godot
```

## 🚀 Running

1. Install [Godot 4.6](https://godotengine.org/download/)
2. Clone this repo
3. Open `project.godot` in Godot
4. Press F5 to play

---

*Built by [Vitor Vareiro](https://github.com/lel1guy) — part of the journey from electrician to game developer.*
