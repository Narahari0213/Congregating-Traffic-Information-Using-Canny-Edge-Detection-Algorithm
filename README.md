# 🚦 Congregating Traffic Information Using Canny Edge Detection

A smart traffic control system that uses **image processing and the Canny Edge Detection algorithm** to measure real-time traffic density and dynamically allocate green signal time. This project aims to improve traffic flow efficiency by leveraging computer vision instead of traditional sensor-based systems.

---

## 📌 Project Overview

Urban traffic congestion is a major challenge in modern cities. Traditional traffic control systems rely on fixed timers or hardware sensors, which often fail to adapt to real-time traffic conditions.

This project proposes an **image-based traffic control system** that:

* Analyzes traffic images
* Detects vehicle edges using **Canny Edge Detection**
* Counts white (edge) pixels to estimate traffic density
* Dynamically allocates green signal time based on congestion level

---

## 🎯 Objectives

* Detect traffic density using digital image processing
* Replace hardware-based sensors with camera-based analysis
* Allocate traffic signal time dynamically
* Reduce congestion, waiting time, and fuel consumption

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Libraries & Tools:**

  * OpenCV
  * NumPy
  * SciPy
  * Matplotlib
  * Tkinter (GUI)
* **Algorithm:** Canny Edge Detection
* **Operating System:** Windows 10 or above

---

## ⚙️ System Architecture

1. Upload traffic image
2. Convert image to grayscale
3. Apply Gaussian smoothing
4. Perform Canny edge detection
5. Count white (edge) pixels
6. Compare with reference image
7. Allocate green signal time

---

## 🖥️ Application Features

* GUI-based application using Tkinter
* Upload traffic images easily
* Visualize edge-detected images
* Automatic traffic density calculation
* Green signal time allocation:

  * Very High Traffic → 60 seconds
  * High Traffic → 50 seconds
  * Moderate Traffic → 40 seconds
  * Low Traffic → 30 seconds
  * Very Low Traffic → 20 seconds

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/traffic-canny-edge-detection.git
   ```

2. Navigate to the project directory:

   ```bash
   cd traffic-canny-edge-detection
   ```

3. Install required dependencies:

   ```bash
   pip install numpy opencv-python matplotlib scipy scikit-image
   ```

4. Run the application:

   ```bash
   python Main.py
   ```

5. Upload a traffic image and follow the on-screen steps.

---

## 📂 Project Structure

```
├── images/               # Traffic and reference images
├── gray/                 # Processed grayscale images
├── Main.py               # Main GUI application
├── CannyEdgeDetector.py  # Canny edge detection implementation
├── run.bat               # Windows execution file
└── README.md             # Project documentation
```

---

## 📊 Results

* Accurate traffic density estimation using edge pixel count
* Dynamic signal timing improves traffic flow
* Cost-effective solution using existing camera infrastructure

---

## 🔮 Future Enhancements

* Real-time video stream processing
* Integration with IoT traffic cameras
* Deep learning–based vehicle detection
* Cloud-based traffic monitoring dashboard
* Multi-lane and junction-level optimization

---

## 🏫 Academic Details

* **Degree:** B.Tech – CSE (Data Science)
* **Institution:** Sphoorthy Engineering College
* **Affiliated to:** JNTU Hyderabad
* **Academic Year:** 2023–2024

---

## 📜 License

This project is developed for **academic purposes**.
You are free to use, modify, and extend it with proper attribution.

---
