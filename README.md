# CraftGate Asset Service

## Includes:
- cgAssetService
- [web application](https://cg.6qn.cc)

## Versions:
v0.2.3-b2
- Fix missing SE maps.

v0.2.3-b1
- Added no. 38xxx maps.
- Updated map name translations.

v0.2.2-b1
- Added archive toolset. usage:
   ```
   cgAssetService.exe -conv=<export_to_path>
   ```

v0.2.1-b1
- Added sound effect to anime object.
- Added mute button in anime view.
- Added obstacles info from PUK2 maps.

v0.2.0-alpha.3
- Added a detail button for the map view, which can show obstacles and warp positions.
- Added a minimap from PUK2.
- Updated map name translations.

v0.2.0-alpha.2
- Added a version check page.
- Optimized memory usage in the web application.
- Map ordered by number.
- Updated anime UI bounding calculation.

v0.2.0-alpha.1
- The initial version includes features for graph view, anime view, and map view.

## cgAssetService Installation Guide:
1. let `bin` folder of CrossGate client sibling to `cgAssetService.exe`, for examples:
   - copy `bin` folder to `cgAssetService.exe` place
   - copy `cgAssetService.exe` to CrossGate client folder which contains `bin` folder
2. make sure 8076 tcp port is not using
3. run `cgAssetService.exe`
4. open web application above and enjoy browsing

## Known Issues
1. Memory out of limit after browse many maps
2. Missing map name translation
3. NPC's default direction not correct
4. Some animation not present correctly (wrong palette reference)