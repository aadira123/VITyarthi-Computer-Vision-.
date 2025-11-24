# VITyarthi-Computer-Vision-.
This project was made under the assignment of course offered by VITyarthi portal on computer vision .
We will explore the fundamental concept of convolution. We'll discover how a small matrix called a kernel can slide over an image to modify pixels based on their neighbors. This simple operation is the key to powerful techniques like blurring, sharpening, and, most importantly, edge detection—the first step towards identifying the structure of objects in an image.

Functional Requirements


o	Image Loading: Must be able to load an image from a specified file path.
•	Image Blurring: Must implement and demonstrate Averaging Filter (via cv2.filter2D and cv2.blur) and Gaussian Blur (cv2.GaussianBlur).
•	Image Sharpening: Must implement and apply a Sharpening Kernel using cv2.filter2D.
•	Edge Detection: Must implement the Canny Edge Detection algorithm (cv2.Canny).
•	Color Conversion: Must convert the image to Grayscale for optimal edge detection.
•	Image Display: Must provide a helper function to correctly display OpenCV's BGR images in Matplotlib (RGB).


Non-functional Requirements
•	Performance: Image filtering operations should complete quickly for typical image sizes (achieved via OpenCV's optimized C/C++ backend).
•	Maintainability: The code should be clear, modular, and well-commented (e.g., using helper functions like display_image).
•	Readability: The convolution kernels should be clearly defined using NumPy arrays.

Steps to install & run the project

step1:open the main file.
step2: click on the folders--> content.
step3: under the content section create a new folder named assets.
step4: under assets upload image of you choice for uploading in the project.
step5: copy the path and use is for the algorithm to navigate through the image .
