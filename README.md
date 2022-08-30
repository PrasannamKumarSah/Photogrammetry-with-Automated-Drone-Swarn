# Photogrammetry Using Automated Drone Swarming
###### OBJECTIVE :
To create a 3D model of any object or Environment using photographs and then extracting required important information and data from this model.
###### OVERVIEW :
<img src="https://github.com/PrasannamKumarSah/Photogrammetry-with-Automated-Drone-Swarn/blob/main/Images/Topic.png" width="250"> <img src="https://github.com/PrasannamKumarSah/Photogrammetry-with-Automated-Drone-Swarn/blob/main/Images/AirSim.png" width="250"> <img src="https://github.com/PrasannamKumarSah/Photogrammetry-with-Automated-Drone-Swarn/blob/main/Images/AgiSoft.png" width="250">

This Project aims to automate drone swarming to take images of the residential house site, and create a 3D model of that Residential House using images of residential house site that we take from our drones.We have done all this in Simulation but this all can be done in the real world also. For Simulation and for getting the virtual feel of a real environment we use AirSim and used its API with python to automate the drones and for swarming we used the AirSim Setting file. For creating a 3D model we used Agisoft Metashape Professionals.

###### Applications of this project:
- Land Surveying
- Agriculture and Forestry
- Construction and Mining
- Film and Entertainment
- Military Intelligence

###### Future Plans of this Project :
To practice this in the real world & add obstacle Avoidance to drone so that drone doesn’t crash in tree or building while taking images of site.

###### Setup :
First off all we need some software and simulators that should be downloaded to our PC so that we can start working. These are : AirSim ( Aerial Information and Robotics Simulation ), Agisoft Metashape & Sublime [or any Text editor you are comfortable with]

###### Approach :
Now the major steps that we have to follow are :
1. Launching AirSim with multiple drones that is we have to swarm first.
2. Automating all these drones to take images of the survey site with different angles and different height.
3. Surveying site and Collecting all images from drone and make sure the two consecutive images must have an overlap of (60 to 70)%.
4. Processing all collected images of the site to make a 3D model.
5. Now analyze and collect all the information that you want from this model.

###### Basic Information's :
- **Photogrammetry** :
Photogrammetry is the technology of obtaining reliable information about physical objects and the environment by the use of Aerial photographs.

<img src="https://github.com/PrasannamKumarSah/Photogrammetry-with-Automated-Drone-Swarn/blob/main/Images/1.png" width="800">

- **AirSim** :
AirSim(Aerial Informatics and Robotics Simulation) is an open-source, cross platform simulator for drones, ground vehicles such as cars and various other objects. It is developed by Microsoft and can be used to experiment with deep learning, computer vision, and reinforcement learning algorithms for autonomous vehicles. This allows testing of autonomous solution without worrying about real-world damage.

<img src="https://github.com/PrasannamKumarSah/Photogrammetry-with-Automated-Drone-Swarn/blob/main/Images/2.png" width="800">

- **Agisoft Metashape** :
It is a tool of Photogrammetry. This software is available in Standard and Pro version, the standard version is sufficient for interactive media tasks, while the Pro version is designed for authoring GIS content.

<img src="https://github.com/PrasannamKumarSah/Photogrammetry-with-Automated-Drone-Swarn/blob/main/Images/3.png" width="800">

###### Procedure :
- **Launching AirSim with multiple drones that is we have to swarm first.**

Step 1 : Install and launch AirSim. This will automatically create a file named “settings.json” in your PC documents under the folder named AirSim.

Step 2 : Now Replace “settings.json” file available in your PC to the file named “settings.json” in project resource.
- **Automating all these drones to take images of the survey site with different angles and different height.**

Step 3 : Now open sublime or any text editor to start writing code for the drone to automate it. In this project we did this using python but if you want you can do the same with C++ also. For the reference of writing and understanding code in python use the file named “ ProjectTry1.py “ and “ ProjectTry2.py “ in resouces.

Step 4 : Or if you don’t want to write the code Just skip step 3 and Download the file named “ ProjectTry1.py “ and “ ProjectTry2.py “ from resources.
- **Surveying site and Collecting all images from drone and make sure the two consecutive images must have an overlap of (60 to 70)%.**

Step 5 : Now open AirSim(if already opened, close it and open again) and then Run both the Python Script in the command prompt (if you are using Windows PC ).

Step 6 : Now wait until the survey gets completed and you get your collection of images of your survey site.
- **Processing all collected images of the site to make a 3D model. (NOTE : In images “ Chunk “ is “ Model 1 “. This is because Chunk name can be renamed. )**

Step 7 : Now close Everything and open Agisoft Metashape.

Step 8 : Now in the left hand side option, Right click on Chunk and under Add menu select “ Add Photos “. This will open a pop-up window now in this window browse photos of site Select them all and then click open. This will import images to Agisoft Metashape.

Step 9 : Now again right click on Chunk and under Process menu select “Align Photos “ . This will again open a pop-up window just click “ OK “ and wait to Get this process done.

Step 10 : Now again right click on Chunk and under Process menu select “ Build Dense Cloud “ . This will again open a pop-up window just click “ OK “ and wait to Get this process done.

Step 11 : Now again right click on Chunk and under Process menu select “ Build Mesh “ . This will again open a pop-up window just click “ OK “ and wait to Get this process done.

Step 12 : Now again right click on Chunk and under Process menu select “ Build Texture “ . This will again open a pop-up window just click “ OK “ and wait to Get this process done.

Step 13 : Now Just Click on option “ 3D Model “ available under the section “ Chunk “ . You are ready with your 3D model.

Step 14 : Now Use Shortcut “ CTRL+C “ to save this file. To Understand better visit our YouTube channel or Youtube Video link in resources.

- **Now analyze and collect all the information that you want from this model.**

Step 15 : Now Explore Agisoft Metashape and Extract all the data and information for which you made this Model.

###### Project By :
Prasannam Kumar Sah ( 20191066 )

###### Acknowledgment :
We thank Microsoft Corporation for Aerial informatics and Robotics Simulation (AirSim) & We thank Agisoft LLC for Agisoft Metashape .

## Resources
- Project Resource : https://drive.google.com/drive/folders/1ZZeIXIs_-9mvnybpSz-IB0HB1uIV6Git?usp=sharing
- YouTube Channel : https://www.youtube.com/channel/UCm7uHtNLbmq--wBzt7Yf23w
- Process of Photogrammetry (Video Link) : https://youtu.be/HL2elmYYLQ0
