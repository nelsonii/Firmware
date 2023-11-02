# Firmware
Firmware for Seven Mile Mountain (7MM) Products


By popular request all joysticks and other controllers shipped as of June 2023 allow for easy field firmware updates. This means you can update to the newest code without a lot of hassle. No more sending sticks back to me for reprogramming!

Normally, this is not something you’ll need to do. But sometimes important changes come out (new features, bug fixes) or a user has a custom request which needs the code tweaked to their specific needs (much more common).

Firmware (pre-compiled UF2 files) files are found at: https://github.com/nelsonii/Firmware

Here’s how it works: 
•	Unplug / disconnect your joysticks/controller.
•	Perform the function listed below (it depends on the stick).
o	JoyCon/Palm/Floating Gaming Sticks: Press stick button and hold.
o	Slider: Slide the stick forward (to 12 o’clock) and hold.
o	Nunchuck: Press the “C” button (small round one) and hold.
o	GlidePoint: Touch the sensor at the 12 o’clock position and hold.
•	Plug in the joystick while continuing to press / hold as indicated above.
•	The joystick will flash pink and white for 5 seconds. Keep holding.
•	After 5 seconds, the joystick will reboot and go into programming mode.
•	A new Windows Explorer window will appear, and a new drive will show up. It will be called “QTPY_BOOT”
•	Drag and drop the UF2 firmware file downloaded from Github onto the drive. You do not need to rename it. Just make sure it has the UF2 extension.
•	After the file copy is complete (it is fast) the window will close, and the joystick will reboot automatically.

If you accidentally trigger the firmware update process, or want to abort, simply unplug the joystick and plug it back in. It will revert to its prior state (regular gaming mode).

My naming convention is Type (“Palm”) Mode (“Joystick” “Mouse” etc) and version in Year Letter format (“2023A”). So, if you wanted your JoyCon stick to act like a mouse, look for “JOYCON_MOUSE_2023A.UF2”. Status LED green = joystick, teal = keyboard, blue = mouse.
