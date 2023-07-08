# 3D Maze
![1_2aMuMsqUbC9Dvb82lKId_w](https://github.com/Lhartey/Maze_Project/blob/master/3D_Maze/Images/1_2aMuMsqUbC9Dvb82lKId_w.jpg) COVER PHOTO
-----

### Creating a 3D maze with raycasting
![retextured_1](https://github.com/Lhartey/Maze_Project/blob/master/3D_Maze/Images/retextured_1.png)
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

### Project Inspiration
The inspiration for this maze game project came from my childhood memories of playing classic maze games and the joy they brought me. I vividly remember spending hours trying to navigate through intricate mazes, solving puzzles, and feeling a sense of accomplishment when I reached the end. These experiences sparked my interest in creating my own maze game and bringing that same joy to others.

During my time at [Holberton School](https://www.holbertonschool.com/about-holberton), I had the opportunity to explore various programming concepts and develop my skills in web development. As part of my portfolio, I wanted to showcase my abilities and create something fun and interactive. This led me to develop this maze game project, incorporating my passion for game design and programming.

### Personal Focus:
Throughout the project, I had specific areas of focus. My main focus was on back-end development, including implementing the pathfinding algorithm, managing data persistence, and ensuring seamless server-side functionality. I dedicated my efforts to creating efficient and robust code that facilitated smooth gameplay and a reliable gaming experience. By concentrating on the back-end aspects, I aimed to contribute to the game's overall performance, enhance the player's navigation experience within the maze, and ensure optimal functionality of key game features.
Overall, my project sought to create a captivating maze game for a diverse audience, with each team member bringing their skills and expertise to different aspects of the development process.
Growing up, I had always been fascinated by puzzles and problem-solving challenges. I spent hours absorbed in books filled with brain teasers and logic games, trying to crack each puzzle with determination and curiosity. This love for puzzles eventually led me to discover the world of video games, where I found the perfect blend of interactive challenges and immersive storytelling.
One summer, while I was visiting my grandmother, I stumbled upon an old puzzle hidden away in her storage room. The intricate maze, with its tilting platforms and tiny metal ball, instantly captivated me. I spent hours maneuvering the ball through the maze, trying to navigate the twists and turns to reach the end.
This experiences ignited a spark within me, fueling a deep fascination with mazes and their inherent complexity. I started exploring various maze games, both digital and physical, and the joy they brought me was unparalleled. The sense of achievement upon solving a challenging maze and the thrill of discovering hidden paths left an indelible impression on me.
When the opportunity arose to work on a project of our choice, the maze project really caught my eye and I knew that was the project I wanted to do, It was a chance to combine my passion for puzzles, my love for games , my skill of coding, and my desire to bring joy to others. I was excited to create an immersive maze game that would challenge players' problem-solving skills and provide them with a sense of accomplishment.
Working on this project not only allowed me to explore my technical skills but also tapped into a deeper personal connection. It reminded me of the joy and satisfaction I experienced as a child, engrossed in solving intricate mazes. I wanted to recreate that feeling for others, to share the thrill and satisfaction of overcoming challenging obstacles in a maze-like world.

### Technologies Used and Choices
In my maze game project, I carefully selected technologies to fulfill specific requirements and align with our development goals. Here is an overview of the technologies used and the reasoning behind our choices:
Technologies Used and Choices Made: In our maze game project, we carefully selected technologies to fulfill specific requirements and align with our development goals. Here is an overview of the technologies used and the reasoning behind our choices:

1. SDL2 (Simple DirectMedia Layer):
I chose SDL2 as the primary library for game development due to its cross-platform compatibility and extensive functionality.
SDL2 provided me with low-level access to graphics, audio, and input handling, allowing me to create an immersive and interactive game experience.
By working directly with SDL2, I had greater control over the game's performance and customization options.

2. Raycasting:
I implemented raycasting as the rendering technique for creating a 3D-like representation of the maze on a 2D screen.
Raycasting allowed me to achieve a pseudo-3D effect, giving depth and perspective to the maze environment.
This technique, popularized by early first-person shooter games, provided an efficient and visually compelling way to render the maze and optimize performance.

3. C Programming Language:
I chose C as the primary programming language for its efficiency, performance, and ability to work seamlessly with SDL2.
C allowed me to take full advantage of hardware acceleration and optimize the game's rendering and processing capabilities.
Additionally, C provided the necessary flexibility for memory management and control over resources, critical for game development.

### Timeline
The project timeline spanned several weeks, from the initial concept and planning stages to the implementation and testing phases. I dedicated significant time and effort to design engaging mazes, create challenging gameplay mechanics, and ensure a smooth user experience.

Portfolio Project for Holberton School:
This maze game project is part of my portfolio for Holberton School, where I have been honing my programming skills and expanding my knowledge in various areas of software development. It demonstrates my ability to design and develop interactive web applications, showcasing both my technical proficiency and creativity.

### Project Summary

![Screenshot(10)](https://github.com/Lhartey/Maze_Project/blob/master/3D_Maze/Images/Screenshot(10).png)

This maze game project is part of my portfolio for Holberton School, where I have been honing my programming skills and expanding my knowledge in various areas of software development. It demonstrates my ability to design and develop interactive web applications, showcasing both my technical proficiency and creativity. 

Thanks for taking your time to read if you have any questions, contribution or reviews you can contact me through my social media links below.

-			![thank-you](https://github.com/Lhartey/Maze_Project/blob/master/3D_Maze/Images/thank-you.gif)
-----

### Author/Developer
- Augustine .A Lartey
#### Socials:
- [GitHub](https://github.com/Lhartey)
- [linkdin](https://www.linkedin.com/in/augustine-lartey-56b3951ba/)
- [Twitter](https://twitter.com/Lhartey1)

### Resources
- [SDL2 API](https://wiki.libsdl.org/CategoryAPI)
- [LazyFoo Beginning Game Programming](http://lazyfoo.net/tutorials/SDL/index.php)
- [Ray-Casting Tutorial For Game Development And Other Purposes by F. Permadi](http://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/)
- [LodeV Raycasting Tutorial](http://lodev.org/cgtutor/raycasting.html)
- [Game Engine Black Book](https://www.amazon.com/Game-Engine-Black-Book-Wolfenstein/dp/1539692876)
- [John Watson](https://www.youtube.com/@johnwatson2675/streams)
