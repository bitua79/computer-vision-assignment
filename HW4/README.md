# Frequency Domain

## Overview
This exercise focuses on applying the Discrete Fourier Transform (DFT) to perform linear convolution and frequency domain filtering on grayscale images.

## Exercise Content

#### 4.2.1. Linear Convolution using DFT
- **Step 1**: Use the DFT function to compute the linear convolution of a 256 × 256 image with an 11 × 11 filter.
- **Step 2**: Explain the required DFT size to achieve convolution.
- **Step 3**: Analyze the convolution output and determine for which values of (𝑚, 𝑛) the result matches the expected output.

#### 4.2.2. Frequency Domain Filtering
- **Step 1**: Perform a 2D DFT on the grayscale Barbara image.
- **Step 2**: Zero out specific DFT coefficients for low-pass filtering with thresholds 𝑇 = 1/4 and 𝑇 = 1/8.
- **Step 3**: Apply custom filters by zeroing out coefficients in different frequency regions.
- **Step 4**: Perform inverse DFT to obtain the filtered image, and display the original and filtered images.

## Photo Sources
The images used for this exercise can be found in the `data` folder:
- **Baboon Image**: `data/Baboon.bmp`
- **Barbara Image**: `data/Barbara.bmp`
- **Lena Image**: `data/Lena.bmp`

## Colab Notebook
The implementation and output for this exercise can be found in the [Colab Notebook](https://colab.research.google.com/github/bitua79/computer-vision/blob/main/HW4/Vision_HW4.ipynb). The notebook includes:
- Linear convolution using DFT for a 256 × 256 image.
- Zeroing out DFT coefficients to apply low-pass and custom filters.
- Comparison of original and filtered images.
- Discussions on the effects of the applied filters.

## Instructions to Run
1. Clone this repository and navigate to the folder for this exercise.
2. Open the notebook file (`Vision_HW4.ipynb`) either locally or in Google Colab.
3. Ensure the required images are in the `data` folder, and run the code cells to see the outputs.

## Results and Discussion
The notebook contains detailed discussions on the effect of different DFT-based filters. It includes visual comparisons of the original and processed images, showcasing the impact of filtering in the frequency domain.
