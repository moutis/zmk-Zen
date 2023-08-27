![Corne-ish Zen Logo](zenlogo.png)

Tinkering with putting **Hands Down** (*Vibranium*, a.k.a Neu-vv) on a Cornish-Zen using just the github actions.

```
     ╭─────────────────────╮ ╭──────────────────────╮
ESC  │  X   W   M   G  "[  │ │  #$  .:  ']   J   B  │ BSP
TAB  │  S   C   N   T   K  | |  ,;   A   E   I   H  │ Tg(Num)
LSFT │  V   F   L   D   /* │ │  -+   U   O   Y   P  │ RSFT
     ╰──────╮  App BSP  R  │ │  SPC RET TAB  ╭──────╯
            ╰──────────────╯ ╰───────────────╯
```
*Vibranium* is great with all the other smart behaviors, and is not advized without some (esp `H` digraphs…combos to send TH,CH,WH,SH,GH,PH bigrams). Currently I have most of the "essential" combos, and a ZMK take on *Adaptive Keys* (using macros and sticky layers) and *Linger Keys* (using macros and hold-tap behaviors). They behave a bit differently than in QMK, but are quite usable. Eventually I hope to deploy a properly coded solution to these features so they have similar responsiveness as in QMK.

Currently building only for a Mac (hard coded for gui instead of ctrl, some mac specific keycodes). My "Semantic Keys" feature for platform independence isn't yet fully fleshed out on my QMK implementations, and will reguire more invasive work for ZMK, so this too is for later.
