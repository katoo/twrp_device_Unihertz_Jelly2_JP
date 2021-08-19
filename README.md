Device configuration for Unihertz Jelly2 JP
===========================================

# Still doesn't work
* boot: OK
* adb shell: OK
* mount system partition: manually OK
* mount data partition: can"t decrypt
* GUI: loops splash screen until to mount system partition manually
* TouchScreen: doesn't work

This region device tree is intended for a special usage in a TWRP or similar environment.

If you are looking for a special device tree for the usage in a LineageOS or similar environment head over to https://github.com/Meetoul/android_device_Unihertz_Jelly2.

The Unihertz Jelly2 (codenamed simply _"Jelly2"_) is a smallest modern Android smartphone from Unihertz, released in March 1, 2021.

![](https://github.com/Meetoul/twrp_device_Unihertz_Jelly2/blob/master/docs/images/jelly2.png)

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core                                                                                                                      |
| Chipset                 | Mediatek Helio P60                                                                                                             |
| GPU                     | Mali-G72 MP3                                                                                                                   |
| Memory                  | 6 GB RAM                                                                                                                       |
| Shipped Android Version | 10                                                                                                                             |
| Storage                 | 128 GB                                                                                                                         |
| Battery                 | Non-removable Li-Po 2000 mAh battery                                                                                           |
| Display                 | 480x854 pixels, 3.0 inch                                                                                                       |
| Camera (Rear - Main)    | 16MP                                                                                                                           |
| Camera (Front)          | 8MP                                                                                                                            |

# Dependencies

Additionally to this region device tree, you'll need the common device tree

- [Jelly2](https://github.com/Meetoul/twrp_device_Unihertz_Jelly2)

## Documentations

- [HOW-TO-BUILD.md](https://github.com/katoo/twrp_device_Unihertz_Jelly2_JP/blob/master/docs/HOW-TO-BUILD.md) - Building instructions for TWRP.
- [HOW-TO-INSTALL.md](https://github.com/Meetoul/twrp_device_Unihertz_Jelly2/blob/master/docs/HOW-TO-INSTALL.md) - Installation instructions for the Jelly2.
- [HOW-TO-UPDATE.md](https://github.com/Meetoul/twrp_device_Unihertz_Jelly2/blob/master/docs/HOW-TO-UPDATE.md) - Update instructions for the Jelly2.
- [HOW-TO-EXTRACT-FILES.md](https://github.com/Meetoul/twrp_device_Unihertz_Jelly2/blob/master/docs/HOW-TO-EXTRACT-FILES.md) - Instructions to extract files directly from the Jelly2 stock ROM files.
- [HOW-TO-PATCH.md](https://github.com/Meetoul/twrp_device_Unihertz_Jelly2/blob/master/docs/HOW-TO-PATCH.md) - Patching the prebuilt kernel to activate touchscreen in recovery mode.

## Special Thanks To

- [Meetoul](https://github.com/Meetoul) - I used his [Jelly2_TEE device tree](https://github.com/Meetoul/twrp_device_Unihertz_Jelly2_TEE) as a base for this one. Phones are almost identical, so device trees are almost identical as well.
