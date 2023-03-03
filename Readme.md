# unicorne Keymap

This repo holds the keymap for the unicorne keyboard, a semi-wireless corne keyboard with a single MCU.


## Render Keymap

To render the keymap, the [`keymap-drawer` library](https://github.com/caksoylar/keymap-drawer) is used. Run the
following commands to update the rendered keymap:

```
keymap parse -c 12 -z unicorne.keymap > unicorne_keymap.yaml
keymap draw -o '{split: true, rows: 3, columns: 6, thumbs: 3}' unicorne_keymap.yaml >unicorne_keymap.svg
```

This produces the following SVG file:

![](https://github.com/fgebhart/zmk-config/raw/main/unicorne_keymap.svg)

