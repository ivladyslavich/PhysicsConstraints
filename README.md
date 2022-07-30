# BossFighters

## Build
Build project using make-build.bat 
### Parameters for build
There is several editable parameters for make-build.bat
- PROJECT_NAME - name of current project (as in \*.uproject file). Default is "BossFighters"
- MAKE_BUILDS = (0\1) - do we need to make game builds? Default is "0"
- VERSION - version of .bat script. Don't change.

## Project Structure

## Content

This project's content is separeted into two layers of assets:
 - BFCore Content 
 - Boss Fighters Content
  
*BF Core* contains core blueprint logic and core assets.
*Boss Fighters* contains core extensions and game-related assets.

## Source

Source code splitted into various modules and also contains *BFCore* modules and game-specific modules.

### BFCore Modules
- BFCoreBeacons - blueprint-exposed online beacons actors.
- BFCoreNodes - helper editor nodes. 
- BFCoreSkins - modular skins core
  - BFCoreSkinsEditor - BFCoreSkins editor features
- BFCoreTags - module that contains native Gameplay Tags. Used by other modules

### Boss Fighters Modules
- BossFighters - main game module
- BossFightersEditor - game editor features

### Tools
- Tool_ModuleGenerator - simple python script that automates new modules creation