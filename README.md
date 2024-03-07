# Blobulator-ASW

These header files allow for the use of the Blobulator in the Alien Swarm SDK. 

# How to:

Setup Paintblob Example Code:

	- Pull this repo, and drop the files on top of your current SDK. Doing this should add the "blobulator" folder your SDK's copy of "src/common/", 
		and the "src/game/client/emulsion" + "src/game/server/emulsion" + "src/game/shared/emulsion" (containing paintblob streams) folders to your "src/game" folders
	
	- Once you have added these files into your SDK, add the following files to your project:
		-Client
			-client/emulsion/c_paintblob_stream.cpp / .h
			-shared/emulsion/paintblob_manager.cpp / .h
		
		-Server
			-server/emulsion/paintblob_stream.cpp / .h
			-shared/emulsion/paintblob_manager.cpp / .h
	
	- Finally, you should be able to use the paintblob managers to spawn blobs using something like a paintgun weapon. One will be added soon for Demo purposes.


Setup custom implmentation of Blobulator:

	- Pull this repo, and drop the files on top of your current SDK. Doing this should add the "blobulator" folder your SDK's copy of "src/common/"
	
	
	
	