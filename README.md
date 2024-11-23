# Face Recognition Project

## Overview

This project implements a **Face Recognition** system using Python and OpenCV. It covers fundamental steps in image processing, including face detection and recognition. The repository includes a Jupyter Notebook that walks through the process step-by-step, making it easy to understand and extend.

---

## Features

- **Face Detection**: Utilizes Haar cascades to detect faces in images.
- **Face Recognition**: Implements recognition techniques for identifying individuals.
- **Interactive Jupyter Notebook**: Provides a clean and reproducible environment for experimentation.
- **Image Processing**: Converts images to grayscale and processes them for efficient recognition.
- **Output Visualization**: Displays images with detected faces and saves cropped face images.

---

## Requirements

To run the notebook and scripts, you need the following:

- Python 3.x
- Jupyter Notebook
- Required Python packages:
  - `opencv-python`
  - `numpy`
  - `matplotlib`

Install dependencies using:
```bash
pip install opencv-python numpy matplotlib
```

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/sarvzz/FaceRecognition.git
   cd FaceRecognition
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Face-Recognition.ipynb
   ```

3. Follow the steps in the notebook to:
   - Load and preprocess images.
   - Detect faces in images.
   - Recognize faces and visualize results.

4. Check the output images saved in the working directory.

---

## Example Workflow

1. **Input Image**:
   - An image with one or more faces.
2. **Face Detection**:
   - Haar cascades detect faces and output bounding boxes.
3. **Face Recognition**:
   - Identifies known faces or marks unknown ones.
4. **Cropped Faces**:
   - Cropped face images are saved locally.

---

## Folder Structure

```plaintext
FaceRecognition/
│
├── Face-Recognition.ipynb  # Main Jupyter Notebook
├── Output/                 # Folder for cropped face images
└── README.md               # Documentation file
```


