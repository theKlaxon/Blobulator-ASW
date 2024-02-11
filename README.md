# Blobulator-ASW

These header files allow for the use of the Blobulator in the Alien Swarm SDK. 

# How to:

Setup NPC_Surface Demo:

	- Pull this repo, and drop the files on top of your current SDK. Doing this should add the "blobulator" folder your SDK's copy of "src/common/", 
		and the "src/game/client/ep3" + "src/game/server/ep3" (containing npc_surface) folders to your "src/game" folders
	
	- Once you have added these files into your SDK, you can add "src/game/client/c_npc_surface.cpp" to your client project, and "src/game/server/npc_surface.cpp" + "src/game/server/npc_surface.h" to your server project. 
	
	- Next, compile the project and you should be able to interact with npc_surface in any map compiled with the "npc_surface" entity. ( one is included in this repo's game files. )


Setup custom implmentation of Blobulator:

	- Pull this repo, and drop the files on top of your current SDK. Doing this should add the "blobulator" folder your SDK's copy of "src/common/"
	
	
	
	