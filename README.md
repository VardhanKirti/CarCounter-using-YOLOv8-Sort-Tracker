# 🚗 Car Counter with YOLOv8 + SORT Tracker

This project implements a real-time vehicle counting system using **YOLOv8 object detection** and the **SORT tracking algorithm**. It detects and tracks cars in a video stream, draws bounding boxes, and counts cars as they cross a defined line.

---

## 📌 Features

- 🔍 Object Detection using YOLOv8 (`ultralytics`)
- 📦 Tracking with SORT and Kalman Filters
- 📈 Real-time car counting with region-based filtering
- 🖼 Visual overlays with OpenCV + CVZone
- 🗺 Optional area-of-interest masking using `mask.png`

---

## 🖥️ Screenshots

### 🎯 Detected vehicles with bounding boxes and tracking IDs
<img width="800" height="478" alt="Screenshot 2025-08-02 235941" src="https://github.com/user-attachments/assets/e7e7935e-8a05-4575-88c9-707558d051d8" />


### 🚘 Real-time counting as cars cross the red line
<img width="792" height="483" alt="Screenshot 2025-08-03 000024" src="https://github.com/user-attachments/assets/924601d3-f354-4084-90e3-f69fd0cf2ab6" />


---

## 🗂️ Install Dependencies
pip install ultralytics opencv-python cvzone filterpy numpy

---

##📁 Requirements
Python 3.8+

YOLOv8 weights: yolov8n.pt (downloaded automatically via Ultralytics)

Input video file (.mp4)

---

##🙏 Credits
Ultralytics YOLOv8

SORT Tracker

CVZone


