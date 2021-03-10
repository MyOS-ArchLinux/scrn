# scrn

This script lets you choose the kind of screenshot to take
including copying the image or even highlighting an area to copy.

### Requirements

- `dmenu` or `rofi` - user input
- `xclip` - used to access to clipboard
- `xdotool` - get active window id
- `ps` - get active window name
- `maim` - utility that takes screenshots of your desktop
- `adb` - used to take screenshot from your phones

## Installation

```
git clone https://github.com/MyOS-ArchLinux/scrn
cd scrn/
sudo install -m755 scrn /usr/local/bin/scrn
```
[set a keyboard shortcuts](https://wiki.archlinux.org/index.php/Keyboard_shortcuts)
