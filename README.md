# Kinect 2 Face Database
## Description
A database of data captured by the Microsoft Kinect 2, containing color, IR, and depth data for multiple people sitting in front of the Kinect, showing multiple expressions, and having good and poor illumination scenes.
The cropped faces for the same people will be also included.
## Full Database Structure
Each folder represents a unique identity, where in each one a collection of images and text files representing the color, IR, and depth map are organized.

Color and IR images are saved as png files, while the corresponding depth map is saved in text files.

The files are named in the following format: "data type-time stamp.file type", where 3 files will have the same time stamp representing the color, IR, and depth recorded in that instance.

This database can be downloaded from [here](https://drive.google.com/open?id=0B5xrN4o5hrWrYnhRQnZySm1tVGM).
## Cropped Faces Database Structure
Each folder represents a unique identity, where in each one two folders are created, one called Bright for the data captured while the room light is on and Dark when the room was dark, in each of the previous folders a collection of images representing the color, and the converted depth map as image are organized.

Color images are saved as png files, while the corresponding depth map images are saved as jpg files.

The files are named in the following format: "image ID.file type", where 2 files will have the same image ID representing the color and depth recorded in that instance.
