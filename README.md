# Auto-Reverser-DCC
ACS712-based sensor for short-circuit detection and track polarity reverser

This circuit and the software included take care of DCC track polarity reversal upon short circuit detection.

The reaction speed, from detection until polarity reverse command, is approx. 2 microseconds (measured with an AtMega328 at 16MHz)! Therefor it beats every short-circuit and overload detection including the DCC-EX Command Station.

Its creation is linked to a conversation on Train Board where an issue was raised on the control of turntable track polarity control:
https://www.trainboard.com/highball/index.php?threads/turntable-controller-finalised-project-proposed.154256/page-4

This circuit can also be used for reversing track polarity control or where ever DCC track polarity requires reversal control.

The program makes use of ACS712.h library created by Rob Tillaert.

The switching relay is an Omron G6S-2 5VDC type.

![ACS712](https://github.com/Erik84750/Auto-Reverser-DCC/assets/20128852/e95ff3a0-db89-4341-a467-8d4ad5d98f4b)


![Omron_G6S-2_5VDC](https://github.com/Erik84750/Auto-Reverser-DCC/assets/20128852/4e6ae6d1-0a37-4376-94b5-8236774471b1)
