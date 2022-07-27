# Doom Engine (Renderer) in Python (For mice!)

## Built with
- Python 3.7.1
- pygame, numpy, pyopengl, pillow

Thanks to the great work done by jordansavant, based on the this doom engine I was able to recreate a virtual representation of the labyrinth used for study of mice behavior, first described in this research article: https://doi.org/10.7554/eLife.66175

In order to create the labyrinth I used the program Doom Builder (http://www.doombuilder.com/) 
* Some screenshots are attached
* If you would like to make changes to the labyrinth, you will need to install doom builder and open the 'DOOM.WAD' file located under the "wads" directory

## Changes that were made: 
- Changed all walls in the labyrinth to a shade of gray
- Increased the resolution to 1280x720 
- When the "UP" button is pressed the map appears, and when "DOWN" is pressed the map disappears
- Removed all other resources in the respitory and left the bare minimum for the program to run

## Running the labryinth
- Run with "py.exe main_diy.py wads/DOOM.wad"
- Use 'wasd' and left and right arrows to navigate  

## Resources

- Program to change map (Doom Builder) :http://www.doombuilder.com/
- Original C++ DIY Doom Engine: https://github.com/amroibrahim/DIYDoom
- Python port from C++ done by jordansavant: https://github.com/jordansavant/doomengine.python
