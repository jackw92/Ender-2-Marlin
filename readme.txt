Copy/paste extracted "Marlin" file into a fresh copy of Marlin 2.0.x - https://marlinfw.org/meta/download/

Sensor location is set up for this BLTouch mount - https://www.thingiverse.com/thing:3148733
 If using a different mount update NOZZLE_TO_PROBE_OFFSET value.

Copy auto0.g to SD card - BLTouch sometimes errors without being actuated before homing, so the auto0 file does this.

Due to a hardware fault with my MKS Gens 1.4, I wired the BLTouch to Z+, changing pin 18 to pin 19 within src>pins>ramps>pins_RAMPS.

Check for EEPROM errors after flashing.