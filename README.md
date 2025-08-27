# Face and Eye Detection Using OpenCV

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-orange.svg)](https://opencv.org/)

---

## 1. Project Overview
This project uses **OpenCV** to perform **real-time face and eye detection** via your webcam.  

- Faces are detected using `haarcascade_frontalface_default.xml`.  
- Eyes are detected using `haarcascade_eye.xml`.  
- Detected faces are highlighted with **blue rectangles** and eyes with **green rectangles**.  

The program captures video from the webcam and processes each frame for detection continuously.

---

## 2. Features
- Real-time face and eye detection  
- Multiple face and eye detection in a single frame  
- Visual feedback with rectangles drawn around faces and eyes  
- Press `q` to quit the application  

---

## 3. Prerequisites
- Python 3.x  
- OpenCV library  
- Haar cascade XML files (`haarcascade_frontalface_default.xml`, `haarcascade_eye.xml`)  

### Install Dependencies
```bash
pip install opencv-python
