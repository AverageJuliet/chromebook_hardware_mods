## Chromebook hardware mods

A repo made for showing off the various mods that can be done to improve the shitty hardware of a google chromebook.

### mod #1: The copper mod

What is the copper mod?  it is a rather simple drop in replacement that gets rid of the trashy thermal pad and replaces it with a copper + thermal paste sandwich.

It provides overall better thermal heat transfer compared to the stock thermal pad at the cost of nothing other than possible sanity loss if you mess it up.

### How to perform it?

step 1. get a flat piece of copper and cut it to the same width as the die (also has to be slightly thinner than the original thermal pad to prevent the board from bending possibly)


step 2. sand it a bit to get rid of rough surfaces/edges.


step 3. place an appropriate amount of thermal paste on both sids of the copper piece and place it on the CPU then put the board back into place making sure the copper is making soild contact with both the CPU and the heatsink/keyboard backplate.
![20240223_200224](https://github.com/AverageJuliet/chromebook_hardware_mods/assets/134985726/772c787e-aad6-45ec-9898-3246fdc46390)
It should look something like this if its cut and sanded correctly.


step 4. screw the board down and close up the unit.


step 5. install the stress package and do stress --cpu 100


step 6. monitor temps to ensure the mod was successful. 
![20240223_201337 (1)](https://github.com/AverageJuliet/chromebook_hardware_mods/assets/134985726/5d735a71-1a4c-4aa0-af0f-8dd669dd2527)
This is an example of the mod performed successfully. 

Also if you have a CB featuring the N4500 or another chip where the iGPU is on a seperate die this guide works as well but you need a longer piece of copper 

