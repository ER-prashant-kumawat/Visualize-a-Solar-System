# Visualize-a-Solar-System
Visualize a Solar System


Planet Simulation Using Python Turtle
This project simulates the movement of planets around the Sun using Python's turtle graphics library. Each planet follows an elliptical orbit around the Sun, and their positions are updated in real time.

Prerequisites
Python 3.x
Turtle Graphics Library (comes pre-installed with Python)
Files
Python Script: This is the main script that initializes the Turtle window, creates planets with specified characteristics (name, radius, and color), and simulates their movement around the Sun.
Features
The Sun is represented as a yellow circle at the center of the screen.
The planets orbit around the Sun in circular paths.
The planets have different radii and colors, making each unique.
The movement of the planets is updated continuously.
How It Works
Turtle Setup: The turtle.Screen() and turtle.Turtle() functions are used to set up the screen and create turtle objects.
Planet Class: A custom class Planet is defined, which inherits from turtle.Turtle(). Each planet has:
A name, radius, and color.
A move() method that calculates the planet's new position using trigonometric functions (cos and sin).
Main Loop: The planets' positions are updated in an infinite loop, and the angle of their orbit increases gradually.
Steps to Run
Make sure you have Python 3.x installed on your system.
Copy the code provided into a Python file (e.g., planet_simulation.py).
Run the script:
bash
Copy code
python planet_simulation.py
A window will open showing the Sun at the center and the planets orbiting around it. The planets will keep moving around the Sun.
Customization
You can easily adjust the simulation:

Planet Size and Color: Modify the parameters when creating each Planet object to change the size (radius) and color of the planets.
Speed of Orbit: The speed of the planets' movement can be adjusted by changing the increment values for angle in the while loop (e.g., 0.05, 0.03, etc.).
More Planets: You can add more planets by creating new instances of the Planet class and adding them to the myList.
Example
python
Copy code
# Example of creating a new planet
new_planet = Planet("New Planet", 300, 'purple')
myList.append(new_planet)
License
This project is licensed under the MIT License.
