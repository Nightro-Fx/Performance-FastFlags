### ⚠️   DISCLAIMER
FastFlags should **never** be used for hacking. These flags are strictly meant for FPS boosting and ping stabilization. If frustration over skill-issue is pushing you to hacking, consider staying away from competive games where you get sh*t on by genuine player. Please do not ruin it for the Linux community for your selfish behaviour.
# Getting Started
First we need to locate your _ClientAppSettings.json_
- Make sure _Show Hidden File_ is toggled on (CTRL + H)
- Your ClientAppSettings.json is located at `~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/`
- We run: `xdg-open ~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/ClientAppSettings.json`
- OR We can run `nano ~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/ClientAppSettings.json`

**We recommend checking out [Lucem](https://github.com/xTrayambak/lucem), which is blostraps but for Sober. These commands above are also for Ubuntu, So if you have any knowledge about your Distro use these commands as a reference.**

## Troubleshooting
Please be adviced, Even a small comma in the wrong place can make your Sober not open AT ALL. 
- Open Sober from terminal to see the specific cause of the failure to launch.
- If you have messed up your fastflag and have no idea what to do. Just delete your _ClientAppSettings.json_, Sober will will auto-generate a new one upon the next launch.
- If there is a specific change made by our configuration that your dissatisfied by, Try bulk deleting the fastflags then launching Sober. Continue deleteing chunks until you notice your problem is solved after deleting a specific section. With enough tries, You will be able to isolate the issues to a specifc fastflag.
