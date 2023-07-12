---
layout: default
title: Vive Focus 3 Standalone Setup
parent: 
nav_order: 8
has_children: true
---

# vrCAVE Lite
We offer a *"Lite"* version of our software which has been specially redesigned for an optimal experience on the Vive Focus 3 headset.


## Hardware Requirements
1. ##### Vive Focus 3 Headset with Controllers
    - Recommended 5 sets (plus 1 backup)
	- one USB-A to USB-C sync cable
2. ##### Windows Computer
    - **OS:** Windows 10
    - **CPU:** anything above a [PassMark Score of 7,700](https://www.cpubenchmark.net/high_end_cpus.html)
    - **Graphics:**  anything above a [PassMark Score of 8,800](https://www.videocardbenchmark.net/high_end_gpus.html)
	- **RAM** 8Gb minumum, 16GB or more recommended 
    - **Peripheries:** Ethernet port, ports for mouse, keyboard, and monitor
3. ##### Router
    - Netgear Nighthawk X6 R8000 Tri Band Gigabit Wireless Router (or similar)
    - Recommended 2 bands of 5GHz (in case of future side by side rooms setup)
	- Connection to the internet is recommended


## Room Requirements
vrCAVE Lite requires a play space of 4.5M x 5.5M (15'x18') . We recommend having at least an additional 50cm (20") of buffer beyond this to reduce the danger of bumping into walls.

Make sure your headset’s boundary is set up so you can walk freely around the entire 15' x 18' (4.5m x 5.5m) space. 

### Achieving Optimal Tracking
A brightly lit room is important for the Inside-Out tracking. Inside-Out also requires some room features to help with its visual insight tracking, posters or banners should be enough for the walls, the floor may be a bit more complicated. An example of a good tracking floor is a carpet with a non-symetrical design or carpet tiles of different colors. If that isn't possible, you can also mark the floor with some painters tape or duct tape. as long as the markings are non-symetrical and visible when viewed in the headest passthough mode shouldn't have any troubles tracking.

(These suggestions are subject to change as Inside-Out Tracking continues to develop.)

## Location Based Entertainment (LBE) mode

We highly recommend contacting HTC to get a Location Based Entertainment (LBE) License. The license gives operators features that are designed for shared space multiplayer, mainly the ability to create a playspace map that will be shared with all the headsets, This will automatically have the headsets be calibrated with each other. 

HTC will send you documentation to get your headsets enrolled and how to create a map for your arena. When creating your Batch Config for headset groups, you have to set your tracking mode to **LBE Mode** This will allow you to assign a shared map for the headsets in the group, then we recommend turing off **Boundary related messages**. This will removed the warning when players venture outside the defined play area, normally this would be okay, but it also gives the player the option to redraw the playarea, and that will overwite the current map, we do not want this. 

![](media/vrcaveLite/LBESettings.png)
 
## Downloading the Lastest Version 

1. Go to the [Partner Success Portal](https://partnersuccess.vrcave.ca/) 

	![](media/CSP/CustomerSuccessPortalLogin.PNG)

2. Log in using the Login credentials provided by VRCave

3. Find the "Download Latest vrCAVE Version" Button

	![](media/CSP/CSP_DownloadButton.PNG)
	
4. Select the Download details that best describe your VR Setup

	![](media/CSP_DownloadDetails_Vive.png)


## Installing (Sideloading) the VRcaveLibrary app on to your Vive Focus 3
#### *PLEASE NOTE*
Your file path to the *vrcaveLite* software should to be free of any spaces. 
* **Bad:** *C:\Windows\Username with spaces\Desktop\Some folder with spaces\vrcaveLite*
* **Bad:** *C:\Windows\Username\OneDrive\Desktop\vrcaveLite*
* **Good:**  *C:\Windows\UsernameWithNoSpaces\Desktop\vrcaveLite*

Make sure your headset is connected to your Windows PC via USB.

- Download and extract the `vrCAVELite-<version>.zip` from the provided link. Navigate into the **vrcaveLite\Android_ASTC\** folder and double-click on **Install_VRcaveLibrary-arm64.bat**. 
 

	![](media/vrcaveLite/Sideload.png)

- It should take 2-3 minutes - if the install completes successfully, the window will close with no further feedback.

## Launching VRcaveLibrary on the Vive Focus 3

In VR, from the main menu bar at the bottom of the screen, click on the **Library** Button,  In the Library window, you should see VRCaveLite
	![](media/vrcaveLite/VRcaveLiteonHTC.png)

	

## Setting up the Server Computer

- On the Windows PC, Navigate to the `vrCAVELite-<version>` folder and then move the folder titled **vrcaveLite** to the desktop as well as "LaunchVRCaveLiteServer" shortcut.


- Double click the launch server shortcut. 

- If you get an error that says some .dll files cannot be found, you may need to update your [DirectX drivers](https://www.microsoft.com/en-us/download/details.aspx?id=35) 

## Router Setup

*The server computer communicates game data to the VR Headsets, this is done by setting up a local network with this router for the server computer and VR headsets to all be on. Having the headsets connnected to the internet will allow them to update their firmware and software which allows for improvments to tracking and other features.*

- Connection: Make sure your Nighthawk Netgear X6 R8000 router is plugged in and powered on. Use its provided ethernet cable to connect the server computer to LAN port 1 on the back of the router (do NOT plug it into the port titled “INTERNET“).

- Connect the router to the internet by plugging an ethernet cable from a modem into the port titled “INTERNET“

- Put the server computer in airplane mode so that it doesn’t have any WiFi internet connection anymore, and is only connected to the Nighthawk X6 router.


## Network Environment

- To connect the clients to the server, all the headsets and the server need to connect to the Nighthawk X6

- In the headsets, On the main menu bar at the bottom of the screen, click on the **Wifi Symbol** or click the settings app and then the **Wi-fi** button. From there, find Router network you set up, it should be named something like NETGEAR##-5G-2. Enter the password provided for the router or the one you set up if you decided to do that. 

	![](media/vrcaveLite/ViveWifiSettings.png)
	
- Do this for each of the Headsets and then restart the VRcaveLibrary app

- On the server computer, you should start to see players begin to connect on the top righthand corner of the UI, from there you can name the headsets and change the player color. 

- If the players do not show up, check to see if your server computer has any firewalls that might be blocking vrcavelibrary from accessing the network. For Windows Defender Firewall, you can allow vrcave through by searching "Allow an App through Windows Firewall" in a windows search bar and adding **vrcaveLibrary.exe** to the allowed apps. **vrcaveLibrary.exe** can be found in *vrcaveLite/WindowsNoEditor/* folder. Any other firewalls should just be disabled as they will usually try to block vrcave even after permissions are granted. 

## In Game Calibration

**If you have an LBE License with HTC, this step is not necessary.**

- To make sure that each player is where they are supposed to be in game, you will need to perform a calibration on each headset, you can start the calibration from the server by clicking on the gear next to the player name and then clicking the crosshairs that appear when the gear is clicked. 

	![](media/vrcaveLite/ServerPlayerOptions.png)
	
-  In the selected headset, you will see the calibration window pop up and a red ball attached to the left hand. 

	![](media/vrcaveLite/QuestCalibration.png)
	
- You will need to touch the controller to all 4 corners of the room like the diagram below, It helps to mark out the corners with numbers so the first corner can be quickly identified when calibration needs to be done. You must place the markers in the corners on the floor of your real world space as the calibration also sets the games floor height. You will need to keep the headset on, while also looking out from under the headset to see where you are going. 


	![](media/vrcaveLite/CalibrationPointswitharrow.png)
	
	
- When you are done, point the laser pointer on the right hand at the Confirm Calibration button, the play area should visibly shift into position, you can test the calibration by performing a "high five" with another player who is calibrated in the game, you will know the calibration worked if the controllers clack against each other when your hands are close to each other. If the hands connect in game but miss In real life (or using the professional VR Developers term: "Meat Space") then the calibration was not successful and one or both of the players needs to calibrate again. 


## Optional Features

- By clicking on the players name on the server, you can type out a new name for that headset, the sever will remember that name next time that headset connects. 


### Changing the number of given hints and default time limit

- Navigate to the vrcave library config folder by following this path: **vrcave\WindowsNoEditor\VRcaveLibrary\Saved\Config\WindowsNoEditor\Game.ini**

- open **Game.ini** with notepad and add these lines:

```
[/Game/Maps/DragonTower/DragonTower_GameState.DragonTower_GameState_C] 
defaultMaxGameTime=2100 
defaultMaxHints=2

[/Game/Maps/Manor/Manor_GameState.Manor_GameState_C]
defaultMaxGameTime=2100
defaultMaxHints=2

[/Game/Maps/SST/SST_GameState.SST_GameState_C]
defaultMaxGameTime=2100
defaultMaxHints=2

[/Game/Maps/TimeTravel/TimeTravel_GameState.TimeTravel_GameState_C]
defaultMaxGameTime=2700
defaultMaxHints=2

[/Game/Maps/underwater/USA_GameState.USA_GameState_C]
defaultMaxGameTime=2100
defaultMaxHints=2

[/Game/Maps/Pirate/Pirate_GameState.Pirate_GameState_C]
defaultMaxGameTime=2700
defaultMaxHints=2  

[/Game/Maps/LaserBlocks/LaserBlocks_GameState.LaserBlocks_GameState_C]
defaultMaxGameTime=600
defaultMaxHints=2  
```

- defaultMaxGameTime is measured in seconds, so 2100 seconds is 35 minutes.  
