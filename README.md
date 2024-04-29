<h1>MAZE PROJECT</h1>
The Maze is a 3D Maze game that uses ray casting to render a 2D map unto a 3D navigable world!

The Maze was written in C using the SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

<h2>About SDL2</h2>

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

<h3>Instalation</h3>

	- $ git clone https://github.com/OLLIERANT/Maze-Project.git

<h3>Usage & How to Play</h3>

	- Execute ./maze or type make run
	- Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
	- Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

<h3>Compilation</h3>

	- $ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;

<h3>Flowchart</3>

<h3>Demo</h3>
