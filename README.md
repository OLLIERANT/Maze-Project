<h1>MAZE PROJECT</h1>
The Maze is a 3D Maze game that uses ray casting to render a 2D map unto a 3D navigable world!

The Maze was written in C using the SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

<h2>About SDL2</h2>

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

<h2>Background Context</h2>
The goal of this project is to create a game in 3D using the raycasting as the development concept.

<h3>Tasks</h3>
<ol>0. Walls !</ol>
In this first part, you’ll have to:
<li>Create a window with SDL2</li>
<li>Use raycasting to draw walls on your window !</li>
<li>You don't need to be able to rotate the camera during the execution in this part, but you must provide a way to change the angle of the camera in your code to see if it works after recompiling it</li>
<li>The color of the walls must be different from the color of the ground/ceiling</li>
<li>The map doesn’t need to be parsed from a file, but you must provide a way to modify it in your code to see if it works after recompiling it. (e.g. using an array of arrays of integers or characters)</li>
	
<ol>1. Orientation</ol>
In this part, you must draw a different color depending on the orientation of the walls.
<li>You must at least draw walls facing NORTH and SOUTH in a different color from walls facing EAST and WEST</li>
	
<ol>2. Rotation</ol>
You must provide a way to rotate the camera during the execution.
<li>For example, you can rotate the camera when the left,right arrows are pressed on the keyboard</li>
<li>Or you can rotate the camera when the mouse moves, just like a FPS game !</li>

<ol>3. Move</ol>
You must provide a way to move the camera during the execution.
<li>For example, you can move the camera when the w,a,s,d keys are pressed on the keyboard</li>

<ol>4. Ouch !
In this part, you must handle the collisions of the player (yes, let’s call the camera player now, it’s getting serious) with the walls.

<li>The player must not be able to enter walls</li>
<li>You can make the player slide on the walls instead of just stop it</li>
</ol>
<ol>5. Parser
In this part you must implement a parser to get the map from a file.

You are free to define the standards of your map (The character for a wall, the character for nothing, the extension of the file if you want, …)
Your program will need a parameter to run which will be the path to the map file
Draw the map

In this part, you must draw the map on the window.

You’re free to draw the map where you want, with the color you want, …
You must provide a way to enable/disable it during the execution
Include the player’s line of sight in the map
Coding style + Documentation

Check if your code fits the Holberton School coding style
Check if your code is well documented and respect the Holberton School documentation format
You can check all of this by yourself, just follow the instructions on this repository.

Be careful

The check will be done on each file present on your turn in repository. Even the files that was not required. So don’t forget to always keep your turn in directory clean.

Textures

In this part you have to add textures on your walls !

Multi task !

Add a way to move on several directions and rotate in the same time. Basically in this part you’ll have to handle multiple events on the same frame.

For example, if the keys to move are w,a,s,d:

If the keys w and s are pressed in the same time, the player shouldn’t move,
If the keys w and d are pressed in the same time, the player should move forward and right in the same time,
…
Ground textures

In this part you have to add textures on the ground and/or on the ceiling !

Weapons

Add weapons textures !

Enemies

Add some enemies !

Make it rain

Add rain and a possibility to stop / start the rain with a key.

Extra option

Shadows, special lightning, etc… get creative!

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
