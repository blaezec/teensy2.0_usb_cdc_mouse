This is a combination of the teensy 2.0 usb_Serial example (https://www.pjrc.com/teensy/usb_serial.html), and the usb_Mouse example (https://www.pjrc.com/teensy/usb_mouse.html).
I had some code for a USB button box that uses C + Makefile, and I wanted to add the ability to twiddle the mouse from the button box, mainly to keep the display of the host PC from going to sleep during long button box sessions.

The demonstation works exactly as the usb_Serial example on the teensy web site, except that you can now send an 'm' to it and it will twiddle the mouse in a square for a few seconds.
