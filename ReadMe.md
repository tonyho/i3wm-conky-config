i3wm with conky status bar
===

i3wm and conky setting/configurations files.
Based on [ This ](https://github.com/levinit/i3wm-config "i3wm-config") and I did some modification to make it more usable.


----------

#  Setup #
- Install the necessary packagess:
  - conky
  - dmenu
  - feh
  - terminator
  - xcompmgr
  - scrot and ksnapshot
  - alsa-utils
  - networkmanager、nm-connection-editor nm-applet

- Clone the repo into ~/.config/i3

    `git clone https://github.com/tonyho/i3wm-conky-config.git ~/.config/i3`
    `cd ~/.config/i3`

- Install the font i3status-conky/fontawesome-webfont.ttf

- Give the executable permission for files

    `chmod +x wallpaper.sh /home/$USER/.config/i3/i3status-conky/i3status.sh`

- Setup the wallpaper and lock picture

    `cp wallpaper -r ~/Pictures`
    `cp wallpaper/lock/lock.jpg ~/Pictures/`

----------
# Keybindings
The basic key bindings is following:
![](./Pics/Whole_i3w_mini_descp.png)

# Tips
- TeamViewer: Move it to a worksapce(Mod + Shift + N) and make it fullscreen(Mod + f)
- ScreenShot: Use the ksnapshot launched by DMemo(Mod + d)
- Picture Edit: Use the shutter or GIMP
- Lock or quit: Mod + Shift + q, then press the corresponding key
- File Explorer: Mod + e, or launch the `nautilus --no-desktop .` in terminal
