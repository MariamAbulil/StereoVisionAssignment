# Stereo Vision Assignment

## Project Overview

This project builds a stereo vision pipeline using two images captured from slightly different viewpoints to estimate depth.

---

## Project Structure

STEREOVISIONASSIGNMENT/

- data/
  - left.png
  - right.png
- stereo.ipynb
- README.md

---

## Pipeline Steps

1. Load stereo images
2. Convert to grayscale
3. Detect features (SIFT)
4. Match features
5. Compute Fundamental Matrix
6. Epipolar geometry
7. Image rectification
8. Disparity map
9. Depth visualization

---

## Tools Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Input Images

Two images of the same static scene:

- left.png
- right.png

Captured from slightly different horizontal viewpoints.

---

## Output

- Feature matching result
- Epipolar lines
- Rectified images
- Disparity map
- Depth map

---

## Key Idea

Disparity between matching points is used to estimate depth:

- Higher disparity → closer objects
- Lower disparity → farther objects
