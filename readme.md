# Image to Pencil Sketch with Python
#3 Overview
Welcome to the Image to Pencil Sketch project! This repository contains Python code for converting digital images into pencil sketch-like representations. The project utilizes various image processing techniques and libraries to achieve the transformation.

## Image to Pencil Sketch Conversion
The main goal of this project is to take input images and produce pencil sketch-like versions of them. The conversion process involves simulating the look of a pencil sketch by applying techniques that enhance edges and reduce color information while preserving important details.

## How It Works
The image-to-pencil-sketch conversion process can be summarized in the following steps:

## Read the Image: Load the input image using an image processing library.
Gray Scaling: Convert the image to grayscale to remove color information and simplify the image.
Invert the Image: Invert the grayscale image to produce a negative image.
Blur the Image: Apply Gaussian blurring to the negative image to smoothen it and reduce noise.
Blend Images: Blend the grayscale image and the blurred negative image to create the pencil sketch effect.
Project Structure
examples/: This directory contains example input images and their corresponding pencil sketch outputs.
notebooks/: Jupyter notebooks for experimentation and demonstration purposes.
src/: Python scripts containing the image-to-pencil-sketch conversion code.
requirements.txt: A list of required Python libraries for this project.
## Usage
To use the image-to-pencil-sketch conversion code, ensure you have Python and the required libraries installed. You can install the necessary libraries using the requirements.txt file:

## bash
Copy code
pip install -r requirements.txt
After installing the required libraries, you can use the Python scripts in the src/ directory to convert your own images into pencil sketches. You can also explore the Jupyter notebooks in the notebooks/ directory to see the conversion process step-by-step.

## Examples
The examples/ directory contains sample input images along with their corresponding pencil sketch outputs generated by the provided code. Feel free to use these examples to get a sense of how the conversion works.

## Contributions
Contributions to this project are welcome. If you discover any issues or have ideas for improvements, please open an issue or submit a pull request.

## Acknowledgments
This project was inspired by various image processing techniques and tutorials available online. Special thanks to the open-source community for providing valuable resources and libraries.

