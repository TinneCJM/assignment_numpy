# Image manipulations using numpy

This reposititory contains a jupyter notebook contains python scripts that allows various manipulations of an image of choice. 
This project is useful for when you are bored and want to pass time in a unique and interesting way.

## Table of Contents

- [Image manipulations using numpy](#image-manipulations-using-numpy)
  - [Table of Contents](#table-of-contents)
  - [Features ](#features-)
  - [Installation ](#installation-)
  - [Usage ](#usage-)
  - [Examples ](#examples-)


## Features <a name="features"></a>

The notebook includes the following functions:

1. **grid_with_flips**: This function concatenates the given image horizontally and vertically multiple times with rotations based on the number of repeats and the flip matrix.
2. **create_colorful_big_one**: This function creates a collection of images whereby each image is mapped to a color (red, blue, or green). These color images then create a clockwise border surrounding the original image.
3. **add_rainbow**: This function adds a rainbow border to the image.
4. **rainbowify_image**: This function blends the image together with a rainbow gradient.

## Installation <a name="installation"></a>

To run this notebook, you need to have Python installed on your machine. You can download Python from [here](https://www.python.org/downloads/).

After installing Python, you can install the required Python libraries by importing the environment.yaml file in Anaconda Navigator. Within the installed environment, jupyter notebook will need to be installed.


## Usage <a name="Usage"></a>

To run the notebook, navigate to the directory containing the notebook file in your terminal and run the following command:

```jupyter notebook Assignment_notebook.ipynb```

This will open the Jupyter Notebook. From there, you can open the notebook and run the cells to perform your image manipulations.

Load your image of choice. This can be done by saving your image in the data/input directory. If another image is used besides the default, adjust gekkie.jpeg in the second cell to the name of your image. Alternatively, the image manipulations will default to a lovely dog called Gekkie. Fun fact, Gekkie was the brewer's dog of Under The Radar Brewery in Houston, Texas, USA!

1. **grid_with_flips**: This functions requires an image of choice and an input matrix that indicates which flips should be perfomed. Flips are assigned with integers 0, 1, 2 and 3, indicating normal, mirrored, upside down and upside down mirrored respectively. The matrix should contain rows of equal lenght. A default image and matrix is provided if no inputs are specified.

2. **create_colorful_big_one**: This function requires an image of choice and an input list containing 12 colors indicated by 'r', 'b' or 'g' refering to red, blue and green respectively. A default image and color list is provided if no inputs are specified.

3. **add_rainbow**: This function requires and image of choice and a border thickness. A default image and border thickness is provided if no inputs are specified. Border thickness should not exceed 1000. Why? I didn't find it pretty.

4. **rainbowify_image**: This function requires an image of choice. A default image is provided if no input is specified.

## Examples <a name="examples"></a>

```grid_with_flips(np_image,[[j for i in range(7)] for j in range(4)])```

```create_colorful_big_one(['r', 'b', 'g', 'b', 'r', 'r', 'g', 'r', 'b', 'g', 'r', 'r'])```

```add_rainbow(np_image,20)```

```rainbowify_image(np_image)```