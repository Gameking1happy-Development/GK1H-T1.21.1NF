# GK1H-T1.21.1NF 1.1.2 - C2ME Addition  
## How to make a new server  
1. Mattering on what you are using to create the server:  
   1. If using a server hosting service, use one that allows file management, including the mod folder. **DO NOT USE ATERNOS!!!** Choose Minecraft version 1.21.1, NeoForge version 21.1.208. If the config folder and server.properties file were created, delete them.   
   2. If using ATLauncher, search for the pack, choose create server, select 1.1.2. Remove the config and configureddefaults folders, and the server.properties file.  
   3. If manually making a server, download a 1.21.1 NeoForge 21.1.208 server [here.](https://maven.neoforged.net/releases/net/neoforged/neoforge/21.1.208/neoforge-21.1.208-installer.jar)  
2. Copy everything in this folder to the server folder.  
3. Copy the mods folder from a client instance of the modpack, version 1.1.2. **MAKE SURE THAT THERE IS NOT A .connector FOLDER INSIDE IT!!! REMOVE IT IF THERE IS!!!**  
4. Delete all the mods not in the [list given.](mods.md) Then make sure all the mods on the list are there.  
5. Change eula from false to true in the [EULA.](eula.txt) By changing the setting to TRUE you are indicating your agreement to Minecraft's EULA (https://aka.ms/MinecraftEULA).  
6. You now have a server on version 1.1.2 of the modpack.  
## How to update an existing server  
1. Copy the new config folder into the server folder, and choose to replace all files. This will only replace the few files included in the config folder, not the other configs.  
2. Delete the existing configureddefaults folder, and copy the new configureddefaults folder into the server folder.  
3. Since this is the first version with a server pack folder and instructions, replace the existing server.properties and server.png. Usually you will not be told to modify the existing server.properties, and if you are, you will be told to replace certain lines in the file. You also will usually not be told to replace the server.png, and if so, it is optional, though recommended if not using your own image.  
4. Copy both README.md, which you are currently reading, and mod.md, into the server folder.  
5. Delete the mods folder.  
6. Copy the mods folder from a client instance of the modpack, version 1.1.2. **MAKE SURE THAT THERE IS NOT A .connector FOLDER INSIDE IT!!! REMOVE IT IF THERE IS!!!**  
7. Delete all the mods not in the [list given.](mods.md) Then make sure all the mods on the list are there.  
8. Your server is now updated to version 1.1.2 of the modpack.