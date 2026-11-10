# Fourier_tranform_in_image_and_video-processing# 
This project demonstrates the application of Fourier Transform in image and video processing using Python. It explores how images and video frames can be converted from the spatial domain into the frequency domain for analysis.

## 2. Project Objectives
- To understand the concept of Fourier Transform.
- To apply Fourier Transform to digital images.
- To apply Fourier Transform to video frames.
- To analyse frequency components using magnitude spectra.
- To gain practical experience with Python image and video processing libraries.

## 3. Technologies and Libraries Used
- **Python:** Programming language used to develop the project.
- **OpenCV (cv2):** Used for reading and processing images and videos.
- **NumPy:** Used for numerical calculations and Fourier Transform operations.
- **Matplotlib:** Used for displaying images and frequency spectra.
- **Google Colab:** Used as the coding and execution environment.
- **GitHub:** Used for storing and sharing project files and group collaboration.

## 4. How It Works

### A. Image Processing
1. The user uploads an image.
2. The image is read and displayed.
3. The image is converted into grayscale.
4. The 2D Fourier Transform is applied using `np.fft.fft2()`.
5. Frequency components are shifted using `np.fft.fftshift()`.
6. The magnitude spectrum is calculated and displayed.

### B. Video Processing
1. The user uploads a video.
2. OpenCV opens the video.
3. A frame is extracted from the video.
4. The frame is displayed and converted into grayscale.
5. Fourier Transform is applied to the extracted frame.
6. The magnitude spectrum is calculated and displayed.

## 5. Project Structure
- `Fourier_Transform_Image_Video_Processing.ipynb` – Contains the Python code and implementation of the project.
- `README.md` – Contains information and documentation about the project.

## 6. Expected Results
The project produces:
- Original and grayscale images.
- Image Fourier Transform magnitude spectrum.
- Extracted video frames.
- Video frame Fourier Transform magnitude spectrum.

## 7. Conclusion
This project demonstrates the use of Fourier Transform in image and video processing. Through Python libraries such as OpenCV, NumPy and Matplotlib, it shows how digital images and video frames can be analysed in the frequency domain.






