# stack-light

I've decided to build my own in my spare time,
for integration with a CI/CD system (and for a friend who needs an "on-air indicator") ;)


### 3D print

The 3D files are from Thingiverse, designed by Ryal Deveau:
[https://www.thingiverse.com/thing:4268994](https://www.thingiverse.com/thing:4268994)
```
"Industrial" Led Stack Light
by Loocpac is licensed under the Creative Commons - Attribution license.
```

I've decided to print the lenses in transparent PET-G and the base elements in black PET-G
to take full advantage of the RGB. White PET-G would've probably been better for brightness,
but I had none on hand and black looks better.

2023-11-06 - `FIrst version failed, concentric walls with concentric infill does not play well :<`



### Hardware

I've decided to use adressable RGB LEDs and some microntroller depending on what I can find
in my drawers. It should preferably have Wi-Fi and be able to power 3 stacklights without an
additional external power supply (besides the one on the board).

### Software

TBD, probably custom based on [WLED by Aircookie](https://github.com/Aircoookie/WLED)
