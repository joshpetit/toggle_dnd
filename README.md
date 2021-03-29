# toggle_dnd
A shell script to toggle do not disturb on and off in the gnome desktop environment.

Note: After fiddling around, I noticed that you can just press `Super + V` and then `Space` to toggle Do Not Disturb.
This script will help make it a single hotkey though.

### Installation and Usage
```
$ git clone https://github.com/joshpetit/toggle_dnd.git
$ cd toggle_dnd
$ chmod +x toggle_dnd
$ ./toggle_dnd
```

### Keyboard Shortcut
Create a keyboard shortcut in settings panel
to quickly toggle the script.
```
Settings > Keyboard Shortcuts > Custom Shortcuts > +
```
Name: toggle_dnd

command: /absolute/path/to/toggle_dnd

shortcut: \[Keys\]

### Testing

To ensure this is working, you can test it by enabling DnD and running:

```
$ notify-send "Hello world"
```

## Alternatives

* [Do Not Disturb](https://extensions.gnome.org/extension/964/do-not-disturb-button/) Gnome extension ([home page](https://nls1729.github.io/donotdisturb_button.html))
* [NoNotifications](https://launchpad.net/~vlijm/+archive/ubuntu/nonotifs) apt package

## Very Important
Have a nice day :)
