# ZMK Studio Audit — CorneKBH (CorneWireless)
**Date:** 2026-03-18 (final scan)
**Source:** zmk.studio live connection via Playwright

> **NOTE:** Several keys differ from `config/corne.keymap` on disk. This audit reflects what is actually loaded on the keyboard as reported by zmk.studio.

## Key Position Map
```
Row 0:  [0]  [1]  [2]  [3]  [4]  [5]     [6]  [7]  [8]  [9]  [10] [11]
Row 1:  [12] [13] [14] [15] [16] [17]    [18] [19] [20] [21] [22] [23]
Row 2:  [24] [25] [26] [27] [28] [29]    [30] [31] [32] [33] [34] [35]
Thumb:            [36] [37] [38]          [39] [40] [41]
```

---

## Layer 0: Base

| Pos | Label | Behavior | Key / Binding | Modifiers |
|-----|-------|----------|---------------|-----------|
| 0 | Esc | Key Press | Keyboard Escape | |
| 1 | Q | Key Press | Keyboard Q | |
| 2 | W | Key Press | Keyboard W | |
| 3 | E | Key Press | Keyboard E | |
| 4 | R | Key Press | Keyboard R | |
| 5 | T | Key Press | Keyboard T | |
| 6 | Y | Key Press | Keyboard Y | |
| 7 | U | Key Press | Keyboard U | |
| 8 | I | Key Press | Keyboard I | |
| 9 | O | Key Press | Keyboard O | |
| 10 | P | Key Press | Keyboard P | |
| 11 | BkSp | Key Press | Keyboard Delete | |
| 12 | Tab | Key Press | Keyboard Tab | |
| 13 | A | Key Press | Keyboard A | |
| 14 | S | Key Press | Keyboard S | |
| 15 | D | Key Press | Keyboard D | |
| 16 | F | Key Press | Keyboard F | |
| 17 | G | Key Press | Keyboard G | |
| 18 | H | Key Press | Keyboard H | |
| 19 | J | Key Press | Keyboard J | |
| 20 | K | Key Press | Keyboard K | |
| 21 | L | Key Press | Keyboard L | |
| 22 | ; | Key Press | Keyboard SemiColon and Colon | |
| 23 | Shft | Key Press | Keyboard RightShift | |
| 24 | Ctrl | Key Press | Keyboard LeftControl | |
| 25 | Z | Key Press | Keyboard Z | |
| 26 | X | Key Press | Keyboard X | |
| 27 | C | Key Press | Keyboard C | |
| 28 | V | Key Press | Keyboard V | |
| 29 | B | Key Press | Keyboard B | |
| 30 | N | Key Press | Keyboard N | |
| 31 | M | Key Press | Keyboard M | |
| 32 | , | Key Press | Keyboard Comma | |
| 33 | . | Key Press | Keyboard Period | |
| 34 | / | Key Press | Keyboard ForwardSlash | |
| 35 | Ret | Key Press | Keyboard Return Enter | |
| 36 | (blank) | Momentary Layer | Layer: NumPad | |
| 37 | (blank) | Momentary Layer | Layer: Symbols | |
| 38 | GUI | Key Press | Keyboard Left GUI | |
| 39 | ␣ | Key Press | Keyboard Spacebar | |
| 40 | Alt | Key Press | Keyboard LeftAlt | |
| 41 | (blank) | Momentary Layer | Layer: NumPad | |

### Base Layer Visual
```
 Esc   Q    W    E    R    T       Y    U    I    O    P   BkSp
 Tab   A    S    D    F    G       H    J    K    L    ;   Shft
Ctrl   Z    X    C    V    B       N    M    ,    .    /   Ret
              [NAV] [SYM]  GUI    Spc  Alt  [NAV]
```

---

## Layer 1: NumPad

| Pos | Label | Behavior | Key / Binding | Modifiers |
|-----|-------|----------|---------------|-----------|
| 0 | Cmd+W | Key Press | Keyboard W | + L GUI |
| 1 | Home | Key Press | Keyboard Home | |
| 2 | Up | Key Press | Keyboard UpArrow | |
| 3 | End | Key Press | Keyboard End | |
| 4 | PgUp | Key Press | Keyboard PageUp | |
| 5 | — | Transparent | | |
| 6 | — | Transparent | | |
| 7 | 7 | Key Press | Keyboard 7 | |
| 8 | 8 | Key Press | Keyboard 8 | |
| 9 | 9 | Key Press | Keyboard 9 | |
| 10 | C+A+G+P | Key Press | Keyboard P | + L Ctrl + L Alt + L GUI |
| 11 | Cmd+Q | Key Press | Keyboard Q | + L GUI |
| 12 | (blank) | Momentary Layer | Layer: Functions | |
| 13 | Ctrl+Left | Key Press | Keyboard LeftArrow | + L Ctrl |
| 14 | Down | Key Press | Keyboard DownArrow | |
| 15 | Right | Key Press | Keyboard RightArrow | |
| 16 | PgDn | Key Press | Keyboard PageDown | |
| 17 | — | Transparent | | |
| 18 | — | Transparent | | |
| 19 | 4 | Key Press | Keyboard 4 | |
| 20 | 5 | Key Press | Keyboard 5 | |
| 21 | 6 | Key Press | Keyboard 6 | |
| 22 | C+A+G+\ | Key Press | Keyboard Backslash and Pipe | + L Ctrl + L Alt + L GUI |
| 23 | C+A+G+Spc | Key Press | Keyboard Spacebar | + L Ctrl + L Alt + L GUI |
| 24 | Shft | Key Press | Keyboard LeftShift | |
| 25 | C+A+Q | Key Press | Keyboard Q | + L Ctrl + L Alt |
| 26 | S+G+/ | Key Press | Keyboard ForwardSlash | + L Shift + L GUI |
| 27 | S+G+A | Key Press | Keyboard A | + L Shift + L GUI |
| 28 | S+G+V | Key Press | Keyboard V | + L Shift + L GUI |
| 29 | — | Transparent | | |
| 30 | — | Transparent | | |
| 31 | 1 | Key Press | Keyboard 1 | |
| 32 | 2 | Key Press | Keyboard 2 | |
| 33 | 3 | Key Press | Keyboard 3 | |
| 34 | C+S+Tab | Key Press | Keyboard Tab | + L Ctrl + L Shift |
| 35 | C+Tab | Key Press | Keyboard Tab | + L Ctrl |
| 36 | — | Transparent | (held to activate) | |
| 37 | — | Transparent | | |
| 38 | — | Transparent | | |
| 39 | . | Key Press | Keyboard Period | |
| 40 | 0 | Key Press | Keyboard 0 | |
| 41 | — | Transparent | | |

### NumPad Layer Visual
```
Cmd+W Home  Up   End  PgUp  —       —    7    8    9  C+A+G+P Cmd+Q
[SYS] C+Left Down Right PgDn  —      —    4    5    6  C+A+G+\ C+A+G+Spc
 Shft C+A+Q S+G+/ S+G+A S+G+V —      —    1    2    3  C+S+Tab C+Tab
              [NAV] [  ] [  ]    .    0   [  ]
```

> **Note:** zmk.studio shows the tap dance keys (td_0–td_9) from the keymap as their resolved first-binding values. The original tap dance behavior is preserved on the keyboard but not fully visible in studio.

---

## Layer 2: Symbols

| Pos | Label | Behavior | Key / Binding | Modifiers |
|-----|-------|----------|---------------|-----------|
| 0 | ` | Key Press | Keyboard Grave Accent and Tilde | |
| 1 | ! | Key Press | Keyboard 1 | + L Shift |
| 2 | @ | Key Press | Keyboard 2 | + L Shift |
| 3 | # | Key Press | Keyboard 3 | + L Shift |
| 4 | $ | Key Press | Keyboard 4 | + L Shift |
| 5 | % | Key Press | Keyboard 5 | + L Shift |
| 6 | ^ | Key Press | Keyboard 6 | + L Shift |
| 7 | & | Key Press | Keyboard 7 | + L Shift |
| 8 | * | Key Press | Keyboard 8 | + L Shift |
| 9 | ( | Key Press | Keyboard 9 | + L Shift |
| 10 | ) | Key Press | Keyboard 0 | + L Shift |
| 11 | \ | Key Press | Keyboard Backslash and Pipe | |
| 12 | Meh+J | Key Press | Keyboard J | + L Ctrl + L Shift + L Alt |
| 13 | Meh+A | Key Press | Keyboard A | + L Ctrl + L Shift + L Alt |
| 14 | Meh+S | Key Press | Keyboard S | + L Ctrl + L Shift + L Alt |
| 15 | Meh+D | Key Press | Keyboard D | + L Ctrl + L Shift + L Alt |
| 16 | Meh+K | Key Press | Keyboard K | + L Ctrl + L Shift + L Alt |
| 17 | — | Transparent | | |
| 18 | ' | Key Press | Keyboard Left Apos and Double | |
| 19 | - | Key Press | Keyboard Dash and Underscore | |
| 20 | Meh+= | Key Press | Keyboard Equals and Plus | + L Ctrl + L Shift + L Alt |
| 21 | Meh+L | Key Press | Keyboard L | + L Ctrl + L Shift + L Alt |
| 22 | Meh+; | Key Press | Keyboard SemiColon and Colon | + L Ctrl + L Shift + L Alt |
| 23 | Meh+Ret | Key Press | Keyboard Return Enter | + L Ctrl + L Shift + L Alt |
| 24 | Ctrl+1 | Key Press | Keyboard 1 | + L Ctrl |
| 25 | Ctrl+0 | Key Press | Keyboard 0 | + L Ctrl |
| 26 | — | Transparent | | |
| 27 | — | Transparent | | |
| 28 | — | Transparent | | |
| 29 | — | Transparent | | |
| 30 | — | Transparent | | |
| 31 | S+Prev | Key Press | Scan Previous Track | + L Shift |
| 32 | S+Vol- | Key Press | Volume Decrement | + L Shift |
| 33 | S+Vol+ | Key Press | Volume Increment | + L Shift |
| 34 | Next | Key Press | Scan Next Track | |
| 35 | Play | Key Press | Play/Pause | |
| 36 | — | Transparent | | |
| 37 | (blank) | Momentary Layer | Layer: Functions | |
| 38 | — | Transparent | | |
| 39 | Meh+Spc | Key Press | Keyboard Spacebar | + L Ctrl + L Shift + L Alt |
| 40 | { | Key Press | Keyboard Left Brace | + L Shift |
| 41 | } | Key Press | Keyboard Right Brace | + L Shift |

### Symbols Layer Visual
```
  `    !    @    #    $    %       ^    &    *    (    )    \
Meh+J Meh+A Meh+S Meh+D Meh+K  —     '    -  Meh+= Meh+L Meh+; Meh+Ret
Ctrl+1 Ctrl+0  —    —    —    —      —   S+Prev S+Vol- S+Vol+ Next Play
              [  ] [SYS] [  ]  Meh+Spc  {    }
```

> **Note:** "Meh" = Ctrl+Shift+Alt (without GUI). Row 1 positions 12-16 and 20-22 are Meh+letter shortcuts. Row 0 positions 1-10 are shifted numbers producing symbols (!@#$%^&*()).

---

## Layer 3: Functions

| Pos | Label | Behavior | Key / Binding | Modifiers |
|-----|-------|----------|---------------|-----------|
| 0 | — | Transparent | | |
| 1 | — | Transparent | | |
| 2 | G+Up | Key Press | Keyboard UpArrow | + L GUI |
| 3 | — | Transparent | | |
| 4 | — | Transparent | | |
| 5 | — | Transparent | | |
| 6 | — | Transparent | | |
| 7 | F7 | Key Press | Keyboard F7 | |
| 8 | F8 | Key Press | Keyboard F8 | |
| 9 | F9 | Key Press | Keyboard F9 | |
| 10 | F10 | Key Press | Keyboard F10 | |
| 11 | — | Transparent | | |
| 12 | — | Transparent | | |
| 13 | G+Left | Key Press | Keyboard LeftArrow | + L GUI |
| 14 | G+Down | Key Press | Keyboard DownArrow | + L GUI |
| 15 | G+Right | Key Press | Keyboard RightArrow | + L GUI |
| 16 | — | Transparent | | |
| 17 | Unlock | Studio Unlock | | |
| 18 | — | Transparent | | |
| 19 | F4 | Key Press | Keyboard F4 | |
| 20 | F5 | Key Press | Keyboard F5 | |
| 21 | F6 | Key Press | Keyboard F6 | |
| 22 | F11 | Key Press | Keyboard F11 | |
| 23 | — | Transparent | | |
| 24 | — | Transparent | | |
| 25 | BT0 | Bluetooth | Select Profile 0 | |
| 26 | BT1 | Bluetooth | Select Profile 1 | |
| 27 | BT2 | Bluetooth | Select Profile 2 | |
| 28 | BTClr | Bluetooth | Clear Selected Profile | |
| 29 | BTAll | Bluetooth | Clear All Profiles | |
| 30 | C+A+F1 | Key Press | Keyboard F1 | + L Ctrl + L Alt |
| 31 | F1 | Key Press | Keyboard F1 | |
| 32 | F2 | Key Press | Keyboard F2 | |
| 33 | F3 | Key Press | Keyboard F3 | |
| 34 | F12 | Key Press | Keyboard F12 | |
| 35 | — | Transparent | | |
| 36 | — | Transparent | | |
| 37 | — | Transparent | | |
| 38 | — | Transparent | | |
| 39 | — | Transparent | | |
| 40 | [ | Key Press | Keyboard Left Brace | |
| 41 | ] | Key Press | Keyboard Right Brace | |

### Functions Layer Visual
```
  —    —   G+Up   —    —    —       —    F7   F8   F9  F10   —
  —   G+Left G+Down G+Right — Unlock  —    F4   F5   F6  F11   —
  —   BT0  BT1  BT2  BTClr BTAll  C+A+F1 F1   F2   F3  F12   —
                 [  ] [  ] [  ]    —    [    ]
```

---

## Layer 4: Extra

| Pos | Label | Behavior | Key / Binding | Modifiers |
|-----|-------|----------|---------------|-----------|
| 0 | — | Transparent | | |
| 1 | — | Transparent | | |
| 2 | — | Transparent | | |
| 3 | MB3 | Mouse Key Press | Middle Click (MB3) | |
| 4 | — | Transparent | | |
| 5 | ScrollUp | mouse_scroll | Scroll Up | |
| 6 | — | Transparent | | |
| 7 | C+A+7 | Key Press | Keyboard 7 | + L Ctrl + L Alt |
| 8 | C+A+8 | Key Press | Keyboard 8 | + L Ctrl + L Alt |
| 9 | C+A+9 | Key Press | Keyboard 9 | + L Ctrl + L Alt |
| 10 | Alt | Key Press | Keyboard LeftAlt | |
| 11 | Meh+Spc | Key Press | Keyboard Spacebar | + L Ctrl + L Shift + L Alt |
| 12 | — | Transparent | | |
| 13 | — | Transparent | | |
| 14 | MB1 | Mouse Key Press | Left Click (MB1) | |
| 15 | MoveUp | mouse_move | Move Up | |
| 16 | MB2 | Mouse Key Press | Right Click (MB2) | |
| 17 | ScrollDn | mouse_scroll | Scroll Down | |
| 18 | — | Transparent | | |
| 19 | C+A+4 | Key Press | Keyboard 4 | + L Ctrl + L Alt |
| 20 | C+A+5 | Key Press | Keyboard 5 | + L Ctrl + L Alt |
| 21 | C+A+6 | Key Press | Keyboard 6 | + L Ctrl + L Alt |
| 22 | — | Transparent | | |
| 23 | — | Transparent | | |
| 24 | — | Transparent | | |
| 25 | — | Transparent | | |
| 26 | MoveLeft | mouse_move | Move Left | |
| 27 | MoveDown | mouse_move | Move Down | |
| 28 | MoveRight | mouse_move | Move Right | |
| 29 | — | Transparent | | |
| 30 | C+A+0 | Key Press | Keyboard 0 | + L Ctrl + L Alt |
| 31 | C+A+1 | Key Press | Keyboard 1 | + L Ctrl + L Alt |
| 32 | C+A+2 | Key Press | Keyboard 2 | + L Ctrl + L Alt |
| 33 | C+A+3 | Key Press | Keyboard 3 | + L Ctrl + L Alt |
| 34 | — | Transparent | | |
| 35 | — | Transparent | | |
| 36 | — | Transparent | | |
| 37 | — | Transparent | | |
| 38 | — | Transparent | | |
| 39 | Shft | Key Press | Keyboard LeftShift | |
| 40 | — | Transparent | | |
| 41 | — | Transparent | | |

### Extra Layer Visual
```
  —    —    —   MB3   —   ScrUp     —   C+A+7 C+A+8 C+A+9 Alt Meh+Spc
  —    —   MB1  MvUp MB2  ScrDn     —   C+A+4 C+A+5 C+A+6  —    —
  —    —   MvL  MvDn MvR   —      C+A+0 C+A+1 C+A+2 C+A+3  —    —
                 [  ] [  ] [  ]   Shft   —    —
```

---

## Combos (from keymap file — not auditable via zmk.studio click-through)

| Combo Keys | Output | Layer |
|------------|--------|-------|
| 13 + 29 | Escape | All |
| 15 + 21 | Delete | All |
| 5 + 17 | % | Base |
| 28 + 16 | = | Base |
| 4 + 16 | $ | Base |
| 3 + 15 | # | Base |
| 2 + 14 | @ | Base |
| 26 + 14 | \ | Base |
| 8 + 20 | * | Base |
| 32 + 20 | / | Base |
| 7 + 19 | + | Base |
| 31 + 19 | - (KP) | Base |
| 30 + 18 | _ | Base |
| 31 + 32 | [ | Base |
| 33 + 32 | ] | Base |
| 20 + 19 | paraless (tap-dance: ( / <) | Base |
| 20 + 21 | paragreat (tap-dance: ) / >) | Base |
