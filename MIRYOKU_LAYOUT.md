# Miryoku Layout for Travel Corne (Colemak-DH)

This configuration implements the Miryoku layout with Colemak-DH for your Corne keyboard with the following features:

## Key Features
- **36-key layout** optimized for ergonomic typing
- **Colemak-DH base layout** - matrix-optimized version for better finger comfort
- **Home row modifiers** on ARSTG and KNEIO keys
- **6 layers** for complete functionality
- **Layer-tap thumb keys** for efficient layer switching

## Layout Overview

### Base Layer (Layer 0) - Colemak-DH
```
Q  W  F  P  B       J  L  U  Y  ;
A  R  S  T  G       K  N  E  I  O
Z  X  C  D  V       M  H  ,  .  /
   ESC SPC TAB   RET BSP DEL
```

**Home Row Mods (Colemak-DH):**
- A = GUI (hold) / A (tap)
- R = ALT (hold) / R (tap)  
- S = CTRL (hold) / S (tap)
- T = SHIFT (hold) / T (tap)
- N = SHIFT (hold) / N (tap)
- E = CTRL (hold) / E (tap)
- I = ALT (hold) / I (tap)
- O = GUI (hold) / O (tap)

### Thumb Keys
- **Left thumb:**
  - ESC / Media layer (layer 5)
  - SPACE / Nav layer (layer 1)
  - TAB / Num layer (layer 3)
- **Right thumb:**
  - ENTER / Sym layer (layer 2)
  - BACKSPACE / Fun layer (layer 4)
  - DELETE / Mouse layer (layer 6)

## Layer Details

### Layer 1 - Navigation (NAV)
Access with SPACE + hold
- Arrow keys, page up/down, home/end
- Cut, copy, paste shortcuts
- Word navigation

### Layer 2 - Symbols (SYM)
Access with ENTER + hold
- Symbols: { } ( ) & * % ^ + etc.
- Special characters for programming

### Layer 3 - Numbers (NUM)
Access with TAB + hold
- Number pad layout (7,8,9 top row)
- Mathematical operators
- Brackets [ ]

### Layer 4 - Function Keys (FUN)
Access with BACKSPACE + hold
- F1-F12 function keys
- Screen capture, scroll lock, pause

### Layer 5 - Media (MEDIA)
Access with ESC + hold
- Volume controls
- Media playback (prev, next, play/pause)
- Bluetooth device switching

### Layer 6 - Mouse (MOUSE)
Access with DELETE + hold
- Simplified mouse layer
- Can be customized for mouse movement if needed

## Colemak-DH Benefits

This layout uses the **Colemak-DH matrix variant** specifically optimized for ortholinear keyboards like the Corne:

- **Better D & H placement** - Moved to more comfortable bottom row positions (index finger curl)
- **Reduced lateral stretching** - Less sideways hand movement compared to standard Colemak
- **Optimized for matrices** - Designed specifically for grid-layout keyboards
- **Improved bigram flow** - Common letter combinations like "HE" flow more naturally

## Tips for Adaptation

1. **Start slow** - Practice the base Colemak-DH layout first before exploring layers
2. **Focus on one layer at a time** - Master the base layer before exploring others  
3. **Learn common words** - Practice "THE", "AND", "FOR" to get comfortable with the layout
4. **Timing matters** - 200ms hold time for modifiers, adjust if needed
5. **Muscle memory** - Give yourself 3-4 weeks to fully adapt to Colemak-DH
6. **Use typing trainers** - Consider Colemak-specific typing practice tools

## Customization

The layout is configured in `config/corne.keymap`. Key timing and behavior can be adjusted in `config/corne.conf`.

To modify:
- Tapping term: Adjust `tapping-term-ms` in the home row mods behavior
- Layer assignments: Change the `&lt` bindings on thumb keys
- Key positions: Modify individual key bindings in each layer