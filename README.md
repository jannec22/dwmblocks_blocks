## scripts for dwmblocks (based on [LukeSmithxyz's implementation](https://github.com/LukeSmithxyz/voidrice/tree/master/.local/bin/statusbar))

You can find here some usefull scripts for displaying things in your [dwmblocks](https://github.com/LukeSmithxyz/dwmblocks) statusbar.

### Layout
the last block indicates the current layout of the status bar.
you can define more layouts by putting a new layout icon in the ~/.config/barlayouts_icons, a list of refresh signals of the blocks you want in your layout in ~/.config/barsignals and a list of layout descriptions in "~/.config/bar_layouts_descriptions".

these three files must be changed together so they describe the layouts correctly.
each line is the index of the layout

eg:

~/.config/barlayouts_icons:
```
layout1
layout2
```

~/.config/barsignals:
```
8 10 18 14 6 16 4
11 6 12 5 17
```

~/.config/bar_layouts_descriptions
```
"packages updates" volume cpu "ram usage" "disk usage" "network traffic" "wifi / eth" clock battery
music news weather "network used in month" clock battery
```
