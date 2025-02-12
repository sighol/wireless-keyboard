# Sighol-44

![](docs/pcb.png)

# Installation

Remember to add the [marbastlib](https://github.com/ebastler/marbastlib) symbol and footprints library.
Check the github page for installation instructions.

# Documentation

[Nice nano pinout and schematic](https://nicekeyboards.com/docs/nice-nano/pinout-schematic)

![Nice nano pinout](docs/nice-nano-pinout-v2.png)

## [Video about batteries](https://www.youtube.com/watch?v=zoCKINGh2DQ)

- GEt mill max sockets that are avtagbare.
- Get taller ones so that battery fit underneath.
- Solder on the power switch early on. He said "the first thing", but I am not sure if
  that matters a lot.

## Nice View

<img src="docs/niceview_pinout.png" alt="" width="200px" />

https://nicekeyboards.com/docs/nice-view/pinout-schematic#default-pins

- CS: D1/P0.06
- SCL: D2/P0.17
- MOSI: D3/P0.20

# Parts

- 2 x [Nice!Nano V2](https://42keebs.eu/shop/parts/controllers/nice-nano-v2-wireless-controller/)
- 2 x [Controller sockets/pins/headers medium](https://42keebs.eu/shop/parts/components/controller-sockets-pins-mill-max-generic/?attribute_pack=Medium+Profile+Sockets+%2B+Pins+%2825%29). Medium will fit 3mm batteries.
- 1 x [Nice!view](https://42keebs.eu/shop/parts/niceview-power-efficient-lcd-display/). I only need one for the left half.
- 2 x [SDM power switch](https://42keebs.eu/shop/parts/components/power-switch/?attribute_type=Micro+SMD+SPDT).
- 2 x [reset switch](https://42keebs.eu/shop/parts/components/reset-switch/).

Total: 93.95 EUR on 42keebs.eu.

# TODO:

- Lage reversible footprint for power switch.
- Redo edge cut in inkscape. Use radius path and then offset to get nice corners everywhere.
- Add TRRS so that the same PCB can be used wired with QMK.
- Figure out if I need a screen protector for thr nice nano.
