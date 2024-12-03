<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1 align="center">
        <img src="https://github.com/Nightro-Fx/Performance-FastFlags/blob/main/img/Sober.png" width="40" alt="Logo"/> 
        Performance Sober Fast Flags
    </h1>
  
  <p align="center">
  <a href="https://discord.gg/kNHaaFsGZ2">
    <img src="https://github.com/Nightro-Fx/Performance-FastFlags/blob/main/img/Discord_Join.png" alt="Join Now" width="150">
  </a>
</p>
<p align="center">
  <a href="https://www.youtube.com/@Nightro-Fx">
    <img src="https://github.com/Nightro-Fx/Performance-FastFlags/blob/main/img/Subscribe_Hover.png" alt="Sub Now" width="130">
  </a>
</p>
</body>
</html>





#### ⚠️ DISCLAIMER  
FastFlags should **never** be used for hacking. These flags are strictly meant for FPS boosting and ping stabilization. If frustration over skill issues is pushing you to hacking, consider staying away from competitive games where you get outplayed by genuine players. Please do not ruin it for the Linux community through your selfish behavior.


# Getting Started
First we need to locate your _ClientAppSettings.json_
- Make sure _Show Hidden File_ is toggled on (CTRL + H)
- Your ClientAppSettings.json is located at `~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/`
- We run: `xdg-open ~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/ClientAppSettings.json`
- OR We can run `nano ~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/ClientAppSettings.json`
- Now just delete everything inside and paste everything from [ClientAppSettings.json](https://github.com/Nightro-Fx/Performance-FastFlags/edit/main/ClientAppSettings.json) in here to your _ClientAppSettings.json_.

###### Checking out [Lucem](https://github.com/xTrayambak/lucem), which is blostraps but for Sober. These commands above are also for Ubuntu, So if you have any knowledge about your Distro use these commands as a reference.

# User's Manual

###### Setting OpenGL as rendering API
```json
"use_opengl": true
```

###### Setting FPS Limit
```json
"DFIntTaskSchedulerTargetFps": "60"
```
###### Setting Monitor Hertz
```json
"FIntTargetRefreshRate": "60"
```
###### Enable/Disable Bubble Chat
```json
"FFlagEnableBubbleChatFromChatService": "False" 
```
###### Adjust these values based on your internet speed (Lower it if you can't join a game
###### 980 for slow internet speed / 1480 for fast internet speed
```json
"DFIntRakNetMtuValue1InBytes": "1480",
"DFIntRakNetMtuValue2InBytes": "1480",
"DFIntRakNetMtuValue3InBytes": "1480",
"DFIntConnectionMTUSize": "1480"
```
###### Fix for corrupted leaderboards:
```json
 "DFFlagOptimizeIsA": "False"
```

###### Low Render Distance
```json
"DFIntDebugRestrictGCDistance": "1"
```
###### Disable ALL Lights
```json
"DFFlagDebugPauseVoxelizer": "True"
```
###### Version 2 ESC menu
```json
"FIntNewInGameMenuPercentRollout3": "100",
"FFlagEnableInGameMenuControls": "False",
 "FFlagDisableNewIGMinDUA": "True",
"FFlagEnableInGameMenuChromeABTest4": "False"
```
###### Custom Font Size
```json
"FIntFontSizePadding": "1"
```
###### Enable GPU Curling
```json
"FFlagFastGPULightCulling3": "True"
```

## Troubleshooting
Please be adviced, Even a small comma in the wrong place can make your Sober not open AT ALL. 
- Open Sober from terminal to see the specific cause of the failure to launch.
- If you have messed up your fastflag and have no idea what to do. Just delete your _ClientAppSettings.json_, Sober will will auto-generate a new one upon the next launch.
- If there is a specific change made by our configuration that your dissatisfied by, Try bulk deleting the fastflags then launching Sober. Continue deleteing chunks until you notice your problem is solved after deleting a specific section. With enough tries, You will be able to isolate the issues to a specifc fastflag.

> [!WARNING] 
>This page will not use physics-related fastflags to avoid any risk of users being banned. It is dedicated to performance improvements. Although updates may become less frequent once the page is finished, we will continue to add new fastflags as they are discovered.

