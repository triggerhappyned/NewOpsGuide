[Support Home](Support_Forum.md)

# Players Not Connecting at all


## Troubleshooting tips

1. The most common occurance of this is version missmatch, the server computer and client are running different versions of the game. Deleting the vrcave folder on the backpack and replacing it with a copy of the server computer vrcave folder should resolve it.

2. Check the wifi network for both server and backpack. they both need to be on the same network.

3. Check the backpack is starting the game. the shell:startup folder needs to have a .bat file in it.

   - you can get into this by clicking the windows icon on the bottom left corner and typing "Run" and pressing enter, then entering `shell:startup` into the run program application that opens. 


	![](media/vrcave_client.png)
	
4. Check the server computer and backpack's Windows Defender Firewall app permissions, if the **vrcaveLibrary.exe** is not allowed to use your network, then it cannot host or join a game. 

	- In the windows search bar, type *"allow an app through windows firewall"* and select the option of the same title. Look for vrcavelibrary.exe in the list and make sure it has both public and private selected.
	
	- If it is not in the list, select *"allow another app"* and then navigate to the vrcave folder, open *windowsNoEditor* folder, and select **vrcavelibrary.exe**. Finally allow that newly added application to use public and private networks
	
	![](media/Libraryexe.png)

[Support Home](Support_Forum.md)