# MIM_Tension
This Python script processes microscopy images of MIM out of the MOM to compute **membrane tension** using image analysis techniques

# Membrane Tension Analysis from MIM extrusion from MOM

This Python script processes microscopy images of phase MIM exposed to cytosolic media due to MOM extrusion to compute **membrane tension** using image analysis techniques. The results are visualized using Seaborn (v0.13.2).

## Overview

- Input: Experimental images of vesicles showing phase separation.
- Processing: Image segmentation, contour detection, curvature estimation.
- Output: Membrane tension values per vesicle, visualized and saved.
- Tools: OpenCV for image processing, Seaborn for data visualization.

## Features

- Automated batch processing of mitochondrial images
- Calculates tension based on contour curvature and geometry
- Saves plots of processed vesicles and provides values

## Requirements

- Python 3.11.8
- Seaborn 0.13.2
- OpenCV (cv2)
- NumPy
- Pandas
- Matplotlib
- SciPy

## Installation

1. **Clone this repository:**

```bash
git clone https://github.com/DavidGomez82/MIM_Tension.git
cd MIM-tension-analysis
