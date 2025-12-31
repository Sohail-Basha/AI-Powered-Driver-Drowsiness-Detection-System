# AI-Powered-Driver-Drowsiness-Detection-System
Real-time driver drowsiness detection system using Python, OpenCV, and MediaPipe to monitor eye blinks and alert drivers for accident prevention.

## 🚀 Features
- Real-time face and eye detection
- Drowsiness detection using eye blink analysis
- Visual alert when drowsiness is detected
- Works with a standard webcam
- Lightweight and fast processing

---

## 🛠️ Tech Stack
- Python  
- OpenCV  
- MediaPipe  
- NumPy  

---

## 📂 Project Structure
├── AI-Powered Driver Drowsiness Prediction System.ipynb
└── README.md

````


How It Works
1. Captures real-time video feed using a webcam.
2. Detects facial landmarks using **MediaPipe Face Mesh**.
3. Calculates **Eye Aspect Ratio (EAR)** to track eye openness.
4. Monitors blink frequency and eye closure duration.
5. Triggers an alert when drowsiness is detected.

---

Key Concepts Used
- Computer Vision
- Facial Landmark Detection
- Eye Aspect Ratio (EAR)
- Real-time Video Processing

---

Installation & Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/driver-drowsiness-detection.git
cd driver-drowsiness-detection
````

### Step 2: Install Dependencies

```
pip install opencv-python mediapipe numpy
```

### Step 3: Run the Notebook

* Open the `.ipynb` file in **Jupyter Notebook** or **Google Colab**
* Run all cells
* Allow webcam access

---

Output

* **Normal State** → Eyes open, no alert
* **Drowsy State** → Eyes closed for a threshold time, alert triggered

---

Use Cases

* Driver safety and accident prevention systems
* Computer vision learning project
* Real-time monitoring applications
* AI-based transportation safety solutions
