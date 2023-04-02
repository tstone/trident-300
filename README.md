# Trident 300 "Teal"

## Colors
  - Primary: [Paramount 3D ABS Fighter Jet Blue](https://www.paramount-3d.com/product-page/abs-pantone-fighter-jet-blue-7546c-1-75mm-1kg-filament-fbrl50087546c)
  - Secondary: [Polymaker Polylite ASA Teal](https://us.polymaker.com/products/polylite-asa?variant=40294530940985)
  - Frame: LDO Space Gray

## Electronics
 - **A/B Motors**: LDO-42STH48-2004MAH
 - **Z Motors**: LDO-42STH40-1684L300E
 - **Extruder Motor**: LDO-36STH20-1004AHG
 - **Pi**: BTT CB1
 - **Controller**: BTT Manta M8P
 - **Can Interface**: BTT U2C v2.1
 - **Toolhead Board**: BTT EBB36 v1.2
 - ~**Hotend**: E3D Revo Voron~
 - **Hotend**: [DropEffect/Phaetus XG](https://dropeffect.phaetus.com/products/xg-hotend)

## End Stops
 - ~X: [X Carriage](https://github.com/VoronDesign/Voron-Stealthburner/tree/main/STLs/X_Carriage)~
 - X: [Sensorless homing](https://mmone.github.io/klipper/Sensorless_Homing.html)
 - Y: [y_endstop_housing](https://github.com/VoronDesign/Voron-Trident/blob/main/STLs/Gantry/AB_Drive_Units/%5Ba%5D_y_endstop_housing.stl)
 - ~Z: [SexBolt](https://mods.vorondesign.com/detail/t1DBVlcUBbdEK6habEsVzg)~ 
 - ~Z: [Probe as Z Endstop](https://github.com/Klipper3d/klipper/blob/master/config/sample-probe-as-z-endstop.cfg)~
 - Z: [Voron Tap](https://github.com/VoronDesign/Voron-Tap)

## Mods
 - Pin Mod: https://mods.vorondesign.com/detail/C8XJJ0fBGfBFKQZctjKeA
 - Stealth Bed Front: https://github.com/MapleLeafMakers/Stealth_Bed_Front
 - U2C Mount: https://mods.vorondesign.com/detail/guUSuCXHsOqPH1Xn5cS1Ag 
 - M8P bracket: https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/gerritwellen/manta-m8p-bracket
 - Insulation: [3mm cell foam](https://www.amazon.com/dp/B01KX94XE6?psc=1&ref=ppx_yo2ov_dt_b_product_details) under deck
 - Umbilical (A drive): https://www.printables.com/model/326623-voron-trident-wire-cover-w-pg7-cable-gland-adapter
 - Z motor covers: https://www.teamfdm.com/files/file/555-z-motor-cover-trident/?tab=details
 - Nozzle Scrubber Trident Mount: https://www.printables.com/model/298565-nozzle-scrubber-arm-extension-voron-trident
 - CB-CW: https://github.com/kejar31/VoronMods/tree/main/CB-C2
 - Bowden Guide: https://github.com/GalvanicGlaze/Voron_Mods/tree/main/Trident%20Bowden%20tube%20PTFE%20guide
 - LED effects: https://github.com/julianschill/klipper-led_effect
 - Vent hose adapter: https://www.printables.com/model/222658-voron-24r2-60mm-exhaust-flex-tube-adapter
 - Back Logo (based on): https://www.vecteezy.com/vector-art/7501249-vintage-trident-spear-of-poseidon-neptune-god-triton-king-logo
 - Nevermore Micro Duo v5: https://github.com/nevermore3d/Nevermore_Micro
 - Deck Panel Clips: https://mods.vorondesign.com/detail/7vnCQwmDSUxvUPSLaLtElg
 - Side Entry Exhaust: https://mods.vorondesign.com/detail/YI1xmcLeAMZ4mNkh0Ytg
 - Chamber Thermistor: https://mods.vorondesign.com/detail/dfRX88k7wwS6tpYlvyCEw
 - One piece door with...
   - 270 Front Hinges: https://mods.vorondesign.com/detail/eeRCH8EJiLrIF5q5l3AQg
   - Snap Latches (front door): https://mods.vorondesign.com/detail/9Rdnf5vD2oaJLmR7BpAuQ
   - Video: https://youtube.com/shorts/7rg-bvvLkAM?feature=share
 - Edge-to-edge heater
 - Trident Bed Fans (dual 5015): https://mods.vorondesign.com/detail/qtM0MIMBV51pSVvU2BezEw
 - Lightweight Labware kinematic mount: https://github.com/tanaes/whopping_Voron_mods/tree/main/kinematic_bed
 - Horizontal Spool Holder: https://mods.vorondesign.com/detail/x2umK6ZcG6l2c5EEM2LQjQ
 - Bed mesh only print area: https://gist.github.com/ChipCE/95fdbd3c2f3a064397f9610f915f7d02
 - Profile covers: https://mods.vorondesign.com/detail/8PtM9BKgRdBUN7CZ8g6Q
 - Chainflex 018-D series umbilical
 - DIY silicon flap brush (to be released after more testing)
 - Rainbow Barf: https://github.com/tanaes/whopping_Voron_mods/tree/main/LEDs/Rainbow_Barf_Logo_LED
 - Daylight on a Stick: https://github.com/VoronDesign/Voron-Hardware/tree/master/Daylight
 - Frame Handles https://github.com/VoronDesign/Voron-2/blob/Voron2.2/STLs/VORON2.2/Panel_Mounting/Handles_Panel_Rests_Misc/front_panel_rest_3%2B6mm_x2_Rev1.STL
  - Nozzle Scrubber: https://www.printables.com/model/201999-nozzle-scrubber-with-a-little-bucket-for-voron-24
  - Custom LCD display: https://github.com/alchemyEngine/VoronUsers/tree/master/firmware_configurations/klipper/alch3my
 
### TODO
 - Top spool holder: https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/elcrni/V2.4-Trident-Spool-Holders
 - Filament swap macro (M600?)
 - Trident Tophat: https://github.com/jakub874/Jakub3DPrinterMods/tree/main/Tophat
 - Lift-off hinges: https://www.printables.com/model/302551-lift-off-hinges-for-voron-trident-or-v2
 - Door handle: https://www.printables.com/model/261630-voron-door-handle
 - VzBot style PLA cooling ducts
 - Rebreather XL: https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Misc/Rebreather/Kirby-RebreatherXL

### Project 500hrs
 - CNC Tap
 - MCU to Klipper 11
 - Replace Brass nuts with POM nuts
 - Re-calibrate pressure advance + input shaping
 - Check screw tightness and rail lubrication

### Project Meow
 - Meowburner: https://www.printables.com/model/362807-meowburner-the-puurrfect-stealthburner
 - Bondtech integrated drive gear

### Project More Powah Baby
 - 48v X/Y
 - 5160 step stick
 - speedy X/Y motors

### Removed Mods
 - Klicky PCB (replaced by Tap): https://github.com/tanaes/whopping_Voron_mods/tree/main/pcb_klicky
   - Trident dock mount: https://github.com/jlas1/Klicky-Probe/tree/main/Printers/Voron/v1.8_v2.4_Legacy_Trident/Usermods/Mneuhaus
 - SexBolt (replaced by Tap): https://mods.vorondesign.com/detail/t1DBVlcUBbdEK6habEsVzg
  
## Reference
 - [Voron Trident Manual](https://github.com/VoronDesign/Voron-Trident/tree/main/Manual)
 - [BTT Manta M8P Manual](https://github.com/bigtreetech/Manta-M8P/blob/master/BIGTREETECH%20MANTA%20M8P%20V1.0%26V1.1%20User%20Manual.pdf)
 - [BTT EB36 Manual](https://github.com/bigtreetech/EBB/tree/master/EBB%20CAN%20V1.1%20(STM32G0B1)/EBB36%20CAN%20V1.1)
 - [BTT U2C v2.1 Setup Instructions (Voron Discord)](https://discord.com/channels/460117602945990666/1000794039832035530/1016059566439538759)
 - [Klipper neopixel](https://github.com/digitalninja-ro/klipper-neopixel)
