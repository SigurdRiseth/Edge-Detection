# Edge Detection and Diffusion

This project implements edge detection and diffusion using the Perona-Malik diffusion algorithm and displays the process through visualizations.

This project was part of the grading in IMAG2024 - Mathematics for engineering 2D, and resulted in the report in the repository.

## Overview

The Perona-Malik algorithm is a method for edge detection and image denoising that utilizes anisotropic diffusion. This project demonstrates the application of this algorithm on a grayscale image to enhance edges while reducing noise.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- Pillow (PIL)

## Usage

1. **Install Dependencies**: Ensure Python and required libraries are installed.
   
2. **Run the Code**: Execute the script `perona_malik.py`. The script loads an image named `image.png`, performs edge detection using the Perona-Malik algorithm, and displays the processed images.

    ```sh
    python perona_malik.py
    ```

## Details

- **Visualization Script**: The script includes visualizations of the original image, derivatives in X and Y directions, gradient magnitude, filtered gradient magnitude after diffusion, and the final edge-detected image.
  
- **Parameters**: Adjust `iterations`, `deltaT`, and `lam` in the script to control the diffusion process and edge detection sensitivity.

## Example Images

- **Original Image**: The input image used for edge detection.
  
- **Processed Images**: Demonstrations of the edge detection process including derivative calculations, gradient magnitudes, and final edge-detected results.
