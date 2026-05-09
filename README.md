# Image to Grayscale Converter 🖼️➡️🌑

A lightweight Python utility designed to load an image and convert it into a professional grayscale format using the OpenCV library. This script is ideal for basic image processing tasks and understanding color-space transformations.

## 📌 Project Overview
This tool automates the process of converting standard BGR (color) images into Grayscale. It is a fundamental step in many computer vision pipelines, such as edge detection, face recognition, and object tracking, as it reduces computational complexity while retaining essential structural information.

## ✨ Key Features
* **Automated Conversion:** Instant transformation of high-resolution images to grayscale.
* **Real-Time Display:** Displays both the original and converted images in separate windows for side-by-side comparison.
* **Error Handling:** Robust check to ensure the image path is valid before processing.
* **Auto-Save Functionality:** Automatically saves the processed grayscale image to a designated directory.

## 🛠️ Technical Stack
* **Language:** Python 3.x
* **Library:** `OpenCV` (Open Source Computer Vision Library)
* **Library:** `NumPy` (For array manipulations)

## 📂 Project Structure
* `image_Grayscale.py`: The main Python script containing the image loading, conversion, and saving logic.
* `README.md`: Comprehensive documentation.

## ⚙️ Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone (https://github.com/UmamaNoor174/image-grayscale-converter.git)
   cd image-grayscale-converter

2. **Install Dependencies:**
Ensure you have OpenCV installed:
Bash
pip install opencv-python numpy
Configure Image Path:
Open image_Grayscale.py and update the image_path variable with the location of your image:

Python
image_path = r"YOUR_IMAGE_PATH_HERE"

**Run the Script:**
Bash
python image_Grayscale.py

🎮 **How it Works**
1. Loading: The script reads the image from the specified local path.

2. Processing: Uses the cv2.cvtColor function with the COLOR_BGR2GRAY flag.

3. Visualization: Opens a window to show the original image for 1 second, followed by the grayscale result.

4. Exporting: Saves the final grayscale image to the output path defined in the script.

🎓 **Academic Context**
This project serves as a foundational component for the Department of Information Technology. It demonstrates the practical application of image manipulation techniques used in wider Artificial Intelligence and Computer Vision research.

👤 Developer
Umama Noor
Program: Artificial Intelligence