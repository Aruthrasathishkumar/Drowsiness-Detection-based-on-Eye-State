# Drowsiness Detection Based on Eye State

This project implements a computer vision-based system to detect drowsiness by analyzing a person’s eye state using facial landmarks. It uses OpenCV, Dlib, and Haar cascades to determine if a person’s eyes are closed for prolonged periods, indicating potential drowsiness.

---

## 📌 Features

- Real-time eye tracking and drowsiness detection
- Uses Haar cascades and Dlib facial landmark predictor
- Alert system with sound if drowsiness is detected
- Lightweight and efficient Python implementation

---

## 🛠 Technologies

- Python 3.x
- OpenCV
- Dlib
- Haar Cascade Classifiers

---

## 🚀 How to Run

1. **Install dependencies**:
   - Place `shape_predictor_68_face_landmarks.dat` manually in your project directory. Download from:  
  [http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2)

   - Required XML files:
     - `haarcascade_frontalface_default.xml`
     - `haarcascade_eye.xml`
2. **Ensure the required files are present in your project directory**
3. **Run the Program**
