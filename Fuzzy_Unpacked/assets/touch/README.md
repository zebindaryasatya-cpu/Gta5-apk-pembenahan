# Touch control icons

256 px square, drawn in one style by `tools/touch_icons.py`: a white glyph outlined in black on a
black ring around a clear centre. They are original art, generated from the shapes in that script, so
edit it and rerun it rather than editing a PNG. The letters on the pad icons are Noto Sans, under the
SIL Open Font License. `TouchOverlay.ICONS` maps them to `AndroidTouchIcon`.

Packaging copies `Fuzzy-3rdparty/touch/*.png` over these when that checkout is there: art in the same
style that cannot enter this repository (`tools/touch_icons.py --es2`).
