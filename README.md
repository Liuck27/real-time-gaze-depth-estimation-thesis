# Real-Time Gaze Depth Estimation

This repository contains the documentation of my **MSc Thesis**, focused on the design and development of a **real-time system for gaze depth estimation** using **wearable eye-tracking device** and computer vision techniques.
This project is part of a larger initiative focused on developing a robotized wheelchair for individuals with disabilities.

The project investigates how gaze direction, and depth estimation can be combined to infer **where in 3D space a user is looking**, under real-time constraints.

---

## 🚀 Project Overview

Modern wearable eye-trackers provide accurate gaze direction but do not directly measure **gaze depth** — i.e., *how far* the user is looking.

This project proposes an end-to-end pipeline that:
- acquires gaze data from a wearable eye-tracking device
- processes RGB images to extract pupils coordinates 
- estimates gaze depth from pupils position using a Gaussian regression model
- Decodes a H264 video stream in real-time to obtain a continuos estimation of the gaze depth

The system is designed with a strong focus on **real-time performance**, **modularity**, and **reproducibility**.

---

## 🛠️ Technologies & Tools

- **Python**
- **Computer Vision (OpenCV)**
- **Gaussian Regression Model for Depth Estimation**
- **Wearable Eye-Tracking Device (Tobii Pro Glasses 3)**
- **Real-time video decoding using ffmpeg**

---

## 📊 Key Features

- Real-time inference pipeline
- Wearable eye-tracking integration
- Depth estimation from RGB images
- Experimental evaluation on real-world data
- Modular and extensible system design

---

## 📄 Thesis Document

The full MSc thesis is available in this repository:

📘 **`Tesi_Magistrale_.pdf`**

The document includes:
- theoretical background
- system design and architecture
- implementation details
- experimental setup
- quantitative and qualitative results

---

## 🎓 Academic Context

- **Degree**: Master’s Degree (MSc)
- **Field**: Computer / Information Engineering
- **Developed during**: Erasmus exchange at UPC Barcelona
- **Hardware**: Tobii Pro Glasses 3

---

## 🔮 Future Work

Potential extensions include:
- improved pupil detection algorithms to better handle variations in lighting and eye occlusions.
- improved depth estimation models
- Integrating additional sensors, such as accelerometers or gyroscopes, may enhance the accuracy of glasses’ positioning and depth estimation.

---

## 📬 Contact

For questions or discussions about this project, feel free to get in touch.
