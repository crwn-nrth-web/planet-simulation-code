# planet-simulation-code
A real-time, physics-based simulation of our solar system built with Python and Pygame. Planets orbit the Sun using Newtonian gravity. 

## Features

- All 8 planets with accurate masses, radii, and orbital distances
- Gravity calculated using Newton's law of universal gravitation
- Orbit trails drawn in real time
- Zoom in/out controls

# Physics

At each timestep, every planet calculates the gravitational attraction from every other body using Newton's law:

**F = G × m1 × m2 / d²**

Force is split into x and y components and applied to update each planet's velocity and position. 

