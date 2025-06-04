# Gesture-Recognition-Gaming

# Gesture-Based Gaming using Pose Estimation

A real-time gesture-controlled gaming project using **MediaPipe**, **OpenCV**, and **TensorFlow**. Control games with your body — no hardware controllers required!

---

##  Overview

This project allows players to interact with games using real-time hand/body gestures. Using computer vision and deep learning, the system identifies specific human gestures and maps them to in-game actions.

Ideal for accessibility, immersive interfaces, and futuristic gaming experiences.

---

##  Features

-  Real-time gesture detection using your webcam
-  Supports multiple dynamic gestures
-  CNN + LSTM-based gesture classification with 95%+ accuracy
-  Controller-free gaming
- Low-latency performance (<50ms on average systems)

---

##  Tech Stack

-   Python 3.x
-   OpenCV – for real-time video feed and processing
-   MediaPipe – for hand and body landmark detection
-   TensorFlow / Keras – for training gesture recognition models
-   NumPy / Pandas – for data handling
-   Matplotlib – for visualizations
-   Tkinter / Pygame (optional) – for in-game GUI control

---

##  How It Works

```markdown
1.  Capture real-time webcam input using OpenCV
2.  Detect body/hand keypoints with MediaPipe
3. Extract features (coordinates, movement vectors)
4. Feed sequences into a trained CNN + LSTM model
5. Trigger game actions based on predicted gestures

```

1) Clone the Repository

git clone https://github.com/your-username/gesture-based-gaming.git
cd gesture-based-gaming

2)  Install Required Libraries

pip install -r requirements.txt

3) Collect Gesture Data

 src/gesture_capture.py

4) Train the Gesture Recognition Model

python src/model_train.py

5) Start Real-Time Gesture Detection

python src/predict.py



 Metric	Result
Accuracy	~95%
Inference Latency	~45ms
FPS	~20-30 fps

Tested on M1 Macbook Air 2020

8GB RAM


