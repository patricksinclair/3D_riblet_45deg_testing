This will be used to test if we can change the boundary conditions instead of the riblet geometry for the
45 degree crossflow system.

We'll use the following boundary condition modifications:

p:
rightWall - zeroGradient -> uniform 0

U:
leftWall - slip -> zeroGradient
rightWall - slip -> inletOutlet
upperWall - z flow -> z+x flow
