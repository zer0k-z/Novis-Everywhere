# Novis Everywhere

In CS:GO community servers that have noclip or freelook spectating, the map does not render once you fly into the void, making navigation difficult. 

Using the default `noclip` or `r_novis 1` console command works, however these commands are cheat protected.

This is a workaround to the problem. *Warning!* Running the script will disconnect you from the server (if you are connected) and prevents you from playing official matchmaking!

## What's inside?
- A script cfg file that disconnects you from the server and prepare necessary convars to load...
- ... a map that makes you noclip and teleports you to the void the moment you spawn.
- A map cfg file that improves execution speed. This is executed before the game actually loads the map.

## Instructions

1. Download the zip file from the releases tab.

2. Extract its contents to your game folder.

3. In console, type ``exec r_novis``. You will load into a map and immediately disconnect once the map start. 
    - How long this step takes mostly depends on your disk drive.

4. You are good to go! Join any community server you want and enjoy!

Bonus: you can also launch this when opening the game by adding `+exec r_novis` to your launch options.
