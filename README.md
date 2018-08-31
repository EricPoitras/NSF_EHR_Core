# NSF_EHR_Core

Design Revisions for Next Version

Soldering of the connectors of the sensor to cables should be the first priority - intermittent connectivity issues causes failures for calibration of the sensor. 

Conclusion

The sensor should be flat (horizontaly) relative to a table surface when the bone is resting in place and immobile to enable calibration of the sensor. The connectors are the following (verified for Arduino Mega):

5V to VCC
GND to GND
SCL21 to SCL
SDA20 to SDA

with ic2 connection to 68

Run a scan for ic2 to confirm on a new board
Install the code and reset (turn on and off the power) to calibrate multiple times
Watch results on the serial monitor
