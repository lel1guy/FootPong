# FootPong

> A football-themed Pong clone built in Godot 4.6.
> My first original game — no tutorial, just vibes.

Built by [@lel1guy](https://github.com/lel1guy) from Quarteira, Algarve, Portugal

---

## The Game

Classic Pong reimagined with a football theme. Two paddles, one ball, infinite goals. Control your striker on the left, block the defender on the right. First to score wins — then do it again.

---

## What's In It

- **Player vs Defender** — W/S controls for player, arrow keys for defender
- **Real-time score tracking** — HUD updates on every goal
- **Ball respawn** — timer between goals, ball resets to center
- **Pause menu** — ESC to pause, resume, or quit
- **Shader effect** — pause menu blur shader

---

## Built With

- [Godot 4.6](https://godotengine.org/) — game engine
- GDScript — scripting language

---

## Run It

```bash
git clone https://github.com/lel1guy/FootPong.git
```

Open Godot 4 -> **Import** -> select `project.godot` -> **F5** to run.

---

## Project Structure

```
FootPong/
├── Assets/          # Sprites, fonts
├── Scenes/          # Godot scene files (.tscn)
├── Script/          # GDScript files
│   ├── Main.gd          # Game loop, scoring, ball timer
│   ├── player.gd        # Player paddle movement (W/S)
│   ├── defender.gd      # Defender paddle movement (arrows)
│   ├── ball.gd          # Ball physics + respawn
│   ├── main_menu.gd     # Title screen
│   ├── pause_menu.gd    # Pause overlay + resume/quit
│   └── playerdefender.gd # Player vs defender scene logic
├── Shader/          # Pause menu blur shader
└── project.godot
```

---

## What I Learned

- Godot scene structure — nodes, scenes, signals
- Input mapping with `InputEventKey`
- Signal connections — `body_entered`, timers
- UI/HUD with `CanvasLayer`
- Exporting to Android

---

## Status: Complete

First game shipped. It's simple and it works. No plans to expand — this was a learning project, and it served its purpose.

---

## License

This project is currently unlicensed. All rights reserved.
