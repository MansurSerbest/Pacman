Controls
========
Menu:
----
Xbox Controller : Use D-Pad

Play:
-----
Xbox Controller : Use D-Pad
Keyboard: player1 uses the arrow, player2 uses wasd

GitHub
=========

https://github.com/SariCari92/PacMan

Engine
=========

- The engine uses a component based system
- The game loop will pass delta time to the update method of the sceneobjects
- Command pattern is used to control the pacman and the ghost
- A class GameData is used to transfer data between different scenes
- To Turn off Debug Render, change the m_IsDebugRender to false in MovementComponent.h