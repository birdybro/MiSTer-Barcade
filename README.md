# Mini-MiSTerBarcade (WORK IN PROGRESS)

License: Creative Common Attributions License (and all thingiverse files were the same)

Original source of print here --> [Mini Arcade Machine by iClint](https://www.thingiverse.com/thing:2216740)

Remixed content from here --> [Bezel File from Mini Arcade Machine by Franks3dShop](https://www.thingiverse.com/thing:3529914) and here --> [10 button control panel for Mini Arcade Machine by alecreator](https://www.thingiverse.com/thing:3817837)

## Description

This is a project to build a Mini Bartop Arcade system with a MiSTer FPGA device integrated into it. It's not meant to be the best, it's just meant to be printable on cheap enthusiast 3d printers, using decently high quality components. This is not a very cheap project, if you want to make it cheaper, substitute a raspberry pi like the above-linked original source of the print from Thingiverse by iClint, and substitue the screen for a cheaper one from Aliexpress. All costs below are based on my personal selection of items as of May 2021. Your results and methods may vary.

## Tools Required
* [Metric Hex Wrench set](https://www.amazon.com/TEKTON-Wrench-Metric-13-Piece-25272/dp/B00I5THFR4/)
* [Loctite Ultra Gel Control Super Glue](https://www.amazon.com/dp/B01EZTPXEO) (or another cyanoacrylate super glue for bonding PLA pieces of different colors together)
* [Power drill](https://www.amazon.com/Dewalt-DCD771C2-Cordless-Lithium-Ion-Compact/dp/B00ET5VMTU/)
* [M3 Tap bits](https://www.amazon.com/Hakkin-Nitriding-Plastic-Tapping-Cutting/dp/B07S5KKCS4)
* 

## Bill of Materials

### MiSTer FPGA Platform devices
* [Terasic DE10-Nano](https://www.digikey.com/en/products/detail/terasic-inc/P0496/6817231) - $170.00
* [Mean Well 5v 20W 4A Power Supply](https://www.digikey.com/en/products/detail/mean-well-usa-inc/GST25A05-P1J/7703645) - $16.63
* [Mean Well NEMA5-15P to IEC320 Power Cored](https://www.digikey.com/en/products/detail/mean-well-usa-inc/YP12-YC12/7707223) - $ 5.78
* [128MB MiSTer FPGA SDRAM Add-on Board](https://misteraddons.com/products/sdram-xsd-2-5-128mb) - $60.00
* [USB Hub Add-on board With DC Splitter and USB Bracket](https://misteraddons.com/products/usb-hub-v2-1) - $50.00
* [Heatsink](https://www.amazon.com/gp/product/B01JB8MQ76/) - $9.97
* [2 pin 5v 40mm Fan](https://www.amazon.com/GeeekPi-Raspberry-40x40x10mm-Brushless-Radiator/dp/B07X6CXQLN) - $7.99

### Sanwa Joystick and Buttons
* [Sanwa JLF-TP-8YT Joystick](https://focusattack.com/sanwa-jlf-tp-8yt-joystick/) - Add 5-Pin Double End Female Harness, GT-Y Octo Gate, and KOWAL Flat Plate Converter - $35.20
* [10x Japanese Style .110" Harness](https://focusattack.com/spare-japanese-style-110-harness-for-zero-delay-usb-encoder-pcb/) - $4.50
* [8x Sanwa OBSF 30MM Pushbuttons](https://focusattack.com/buttons/sanwa/30mm/obsf-30-pushbutton/) - $19.60
* [2x Sanwa OBSF 24MM Pushbuttons](https://focusattack.com/buttons/sanwa/24mm/obsf-24-pushbutton/) - $4.50

### Adafruit Components
* [HDMI 7" 800x480 Display Backpack - Without Touch](https://www.adafruit.com/product/2406) - $79.95
* [Stereo 3.7W Class D Audio Amplifier - MAX98306](https://www.adafruit.com/product/987) - $8.95
* [Speaker - 3" Diameter - 4 Ohm 3 Watt](https://www.adafruit.com/product/1314) - $1.95

### Screws/mounts and other hardware
* [8x (100 in pack) M3 Hex Nuts](https://www.amazon.com/gp/product/B01IWUSDYY/) - $5.22
* [30x (50 in pack) M3x12mm Countersunk Hex Bolt](https://www.amazon.com/gp/product/B01E6EIC2S/) - $6.99
* [12x (80 in pack) M3x4mm Machine Screws](https://www.amazon.com/gp/product/B07WCT6VY6/) - $6.99

### Estimated total cost
$

## 3D Printing

All 3d Printed Parts were sliced in PrusaSlicer on a Prusa i3 MK3S+ set to 0.30mm draft profile (15% grid infill) using Hatchbox PLA, unless otherwise stated below.

### Arcade Cabinet

* [Front Panel](https://cdn.thingiverse.com/assets/3f/01/7c/28/23/Front_Panel.stl)
* [Top Panel](https://cdn.thingiverse.com/assets/83/88/73/ff/92/Top_panel.stl)
* [Left Panel](https://cdn.thingiverse.com/assets/d0/cb/0b/19/be/left_Panel.stl)
* [Right Panel](https://cdn.thingiverse.com/assets/4f/1d/11/f3/97/right_panel.stl)
* [Back Panel](https://cdn.thingiverse.com/assets/98/93/cd/c9/cd/Back_Panel.stl) - Print with generated supports, 0.2 detachable. The handle area will slouch otherwise. You may have to paint on support blockers to keep unnecessary supports from being made around the edges which would cause it to exceed the build plate size.
* [Base Panel](https://cdn.thingiverse.com/assets/87/da/83/f2/4b/Base_panel.stl)
* [Rubber Feet](https://cdn.thingiverse.com/assets/22/47/79/eb/ac/Rubber_foot.stl) - Use TPU instead of PLA because "rubber".
* [Control Panel 10 Buttons Remix by alecreator](https://cdn.thingiverse.com/assets/d9/a1/a0/62/c1/Mini_Arcade_10_buttons.stl) - Used 0.20mm Quality profile instead because it is an obvious cosmetic surface. Use supports or else some loose bridging occurs on the interior wall that connects to the Bezel. You may have to use paint-on support blockers around the edges except for the bezel-facing interior wall in order for the slicer to fit it to your build plate.
* [Bezel for Adafruit 7" screen](https://cdn.thingiverse.com/assets/7f/f2/e9/ba/73/Bezel-Adafruit_7_Touchscreen.stl)

### Decorations

## Notes
* Power stereo amp from GPIO on the DE10-nano. 5v is required. Occupy pin 11 (5v) and 12 (GND) of the available header.
* Power the fan from GPIO on the DE10-nano. 3.3v is required. Occupy pin 29 (3.3v) and 30 (GND) of the available header.
