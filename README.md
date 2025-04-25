# ssp
SSP: Simple Spherical Physics is a physics engine designed to be super simple yet versatile, using only spheres

## Idea
Using spheres is easy, as detecting sphere collision is just a distance check between the center of the sphere. Spheres also don't rotate, making the math significantly easier. Using constraints between spheres, complex objects can still be created. For collision with the static environment, Signed Distance Functions (SDF) are used, as these can very easily and accurately describe a complex static environment.

The idea is inspired by tinyphysicsengine.
