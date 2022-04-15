# raspberrypi-steppermotor-28BYJ-48
Code & Wiring Diagram to control the 28BYJ-48 5VDC Stepper Motor with RaspberryPi 3b+ via Stepper Motor Driver Module.

python motordeg.py [step_time] [degrees] [direction] [step_start]

step_time: 1 for fastest possible rotation - only works when using half steps (8)
           needs at least 2 when working with full steps (4)

degrees: rotation in degrees (doubles when using only full steps)

direction: cw for clockwise, ccw for counter clockwise

step_start: only required for multiple high-precision rotations

Example would be.. within terminal and within the directory of where the py file is.
python motordeg.py 2 50 cw
This would mean the motor would turn counterwise for 50 degrees at speed 2. (The lower the speed the quicker it will turn.)


