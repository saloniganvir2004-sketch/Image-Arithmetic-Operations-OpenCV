# Image Arithmetic Operations using OpenCV

## Project Overview

This project demonstrates fundamental Digital Image Processing arithmetic operations using Python and OpenCV.

It explores pixel-level mathematical operations on grayscale and colour images, including addition, subtraction, multiplication, and weighted blending.

## Implemented Operations

### 1. Image Addition
- Adds two grayscale images using OpenCV.
- Performs pixel-wise addition on colour images.
- Uses cv2.add().

### 2. Image Subtraction
- Subtracts one grayscale image from another.
- Performs pixel-wise subtraction on colour images.
- Uses cv2.subtract().

### 3. Image Multiplication
- Multiplies grayscale images using normalized pixel values.
- Performs multiplication on colour images.
- Uses NumPy for pixel-wise multiplication.

### 4. Image Merging and Blending
- Combines two colour images.
- Uses weighted addition with 50% contribution from each image.
- Implements cv2.addWeighted().

### 5. Image Visualization
- Displays original and processed images.
- Uses Matplotlib for visual comparison.

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## Project Structure

Image-Arithmetic-Operations-OpenCV/
├── Image_Arithmetic_Operations.ipynb
├── README.md
└── requirements.txt

## Execution

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload two input images when prompted.
3. Execute the notebook cells sequentially.
4. Observe the results of addition, subtraction, multiplication, and blending.

