<h1 align="center">
  <img src="https://github.com/Nightro-Fx/Performance-FastFlags/blob/main/img/Sober.png" width="40"/> 
  Performance Sober Fast Flags
</h1>





#### ⚠️ DISCLAIMER  
FastFlags should **never** be used for hacking. These flags are strictly meant for FPS boosting and ping stabilization. If frustration over skill issues is pushing you towards hacking, consider staying away from competitive games where you might struggle against genuine players. Please do not ruin it for the Linux community through selfish behavior.


# Getting Started
First we need to locate your _ClientAppSettings.json_
- Make sure _Show Hidden File_ is toggled on (CTRL + H)
- Your ClientAppSettings.json is located at `~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/`
- We run: `xdg-open ~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/ClientAppSettings.json`
- OR We can run `nano ~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/ClientAppSettings.json`

###### We recommend checking out [Lucem](https://github.com/xTrayambak/lucem), which is blostraps but for Sober. These commands above are also for Ubuntu, So if you have any knowledge about your Distro use these commands as a reference.

# Configurations
###### FPS Limit
```json
{"DFIntTaskSchedulerTargetFps": 60}
```
###### Set Monitor Hertz
```json
{"FIntTargetRefreshRate": 60}
```
###### Enable/Disable Bubble Chat
```json
{ "FFlagEnableBubbleChatFromChatService": "False" }
```

## Troubleshooting
Please be adviced, Even a small comma in the wrong place can make your Sober not open AT ALL. 
- Open Sober from terminal to see the specific cause of the failure to launch.
- If you have messed up your fastflag and have no idea what to do. Just delete your _ClientAppSettings.json_, Sober will will auto-generate a new one upon the next launch.
- If there is a specific change made by our configuration that your dissatisfied by, Try bulk deleting the fastflags then launching Sober. Continue deleteing chunks until you notice your problem is solved after deleting a specific section. With enough tries, You will be able to isolate the issues to a specifc fastflag.

## NOTICE
Any physics related fastflags will not be used within this page, as we do not want anyone using our fastflags to be banned.
- This is a page for simply increase in performance, although updates wont be frequent once this page is completed we will still make sure to add more fastflags as they are discovered.
