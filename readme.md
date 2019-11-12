# Roguelike tutorial 2019 made with Vox programming language

[Vox compiler](https://github.com/MrSmith33/tiny_jit)

Compile with `tjc source/main.vx source/kernel32.vx source/sdl.vx source/sdlimage.vx source/utils.vx SDL2.dll SDL2_image.dll C:\Windows\System32\kernel32.dll`
produces `main.exe` for win64

Requires `SDL2.dll` and `SDL2_image.dll` libraries for compilation and start.

Controls:
* `WASD` - move
* `LMB` / `RMB` - place / remove wall
* `[` / `]` - change view radius
* `Esc` - close