# Face and Eye Detection Using OpenCV

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-orange.svg)](https://opencv.org/)

---

## 1. Project Overview
This project uses **OpenCV** to perform **real-time face and eye detection** via your webcam.  

- Faces are detected using `haarcascade_frontalface_default.xml`.  
- Eyes are detected using `haarcascade_eye.xml`.  
- Detected faces are highlighted with **blue rectangles** and eyes with **green rectangles**.  

The program continuously captures video from the webcam and processes each frame for detection.

---

## 2. Features
- Real-time face and eye detection  
- Detect multiple faces and eyes in a single frame  
- Visual feedback with rectangles drawn around faces and eyes  
- Press `q` to quit the application  

---

## 3. Prerequisites
- Python 3.x  
- OpenCV library  
- Haar cascade XML files (`haarcascade_frontalface_default.xml` and `haarcascade_eye.xml`)  

### File Structure
FaceEyeDetection/
├── haarcascade_frontalface_default.xml
├── haarcascade_eye.xml
├── face_eye_detection.ipynb
├── README.md
├── requirements.txt
└── images/
├── face_detected.png
└── face_eye_detected.png

### 5. How It Works
- Captures video from the webcam  
- Detects faces in real-time  
- Detects eyes inside the detected faces  
- Displays rectangles around faces and eyes on the video feed  

---

## 6. Usage
1. Ensure Python and OpenCV are installed  
2. Place Haar cascade XML files in the project folder  
3. Run the notebook or script  
4. Webcam feed will appear with rectangles  
5. Press `q` to exit  

---

## 7. Results

### Face Detection
![Face Detection](https://raw.githubusercontent.com/your-username/FaceEyeDetection/main/images/face_detected.png)  

*Blue rectangles highlight detected faces.*

---

### Face and Eye Detection
![Face and Eye Detection](https://raw.githubusercontent.com/your-username/FaceEyeDetection/main/images/face_eye_detected.png)  

*Blue rectangles indicate faces, green rectangles indicate eyes detected inside the faces.*

> Replace `your-username` in the image URLs with your GitHub username.  

---

## 8. Notes
- Good lighting improves detection accuracy  
- Works best with frontal faces  
- Multiple faces detected will all have rectangles  

---

## 9. Requirements
- OpenCV Python library  
- Haar cascade XML files  

---

## 10. References
- OpenCV Documentation: [https://opencv.org](https://opencv.org)  
- Haar Cascades: [https://github.com/opencv/opencv/tree/master/data/haarcascades](https://github.com/opencv/opencv/tree/master/data/haarcascades)  

---

## 11. License
This project is open-source and free to use.
