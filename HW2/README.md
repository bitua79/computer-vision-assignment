# Contrast Adjustment - Histogram Equalization

## Overview
This exercise explores histogram equalization and contrast adjustment techniques.

## Exercise Content
#### 2.1. Histogram Equalization
- **2.1.1**: Write a program to compute and plot the histogram of the grayscale Camera Man image using a stem plot.
- **2.1.1.1**: Reduce the brightness by dividing intensity values by 3 (output as D).
- **2.1.1.2**: Plot histograms of the original image and D, and discuss the results.
- **2.1.1.3**: Perform global histogram equalization on D (output as H).
- **2.1.1.4**: Perform local histogram equalization on D (output as L).
- **2.1.1.5**: Plot histograms of H and L, and discuss the difference between global and local equalization.
- **2.1.1.6**: Apply log, inverse log, and power-law transforms to D, and provide results with parameter tuning.

## Photo Sources
The images used for this exercise can be found in the `data` folder:
- **Camera Man Image**: `data/Camera Man.bmp`

## Colab Notebook
The implementation and the output for this exercise can be found in the [Colab Notebook](https://colab.research.google.com/github/bitua79/computer-vision/blob/main/HW2/Vision_HW2.ipynb). 
The notebook covers:
- Histogram computation and display.
- Brightness adjustment and its impact on histograms.

## Instructions to Run
1. Clone this repository and navigate to the folder for this exercise.
2. Open the notebook file (`Vision_HW2.ipynb`) either locally or in Google Colab.
3. Make sure the required images are in the `data` folder, and run the code cells to see the outputs.

## Results and Discussion
The results are provided in the notebook, with visual comparisons of histograms of the image with different intensities.
