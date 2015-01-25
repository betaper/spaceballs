# spaceballs
C64 Demo Effect

WHAT'S THIS ABOUT?
This little project aims at a C64 demo effect. The blueprint idea is as follows. Have a few balls (sprites) 
moving across the screen. The balls get reflected at the screen borders, and when colliding among each other. Basic
physics can be selected, like e.g. 1/r^2 type attractive or repulsive force between the balls, constant force field 
across the screen, friction. The balls get periodically excited by the bass beat (velocity offset) of the music tune.

The whole magic should ideally happen at 50 fps,, i.e. I have to squeeze this stuff into the ~ 20k CPU cycles 
available between two 50 Hz screen rasters. Phew! Well, let's see how far we can get ... My committment for this 
year (2015): 10 lines of (net) machine code instructions per day, on average ;-)

BUILD INSTRUCTIONS
Get a SID file from e.g. HVSC, change filename accordingly in spaceballs.acm, and compile with 'acme spaceballs.acm'
