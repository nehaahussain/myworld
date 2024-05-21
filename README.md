## Game World Generation


### 1. Introduction
A 2D tile-based world generation using Java with a feature that only displays tiles on the screen that are within the line of sight of the avatar. Please email me to view the code.

### 2. Class Project Site
https://sp24.datastructur.es/projects/proj3/

### 3. Features
Once the program is launched, a menu window will be displayed.

<img width="400" alt="Screenshot 2024-05-21 at 6 11 29 PM" src="https://github.com/nehaahussain/myworld/assets/67764423/075b992b-45c8-484d-8fbb-d0f2c323bd73">

The following options are available:

  • Press 'N' or 'n' to generate a new world.

  • Press 'L' or 'l' to load a saved world.

  • Press 'Q' or 'q' to quit the world.

After selecting a new world, another window will be displayed, asking the user to enter a seed. The seed is a positive number up to 9,223,372,036,854,775,807 and is used by the random generator to generate a unique game world. If you enter the same seed, an identical world will be generated.


<img width="450" alt="Screenshot 2024-05-21 at 6 12 17 PM" src="https://github.com/nehaahussain/myworld/assets/67764423/aae13c8c-bc7c-4f22-a2c5-26821279c9f6">
<img width="450" alt="Screenshot 2024-05-21 at 6 12 29 PM" src="https://github.com/nehaahussain/myworld/assets/67764423/c061be40-e73e-43f5-9766-29089305ba50">

Once the seed is entered, press 'S' or 's' to pick the type of world — original, flower, or tree. 

<img width="500" alt="Screenshot 2024-05-21 at 6 12 43 PM" src="https://github.com/nehaahussain/myworld/assets/67764423/a8ef5a8f-4aff-4b33-b117-efe77645d446">

After pressing one of the keys to generate the world, only the player avatar (@) and its surroundings are visible, while the rest of the map is covered. Users can press 'W', 'A', 'S', 'D' to move the avatar around the world and ':Q' to quit and save the current state of the world. Also, a status bar is shown on the top left, displaying the type of tile over which a mouse cursor is hovering.

<img width="500" alt="Screenshot 2024-05-21 at 6 20 01 PM" src="https://github.com/nehaahussain/myworld/assets/67764423/b6a76224-c460-4416-8c45-f28da10c7932">

Users can press 'T' to increase the line of sight and view the entire world which consists of uniquely generated rooms and hallways. Below is the same world in different types.

<img width="400" alt="Screenshot 2024-05-21 at 6 12 58 PM" src="https://github.com/nehaahussain/myworld/assets/67764423/de7ce615-436b-452c-9122-2ea6db8e831c">
<img width="400" alt="Screenshot 2024-05-21 at 6 14 12 PM" src="https://github.com/nehaahussain/myworld/assets/67764423/c9d35482-cfa7-4d24-b7a2-351d98fb2312">
<img width="400" alt="Screenshot 2024-05-21 at 6 14 49 PM" src="https://github.com/nehaahussain/myworld/assets/67764423/b8dae9b2-29fc-476e-bb51-386cb21e147e">
