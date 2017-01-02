# linuxcnc-iot
Hooks and Scipts for enabling linuxcnc to publish to IOT channels

# Setup
0. I am using the [Adafruit IO beta REST API](http://io.adafruit.com).  Adjust for your endpoint and IOT provider API.
1. Add the project directory to your user PYTHONPATH to rip-environment PYTHONPATH.
2. Add the iot-hal file to your postgui hal file.  I intend to find a different way to do this later.
3. Start hal.

# Misc
Right now I'm just wiring halui.program.is-running to the iot.is-running.  It should at least demonstrate a simple way to watch the HAL and send messages based on various pins / signals available in your hal.

We'll see where this goes...
