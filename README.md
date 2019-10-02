# Doors-and-levels
It is a console application which prints 5 any numbers including number 0.
User can select any number include number 0. "Select" means that he wants to type number and press enter.

If user select non zero number - game should plot "next level" numbers where numbers values must be calculated using this
formula: [number on previous level] * [choosed number on previous level].
If user select zero value, console application should go to upper level.

Console application should plot numbers on each level.

Example:
We have numbers: 2 4 3 1 0
We select number 2 and go to next level: 4 8 6 2 0 (2x2 4x2 3x2 1x2 0x2)
We select number 4 and go to next level: 16 32 24 12 0 (4x4 8x4 6x4 2x4 0x4)
We select number 0 and go to previous level: 4 8 6 2 0
We select number 0 and go to previous level: 2 4 3 1 0


