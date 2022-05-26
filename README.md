# Leon's scripts

## shell scripts

### **blurlock.sh**
+ fuctions \
pauses web browser media, mpv, mpc(ncmpcpp) 
and takes a screenshot of your current desktop, blur it, and use it as a background to lock your pc.

+ dependences \
`playerctl imagemagick i3lock`
note that (maybe) playerctl is only available on arch-based distros.

### **alacritty-pywal.sh**
+ funcs \
    export pywal color scheme to alacritty.yaml
+ setup \
    add `source /path/to/alacritty-pywal.sh` to ~/.config/wal/postrun 
    check [pywal on github](https://github.com/dylanaraps/pywal) for more info 

### **copy2clipboard**
+ func \
    copy file to clipboard based on its file type, so you can paste it later use default key binding such as Ctrl-V. Note that this script only works on a single file, not directory.

+ dependency \
    `xclip`
+ You can rename it to `copy` if nothing conflicts.

### **maimsel, maimall**
+ func
    - maimsel: select rectangle area, take a screenshot, save it, and copy it to clipboard.
    - maimall: similar to maimsel, take a fullscreen shot
+ dependency \
    `maim`
+ note \
    You can check `maim --help` for more mode. 
    Folder which screenshots are saved to is set in script.


## python scripts


## and more
