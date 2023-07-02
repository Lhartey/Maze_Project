# 3D Maze
### Creating a 3D maze with raycasting
![textured_1](https://github.com/hicarrie/maze/blob/master/screenshots/textured_1.png)
-----

### About SDL2
- Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games. for more information on [SDL2](https://wiki.libsdl.org/SDL2/FrontPage)

### Requirements to Play
- `Linux/ubuntu or Macos`
- `SDL2 and its sdl_image`

### How to Compile and Run
- [SDL2](https://www.libsdl.org/download-2.0.php) and [SDL2_image](https://www.libsdl.org/projects/SDL_image/) are required to compile and use this program
- Compile with `gcc 4.8.4` with the following flags:
    ``gcc -O2 -g -Wall -Werror -Wextra -pedantic -Isrc/headers *.c -lSDL2 -lSDL2_image -lm -o maze `sdl2-config --cflags --libs` `` OR `make -f Makefile`
- Run the maze: `./maze` or `./maze maps/<map_name>`
- Disable textures: `./maze no_tex` or `./maze maps/<map_name> no_tex`

-----

### Synopsis
This 3D maze uses raycasting to draw the maze walls, utilizing [LodeV's](http://lodev.org/cgtutor/raycasting.html) method of using vectors to calculate ray length. By default the maze uses textures but textures can be disabled on execution.

#### Controls
- `W` : move forward
- `S` : move backward
- `D` : rotate camera right
- `A` : rotate camera left
- `E` : strafe right
- `Q` : strafe left
- `F` : toggle fullscreen
- `ESC` : quit

#### Maps
The maps are defined in 2D arrays in text files, which are parsed when passed as an argument to the maze executable. `0` represents open space, all other integers are drawn as walls.

### Author
- [Augustine Lartey](https://github.com/Lhartey)

### Resources
- [SDL2 API](https://wiki.libsdl.org/CategoryAPI)
- [LazyFoo Beginning Game Programming](http://lazyfoo.net/tutorials/SDL/index.php)
- [Ray-Casting Tutorial For Game Development And Other Purposes by F. Permadi](http://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/)
- [LodeV Raycasting Tutorial](http://lodev.org/cgtutor/raycasting.html)
- [Game Engine Black Book](https://www.amazon.com/Game-Engine-Black-Book-Wolfenstein/dp/1539692876)
- [John Watson](https://www.youtube.com/@johnwatson2675/streams)
