# amixer-volume-script-for-WM
Amixer volume scripts for window manager.
Explanation :
- volmu = volume mute/unmute (amixer -q sset Master toggle)
- volup = volume up (amixer -q sset Master 5%+)
- voldown = volume down (amixer -q sset Master 5%-)

PS: you can make it into executable with command "chmod +x <script>" and bind it with your desired shortcut tools (sxhkd, xbindkeys, etc). You also can place it into your local path (/home/$USER/bin , /home/$USER/.local/bin).
