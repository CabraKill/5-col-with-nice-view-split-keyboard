# 5-Column Split Keyboard with Nice View

![diagram](./visualizer.svg)

## Diagram generator

![keymap-drawer-web](https://github.com/caksoylar/keymap-drawer-web)

For local generation use the bellow but the dark mode is handled on the website with the ZMK link parse.

```bash
keymap parse -c 10 -z ./config/corne.keymap >sweep_keymap.yaml
keymap draw sweep_keymap.yaml > visualizer.svg
```

## doc

[home row mods](https://www.youtube.com/watch?v=EQCaQBlv1UM)
[key reader](https://w3c.github.io/uievents/tools/key-event-viewer.html)
