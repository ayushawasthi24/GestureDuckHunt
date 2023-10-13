# Gesture Duck Hunt Game

This is the old duckhunt game that uses hand geestures as controls for the game. This is a project of the Make It Real event of the Cynaptics Club.

# Overview

- The game is built using pygame library of python.
- To control the game using hand gestures, techniques of computer vision are applied.
- Mediapipe is used to detect hand landmarks and gestures.
- The hand movements are tracked and coordinates are found.
- The crosshair is then moved to the corresponding coordiantes and whenever the click gesture is detected, mouse click event is fired.

## How to play this game as a user?

- Clone this repo using
  `git clone https://github.com/CynapticsAI/GestureDuckHunt`

- Go into the root of this directory.
  `cd GestureDuckHunt`

- Now install the required dependencies.
  `pip install -r requirements.txt`

- To run the game, run the following command,
  `python duckhunt.py`

- Alternatively, you can run the duckhunt.exe file to play the game.

- Note that the .exe file must be in the root directory of this game.

### Controls overview

- Move your hand facing it towards the webcam, in order to move the mouse.
- In order to fire, make a pointing up gesture with the index finger (thumb and fingers closed in a fist and the index pointing upwards).

## For developers

- This game uses a mediapipe based model.
- The configurations can be altered using the game/hand_model.py file.
- The controls can also be changed by changing the is_click function of this file.
- Other models like YOLO can also be used by changing this file.
- Make sure to add the dependencies in the requirements.txt file.
