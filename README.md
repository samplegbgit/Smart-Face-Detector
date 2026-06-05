# Smart Face Detector

A real-time face, eye, and smile detection project built using Python and OpenCV with Haar Cascade classifiers.

---

## Features

 Detects faces in real-time using webcam
 Detects eyes inside face region
 Detects smiles inside face region
 Draws bounding boxes on detected faces
 Shows live detection text on screen

---

## Requirements

Install dependencies:

```bash
pip install opencv-python
```

---

## Project Structure

Smart-Face-Detector/
│
├── face & object detection/
│   ├── face_eye.py
│   ├── haarcascade_frontalface_default.xml
│   ├── haarcascade_eye.xml
│   └── haarcascade_smile.xml
│
└── README.md


---

## How to Run

Run the project using:

```bash
python "face & object detection/face_eye.py"
```

---

## Controls

Press **Q** to exit the webcam window

---

## Important Notes

Keep XML files inside `face & object detection` folder
Make sure webcam is enabled

---

## Tech Stack

Python
OpenCV
Haar Cascade Classifiers


