# 🎯 Project Title
Face Recognition Attendance System

---

## 📘 Overview
The **Face Recognition Attendance System** is an intelligent attendance management application built using **Python**, **OpenCV**, and **Tkinter**.  
It automates the process of marking attendance by recognizing faces, storing data in **MySQL**, and maintaining subject-wise attendance records.

---

## ⚙️ Features
- 📸 Real-time face detection and recognition using **OpenCV**
- 🧑‍🎓 Student registration with batch, subject, and department details
- 🗂️ Subject-wise and batch-wise attendance management
- 📁 Attendance stored automatically in CSV and MySQL database
- 🧠 Option to switch between **LBPH**, **SVM**, **CNN**, and **DNN** models
- 🛡️ Future enhancement: Spoof detection (blink or liveness detection)
- 📊 Attendance report generation (PDF/Excel format)

---

## 🏗️ Tech Stack
| Component | Technology Used |
|------------|----------------|
| **Frontend** | Tkinter (Python GUI) |
| **Backend** | Python, MySQL |
| **Face Recognition** | OpenCV, face_recognition library |
| **Data Handling** | Pandas, CSV |
| **Model Options** | LBPH, SVM, CNN, DNN |
| **Future Upgrade** | ESP32-CAM Integration |

---

## 🧩 Project Structure
Face_Recognition_Attendance/
│
├── takeImage.py # Capture and store face images
├── takemanually.py # Manual attendance entry
├── automatic_attendence.py # Real-time face recognition & attendance marking
├── attendence.py # Main Tkinter GUI module
├── model/ # Model files (.caffemodel, .prototxt)
├── Attendance/ # Stores subject-wise attendance CSVs
├── database/ # MySQL or CSV student data
└── README.md # Project documentation

---

## ⚡ How to Run the Project
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/face-recognition-attendance.git
cd face-recognition-attendance
pip install -r requirements.txt
Run the GUI

python attendence.py
