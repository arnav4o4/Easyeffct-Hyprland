## How to run Easyeffect on background in Hyprland ?

[Easyeffect](https://github.com/wwmm/easyeffects) is an audio equalizer for Linux that use [Pipewire](https://github.com/PipeWire) instead of [Legacy Pulseaudio](https://github.com/pulseaudio) . 


 - Easyeffect app have the option to run on background and on system startup. 
 

[![dqaUSEJ.md.png](https://iili.io/dqaUSEJ.md.png)](https://freeimage.host/i/dqaUSEJ)



 - **But in hyprland  this service doen't work effectiverly**




So to run it on  **Hyprland** add the following line in `.config/hypr/hyprland.conf` file **:**


`exec = easyeffects --gapplication-service`



And then open **Easyeffect app** and close it again, You'll see , the app is running in background 😁 

**[ You can check it from your System Monitor ]**


## **Note:** 

### This only works on **<mark>Non-Flatpak version</mark>** and if you are using flatpack version, install the non flatpak version as Hyprland cant allow flatpak apps to run automatically on system startup.



