# Color

## Overview
This exercise focuses on the concepts of color space conversion and image quantization. Tasks include converting a color image from RGB to HSI format, discussing new color spaces, and implementing uniform quantization techniques on grayscale and color images.

## Exercise Content
#### 6.1. Color Space
- **6.1.1.** Convert Lena to HSI format and display the H, S, and I components separately as grayscale images.
  - **Step 1**: Convert the RGB image to HSI.
  - **Step 2**: Display the H, S, and I components as grayscale images.
  - **Step 3**: Comment on what each component represents in the image.
  
- **6.1.2.** Discuss two new color spaces not introduced in class and provide their application.

#### 6.2. Quantization
- **6.2.1.** Implement uniform quantization for grayscale images:
  - **Step 1**: Read the Lena image as a grayscale array.
  - **Step 2**: Apply quantization with varying levels (L = 64, 32, 16, 8).
  - **Step 3**: Compute the MSE and PSNR between the original and quantized images.
  - **Step 4**: Display the quantized images and comment on the quality for each level.
  
- **6.2.2.** Quantize the RGB components of the Lena image:
  - **Step 1**: Quantize the R, G, and B components to 3, 3, and 2 bits, respectively.
  - **Step 2**: Display the original and quantized color images.
  
- **6.2.3.** Color reduction for Baboon image:
  - **Step 1**: Reduce the number of colors in the Baboon image to 32, 16, and 8 for weaving.
  - **Step 2**: Display the images for each color level.

## Photo Sources
The images used for this exercise can be found in the `data` folder:
- **Lena Image**: `data/Lena.bmp`
- **Baboon Image**: `data/Baboon.bmp`

## Colab Notebook
The implementation and output for this exercise can be found in the [Colab Notebook](https://colab.research.google.com/github/bitua79/computer-vision/blob/main/HW6/Vision_HW6.ipynb). The notebook includes:
- Conversion of Lena to HSI format.
- Display separate H, S, and I components as grayscale images.
- Uniform quantization on grayscale and color images with MSE and PSNR calculations.
- Color reduction for the Baboon image, simulating weaving with a limited color palette.

### 5. Instructions to Run
1. Clone this repository and navigate to the folder for this exercise.
2. Open the notebook file (`Vision_HW6.ipynb`) either locally or in Google Colab.
3. Ensure the required images are in the `data` folder, and run the code cells to see the outputs.

### 6. Results and Discussion
The notebook contains detailed discussions on the effect of quantization on both grayscale and color images. Visual comparisons of original and quantized images are included, along with an analysis of the impact on image quality at different levels of quantization. The HSI components of the Lena image are also explored, offering insights into how color is represented in this space.
