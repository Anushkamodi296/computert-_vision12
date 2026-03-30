# computert-_vision12
 Real-Time Color Detection using OpenCV

 Project Overview

This project implements a **real-time color detection system** using computer vision techniques. It captures live video from a webcam and detects objects of a specific color (e.g., red) by applying image processing methods. The detected object is highlighted with a bounding box and labeled accordingly.

This project does not require any dataset or training, making it simple, efficient, and suitable for beginners.

---

 Features

* Real-time webcam video processing
* Detection of specific colors using HSV color space
* Object localization using contour detection
* Bounding box and label display on detected object
* Lightweight and fast execution

---

## Tech Stack

* **Programming Language:** Python
* **Libraries Used:**

  * OpenCV
  * NumPy

---

## Installation & Setup

### 1. Clone the Repository

```id="vsso4w"
git clone https://github.com/your-username/color-detection-opencv.git
cd color-detection-opencv
```

### 2. Install Dependencies

```id="h9l162"
pip install opencv-python numpy
```

### 3. Run the Project

```id="hfa68q"
python main.py
```

---

## Working Principle

1. Capture video from webcam
2. Convert image from **BGR to HSV color space**
3. Define a specific color range (e.g., red)
4. Generate a mask to isolate that color
5. Detect contours from the mask
6. Draw bounding boxes around detected objects

---

## 📂 Project Structure

```id="nfqyno"
color-detection-opencv/
│
├── main.py
├── requirements.txt
└── README.md
```

---

##  Output

* Webcam feed opens in real time
* Colored object is detected
* Bounding box appears around the object
* Label (e.g., "Red Object") is displayed

---

## Applications

* Object tracking systems
* Gesture-based interfaces
* Robotics (color-based navigation)
* Industrial sorting systems

---

## Future Enhancements

* Multi-color detection (red, blue, green)
* Object counting feature
* Integration with GUI (Tkinter/Flask)
* Tracking moving objects

---

Limitations

* Sensitive to lighting conditions
* Limited to predefined color ranges
* Cannot detect complex objects


 Author

Anushka
B.Tech – CCSE (AI & ML)

 License

This project is for educational purposes only.
