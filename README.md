# Attendance Management System Using Facial Recognition

## Overview
This project is a real-time **Attendance Management System** that uses **Facial Recognition** to identify individuals and log attendance efficiently. The system integrates with **Firebase** for real-time database management and storage functionalities.

---

## Features
- **Facial Recognition**: Identifies individuals using a live video feed.
- **Real-Time Attendance Logging**: Updates attendance details directly in Firebase.
- **Data Encoding**: Encodes facial data and stores it securely.
- **Firebase Integration**: Utilizes Firebase Realtime Database and Cloud Storage.
- **Scalability**: Easily extendable for more users and use cases.

---

## Installation and Setup

   1. Clone this repository
        ```bash
         git clone https://github.com/yourusername/Attendance-Management-System-Facial-Recognition.git
         cd Attendance-Management-System-Facial-Recognition

   2. Install the required dependencies
         ```bash
         pip install opencv-python
         pip install face-recognition
         pip install firebase-admin
         pip install cvzone
         pip install numpy


---

## Project Structure


Attendance-Management-System-Facial-Recognition/
├── Images/
│   ├── 23MCA1041.jpg
│   ├── VITCC52288.jpg
│   └── ...
├── Resources/
│   ├── background.png
│   ├── Modes/
│   │   ├── mode1.png
│   │   ├── mode2.png
│   │   └── ...
├── EncodeFile.p
├── serviceAccountKey.json
├── upload_images.py
├── add_data_to_database.py
├── main.py
├── requirements.txt
└── README.md

---

## Requirements

   ### Install dependencies
   - pip install opencv-python
   - pip install face-recognition
   - pip install firebase-admin
   - pip install cvzone
   - pip install numpy


---

## Screenshots

### System in Action

1. **Live Facial Recognition**
   - Screenshort 1

   ![image](https://github.com/user-attachments/assets/f76ea20a-9fd0-46fe-839e-2b0abdc7c134)

   - Screenshort 2

   ![image](https://github.com/user-attachments/assets/cc46c1d5-7045-49b4-bbaa-54addcb32819)

1. **Attendance Logging in Firebase**
   - Images Stored in Firebase: 
   ![image](https://github.com/user-attachments/assets/4641f4fb-e603-4935-b218-f0f66c56456f)

   - Student’s details and records Stored in data base:
   ![image](https://github.com/user-attachments/assets/56af696a-2684-4d94-ae89-8372a44bb1a1)

---

## How It Works

Step 1: Data Preparation
Upload student images to the `Images/` directory.
Encode the images using `upload_images.py`.

Step 2: Database Initialization
Populate student data in Firebase using `add_data_to_database.py`.

Step 3: Real-Time Attendance
Run the main module to start real-time face recognition and attendance logging.
python main.py


---

## Contributors
- **Email:** [manapurepranav03@gmail.com](mailto:manapurepranav03@gmail.com)
- **Linkdin:** www.linkedin.com/in/pranav-manapure
  
---

## License
This project is licensed under the MIT License.



- **credentials:** "serviceAccountKey.json"
- **databaseURL:** "https://attendancemanagementcc-default-rtdb.firebaseio.com/",
- **storageBucket:** "attendancemanagementcc.appspot.com"
