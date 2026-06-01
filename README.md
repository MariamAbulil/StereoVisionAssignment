---

## 🧠 Pipeline Steps

The project follows these main steps:

1. Loading and displaying stereo image pair
2. Converting images to grayscale
3. Detecting feature points using SIFT
4. Matching features between images
5. Estimating the fundamental matrix using RANSAC
6. Computing epipolar geometry
7. Performing image rectification
8. Computing disparity map
9. Generating depth (stereo) map

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📷 Input Images

The input images are:

- `left.png`
- `right.png`

They represent the same scene captured from slightly different viewpoints with minimal camera rotation and no moving objects.

---

## 📊 Output

The pipeline produces:

- Feature matching visualization
- Epipolar geometry visualization
- Rectified stereo images
- Disparity map
- Depth visualization map

---

## 🎯 Key Idea

Disparity between corresponding points in the two images is used to estimate depth:

- Higher disparity → closer object
- Lower disparity → farther object

---

## 👩‍💻 Author

Student Assignment — Computer Vision and Neural Networks
