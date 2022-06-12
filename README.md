# Leon's scripts

add a folder and its sub-folder to path:
<pre>
export PATH="$PATH:${$(find /path/to/folder -type d -printf %p:)%%:}"
</pre>
## shell scripts

### **blurlock**
+ fuctions

  pauses web browser media, mpv, mpc(ncmpcpp),takes a screenshot of your current desktop, blur it, and use it as a background to lock your pc.

+ dependences

  `playerctl imagemagick i3lock`
+ note that (maybe) playerctl is only available on arch-based distros.

### **alacritty-pywal.sh**
+ funcs

    export pywal color scheme to alacritty.yaml
+ setup

    add `source /path/to/alacritty-pywal.sh` to ~/.config/wal/postrun
    check [pywal on github](https://github.com/dylanaraps/pywal) for more info

### **copy2clipboard**
+ func

    copy file to clipboard based on its file type, so you can paste it later use default key binding such as Ctrl-V. Note that this script only works on a single file, not directory.

+ dependency

    `xclip`
+ You can rename it to `copy` if nothing conflicts.


### clip

  this one is quiet simple, but is useful in shell pipe, eg. `pwd | clip` will copy CWD into clipboard.

`xclip -selction clipboard`

### empty_trash
`rm -rf $HOME/.local/share/Trash`

### **maimsel, maimall**
+ func
    - maimsel: select rectangle area, take a screenshot, save it, and copy it to clipboard.
    - maimall: similar to maimsel, take a fullscreen shot
+ dependency: maim
+ You can check `maim --help` for more mode. Folder which screenshots are saved to is set in script.

### **setbg0, setbg1**
+ func
    - set wallpaper for monitor 0 and 1
+ dependency: feh
+ You can copy and change scripts to support more monitors.

## [Vim tricks](https://github.com/blinky39/vimtricks)

## [linux cleaning](Clean.md)

## python scripts
