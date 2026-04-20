# Biomedical Image Processing Projects (MATLAB-Based)

This repository contains a collection of laboratory exercises focused on fundamental biomedical image processing techniques. Each lab explores key methods used in medical imaging analysis, from basic intensity transformations to advanced filtering and geometric corrections.
## Overview
- Total labs: 10
- Field: Biomedical Engineering / Image Processing
- Tools: MATLAB

## Labs Included

- **Lab 1: Histogram Analysis**
  Analysis of images with different exposure levels (low, high, and well-exposed) through grayscale conversion and histogram generation to study pixel intensity distribution using both manual and built-in methods in MATLAB.

- **Lab 2: Intensity Level Transformations**  
  Grayscale image processing using different intensity transformations, including negative inversion, linear contrast stretching, and triangular mapping, with analysis of their effects through histogram comparison before and after transformation.
  
- **Lab 3: Gamma Correction**  
  Gamma correction for intensity level adjustment in both bright and dark grayscale images, with evaluation of different gamma values and their effects on brightness and contrast.

- **Lab 4: Histogram Equalization**  
  Histogram equalization for contrast improvement in a grayscale image, with redistribution of pixel intensities using the cumulative distribution function and comparison of histograms before and after enhancement.

- **Lab 5: Convolution Masks**  
  Application of spatial filtering techniques to a grayscale image, including low-pass filtering for noise reduction and high-pass filtering for edge and detail enhancement.

- **Lab 6: Advanced Convolution Masks**  
  Application of convolution masks for edge detection in grayscale medical images, including Prewitt and Sobel operators. Edge enhancement through gradient computation in both horizontal and vertical directions, with visualization and normalization of the resulting images.

- **Lab 7: High-pass and Low-pass Filters**  
  Frequency domain filtering of grayscale images using the Fourier Transform, including the application of low-pass and high-pass filters. Analysis of frequency components through spectrum visualization and reconstruction of filtered images using the inverse transform.

- **Lab 8: Periodic Noise Removal**  
  Removal of periodic noise in grayscale images through frequency domain analysis using the Fourier Transform. Detection of noise peaks in the frequency spectrum, construction of a notch filter, and reconstruction of the filtered image using the inverse transform.

- **Lab 9: Image Rotation**  
  Rotation of a grayscale image around a defined pivot point using geometric transformation. Coordinate mapping and interpolation for pixel reassignment, with reconstruction of the rotated image.

- **Lab 10: Perspective Correction**  
  Perspective correction of a grayscale image through geometric transformation based on user-selected reference points. Computation of transformation parameters using a system of equations, pixel remapping to a corrected coordinate space, and reconstruction of missing regions through interpolation.

## Repository Structure

Each lab is organized in its own folder:
lab-01-histogram/
lab-02-intensity-transformations/
lab-03-gamma-correction/
lab-04-histogram-equalization/
lab-05-convolution-masks/
lab-06-advanced-convolution/
lab-07-frequency-filters/
lab-08-periodic-noise-removal/
lab-9-image-rotation/
lab-10-perspective-correction/

Each folder contains:
- Source code
- Input images (if applicable)
- Output results
- Brief explanation of the implemented method
