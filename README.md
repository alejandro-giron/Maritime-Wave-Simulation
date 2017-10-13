# Maritime-Wave-Simulation
Final year project for Bachelor of Computer Science at La Trobe University
(Team I)

## Purpose of this project
This software aims to provide a realistic simulation of open sea conditions, and their interactions with a ship model.
The user is able to toggle between varying types of waves and change wind speed settings as per the [Beaufort Scale](https://en.wikipedia.org/wiki/Beaufort_scale). Training beginner ship crew can be a dangerous and expensive process if done out in the real ocean. This project aims to reduce the risk and cost associated with such training by helping learners get a taste of real sea conditions from a simulated environment. 

## Getting started
### System requirements
The minimum recommended hardware specifications as per the [Unreal Engine Wiki](https://wiki.unrealengine.com/Recommended_Hardware) are:

+ Desktop PC or Mac
+ Windows 7 64-bit or Mac OS X 10.9.2 or later
+ Quad-core Intel or AMD processor, 2.5 GHz or faster
+ NVIDIA GeForce 470 GTX or AMD Radeon 6870 HD series card or higher
+ 8 GB RAM

### Downloading and installing Unreal Engine 4

1. [Download](https://www.unrealengine.com/download) the Epic Games desktop application
2. Sign in or create a free Epic Games account
3. Once signed in, download the **Unreal Engine 4.17** version through the application. Please make sure that you download the **4.17 version** as it is required to run the project

### Opening and running the project
1. After installing the engine, launch it
2. Create a new project using the **Blueprint Basic** option, with starter content
3. Once the new project has launched, go to the Unreal launcher again. Your newly created
project should appear in the Library, under **My Projects**. Right click "Show in Folder"
4. Navigate to the **Content** folder of the new project and copy-paste the **Physical Water Surface** folder there
5. Close and re-launch the project. The folder you added should now appear
6. To run the project, go to the **Content** folder, click the **WindSpeedDemo** file, and click "Play" on the top bar
7. Press **Shift + F1** in your keyboard to enable the cursor and interact with the simulation

## Simulation Overview
![simulation screenshot](https://github.com/alejandro-giron/Maritime-Wave-Simulation/blob/master/simulation_view.png)

### User Interface Components
1. **Drop Down Menu:** By clicking the arrow, you can show and hide the menu on the right
2. **Beaufort Scale Menu:** Select a value from 1-12 to set the Beaufort Scale value
3. **Manual Wind Speed Setting:** Alternatively, you may enter a value for the wind speed. Accuracy is handled up to two decimal places (e.g. 45.21 km/h)
4. **Simulate Button:** Once the scale value has been select, clicking **Simulate** will run the simluation with the given values
5. **Current Value Representation:** This section displays the value of the wind speed and the scale
6. **Pawn Boat:** The ship model that the user can control
7. **Simulation Screen:** The boundary of the simulation screen. May be turned into full screen by pressing **Shift + F11**
8. **Start/Stop/Pause:** Start, stop or pausse the simulation
9. **Blueprint Files:** The Blueprint layer where most of the simulation functions exist. 

## Operating the simulation
1. Once the simulation has been started, you may operate the boat using the arrow keys, moving forwards, left of right with the corresponding key
2. To change the value of the scale, click the drop down menu
3. Select a value in the Beaufort Scale from 0-12
4. Alternatively, manually insert the value for the windspeed. The proper Beaufort Scale value will be calculated automatically
5. Click **Simulate**

## Project Contributors
+ Mobarak Alhasem - 17334403
+ Alejandro Giron - 18563086
+ Shippu Rani - 18043381
+ Kirandeep Kaur - 18373380


Last commit: 13/10/2017 4:34 pm
