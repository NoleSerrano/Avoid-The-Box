# Avoid-The-Box
This project is a part of the project 9 in the nand2tetris and CS 3650.

# Controls
Arrow keys and space to create walls\
q to quit\
r to restart (will be implemented in updated version)\
Note: The space is used to create edge walls on the chance that the box flies near the middle of the screen.

# Objective of the Game
Avoid the box flying inside the screen by placing walls where the box is currently not at. The speed of the box has a chance to change at each collision. Specifically, the box's x velocity can be double its base velocity and the y's velocity cane be double its base velocity. Note, the x's velocity is double the y's velocity because the screen inside of the VM Emulator is 512x256. Further note, it's not as easy game as a game you would think where you can just rotate the black wall around the box. The variable speed of the box throws you off. Further note, theoretically, you would never need to use the edge walls if the box is directly in the middle because there is no exact middle in the screen since it's 512x256 pixels.

# Video of Gameplay
Link: https://gyazo.com/e85436737ae5cca00736f7005b81ffd7

# How to Use
Download the folder "CS 3650 Project 9" > Open the VM Emulator supplied by nand2tetris > Load the directory > Accept the OS files > Play
