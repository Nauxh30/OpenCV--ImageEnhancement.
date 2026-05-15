# OpenCV Image Enhancement using Histogram Equalization

## 📌 Overview
Histogram Equalization is an image enhancement technique used to improve the contrast and brightness of images.  
For grayscale images, equalization is directly applied to pixel intensity values.  
For color images, the image is converted from **BGR to HSV** format, and equalization is applied only to the **V (Value)** channel. This improves brightness while preserving the original colors of the image.

---

## 🎯 Aim
To perform Histogram Equalization using OpenCV in Python for enhancing grayscale and color images by improving contrast, brightness, and overall visual quality.

---

## 💻 Software Requirements
- Python 3.7+
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook / VS Code / Anaconda

---

## 🛠️ Procedure
1. Import the required libraries.
2. Read the image in grayscale format.
3. Display the grayscale image.
4. Plot the histogram of the grayscale image.
5. Apply histogram equalization to enhance contrast.
6. Display the enhanced grayscale image and histogram.
7. Read the same image in color format.
8. Convert the color image from BGR to HSV format.
9. Apply histogram equalization only on the V channel.
10. Convert the image back from HSV to BGR format.
11. Display the original and enhanced color images.
12. Compare the histograms before and after equalization.

---

## 📊 Output
- The original image and its histogram are displayed first.
- After applying histogram equalization, the enhanced image appears brighter and clearer.
- The histogram becomes more evenly distributed, indicating improved contrast and intensity levels.
- Color images retain their natural appearance while achieving better brightness and visibility.
- <img width="1357" height="917" alt="image" src="https://github.com/user-attachments/assets/49002c2e-17db-4198-a419-f15f8df016d4" />
<img width="1425" height="928" alt="image" src="https://github.com/user-attachments/assets/48f505e0-0a79-44a6-9be5-8ca8ec7087e1" />



---

## ✅ Result
Thus, Histogram Equalization was successfully performed on both grayscale and color images using OpenCV.  
The contrast and brightness of the images were significantly improved, enhancing the overall visual quality and feature visibility.

---
