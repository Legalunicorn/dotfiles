Previews, some notes of the cofig files, and lastly settings changes using GUI


# Previews 
![empty](./images/preview_0.png)
![max](./images/preview_max.png)
![split](./images/preview_split_2.png)


# .config
## System Information
OS: Xubuntu<br>
DE: xfce 4.16<br>
WM: xfwm 4<br>
WM theme: [2bxfwm lucy](https://github.com/addy-dclxvi/xfwm4-theme-collections)<br>
Style: [Gruxbox-Dark-B-LB](https://www.gnome-look.org/p/1681313/)<br>
Spotify player: [genmon plugin](https://github.com/xtonousou/xfce4-genmon-scripts)<br>
Fancy bash prompt: [synth-shell](https://github.com/andresgongora/synth-shell)

---

## Take note
- my genmon id in `gtk.css` will be different from yours. To check its id, open `panel preferences > items` and hover over the spotify genmon
- the `ascii.txt` inside `.config/neofetch` uses terminal color 6 which is purple for me. Change it as you like 
- My wallpapers are 1920 x1080 and mostly fromm [wallhaven](https://wallhaven.cc)

# XFCE Settings (GUI)

## Panels 
Set your own panel bg colors (dont set panel bacnground color in  `gtk.css` unless you want all panels to have the same bg color)

my colors are <br>
#150729 ,opacity: 93<br>
#021826, opacity: 93

![panel](./images/panel_4.png)

length and sizes of panel
![panel](./images/panel_3.png)

panel 1 items
![panel](./images/panel_1.png)

panel 2 items
![panel](./images/panel_2.png)

---
## Terminal apperance preferences 
![ter](./images/terminal_appearence.png)

--- 
## Workspaces
Unicode character: ●

Workspace Margins to not overlap panel because my panel is not touching the top

- Top margin: 58
- Other sides: 5

---



## Other settings changes

**1. Reduced window decoration opacity <br>**
- Window Managaer Tweaks > Composition > Opacity of window decoration
- Lower it to your liking. Mine is at ~50%.

<br><br>
**2. Clock Format<br>**
- Right click on the clock > properties. Format: Custom Format <br>

<br><br>
**3. Format including the spaces at the ends: (copy the whole line below) <br>**
- &nbsp; %d %b • %H:%M &nbsp;

<br><br>
**4. Different wallpaper for each workspace**
- right click on the desktop > Desktop settings. Uncheck  'apply to all workspaces'.
- Go to each workspace and set desired wallpaper for each.
