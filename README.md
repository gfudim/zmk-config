# zmk-config

## shallow miryoku zmk-config repo

A shallow "miryoku" layout implementation for my 36-Keys, diode-free/gpio-direct, custom keyboard.

<img src="https://raw.githubusercontent.com/gfudim/zmk-config/master/img/k36.jpg"
     alt="K36 Keyboard"
     style="float: left; margin-bottom: 10px;" />

### Parts

* PCB - 2 PCBs of K-36 split keyboard
* Controller - 2 Nice Nano micro controller
* Switches - 36 Kailh Choc switches of your choice
* Sockets - 36 Kailh hotswap sockets for choc switches
* Keycaps - 34 Choc keycaps, 2 Choc homing keycaps
* On\Off Switch - 2 PCM12SMTR micro toggle switch
* Reset Button - 2 B3U-1000P MD 2-foot tact switch 3*2.5*1.6 Micro button
* Battery - 2 301230 3.7v 110mah batteries(they fit under the nice nano mount)
* Connector - 2 PH 2.0 JST Connector Right Angle, Seat+Plug+Terminals
* Pads - Round Silicone Rubber Pads, 8x8x2.5mm (min height is 2.5mm because the hotswap sockets are 2mm in height)

### Details

* 5 columns, 3 rows, 3 thumb keys, 2 hands.
* Can be used on almost any split or non-split ergo or ortho keyboard.
* Includes all keys found on a US layout TKL keyboard, plus media keys and mouse emulation.
* Home row is the middle row, home thumb key is the middle thumb key.
* Maximum 1-u movement from home position for fingers and thumbs, and only along one axis (except for the inner index finger column which is deprioritised compared with the home columns).
* Dual-function modifiers on home row, mirrored on both hands.
* Dual-function layer change on thumbs.
* Layers are designed orthogonally with a single purpose per hand and are accessed by holding a thumb key on the opposite hand.
* All layers on the same hand are based on the same basic key arrangement.
* Holding layer change and modifiers on one hand combined with a single key press on the other hand can produce any combination of modifiers and single keys without any finger contortions.
* Single function mods are also defined on layers on the same hand as the layer change thumb key so layer change and mods can be held in any order or simultaneously without race conditions.
* As mods are only enabled on the opposite hand, auto-repeat is available on the home row on layers for use with cursor and mouse keys.
* Tap-hold auto-repeat is disabled to permit faster tap-hold switching on thumbs, but thumb tap keys are mirrored onto some layers for use with auto-repeat.  On other layers thumb keys are redefined with important functions for that layer.
* Auto Shift for numbers and symbols.
* Reset is available on sub layers on the same hand as the layer change thumb key.  Hold any thumb key and tap the top row pinkie column key on the same hand.

## Layers

### Base

<img src="https://raw.githubusercontent.com/manna-harbour/miryoku/master/data/layers/miryoku-kle-base.png"
     alt="Base Layer"
     style="float: left; margin-bottom: 10px;" />

Qwerty layout implemented

### Media

<img src="https://raw.githubusercontent.com/manna-harbour/miryoku/master/data/layers/miryoku-kle-media.png"
     alt="Media Layer"
     style="float: left; margin-bottom: 10px;" />

### Navigation

<img src="https://raw.githubusercontent.com/manna-harbour/miryoku/master/data/layers/miryoku-kle-nav.png"
     alt="Base Layer"
     style="float: left; margin-bottom: 10px;" />

### Mouse

<img src="https://raw.githubusercontent.com/manna-harbour/miryoku/master/data/layers/miryoku-kle-mouse.png"
     alt="Base Layer"
     style="float: left; margin-bottom: 10px;" />
zmk doesn't support mouse movments on stable, so need's to be implemented once the feature is published.

### Symbol

<img src="https://raw.githubusercontent.com/manna-harbour/miryoku/master/data/layers/miryoku-kle-sym.png"
     alt="Base Layer"
     style="float: left; margin-bottom: 10px;" />

### Number

<img src="https://raw.githubusercontent.com/manna-harbour/miryoku/master/data/layers/miryoku-kle-num.png"
     alt="Base Layer"
     style="float: left; margin-bottom: 10px;" />

### Function

<img src="https://raw.githubusercontent.com/manna-harbour/miryoku/master/data/layers/miryoku-kle-fun.png"
     alt="Base Layer"
     style="float: left; margin-bottom: 10px;" />