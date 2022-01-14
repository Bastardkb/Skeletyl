# Skeletyl

Compact and silent Dactyl-like keyboard for ergo lovers.

![](pics/c1.jpg)
*picture: trekdemo*

# Sourcing the components

## Electronic components

You will need to order the parts from a shop, and order some PCBs directly from the manufacturer.

Parts list:

| Part name                         | Amount | Link                                                                                    |
| --------------------------------- | ------ | --------------------------------------------------------------------------------------- |
| Flexible PCB for the plate   | 2     | https://github.com/Bastardkb/PCB_plate_DM                                                        |
| Flexible PCB for the thumbs   | 2     | https://github.com/Bastardkb/PCB_Thumbs_DM                                                      |
| Elite-C                           | 2      |                                                                                         |
| Elite-C adapter PCB V1.4          | 2      | https://github.com/Bastardkb/Elite-C-holder                                             |
| SOD123 Diodes                     | 36     |                                                                                         |
| Wires                             |        | 28 AWG recommended                                                                      |
| M4 8mm Torx Screw                 | 12     | Conrad                                                                                  |
| M4 screw insert, M4 X D6.0 X L5.0 | 12     | https://fr.aliexpress.com/item/4000232925592.html?spm=a2g0s.12269583.0.0.6aef4f282LZO4v |
| Audio jack, SMD                   | 2      |                                                                                         |
| Button, 4x4x1.5                   | 2      | https://www.aliexpress.com/item/1005001304569553.html?spm=a2g0s.9042311.0.0.27424c4dDwgcp7 |

If you don't want to source the Elite-C adapter PCB, you can use the [printable shield adapter from Geoff](https://github.com/geoffder/dometyl-keyboard/blob/main/things/holders/bastardkb/printable_shield.stl).

If you don't want to source the flexible PCBs, you can also use either amoebas or handwire.

If you want RGB, you will also need:

| Part name          | Amount | Link       |
| ------------------ | ------ | ---------- |
| SK6812 Mini-E LEDs | 36     | Aliexpress |

## Print the case

The STL, STEP and Fusion files are included in this Github.
Feel free to modify them at length. The files are on a non-commercial license, so this is for personal projects only - please do not use those to sell them.

Please find detailed instructions on how to print the case here:
https://docs.bastardkb.com/hc/en-us/articles/360020031180-Print-settings-for-Dactyls

There is also a version that uses a blackpill with its shield PCB, in the `V3/blackpill` folder. The position of the audio jack and usb-c holes are slightly different.

## Print the tents

Optionally, you can print 30 degree tents. Those are removable and attached with screws, and also come with an optional bottom plate.

The tents come in 2 versions: normal, and organic. The organic one provides a sleeker skeleton-style look with a side holder for the shield pcb, but is longer and harder to print.

There is a separate version of the organic tent that accomodates a blackpill with shied on the side.


| Front view               | Side view           |
| ----------------- | ------------------ |
| ![](pics/tent1.jpg) | ![](pics/tent2.jpg) |

## Get a kit from BastardKB

You can get a full Kit, including case and all PCBs and electronics required on the shop:
https://bastardkb.com/

If you want to print the case yourself, you can also get just the electronics Kit.

# Build guide

Please find detailed build instructions here:
https://docs.bastardkb.com/hc/en-us/articles/360020031340-Kit-contents-and-required-tools

This is for the 6x3, but it will work for this keyboard as well.

# Finding help

- Discord: https://bastardkb.com/discord
- Website: https://bastardkb.com/
- Docs: https://docs.bastardkb.com

# Forks

- [Reinforced, increased pinky stagger](https://github.com/dereknheiley/Skeleton-Dactyl-Mini)

# Support me on Patreon

If you like the keyboard, please consider helping me with Patreon: https://www.patreon.com/bastardkb

I post regular updates and hindsight on my work. I work full time on keyboard innovation, and this helps a lot !


# License 

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

# Versions

V1:

- original version

V2:

- smoother
- Compatible with amoebas and flexible pcbs
- more screws !

V3:

- better stronger screw inserts (added aliexpress link in readme)
- switch to adapter V1.4