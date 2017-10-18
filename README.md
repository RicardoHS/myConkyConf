# My Conky Configuration Instructions
Conky configuration for **Gnome 3.22.3** on debian 9

## Installation (-v 1.10.6)
1. Install conky https://github.com/brndnmtthws/conky
2. Install fonts (below)
3. Copy ```conky.conf``` in ```~/.config/conky/conky.conf```
4. Add the following text to a new file in ```~/.config/autostart/conky.desktop```
```
[Desktop Entry]
Type=Application
Exec=sh -c "sleep 10; conky;"
Name=Conky
Comment=Autostart conky at login
``` 
5. Enjoy and search for bugs.

## Fonts
https://github.com/helmuthdu/conky_colors/tree/master/fonts/conkycolors
Install in ```/usr/share/fonts``` and run ```fc-cache```

## Bugs
* Network doesnt work

```Search on your conky.conf for eth0 and replace for your network interface```
* Power doesnt work propertly

```Currently fixing```
