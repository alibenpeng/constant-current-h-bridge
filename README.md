This is my first attempt at building a reverse pulse constant current source for
high aspect ratio through hole plating.

The idea is simple: 

It's just two constant current sources controlled by an ATMega328 combined with
an H-Bridge to reverse the current flow direction. Also, it includes a
PWM-output for a servo or BLDC speed controller and a switch-output for an
airpump.

This design is based on parts from my junk bin, so it uses BJTs where other
people would have used FETs. Feel free to modify the design to fit your needs.

License: The latest GPL

