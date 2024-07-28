# Ender 3 Pro - VSW (Work in progress)
![Ender 3 Pro - VSW](Images/Ender3Pro_VSW.png)

This is a conversion based on the original [Ender 3 Pro Switchwire](https://github.com/boubounokefalos/Ender_SW).

Everyone has different needs, and everyone sees different improvements they can make. I want to show my vision for improving this popular budget printer, which includes the following improvements:
- [x] Replacing the toothless GT2 pulley with a gear wheel,
- [ ] Changing the Rasppery Pi mount under version 4 model B,
- [ ] Removal of the cable chain for the Z axis,
- [ ] Redesigning a BLTouch mount in place of the original Switchwire levelling,

The biggest change, however, will be the design of 2 versions of the hotend with:
- [ ] Bowden system,
- [ ] Direct system.

and cooling of the workpiece with air from outside the chamber:
- [ ] Redesigning the chamber.

In the future, I also plan to modify the hotend mount to make it compatible with, for example, the E3D V6, etc.

## Directory structure
| Directory            | Description                                                                        |
|----------------------|------------------------------------------------------------------------------------|
| CAD/                 | Design files in Fusion 360                                                         |
| STEP/                | Design files in STEP format                                                        |
| STL/                 | Design files in STL format                                                         |
| Images/              | Photo of the project in Fusion 360 and the real one after the project is finished  |


## Replacing the toothless GT2 pulley with a gear wheel
A pulley without teeth can deform the belt teeth, which can cause inaccuracies in the hotend's movement in the XYZ axes. The best solution is to use a pulley with teeth matched to a suitable belt, in my case a GT2 belt.

The gears I purchased were larger in diameter than the previous ones, so it was not without modifications to other components in close contact to avoid collisions.

### Y axle tensioner pulley
| Before                                   | After                                  |
|:----------------------------------------:|:--------------------------------------:|
|![Before](Images/Y_axle_pulley_before.png)|![After](Images/Y_axle_pulley_after.png)|