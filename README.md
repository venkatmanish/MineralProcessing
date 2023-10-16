# MineralProcessing
This project, developed using Python and the OpenCV library, focuses on the intricate analysis of mineral particle images.

# Mineral Particle Image Analysis

Analyze mineral particles from images and extract vital characteristics such as their shape, size, and central location.

## Description

This project employs advanced image processing techniques to extract and visually represent vital characteristics of mineral particles from images. Utilizing Python coupled with the OpenCV library, it meticulously processes each image to deliver insightful analysis results.

## Features

- **Smallest Enclosing Circle**: Computes the minimum circle that fully encapsulates each particle.
- **Total Surface Area**: Calculates and displays the pixel area occupied by each particle.
- **Major Axis Identification**: Highlights the particle's longest internal axis, shedding light on its orientation and shape elongation.
- **Perimeter Measurement**: Determines the particle's size by measuring the total distance around it, represented in pixels.
- **Centroid Location**: Pinpoints and marks the particle's center, or centroid.

## Installation

1. Clone the repository:
```
git clone [repository_link]
```

2. Navigate to the directory:
```
cd [directory_name]
```

3. Install the required packages:
```
pip install -r requirements.txt
```

## Usage

- Ensure your images are placed in the designated `input` folder.
- Run the main script:
```
python MineralProcessing.py
```
- Analyzed images will be saved in the `output` directory.

## Dependencies

- OpenCV: For image processing.
- Matplotlib: For displaying visualized results.
- Numpy: For mathematical operations.
