# 3D Ballistics Simulator

A team-built interactive ballistics simulator written in C++ with openFrameworks. It demonstrates the implementation of a small 3D physics engine rather than relying entirely on an existing engine's physics layer.

## What it demonstrates

- Custom vector, matrix, and quaternion mathematics
- Particle and rigid-body simulation
- Gravity, spring, and friction force generators
- Collision detection and response
- Bounding volumes and octree spatial partitioning
- First-person camera, lighting, and real-time interaction
- Tests for core mathematical primitives

## Technical approach

The simulation separates the world, rigid bodies, force generators, collision system, and rendering layer. An octree reduces the collision-search space, while custom integration and mathematical primitives make the underlying physics explicit in the codebase.

## Tech stack

C++ · openFrameworks · Visual Studio · real-time 3D rendering

## Run locally

1. Install openFrameworks for Visual Studio on Windows.
2. Place the project in an openFrameworks `apps` directory, or update `OF_ROOT` in Visual Studio.
3. Open `myRelentlessSketch.sln`, then build and run the project.

## Team

Developed by Hugo Brisset, Alexandre Bélisle-Huard, Albin Horlaville, and Alan Fresco.
