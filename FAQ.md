VRCAVE Support Quick responses:

Q:  I'm getting a timeout error in the headset as it seems unable to connect.

1. Double check that the headsets are connected to the same router as the server PC, and make them forget any other networks they may have connected to in the past. 

2. Make sure there are no firewalls that could be blocking vrcavelibrary from accessing the network. If you only have windows defender firewall, you can make an exception for vrcavelibrary.exe by typing "allow an app through windows defender firewall" into windows search bar, if vrcavelibrary.exe is not in the list, you can add it by selecting the exe file in vrcavelite/windowsnoeditor 

Q: I am trying to sideload vrcave onto the headsets, but all I get it waiting for headset to connect.

Have you enabled developer mode for your headsets, if no, you can follow this guide to prepare them for sideloading: https://vrcave.github.io/operationGuide/vrcave_Lite_Sideloading.html

When you plug the headset into the computer and run the Install_VRcaveLibrary-arm64.bat file, you should receive a popup in the headset to "Allow USB debugging" select "Always allow from this computer" Close the install cmd popup and double click the Install_VRcaveLibrary-arm64.bat file again. You shoud eventually see a percentage begin to increase from 0 to 100 meaning it is installing. 

If you get "waiting for headset" or "press any key to continue" you will need to close the window, repeat the above checks, and try again.

Q: Firewall permissions


