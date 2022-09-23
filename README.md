# Script to automatically setup secondary monitors
# Uses xrandr and env variables to determine monitor and positioning
# Checks if display is connected using grep to find non-primary output
# Gets positioning using env variable MONITOR_POSITION
# Arguments:
#   default: does nothing
#   off: switches off secondary display
#   on: switches on secondary display
# Get primary display
