# PONG

This is a recreation of the classic pong video game. Implemented in the C
programming language, using SDL library to display graphics on the screen.

To compile you need to have SDL installed on your system and the header files
available to you operating systems PATH environment variable

`gcc pong.c -pthread -lSDL -o pong`

## Controls
* space bar to start a game
* arrow keys and "wasd" for movement
* ESC to exit game
* for multiplayer: server: ./pong, client: ./pong IP.

## Images
![title screen](https://user-images.githubusercontent.com/18473198/28231587-f12187c4-68f4-11e7-85e2-e8aec76ee10e.png)

![game play](https://user-images.githubusercontent.com/18473198/28231684-714e6b10-68f5-11e7-8ac0-31acf50c9e0c.png)
