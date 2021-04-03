## Skeletyl Tenting base.

![skeltyl tenting left side](https://raw.githubusercontent.com/cwebster2/Skeleton-Dactyl-Mini/cw-tenting-base/V2-tenting-base/Skeletyl_Tented_V2.jpg)

This tenting base attaches to the bottom of the skeletyl and provides a 15 degree tenting angle and provides a new bottom plate to attach to the bottom of the tenting base.

STL files for the tenting base and the bottom plate are provided.  A prusa slicer project file is provided for the tenting base that contains the settings I used to successfully print the models.  A Fusion 360 file is provided so you can customize this as you see fit.  For example, the tenting is achieved with a construction plane cutting an extrusion and you can adjust this to achieve your desired tenting and tilting angles.

The tenting base has two holes in the back which are suitable for pushbuttons with M7threads / 7mm holes for reset and power switches.  Power?  Yes, this was designed bluetooth builds!  The bottom plate has a raised rectangular region and this is used to seat an 18650 battery holder.

### Assembly

Things you'll need to build it like me:

- The M4 machine screws that you have from the skeletyl hardware kit (or
  whatever screws go with the inserts you put into the skeletyl)
- Heat-set inserts M3 threads, 4mm thick, 5mm diameter.
- M3 machine screws
- Momentary switch (e.g. https://www.amazon.com/gp/product/B07BD2D96W )
- On/off switch (e.g.  https://www.amazon.com/gp/product/B07DWS195R )
- Battery holder (e.g.  https://www.amazon.com/gp/product/B0721Y3NDQ )
- 18650 battery.

The batteries are optional and only make sense if you are using a nice!nano controller and if that is the case you can of course use any battery that makes sense for you.
To assemble, install the M3 heat set inserts into the tenting base (not holes that are flat on both sides, *not* the countersunk holes).  Install the momentary and on/off swtiches.  Wire the momentary switch to RST and Ground on your microcontroller.  Wire the on/off swtich to your battery positive terminal and to the B+ connection on the nice!nano.  Connect your negative battery wire to the B- connection on the nice!nano.  Screw the tenting base to the skeletyl with the M4 machine screws, then screw the bottom plate to the tenting base with M3 machine screws.

### Flashing ZMK

If you are using a nice!nano, you'll need a ZMK shield for this keyboard.  See https://github.com/cwebster2/zmk-config for an example of a working setup for the skeletyl.  
