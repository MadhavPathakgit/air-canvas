
# Air Canvas with Machine Learning

This computer vision project leverages OpenCV and Machine Learning using Mediapipe to create an innovative drawing experience using hand gestures.

## Overview

Ever wanted to draw your imagination by just waving your finger in the air? In this project, we will learn to build an **Air Canvas** that allows you to draw anything by simply moving your hands and detecting the landmarks on your knuckles. This is a fascinating project for those interested in machine learning and computer vision.

We will utilize the computer vision techniques provided by OpenCV, with Python as our preferred language due to its extensive libraries and easy-to-use syntax. However, the foundational concepts can be applied in any OpenCV-supported language.

### Project Video
Check out the full explanation in this [YouTube video](https://www.youtube.com/watch?v=T7sjrWc4QEc).

## Algorithm

1. Start reading frames from the camera and convert the captured frames to HSV color space (ideal for color detection).
2. Prepare the canvas frame and place the respective ink buttons on it.
3. Adjust the values of the Mediapipe initialization to detect only one hand.
4. Detect landmarks by passing the RGB frame to the Mediapipe hand detector.
5. Store the coordinates of the forefinger in an array for successive frames (arrays for drawing points on the canvas).
6. Finally, draw the stored points on the frames and the canvas.

## Requirements

Make sure you have the following installed on your system:

- Python 3
- NumPy
- OpenCV
- Mediapipe

## Screenshot
![Air Canvas Example](https://raw.githubusercontent.com/infoaryan/Air-Canvas-with-ML/master/Screenshot%20from%202022-06-16%2019-57-44.png)



