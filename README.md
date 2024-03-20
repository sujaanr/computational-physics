# Projectile Motion Simulation with Viscous Drag

This Python script simulates the projectile motion of an object, taking into account the effects of viscous drag. The simulation uses a numerical method to solve the equations of motion for a projectile under the influence of gravity and air resistance. It calculates the maximum distance achieved by the projectile for different initial speeds and launch angles, and plots the results.

## Dependencies

- numpy
- matplotlib

## Features

- Simulates projectile motion with viscous drag using a numerical method.
- Calculates the maximum distance for varying initial speeds and launch angles.
- Plots the relationship between initial speed and maximum distance, and initial speed and optimal launch angle.

## Usage

1. Ensure you have Python and the dependencies installed.
2. Copy the script into a Python file.
3. Run the script. No additional input is required.

## Code Overview

### Function: `projectile_motion`

- Parameters:
  - `v`: Initial speed of the projectile (m/s).
  - `theta`: Launch angle of the projectile (radians).
  - `eta`: Drag coefficient (default: 0.3).
  - `g`: Acceleration due to gravity (m/s^2, default: 9.81).
- Returns: The maximum distance achieved by the projectile (m).

This function calculates the projectile's motion, taking into account viscous drag, and returns the maximum distance achieved.

### Simulation and Plotting

- The script calculates the maximum distance and corresponding launch angle for a range of initial speeds.
- It uses numpy to create arrays of initial speeds and launch angles.
- Matplotlib is used to plot the relationship between initial speed and maximum distance, and initial speed and optimal launch angle.

## Results

After running the script, two plots will be generated:
- The first plot shows the maximum distance achieved as a function of initial speed.
- The second plot displays the optimal launch angle (in degrees) as a function of initial speed.

## Conclusion

This script demonstrates how viscous drag affects the trajectory of a projectile, highlighting the importance of launch angle and initial speed in maximizing the distance achieved.

