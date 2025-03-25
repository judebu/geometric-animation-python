# Geometric Animation in Python

This project implements a simple animated scene using geometric transformations in Python. It includes perspective projection, rotation, translation, and rolling motion for objects in a scene.

## Features
- **Perspective Projection:** Adds depth to the scene.
- **Object Rotation:** Rotates a house around the Y-axis.
- **Translation:** Moves a ball across the scene.
- **Rolling Motion:** Simulates natural rolling of the ball.

## Installation
Ensure you have Python and the necessary libraries installed:

```bash
pip install numpy matplotlib

## Setup and Running the Project

To test your setup, run:

```bash
python hwk07-initial.py

To run each animation step, use the following commands:
python hwk07-1.py  # Perspective projection
python hwk07-2.py  # House rotation
python hwk07-3.py  # Ball translation
python hwk07-4.py  # Ball rolling

Technical Details
This project applies linear transformations using 4×4 homogeneous matrices:
Projection Matrix (project(d)) – Creates depth effect.
Rotation Matrix (rotate(x, y, z)) – Rotates objects around axes.
Translation Matrix (moveTo(start, end)) – Moves objects.
