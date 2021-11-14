## gp_cp_devel

# Gaussian Processes for circuitpython and micopython

Should run on boards with a rp2040 or nRF52840 chip using circuitpython (therefore micropython should work too). 

It allows the usage of simple 2D gaussian processes for parameter-free applications and mainly relys on ulab. If your microcontroller is able to handle the process depends on your data and mainly on the parametrization of your gaussian process. In general, it is recommended to avoid borderline cases.

Examples and working .py-scripts can be found in the examples folder (tested on adafruit feather nRF52840 bluefruit sense and adafruit feather rp2040).

**TO DO**

- add/implement additional kernel functions
- not sure but maybe 3D processes are possible (check ulab maximum number of dimensions)


**GOAL**

Bring something you might call creativity to small devices.
