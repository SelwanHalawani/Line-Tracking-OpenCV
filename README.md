# Line Tracking Project Using OpenCV
## Project Overview 
This project demonstrates how to use OpenCV to track lines in a video feed captured from a webcam. Line tracking is a fundamental task in computer vision with applications in robotics, automated vehicles, and object detection systems. The implementation detects lines in real-time using edge detection and Hough Line Transform techniques.
## Features

- Real-time line detection from a live camera feed.
- Noise reduction using Gaussian Blur.
- Edge detection using the Canny Edge Detector.
- Line detection using the Probabilistic Hough Line Transform.
- Visualization of detected lines.
## Technology Used

### OpenCV
OpenCV (**Open Source Computer Vision Library**) is a powerful tool for real-time computer vision tasks. It provides efficient tools for image processing, object detection, and feature extraction.

## How It Works

**Frame Capture:**
- The program uses the webcam to capture frames in real-time.

**Preprocessing:**
- Each frame is converted to grayscale to simplify processing.
- Gaussian Blur is applied to reduce noise, ensuring better edge detection.

**Edge Detection:**

- The Canny Edge Detector is used to find edges in the frame. It highlights regions of high intensity change, which typically correspond to edges.

**Line Detection:**
- The Probabilistic Hough Line Transform is applied to detect straight lines in the edge-detected frame.
- Detected lines are drawn over the original frame.

**Display:**
- The processed frame with highlighted lines is displayed in real-time.

**Exit:**
- The program runs continuously until the user presses a specific key (q).

## Benefits of Using OpenCV

- **Efficiency:** OpenCV is optimized for real-time image processing.

- **Versatility:** It supports various functionalities like object detection, image transformation, and video analysis.

- **Cross-Platform:** OpenCV works on multiple platforms, including Windows, Linux, and macOS.

- **Community Support:** OpenCV has a vast and active community, making it easier to find resources and support.

## Future Enhancements

- Add support for tracking curved lines.

- Implement a GUI for easier parameter tuning.

- Integrate object detection to track multiple patterns simultaneously.
