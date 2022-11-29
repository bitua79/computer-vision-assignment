# Filters

## Overview
This exercise investigates various filtering techniques used in image processing, including box filters, median filters, edge detection, and unsharp masking. The goal is to analyze how these filters affect image quality, noise reduction, and edge detection.

## Exercise Content
#### 3.1. Box Filter
- **3.1.1**: Discuss why box filters are considered poor smoothing filters.
- **3.1.2**: Investigate if applying box filters multiple times improves performance.
- **3.1.3**: Analyze the result of applying a 3 × 3 box filter repeatedly on the grayscale Elaine image.
- **3.1.5**: Determine the optimal mask size for balancing blurring and noise reduction.
- **3.1.6**: Assess the effect of applying a Laplacian mask (`[0 -1 0; -1 5 -1;0 -1 0]`) multiple times.

#### 3.2. Median Filter
- **3.2.1**: Add salt-and-pepper noise to the Elaine image and apply median filtering with various window sizes. Report the MSE for different noise densities.
- **3.2.2**: Add Gaussian noise and apply both averaging and median filters, comparing their effectiveness.

#### 3.3. Sharpening, Blurring, and Noise Removal
- **3.3.1**: Improve the appearance of blurry and noisy images captured in low light, discussing results.

#### 3.4. Edge Detection
- **3.4.1**: Compare first-order difference filters (`𝑎) 1/2 [1 0 −1]`, `𝑏) 1/6 [[1 0 −1] [1 0 −1] [1 0 −1]]`, `𝑐) 1/8 [[1 0 −1] [2 0 −2] [1 0 −1]]`) for edge detection, assessing their suitability for 2-D gradient calculations.

#### 3.5. Unsharp Masking
- **3.5.1**: Implement an unsharp masking filter and compare results for different Gaussian filter sizes and α values.

## Photo Sources
The images used for this exercise can be found in the `data` folder:
- **Elaine Image**: `data/Elaine.bmp`

## Colab Notebook
The full implementation of the exercise, including code and output results, is provided in the [Colab Notebook](https://colab.research.google.com/github/bitua79/computer-vision/blob/main/HW3/Vision_HW3.ipynb). The notebook covers:
- Analysis of box filter characteristics.
- Median filtering experiments with varying noise densities and window sizes.
- Edge detection comparisons using various filters.
- Results from applying unsharp masking.

## Instructions to Run
1. Clone this repository and navigate to the folder for this exercise.
2. Open the notebook file (`Vision_HW3.ipynb`) either locally or in Google Colab.
3. Make sure the required images are in the `data` folder, and run the code cells to see the outputs.

## Results and Discussion
The results from applying various filters, along with discussions on their effectiveness in noise reduction and edge detection, are included in the notebook. 
