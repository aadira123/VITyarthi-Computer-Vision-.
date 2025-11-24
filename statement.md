## 📄 `statement.md`

### 1. Problem Statement
The challenge is to implement and compare various **2D image convolution filters** and the **Canny Edge Detection** algorithm. This involves mathematically transforming an input image to demonstrate:
1.  **Noise reduction (smoothing)** using both uniform (box) and weighted (Gaussian) averaging.
2.  **Detail enhancement (sharpening)** using a high-pass kernel.
3.  **Effective structural feature extraction (edges)**, specifically highlighting the necessity of **noise suppression** as a preprocessing step for clean edge maps.

---

### 2. Scope of the Project
The project's scope is strictly limited to **grayscale and color image filtering** based on **spatial convolution** implemented in a Python environment using the core functions of the OpenCV library. It covers fundamental $\text{3x3}$ and $\text{5x5}$ kernel operations and the use of specialized functions like $\text{cv2.GaussianBlur}$ and $\text{cv2.Canny}$.

The project **does not** include:
* Real-time video processing.
* Advanced techniques like image restoration (deblurring) or deep learning-based object detection.
* GPU acceleration for filtering.

---

### 3. Target Users
* **Students/Beginners in Computer Vision:** Looking for clear, practical code examples demonstrating fundamental concepts like convolution, kernels, and filter types (low-pass vs. high-pass).
* **Developers:** Needing straightforward scripts to preprocess images by blurring, sharpening, or extracting clean edges before inputting them into machine learning models.
* **Educators:** Seeking a demonstrable code base for teaching initial image processing modules in computer science or engineering courses.

---

### 4. High-Level Features
* **Custom Kernel Implementation:** Definition of various convolution matrices (kernels) using NumPy.
* **Low-Pass Filtering:** Implementation of Averaging/Box Blur and optimized Gaussian blurring for noise reduction.
* **High-Pass Filtering:** Implementation of image sharpening using a detail-enhancing kernel.
* **Feature Extraction:** Implementation of the multi-stage Canny edge detection algorithm.
* **Pre-processing Validation:** Visual comparison of edge detection results with and without a prior Gaussian blur to emphasize noise control.
* **Visualization:** Consistent and correct display of BGR/grayscale filtered images using Matplotlib.
