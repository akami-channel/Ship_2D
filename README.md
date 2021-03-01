
FOSS Game Project

I am making a game and a game engine in OpenGL using C++ and SDL... or maybe using WebGL bc browser is
highly accessible.

What is SDL?
a cross-platform library for setting up a window, handling user input, sound, an OpenGL context, etc.

What am I doing?
Basically it's a 3 layer cake:
1) at the base is a new OpenGL tutorial series I'm making called SDLGL_tuts (need better name) using
C++ and SDL (my previous one was in C using GLFW, you can find it on YouTube).
2) The second layer of the cake is an open-source game engine, which I am calling Ship 2D.
3) Top layer of the cake is a 2D tile-based game, which will take inspiration from Stardew Valley,
Factorio, Minecraft, etc. It will be online and free so people can join and play together.

Notes:

There are also projects called "shipbuilder" and "tutbuilder", which build the engine and the tutorial
series, respectively. For now they are elaborate copy-pasting programs, but I hope they will have a future.

I often have "dirty" versions of a project where I am free to develop in whatever way, then
the primary version is meant to be more clean. I could just have different branches in my repo,
but I want to do things this way because I also want a clean version that has a clean repo history.

Most of this stuff is public and can be found on my Github at github.com/akami-channel
Subscribe to my youtube channel too for updates on the game/engine.
Some of you know I've been working on a game for a while. Yes, that's a proprietary game.
I'm working on 2 games right now. This one is FOSS = free and open-source software.

I'm putting everything in this proj directory because I have this other repo called shipbuilder that is supposed to build ship_2D. That might be useful, for example, if I want to have extensions that can be added or not at will. The idea is that everything in proj can be examined with a checksum and I can test what shipbuilder builds against the ship_2D checksum. That way I can make automated tests.
