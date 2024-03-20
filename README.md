# projectile motion simulation with viscous drag

this python script simulates the projectile motion of an object, taking into account the effects of viscous drag. the simulation uses a numerical method to solve the equations of motion for a projectile under the influence of gravity and air resistance. it calculates the maximum distance achieved by the projectile for different initial speeds and launch angles, and plots the results.

## dependencies

- numpy
- matplotlib

## features

- simulates projectile motion with viscous drag using a numerical method.
- calculates the maximum distance for varying initial speeds and launch angles.
- plots the relationship between initial speed and maximum distance, and initial speed and optimal launch angle.

## usage

1. ensure you have python and the dependencies installed.
2. copy the script into a python file.
3. run the script. no additional input is required.

## code overview

### function: `projectile_motion`

- parameters:
  - `v`: initial speed of the projectile (m/s).
  - `theta`: launch angle of the projectile (radians).
  - `eta`: drag coefficient (default: 0.3).
  - `g`: acceleration due to gravity (m/s^2, default: 9.81).
- returns: the maximum distance achieved by the projectile (m).

this function calculates the projectile's motion, taking into account viscous drag, and returns the maximum distance achieved.

### simulation and plotting

- the script calculates the maximum distance and corresponding launch angle for a range of initial speeds.
- it uses numpy to create arrays of initial speeds and launch angles.
- matplotlib is used to plot the relationship between initial speed and maximum distance, and initial speed and optimal launch angle.

## results

after running the script, two plots will be generated:
- the first plot shows the maximum distance achieved as a function of initial speed.
- the second plot displays the optimal launch angle (in degrees) as a function of initial speed.

## conclusion

this script demonstrates how viscous drag affects the trajectory of a projectile, highlighting the importance of launch angle and initial speed in maximizing the distance achieved.

