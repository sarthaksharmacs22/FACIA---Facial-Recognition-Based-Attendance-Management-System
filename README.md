# FACIA - Facial Recognition Based Attendance Management System

![FACIA Logo]((https://chatgpt.com/s/m_682f4a0507208191af326dbb67eed69f)
)  <!-- Optional -->

## Overview

FACIA is an automated attendance management system using facial recognition technology.  
It leverages OpenCV and face recognition libraries to mark attendance in real-time, making the process efficient and error-free.

---

## Features

- Real-time face recognition with webcam support  
- Automatic login and logout time tracking  
- Attendance duration calculation  
- Export attendance data to Excel  
- User-friendly interface

---

## Tech Stack

- Python  
- OpenCV  
- face_recognition library  
- Pandas (for data handling)  
- NumPy

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sarthaksharmacs22/FACIA---Facial-Recognition-Based-Attendance-Management-System.git
   cd FACIA---Facial-Recognition-Based-Attendance-Management-System
2. Create and activate a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate     # For Windows
3. Install dependencies:
   pip install -r requirements.txt
4. Usage
   Run the main Python script to start the attendance system:
   Make sure your webcam is connected and working.
5. How It Works
   The system captures real-time video feed from your webcam.
    
   It detects faces and matches them with known encodings stored locally.
    
   When a recognized face is detected, attendance is marked with timestamp.
    
   If the person leaves the frame for a certain time, logout time is recorded.
6. Contributing
   Contributions are welcome! Feel free to open issues or submit pull requests.

7. Contact
   Created by Sarthak Sharma
   Email: sarthaksharma1237@gmail.com
    


