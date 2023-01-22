# Features

## Overview
This exercise focuses on extracting interest points using the Harris Corner detector and performing scene stitching using SIFT/SURF features. The tasks include implementing and applying the Harris Corner detector across different scales and using SIFT/SURF to match and align features between images for scene stitching.

## Exercise Content
#### 7.1. Harris Corner Detector
- **7.1.1.** Implement and apply the Harris Corner detector for interest point extraction at multiple scales:
  - **Step 1**: Implement the Harris Corner detector.
  - **Step 2**: Apply the detector to the `harris.jpg` image at a minimum of 4 scales.
  - **Step 3**: Observe and analyze the interest points detected across all scales.
  
#### 7.2. Scene Stitching with SIFT/SURF
- **7.2.1.** Use SIFT or SURF to establish correspondences between images:
  - **Step 1**: Use the OpenCV, Python, and MATLAB implementation of the SIFT/SURF operator to extract interest points from `sl.jpg`, `sm.jpg`, and `sr.jpg`.
  - **Step 2**: Match and align the images using these feature points to perform scene stitching.
  - **Step 3**: Compare the output of each method and discuss the results.

## Photo Sources
The images used for this exercise can be found in the `data` folder:
- **Harris Image**: `data/harris.JPG`
- **Scene Stitching Images**: 
  - `data/sl.jpg`
  - `data/sm.jpg`
  - `data/sr.jpg`

## Colab Notebook
The implementation and output for this exercise can be found in the [Colab Notebook](https://colab.research.google.com/github/bitua79/computer-vision/blob/main/HW7/Vision_HW7.ipynb). The notebook includes:
- Harris Corner detector implementation and feature extraction at multiple scales.
- SIFT/SURF-based feature detection, matching, and alignment for scene stitching.
- Comparisons of feature detection methods and their performance.

## Instructions to Run
1. Clone this repository and navigate to the folder for this exercise.
2. Open the notebook file (`Vision_HW7.ipynb`) either locally or in Google Colab.
3. Ensure the required images are in the `data` folder, and run the code cells to see the outputs.

### 6. Results and Discussion
The notebook provides detailed results for Harris Corner detection at different scales, analyzing the consistency of detected points across scales. The scene stitching task compares SIFT and SURF features for matching and aligning images.
