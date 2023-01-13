
Script to automatically setup secondary monitors

Uses xrandr and env variables to determine monitor and positioning

Checks if display is connected using grep to find non-primary output


Gets positioning using env variable MONITOR_POSITION

Arguments:
  default: does nothing
  off: switches off secondary display
  on: switches on secondary display
Get primary display


Script Purpose: Due to my funny kind of setup which is arch linux and an i3WM so when power goes off from the monitor , i automatically can't have access to those workspaces on the monitors, so this script helps me to reset it all back.


See Beautiful Setup that prompted the writing of the script.

![20230111_223229](https://user-images.githubusercontent.com/98170427/212306009-1cf9d040-bffb-4bca-acf8-169d68fb8059.jpg)


