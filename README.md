# spotmicrolam
SportMicroAI the lean and mean edition.
The design is inspired by MicroSpotAI but developed from scratch.
![Logo](/images/sma_lam_1.png)

## Design goals of the project:
* Sheap, under 500e, ideally towards 300e
* Off the shelf components and 3D printed parts only
* bldc motors

## Challenges:
At the moment the biggest challenge are the motor drivers.  There are plenty of cheap brushless motors for aircrafts, and they should work fine.  
The ESC however are geared towards flying, they offer no reverse rotation or holding torque.  Finding the right ESCs and controlling them is an interesing excersize. 

## Key Ingredients
* 5010 BLDC motors, ~14e per piece
* Some bldc driver ~10e per piece if i can make HMBGC work, may need something else for more current
* Rotary encoder, at the moment AS5600, readymade module (~2e a piece)
* Bearings, pulleys, belts, shafts etc. under 30e per leg
* Carbon fiber pipes for body structure ~40e
* Raspberry Pi or Orange Pi for the brain ~40e

So, 26e (per motor) x 12 = 312
30e (per leg) x 4 = 120

