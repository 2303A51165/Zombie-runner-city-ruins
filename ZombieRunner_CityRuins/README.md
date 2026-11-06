# Zombie Runner - City Ruins : Midnight Edition (Unity 3D)

Open with Unity Hub: Add -> select this folder (the one containing Assets, Packages, ProjectSettings).
Made for Unity 2022.3 LTS (project file says 2022.3.20f1). Any newer 2022.3 or Unity 6 editor also works:
in Unity Hub pick "Choose another editor version" when asked.

Press Play (scene: Assets/Scenes/Main.unity). The game builds its own city, player, zombies, UI and sounds from code.

Controls: A/D or Left/Right = lane, Space/W/Up = jump, S/Down = slide, P = pause, R/Space = restart.
Touch/mouse: swipe left/right/up/down.

Features: running player, zombie enemies, ruined night city, jump + slide obstacles, score + combo multiplier,
100-point health bar with medkits, game over + restart screen, saved best score.

Scripts (Assets/Scripts): GameManager (game loop, health, score, HUD), World (endless city + obstacle spawning),
Player (lane/jump/slide), ZombieRig (zombie model + animation), Horde (chasing pack), Models (props),
Prims (primitive builder), GameInput (keyboard/touch), Sfx (generated sounds).
