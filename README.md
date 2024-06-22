# dimension1800

USB QMK-compatible PCB for the Siemens 10453443 / KBA-D2911

![2b5b1c4b-f160-424f-aae0-397b622dffc3](https://github.com/taylorswift22/dimension1800/assets/22061508/94618f5a-42b8-4fdb-9834-e0e18c50c6fb)


![3cb45aca-eae0-463b-8944-8dda7efd8b32](https://github.com/taylorswift22/dimension1800/assets/22061508/71a17680-3ffc-4d7b-a1c8-498d9a055146)



## Information

This PCB accepts THT or SMD diodes. It requires either the use of an elite-pi (https://docs.keeb.io/elite-pi-guide) or a Raspberry Pi Pico. The elite-pi is positioned so that when it is soldered correctly, the USB-C port is easily accessible from the back of the PCB. The elite-pi is the recommended MCU for this PCB. The Raspberry Pi Pico is the backup in case the elite-pi becomes no longer available - it is positioned further inside the keyboard, so it would result in a "fixed" cable.

I have not tested the PCB with SMD diodes or the Raspberry Pi Pico. Production files are included for SMD diode assembly at JLCPCB.

The keyboard originally uses a plate and PCB. The recommended configuration for my PCB is fully plateless. However, if you want to cut off the tabs from the bottom of the PCB, it could be used with the original plate. I have not tested this configuration.

## Spacebar Stabilizer

My keyboard is a KBA-D2911**C** with a 7u PBT spacebar with nonstandard stabilizer spacing. You will most likely want to re-use the original spacebar stabilizer wire or make your own. Some other versions appear to have an ABS spacebar - I do not know what the spacing for the ABS spacebars is. The PCB can accept either the standard Cherry 7u spacing or the nonstandard PBT spacebar spacing.

## Elite-Pi soldering

In order for the USB-C port on the elite-pi to be accessible, you must solder the elite-pi away from the PCB like this:

![IMG_20240615_160726](https://github.com/taylorswift22/dimension-PCB/assets/22061508/4c59b271-36fa-4435-825e-fdf1b599cb85)

![DSC03401](https://github.com/taylorswift22/dimension-PCB/assets/22061508/0a84e36f-0fb4-41b7-b86e-02bf23a067df)

## Arrow key position

On my prototype, the arrow keys appeared to be slightly too far up and to the left.

![image](https://github.com/taylorswift22/dimension-PCB/assets/22061508/71f76bc1-6a32-4076-b67d-1b09a6f14d8f)

I have moved the arrow keys down and to the left by 0.25mm in the current version.

## Production files
To order, navigate to dimension-PCB/jlcpcb/production_files and copy what you need. If you choose THT diodes, just upload GERBER-dimension-PCB.zip. The BOM and CPL file are for SMD diode assembly at JLCPCB.
I have 4 prototypes left with the slightly off arrow key position. You can contact me on discord if you wish to purchase one for free + the cost of shipping.

## Firmware
Coming soon.







