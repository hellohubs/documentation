# Server / CPU

This section takes you through the process of fixing problems with the server (the system). If the Hello Hub is off for an unknown reason, start with [troubleshooting and restarting the power system](power.md). If the problem is only with one user terminal, and the other is operating properly, [troubleshooting the top box / user terminal](topbox.md) is probably the place to start.

The steps below assume the system is off on both screens and there is no wifi access.

## Checking the System State

There are a number of ways to check the system state. Begin by doing a visual inspection of both user terminals, the top boxes, the keyboards & monitors, and inside the server box.

Look for:

* Obvious damage to any of the equipment or cables
* Disconnected cables or cables connected incorrectly.
* Any evidence of burned out components (that could indicate an electrical short.

Fix or replace any damaged equipment found.

## Starting the system

### Check for power and turn system off

After you open the system, check the LED on the power supply. If it is blinking steadily, and the system fan is off, then the system is off. If the led is on and the system fan is also on, then the system has been turned on. If the system is on, but neither user terminal is working (and the top box power is confirmed working) then proceed to power the system off.

To power off the system, hold down the system power button (bottom left of the motherboard mount) briefly. If the system doesn't stop within 1 minute, you can perform a hard system off by holding the system power button down for around 8 seconds (or until the system fan turns off).

### Turn top boxes on

Prior to turning on the system, make sure that the top boxes are powered on. This will allow you to view the boot-up messages and fix any system issues needed at boot.

### Turn the system on

Press the system power button (bottom left of the motherboard mount) briefly to turn the server on. The power supply LED will stop blinking and turn on solid, and the system fan will turn on.

### Booting

After turning the power on, the system will attempt to boot. One of the user terminals will display the BIOS messages (mostly text) and then the Edubuntu system will start. You may see a light colored screen with "Edubuntu" displayed on it. That is a good sign that the system is starting. Depending on system checks, the booting process could take up to 5 minutes to start.

IMPORTANT NOTE: Do not press any keys on the keyboard while the system is booting, pressing keys may stop the boot process completely and you will have to start over.

### Disk Checks

If the system displays a message about the disk checking, it could ask to press "F" to attempt to check and fix the filesystem or checks. This is safe to do and you should press the "F" key on the keyboard on the terminal that is displaying the message. In some cases, the system may be confused about which keyboard is connected to which monitor, so you may have to press the "F" key on the other keyboard (confusing!) 