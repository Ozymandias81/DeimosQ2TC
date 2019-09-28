Use the first three arguments to control the frenquency and direction the particles are 
spawned.

First argument controls the direction. 0 is up, 1 is down, 2 is forward. Down-facing
spawners should be placed 8 map units below the ceiling.

The second argument controls the frequency of the spawner. Values are divided by 16,
so you can't get a spawner that spawns every time. This argument is only used if the
third argument is 0.

The third argument prevents it from activating spontaneously, and can only be activated
by the ACS function Thing_Activate. 0 will let it spawn automatically (using the second
argument for frequency), and 1 makes it ACS-only.
