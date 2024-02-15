# Image manipulations using numpy

This Jupyter notebook contains a Python script that allows various manipulations of an image of choice. 
This project is useful for visualizing data in a unique and interesting way.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)


## Features <a name="features"></a>

The notebook includes the following functions:

1. **grid_with_flips**: This function concatenates the given image horizontally multiple times based on the number of repeats and the flip matrix.
2. **create_colorful_big_one**: This function creates a collection of images whereby each image is mapped to a color (red, blue, or green) surrounding the original image.
3. **add_rainbo**: This function adds a rainbow border to an image.
4. **TBD**: This function creates ...

## Installation <a name="installation"></a>

To run this notebook, you need to have Python installed on your machine. You can download Python from [here](https://www.python.org/downloads/).

After installing Python, you need to install Jupyter Notebook. You can do this by running the following command in your terminal:

```bash
pip install notebook
```

You also need to install the required Python libraries, which you can do by running the following command:

```pip install numpy matplotlib```

## Usage <a name="Usage"></a>
To use this notebook, you need to have an image and a matrix. The matrix should contain the colors 'r', 'g', 'b' for Red, Green, and Blue respectively, and 'p1', 'p2', 'p3', 'p4' for the four pieces of the image.

To run the notebook, navigate to the directory containing the notebook file in your terminal and run the following command:

```jupyter notebook```

This will open the Jupyter Notebook interface in your web browser. From there, you can open the notebook and run the cells to create your image.

