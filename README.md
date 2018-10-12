# Artificial-intelligence
Artificial intelligence TDDC17 HT 2018 lab 1 Vacuum Agent. Worked with ottodenesfay



ENVIRONMENT:

The main window of the application is divided into two parts: the environment visualization pane on the left and the text output pane which displays the redirected System.out.

In the environment pane the black squares represent obstacles. Trying to move an agent into an obstacle results in perceiving the bump equal to true. The grey squares represent the dirt. Moving into such a square results in perceiving the dirt equal to true. The graphical representation of the agent visualizes its current direction.

The following drop down menus are available to set the simulation parameters (from left):

Environment size can be set to 5x5, 10x10, 15x15, 20x20, 5x10, and 10x5.
Hinder probability indirectly specifies the amount of obstacles in the environment.
Dirt probability indirectly specifies the amount of dirt in the environment.
Random environment specifies whether a new environment should be generated for every run. This function is useful to test an agent in the same environment several times.
Delay specifies the delay between each simulation step.
The following buttons are available (from left):

Clear cleans the text output pane.
Prepare generates a random environment based on the selected parameters.
Run starts the simulation.
Step allows for performing one step of the simulation at a time. Make sure to execute Prepare first.
Cancel terminates the simulation.
