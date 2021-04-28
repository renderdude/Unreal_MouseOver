# HHMI MouseOver virtual environment ported to UE4

This repository contains the code for an Unreal Engine project to replace the existing custom C++ version of MouseOver.

This is a minimal working example that contains an example scene and interface to the HHMI treadmill system and the Behavior Control System (BCS) for recording the experiments.

You will need to download the project and have a modern version of Boost laying around (I've tested against 1.75). You'll need to modify the plugin build file(s) to point to the location of your installed version of Boost.

You also need the FTDI USB controller to interface to the HHMI Treadmill system.

**Compatible with UE 4.26 and below**  
## [DOWNLOAD](https://github.com/renderdude/Unreal_MouseOver.git)

## Known issues:
In order to communicate with the BCS system, you need to install a third-party plugin from the Unreal Marketplace, TCP Socket Plugin.

## Credits:
Mark Bolstad

* From UE4 forums:
  * Epic Games support crew
  * UE4-SpaceMouse for initial ideas