### Binaries to run minecraft on linux arm 64 bit
Works from 1.13 up to the latest version (1.21.1)
It works with PolyMC, may work with other launchers, but I am not sure if that is the case.

## How to install.
0.  Check if PolyMC is available to install from your package manager.
    If it is not present, download PolyMC repo and compile it using provided build instructions by PolyMC.
    After you have started your PolyMC instance:
1.  Create an instance with your desired mc version (from 1.13 and up)
2.  Right click on the instance icon and select 'Instance folder'
3.  Create 'patches' directory and paste the 'org.lwjgl3.json' into that directory from the repository.
4.  Done! Your instance is patched with linux aarch64 lwjgl 3 libraries, now the game should launch and work with mods and/or shaders, assuming you have appropriate java version installed to run the version of the game you chose. GLHF!
