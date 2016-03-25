***	Setup Instructions!	***

1. Preliminary Setup

	- Create a folder for the mod in your /steamapps/common/Quake4 directory (ex /Quake 4/Prop Hunt/)
	
	- Copy game000.pk4 from /Quake4/q4mp into your mod folder


2. Copying modded files

	- Perform a clean build of mpgame in Visual Studio (Optional)
	
	- Copy the def folder from /Modified Defs/ into your mod folder

	- Navigate into /Release/ from the quake4 source directory
		
	- Copy mpgame.dll into the mod folder

	- Rename mpgame.dll to gamex86.dll

	- Copy gamex86.dll into game000.pk4


3. Launching a server

	- Open Quake4

	- Load the Mod

	- Create a server; In advanced server settings, make sure to disable the pure server option