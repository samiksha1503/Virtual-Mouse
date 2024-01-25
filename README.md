# Virtual-Mouse
# 🐭 Python Virtual Mouse 🖱️

A simple Python script to simulate a virtual mouse using the `python` library.

## Overview

This project provides a Python script that allows you to control your mouse cursor using keyboard inputs. It's a fun and interactive way to navigate your computer without using a physical mouse.

## Features

- **Easy to Use:** Just run the script, and you're ready to go!
- **Customizable Hotkeys:** Define your own keybindings for mouse movements and clicks.
- **Cross-Platform:** Works on Windows, macOS, and Linux.


# Task 1
Before starting the coding part of the project, we need to classify the entire project into five main steps.
1.	First step is to opening the video camera.
2.	Once the camera is working properly, we need to detect the hand.
3.	From the image captured we need to separate the index finger.
4.	Now we need to move the mouse pointer using the index finger.
5.	Now we need to enable the click operation using the index finger and thumb.

# Task 2
The first process to complete is, opening the video camera. Here we are using Opencv package in Python. Once the video camera is open we need to create the frame for it. 

# Task 3
The second step of the project is to detect hand from the image captured by the camera. In order to do that we use Mediapipe package in Python. Here we are just detecting the hand. Inside mediapipe package we have enough functionalities to identify the landamarks on the hand. That we can utilize in this step.

# Task 4
Once the hand is detected properly, we need to plot the landmarks on the hand. And then from the hand we need to distinguish the index finger. As shown in the hand landmarks image above, we can use numbering for the index finger tip and for the thumb tip also.  For this we are making use of the Mediapipe package in python.

# Task 5
Now we have detected the index finger and the thumb also. The next step is to give the movement of the mouse pointer when the index is moved. Here we are using the index finger tip for moving the mouse pointer. This action can be implemented with the help of a package called as PyautoGUI. With this package we will move the mouse pointer according to the movement of the index finger.
# Task 6
The final step of this project is to give the click action of the mouse. Here we are using the index finger tip and thumb tip to perform click action. When the thumb tip and index finger meet each other it will wok as a click action of the mouse. Here also we using the PyautoGUI package to perform this task.
