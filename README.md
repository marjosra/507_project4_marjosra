SI 507 W19 - Project 4, Option 2

Author: Mark Ramirez

3 April 2019

# Welcome to the README for Mark's game 'Brick Annihilator'!

This Game is written in the file "SI507_project4.py", which (when run) launches the game 'Brick Annihilator'. Your task in this Game is to use your trusty ball and paddle to destroy the wall of bricks that lie in front of you. Be weary, though - the more bricks you break, the more uncontrollable your ball will be! If you miss hitting the ball, the Game will reset and your ball will be controllable once again.

(Much of this code was utilized from the lecture code 'Sample-Pyglet-Code')

To be able to run 'Brick Annihilator', it is necessary to install all of the modules mentioned in the "requirements.txt".

****************************

_**TO INSTALL MODULES**_

1. cd to the folder in which the files for 'Brick Annihilator' are stored
2. Type the following in the command prompt/terminal to install the necessary modules: **pip install -r requirements.txt**
3. Type the following in the command prompt/terminal to generate a list (which should look exactly like the text in "requirements.txt") of installed modules: **pip freeze**

****************************

_**THE "GUTS"**_

The 'guts' of this game are _many_. Classes and subclasses were necessary to create for the different elements that are visible in the Game's window. These range from object elements such as **Ball** and **Paddle** (each of which set up the properties of their namesakes), to interactive elements of the Game such as **BallDeflector** and **EndLine** (which provide code that allows the ball to bounce or be reset).

The majority of the processes of 'Brick Annihilator' are run within the function **main()**.

In all of the parts of 'Brick Annihilator' mentioned above, there are various **pyglet** methods used, allowing for easy game development.

****************************

Once you have successfully installed all of the necessary modules, you are ready to play 'Brick Annihilator'!

****************************

_**TO RUN THE APPLICATION**_

1. cd to the folder in which the files for this Application are stored.
2. Type the following in the command prompt/terminal: **python SI507_project4.py**
3. Once it begins running, you are playing the game!

****************************

_**CONTROLS**_

**To move paddle up:**
* Hold/Press 'W'

**To move paddle down:**
* Hold/Press 'S'

**To pause/unpause the Game:**
* Press 'P'

**To quit the Game:**
* Press 'Q'

****************************

That is all there is to it! Good luck breaking those bricks!
