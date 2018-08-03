# Bat-Detector
The bat detector takes ultrasonic sound from a source (bat, transmitter, etc) and adds it to a local oscillator.  The combined signal has a beat frequency (intermediate frequency) that is then filter to remove the higher frequencies.  It is currently used with a transmitter to show doppler shift.  The transmitter is mounted on a pendulum that swings towards and away from the detector.
## R7 should be 1.5k&#937; not ~~47k&#937;~~, R9 should be 560 &#937; not ~~1k&#937;~~, and lastly R11 should be 1k&#937; not ~~4.7k&#937;~~
These values work a lot better with this op amp (other values were better for the first one I used)
