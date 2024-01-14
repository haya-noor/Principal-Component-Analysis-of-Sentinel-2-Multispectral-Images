# Principal-Component-Analysis-of-Sentinel-2-Multispectral-Images

## Overview
This project focuses on applying Principal Component Analysis (PCA) to Sentinel-2 multispectral images. The goal is to reduce the dimensionality of the images while preserving essential information, facilitating efficient analysis and visualization.

## Project Structure
- `images/`: Contains Sentinel-2 image files in JP2 format.
- `README.md`: Project documentation.
- `Complex-Engineering-Problem.ipynb`: Jupyter Notebook containing the Python code.

## Code Highlights
Opening and Displaying Images
The project utilizes the rasterio library to open and display Sentinel-2 multispectral images. Image information such as the number of bands, width, and height is displayed.

## Data Preprocessing
The images are cropped and individual bands are stacked to create a 3D array. The code then displays each band using subplots and creates a grayscale image.

## PCA Dimensionality Reduction
The 3D array is reshaped into a 2D array and standardized. PCA is applied to reduce dimensionality, and the optimal number of Principal Components (k) is determined by analyzing the mean squared error.

## Results
The final grayscale image after applying PCA is displayed. Additionally, a histogram of errors is generated, providing insights into the effectiveness of dimensionality reduction.

## Contributors
- **[Lailoma Noor](https://github.com/lailomanoor)**
- **[Itba Malahat](https://github.com/ItbaMalahat)**
- **[Warda Farhan](https://github.com/Warda-F)**
- **[Haya Noor](https://github.com/haya-noor)**

Thank you for your valuable contributions!



