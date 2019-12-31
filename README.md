# F030NG
A ground-up remake of famous Atari Falcon 030 hardware, using contemporary components and technologies wherever possible, while maintaining maximum compatibility with original Atari system.
It aims to fix outstanding stability issues of original Falcon and introduces number of changes and exciting new features, such as
- **New form factor**, closer to never released Atari Microbox030
- Incorporates much, **much faster DSP with four times more on-board memory**
- Replaces fixed TOS ROM socket with swappable add-on modules, what gives room for flash memory based TOS switchers etc.
- IDE port is relocated to allow simple use of cheap and ubiquitous CF-IDE adaptors, with CF conveniently accessible from the outside of the computer. Internal PATA laptop HDD is still an option
- External SCSI replaced with standard **internal 50 pin SCSI interface**. External port can be added with simple breakout board
- Removes two STE jagpad ports to save some space and simplify motherboard design
~~- Expands internal expansion connector for additional pins to allow more different devices to be build, such as test and diagnostics cart (TBD), while still maintaining full compatibility with CT60(e) accelerator~~ no longer necessary, see below
~~- Removes legacy cartridge interface due to general unavailability of replacement edge board connectors~~ as I have found suitbale replacement, cartridge port in some form will appear on rev.B board
- **Newly designed TV-out circuit** is now based on more recent AD725 chip, providing higher quality output. S-Video output is now supported as well.
- Completely remade board power distribution to avoid need for most of leaky electrolytic capacitors. The rest of them is radial now, due to space and obsolescence concerns.
- **HiFi audio** components used for audio-in and audio-out
- Failing NVRAM chip replaced with more recent DS12885 backed by common replaceable CR1223 coin cell
- External and internal keyboard connectors
- Proprietary Atari 19-pin video connector replaced with common **VGA interface**. Now you can plug your VGA monitor directly, without a need for a convertor.
- Onboard implementation of NetUSB adds **one 10-mbit LAN port and two USB ports** (with number of USB devices currently supported)
- **Fully redesigned base clock system**. Whole universe of overclocking options is now available out of the box.  In example you can double the system clock while keeping CPU base clock, bump the CPU base clock in 8 steps, clock FPU independently, etc. Hard to obtain 32.098488MHz base clock crystal in no longer needed, unless you require 100% compatibility with clock-dependant graphics demos.
- Smaller motherboard footprint, with only 315x225mm outer dimensions
- Four-layer design compared to original six-layer Falcon mainboard for a lower production cost and easier manufacturing
- Optimized track routing to avoid infamous Falcon stability issue and need for different clock patches.
- Many more smaller fixes and changes, too many to name them all.

The F030 will eventually be available as bare/half-way/fully assembled mainboards and add-on cards through centuriontech.eu web shop, or available as a set of instruction, how-to and manufacturing data for DIY enthusiasts.

## Discussion platform:
Now you can discuss about F030NG on Discord: https://discord.gg/jRaXBVc

## Documentation:
Want to get started yourself? Read the [GitHub Wiki](https://github.com/salacpavel/F030NG/wiki)

