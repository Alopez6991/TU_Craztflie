# Flashing Firmware

## install crazyflie-firmware from git
## Flash crazyflie
in the terminal run the below
* ` cd crazyflie-firmware`
* `make clean`
* `make cf21bl_defconfig`
* `make`
* set the drone in config mode (press and hold power for 3 seconds till two blinking blue lights)
* `make cload`

## Flash an app to crazyflie
navigate to the location of the app you want to flash i.e.
* `cd /crazyflie-firmware/examples/app_hello_world/`
* `make clean`
* `make cf21bl_defconfig`
* `make`
* set the drone in config mode (press and hold power for 3 seconds till two blinking blue lights)
* `make cload`

# setting the switches on your RC controller to activate comands

## update script crtp_commander_generic.c
* copy and past flie crtp_commander_generic.c over your file

