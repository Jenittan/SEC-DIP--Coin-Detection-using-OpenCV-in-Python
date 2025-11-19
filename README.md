# Coin Detection Project
## Description

This project detects and counts coins from an input image using OpenCV, Canny Edge Detection, and Contour Detection.
It highlights each detected coin and displays all processing steps such as grayscale conversion, blurring, edge detection, and final detection output.

## Features

Detects coins in an image

Counts coins using contour filtering and circle fitting

Shows intermediate processing stages:

Grayscale image

Blurred image

Edge detection

Final coin detection

Uses OpenCV and Matplotlib for visualization

## Requirements

Install the required libraries:

pip install opencv-python numpy matplotlib

## How to Run

Place your input image (CoinsA.png) in the project folder.

Run the Python script:

python coin_detection.py


The script will:

Print the total number of detected coins

Display all visual steps

Show the final output image with coins marked

## Code Overview

The script performs:

Image loading

Grayscale conversion

Gaussian blurring

Canny edge detection

Contour detection

Filtering small/noise contours

Drawing circles using minEnclosingCircle()

Counting valid coin shapes

The final output displays the detected coins with numbering

## Output

Displays original image

Displays processed steps

Shows detected coins with circles

Prints total coin count in console
