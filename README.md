
# Vintage Colorizer


## Objective

To use Python to take old, B&W pictures and render them in color. Why should monochrome dictate important memories from the past?. The purpose of this project is to take black-and-white pictures and imagine what they’d look like if captured today- with color photography.

  
## Problem Statement
You are given a picture of a person or an animal in black-and-white and must add color to it.
## Solution
To let this project semantically colorize black-and-white images, we use Deep Learning and train a Convolutional Neural Network (CNN). In this project, we go about the process of colorizing this way:
* Convert the image from RGB to the Lab color space.
* Use the L channel as grayscale input to the network since it only encodes intensity. Use it to train the network to predict the ‘a’ and ‘b’ channels.
* Combine the input L channel with the predicted ab channels.
* Convert the image from the Lab color space back to RGB.
* We also use tkinter to build a brief GUI to support this project and also provide sample images to try the colorizer on


  
## Tech/framework used:
   - Tkinter
   - OpenCV
   - Deep Learning
