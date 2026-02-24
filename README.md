# Gaze-based-interface-for-physically-disabled-users
This project builds a gaze-controlled interface that allows physically challenged users to interact with a computer system using only their eye movements.
The system captures images of the left and right eye, analyzes gaze direction, and maps it onto a 9-point calibrated grid displayed on the screen. Based on where the user looks, the system performs a selection or click action.
How It Works:
* The camera captures images of both eyes.

* The model processes the eye images to estimate gaze direction.

* The predicted gaze direction is mapped to one of 9 predefined grid points on the screen.

* When the user focuses on a grid cell, the corresponding action is triggered.
