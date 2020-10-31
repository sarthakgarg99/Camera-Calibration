# Assignment 1 (Camera Calibration) [![Maintenance](https://img.shields.io/badge/Python-3.7.x-brightgreen.svg)](https://www.python.org)

This project contains a python code which is used to perform calibration of a camera using an input image provided with the project. A report is also included which explains the calculation behind the code. The code is well commented and contains the following functions:

  - **normalise**: Function that performs homogenization and normarlisation and return T and U which will be used for denormalisation
  - **denormalise**: Function to perform denormalisation on projection matrix. It takes T and U as input 
  - **DLT**: Function to perform DLT on normalised coordinate to return normalised Projection matrix
  - **intrinsic**: Function to calculate intrinsic parameters simple formulae used mentioned in the report
  - **extrinsic**: Function to calculate intrinsic parameters simple formulae used mentioned in the report
  - **ResizeWithAspectRatio**: Function used to resize the image window
  
# Installation

Our project use two python libraries:
- **numpy**: For performing matrix caluculations
- **open cv**: For displaying image and taking input from user
```sh
$ pip install opencv-python-headless
$ pip install numpy
```

To run the code

```sh
$ python3 assignment.py
```

# References
[1] https://stackoverflow.com/questions/35180764/opencv-python-image-too-big-to-display
[2]  https://www.geeksforgeeks.org/displaying-the-coordinates-of-the-points-clicked-on-the-image-using-python-opencv/

# Contributers
- Varun Gupta (2017EE30551)
- Sarthak Garg (2017EE30546)