lx-maze_project
This project serves as an alternative 'Maze project' for the 'Research & Project approval (Part 1)' project in the ALX Software Engineering program.

Maze project
Background Context
The objective of this project is to develop a 3D game using raycasting.

Tasks
Setting Up WallsInitial tasks involve:
Creating a window using SDL2
Employing raycasting to draw walls in the window.
The camera rotation functionality isn't required initially, but provisions should be made to adjust the camera angle in the code for testing after recompilation.
Walls must have different colors from the ground/ceiling.
The map doesn’t need to be loaded from a file initially, but there should be a way to modify it in the code for testing after recompilation (e.g., using arrays of integers or characters).
OrientationWalls must be drawn in different colors based on their orientation.
Walls facing NORTH and SOUTH should have a different color from walls facing EAST and WEST.
RotationImplement functionality to rotate the camera during gameplay.
For example, rotate the camera using keyboard arrow keys or mouse movements like a first-person shooter (FPS) game.
MovementImplement functionality to move the camera during gameplay.
For example, move the camera using the w,a,s,d keys.
Collision DetectionHandle player collisions with walls.
Ensure the player cannot pass through walls.
Implement sliding on walls instead of abrupt stops.
Map ParserImplement a parser to load the map from a file.
Define map standards (e.g., wall and empty space characters, file extension).
The program should accept a parameter specifying the path to the map file.
Map VisualizationImplement map visualization within the window.
Customize map appearance and color.
Allow enabling/disabling map display during gameplay.
Incorporate player's line of sight into the map.
Coding Style and Documentation
Ensure code adheres to the Holberton School coding style.
Ensure code is well-documented following the Holberton School documentation format.
You can verify compliance using the guidelines in this repository.Note: All files in the submission repository will undergo checks, so maintain a clean directory.
TexturesAdd textures to the walls.
Multi-TaskingEnable movement in multiple directions and simultaneous rotation.
Handle multiple events on the same frame effectively.
Ground TexturesAdd textures to the ground and/or ceiling.
WeaponsIncorporate weapon textures.
EnemiesIntroduce enemy characters.
Weather EffectsImplement rain with the ability to toggle it on/off using a key.
Additional FeaturesExplore creative enhancements such as shadows, special lighting effects, etc.




