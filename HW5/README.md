# Wavelet Transform
## Overview
This exercise focuses on the concepts of wavelet transforms and pyramid representation, exploring Gaussian and Laplacian pyramids, quantization of wavelet coefficients, and image reconstruction using Haar filters. The tasks include building pyramids, implementing fast smoothing algorithms, and analyzing the impact of different filters.

## Exercise Content
#### 5.1.1. Gaussian and Laplacian Pyramids
- **Step 1**: Build a 5-level Gaussian pyramid for the Mona Lisa image.
- **Step 2**: Construct a Laplacian pyramid based on the Gaussian pyramid.
- **Step 3**: Display and analyze the pyramids.

#### 5.1.2. Fast Gaussian Smoothing Algorithm
- **Step 1**: Describe how separability and cascading aid in Gaussian smoothing.
- **Step 2**: Design a fast algorithm for constructing a 3-step Gaussian pyramid.

#### 5.1.3. Approximation Pyramid Representation
- **Step 1**: Determine the maximum number of levels in an approximation pyramid for an N × N image.
- **Step 2**: Calculate the total number of pixels in the pyramid and compare it to the original image.
- **Step 3**: Discuss the benefits of using an approximation pyramid.

#### 5.1.4. Manual Pyramid Calculation
- **Step 1**: Manually compute a 3-level approximation pyramid using 2x2 averaging for the Lena image.
- **Step 2**: Construct the corresponding prediction residual pyramid.

#### 5.1.5. Wavelet Transform
- **Step 1**: Compute a 3-level wavelet transform using Haar filters for the Lena image.
- **Step 2**: Compare the results with those obtained from Gaussian pyramids.

#### 5.1.6. Quantization and Reconstruction
- **Step 1**: Quantize wavelet coefficients with a step size of γ = 2.
- **Step 2**: Reconstruct the image from quantized coefficients using Haar synthesis.
- **Step 3**: Report PSNR values and discuss the outcomes.

## Photo Sources
The images used for this exercise can be found in the `data` folder:
- **Mona Lisa Image**: `data/mona lisa.bmp`
- **Lena Image**: `data/Lena.bmp`

## Colab Notebook
The implementation and output for this exercise can be found in the [Colab Notebook](https://colab.research.google.com/github/bitua79/computer-vision/blob/main/HW5/Vision_HW5.ipynb). The notebook includes:
- Construction of Gaussian and Laplacian pyramids.
- Fast Gaussian smoothing algorithm implementation.
- Approximation and prediction residual pyramid calculations.
- Wavelet transform implementation and comparisons.

## Instructions to Run
1. Clone this repository and navigate to the folder for this exercise.
2. Open the notebook file (`Vision_HW5.ipynb`) either locally or in Google Colab.
3. Ensure the required images are in the `data` folder, and run the code cells to see the outputs.

## Results and Discussion
The notebook contains detailed discussions on the results of the wavelet transformations and pyramid representations. It includes visual comparisons and analysis of the effects of quantization and different filtering techniques on image quality.
