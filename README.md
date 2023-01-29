# TP_Framework

*Reworked the "Third Person Template" of UE5.1 - A different and reasonable approach to making use of the Unreal Engine 5 plugin feature.*

Unreal Engine 5.1 [Third Person Template](https://docs.unrealengine.com/5.1/en-US/third-person-template-in-unreal-engine/)

## About:

The "UE5.1 Third Person Template" content has been split into three different plugin folders to be easier available and moved between UE5 projects for quick prototyping.

## Installation

### Project Installation
1. Download the repository as a .7z or clone it for the most up-to-date version
2. Extract the .7z /.zip file
3. Copy the files to wherever you keep Your Unreal Engine projects
4. Open Unreal Engine 5.1 and open the project
5. Done

Now you can use this Third Person Framework as an up-to-date UE5.1 framework

### Plugins:
All of the existing Third Person Template contents have been moved into three different plugin folders.

If any of these plugins are not present, you will be prompted to disable them at launch. You may need to recompile shaders if you choose to do this.

You may be prompted to recompile some plugins, this is required for the editor to start. This only needs to be done once.

- Mannequin
  - Includes the UE4 and UE5 Mannequins.

- TP_Framework
  - Includes the BP_ThirdPersonCharacter & BP_ThirdPersonGameMode
  - Includes the Enhanced Input System & Input Actions

- TP_LevelTemplate
  - Includes the Third Person Level, all the Meshes, Textures and Materials

## Updating existing projects
If you have a project that already uses the Third Person Template then `drag&drop` the 3 plugins into your existing `D:\UnrealEngineProjects\ProjectName\Plugins` folder.

Before the content of the UE5.1 Third Person Template folders can be deleted (if the content has been used in any other BP, like the BP_ThirdPersonCharacter), everything has to be `redirected` to the TP_Framework & Mannequin plugin folder first. This can be seen through the `Reference Viewer` if everything has been set up correctly.

## Player
### Player controls

- Mouse Movement - Look Around
- WASD & Arrows - Movement
- Space Bar - Jump

## Help

If you're unsure how to use the Framework or Plugins, please feel free to contact me here or on my socials.
