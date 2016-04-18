# cubicam
Android Camera Application for UDOO

This application requires a modified Android source tree, specifically the Freescale HAL2.0 and OV5640 driver, in order to control the sensor. The Android HAL and Linux driver missed the setparameters path as well as zoom etc.

The camera application uses the textureview surface, to enable hardware accelerated zoom.
