# Grid Simulation with Delivery Points

## Introduction

This project is a simulation built with **Python** and **Pygame**. It features a 15x15 grid populated with various moving entities such as buildings, a robot, police, and two types of cars. The simulation uses pathfinding algorithms (Best-First Search and A*) to navigate the robot toward dynamically generated delivery points. Additionally, interactive item buttons are provided for extra functionality.

## How to Run the Code

### Prerequisites

- **Python 3.6 or later:** Make sure Python is installed on your system.
- **Pygame:** Install the Pygame library using pip:
  ```bash
  pip install pygame
  
### Setup

##### Download the Code and Assets:
Ensure that all code files and required image assets are in the same directory. (All required assets are already provided.)

Save the Code:
Save the provided code into a file named main.py.

Running the Simulation
Open a Terminal:
Navigate to the directory containing main.py and the assets.

Execute the Script:
Run the simulation with:

python main.py

### Interact with the Simulation:

A window will open displaying the grid with all the entities.
The robot will automatically calculate an optimal path toward the delivery points.
Use your mouse to interact with the delivery points and item buttons displayed below the grid.
Customization
Grid Dimensions:
Modify the rows and cols variables in main.py to change the grid size.

#### Movement Delays:
Adjust the constants CAR_MOVEMENT_DELAY and CAR_CHECK_DELAY to change the speed of entity movements.

### Image Assets:
You can replace the provided image files with your own assets if desired, ensuring that the file names match those referenced in the code.

### Code Overview
Grid and Entity Rendering:

The function draw_grid_with_entities() renders the grid and places buildings, the robot, police, and cars on it.
### Entity Movement:

Functions such as move_police(), move_car1(), and move_car2() handle the dynamic movement of entities while avoiding collisions.
Pathfinding Algorithms:

Implements Best-First Search and A* algorithms to calculate the optimal path from the robot to the delivery points.
Interactive Features:

Delivery points and item buttons allow for user interaction, enabling the simulation state to update as users click on these elements.
License
Include your project’s license information here (e.g., MIT License).

### Acknowledgments
Built with Pygame.
Inspired by various Pygame tutorials and community projects.
