# 3D_Maze using raycasting
![maze gif](https://user-images.githubusercontent.com/88714347/171422634-8adc8811-2559-4ba1-967f-4caf909c3f22.gif)
- The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!.
- The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4.
- It runs on Mac OS X and Linux/Ubuntu. The game uses the technique raycasting to create the apparent 3D nature of the maze.
# About SDL2
- Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games. for more information on [SDL2](https://en.wikipedia.org/wiki/Simple_DirectMedia_Layer)

# Requirements to Play
  - Linux/ubuntu/Macos
  - SDL2 and its sdl_image

# Play the game
 - clone the [github repository](https://github.com/Audraaires/Maze3D-Project)
 - Compile all .c files in the maze directory:
  ```
  gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm $(sdl2-config --cflags --libs) -lSDL_image -o maze
   ```
 - Execute ./mazea and play game.
 - Use up and down arrow keys to move forward and backward (w and s keys perform the same function)
 - Use right and left arrow keys to turn the camera arround (d and a keys perform the same function)
# Controls
 W or up arrow key - Move forward
 S or down arrow - Move backward
 left arrow key - rotate player in anti-clock wise direction
 right arrow key - rotate player in clock wise direction

# Flow chart
![Capture](https://user-images.githubusercontent.com/88714347/171421868-d6a7a3d6-6acd-495e-9506-7ab381bba5a4.JPG)
# project Demo
 [![3D Maze](https://img.youtube.com/vi/y5FlT2oApag/0.jpg)](https://www.youtube.com/watch?v=y5FlT2oApag)
# Authors
Caleb Poku Ackom <https://www.linkedin.com/in/caleb-poku-ackom>
Sandra Bansah <https://www.linkedin.com>
Jabez Ackom <https://www.linkedin.com/in/jabez-ackom>
