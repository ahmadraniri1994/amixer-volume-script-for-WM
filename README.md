# amixer-volume-script-for-WM
Amixer volume scripts for window manager.
Explanation :
- volmu = volume mute/unmute (amixer -q sset Master toggle)
- volup = volume up (amixer -q sset Master 5%+)
- voldown = volume down (amixer -q sset Master 5%-)

multimedia key lists:
- XF86AudioRaiseVolume = for raising volume, you can bind it with "volup" script.
- XF86AudioLowerVolume = for lowering volume, you can bind it with "voldown" script.
- XF86AudioMute = for toggling mute/unmute, you can bind it with "volmu" script.

PS: you can make it into executable with command "chmod +x <script>" and bind it with your desired shortcut tools (sxhkd, xbindkeys, etc). You also can place it into your local path (/home/$USER/bin , /home/$USER/.local/bin).
