# 3D Radar
This modification draws the circle of radar range on the 3D world.

Player Mode: circle of yours and your allies are visible  
Observer Mode: All players' radar ranges are available

The circle becomes visible when the Alt-key is pressed or the radar consumable is in use.  
It also starts to blink when the radar is about to end. (less than 7s~. blinks every second.)  
The reload, and active duration of the radar take all the upgrades and skills into account and is always precise.

The mod is officially checked and approved by WG, thus is safe to use.

# Overview
![image](https://github.com/AndrewTaro/ThreeDimentionalRadarPublic/assets/36262823/7ee6fb5e-e7a6-4d30-9cba-6b954ecfde7c)
![image](https://github.com/AndrewTaro/ThreeDimentionalRadarPublic/assets/36262823/90fefaee-386e-489d-bc93-7dab1303615f)

# Install
1. Download a zip.
2. Unzip the archive and you should get `gui`, `PnFMods` folders and `PnFModsLoader.py`.
3. Move them to `(wows)/bin/(latest_number)/res_mods/`. So the path will look like `res_mods/PnFModsLoader.py`, etc.
4. Done!

# Config
[TTaro Mod Config](../../../TTaroModConfig) supports this mod.  You can adjust the opacity of radar circle, depending on the radar state and has enemy within.

![image](https://github.com/AndrewTaro/ThreeDimentionalRadioPublic/assets/36262823/96d41ff9-027a-4665-8051-5e4bf00657a5)

### Circle Opacity
- The opacity of the circle when there is No visible enemy within the range.
### Circle Opacity (With Enemy in Range)
- The opacity of a circle when there is a visible enemy within the range.
### "Enemy in Range" Distance Offset
- The distance offset for detecting visible enemies within the range. It affects the **Circle Opacity (With Enemy in Range)**.
