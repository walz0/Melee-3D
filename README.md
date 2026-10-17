# Super Smash Bros. Melee 3D
Nintendo's all-stars fight their way into the third dimension!

## 3D Stage List
- Final Destination
- Pokemon Stadium
- Yoshi's Story
- Fountain of Dreams
- Dreamland N64
- Green Greens
- Yoshis Island
- Mute City
- Onett

## How To Play
- Your character moves in the direction you point the control stick.
- All attacks are 'forward' inputs by default, use the Throttle to input up or down!
- The Throttle is bound to R by default but can be changed on the character select screen by pressing L or R.
- Throttle does a slight down input (crouch) by default so a down special can be
performed by hitting Throttle + B.
- Holding the Throttle while recovering will automatically point your up special trajectory toward the ledge!
- Releasing the Throttle before your up special comes out will allow you to aim your recovery in the direction you point the control stick
- Non-Throttled recoveries automatically send the player diagonally upward but can be controlled by moving the C stick up and down!
- Moves like Ness's grounded up special and neutral special can be steered in 3D using the control stick to drive the horizontal axis and the C stick to drive the vertical axis

## WARNING!!!
It is recommended to only use the default Slippi gecko codes when playing through
Slippi Online. Use of other gecko codes may cause desyncs and should be used at your
own risk!

## Requirements
- A legally obtained and *unmodified* copy of a Super Smash Bros. Melee NTSC 1.02 ISO. If the ISO is not vanilla (MD5 0e63d4223b01d9aba596259dc155a174) the patch will fail!

## How To Compile the ISO on Windows
- Simply drag your *Vanilla 1.02 SSBM ISO* onto the .bat file included. The .iso will be placed in the same folder and be named "Super Smash Bros. Melee 3D.iso".

### Common Issues
1) "xdelta3: target window checksum mismatch: XD3_INVALID_INPUT" 
    - You did not provide a valid, unmodified 1.02 NTSC SSBM .iso

2) "xdelta3: file open failed: read: Super Smash Bros. Melee 3D.iso: The system cannot find the file specified."
    - You clicked the .bat file instead of dragging the iso onto the .bat file.

## How To Compile the ISO on MacOS
Open the MulitPatch application included in the zip in the Mac folder.

1) For the first field, browse to "patch.xdelta" in the "Melee3D-Slippi" folder.

2) For the second field, browse to the your unmodified v1.02 NTSC Melee ISO.

3) For the third field, browse to the location you want the newly created Melee 3D ISO to be placed.

4) Lastly, click apply patch.

## How To Compile the ISO on Linux
1.) Install xdelta:
    a) on Debian based distros: sudo apt install xdelta3
    b) on Arch based distros: sudo pacman -S xdelta3
    c) on Fedora/CentOS/Suse: dnf install xdelta
    d) Other: Check your package manager for an xdelta/xdelta3 package
2.) Open a Terminal and issue the command

```
xdelta3 -dfs path/to/vanillassbm path/to/patch.xdelta path/to/patchediso.iso
```

Replace the paths accordingly. The last path will be the destination of the resulting iso. After 1-2 minutes, it will create an iso in the path specified.

### Troubleshooting:

xdelta errors: 
1) Make sure your vanilla .iso is not compressed. If it is, you need to decompress it.
 This can be done via your graphical file browser(for example nautilus in gnome or dolphin in KDE) or in the terminal using unzip/tar.

2) Make sure your vanilla .iso has the correct MD5 hash. You can check that by typing

    md5sum path/to/ssbm.iso

 in a terminal, using the path to your .iso file. It will calculate the MD5 Checksum for you. It should match:

 0e63d4223b01d9aba596259dc155a174.

If it does not you either have the wrong version of melee or an "unclean" one.

---
Credit: UnclePunch, Quad for the ISO builder