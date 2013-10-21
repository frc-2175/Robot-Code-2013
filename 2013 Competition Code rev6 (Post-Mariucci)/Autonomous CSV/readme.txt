Files created here should be in .csv format. All files should have a heading row at the top that reads:
step,param,drive,steering,spatula,shooter,fire,comments

The step conditions are as follows:
0. No condition
1. ms delay
2. Left drive encoder distance above value
3. Left drive encoder distance below value
4. Spatula down
5. Spatula up
6. Plunger not extended
7. Plunger extended
8. Frisbee switch pressed
9. Frisbee switch not pressed
10. Detected rectangle at height



SOME HELPFUL HINTS:

The left encoder should read 1.41' for a 90° turn. It should read 2.81' for a 180° turn. The full circumference distance for spinning in place is 5.63'.
The robot dimensions are 24" x 30".