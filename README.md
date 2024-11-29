![image](https://github.com/user-attachments/assets/6e739315-5c3e-4e8b-8adb-a470902fccef)# Attendance Management System Using Facial Recognition

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

```plaintext
Attendance-Management-System-Facial-Recognition/
├── Images/                # Directory to store all user images
│   ├── 23MCA1041.jpg      # Example: Pranav's photo
│   ├── VITCC52288.jpg     # Example: XYZ's photo
│   └── ...                # Add more user images here
├── Resources/             # Supporting resources for the UI
│   ├── background.png     # Background for the system interface
│   ├── Modes/             # Modes directory for dynamic UI states
│   │   ├── mode1.png      # Mode 1 display
│   │   ├── mode2.png      # Mode 2 display
│   │   └── ...            # Additional modes
├── EncodeFile.p           # Encoded file containing facial data
├── serviceAccountKey.json # Firebase service account key
├── upload_images.py       # Script to encode and upload images to Firebase
├── add_data_to_database.py# Script to initialize and populate Firebase
├── main.py                # Main application script for real-time attendance
├── requirements.txt       # List of dependencies for the project
└── README.md              # Project documentation
```

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

   ![image](https://github.com/user-attachments/assets/112da583-0084-4612-aadb-c8a5ed748222)

   - Screenshort 2

   ![image](https://github.com/user-attachments/assets/bf9239d9-0ef7-431c-8179-91941572bbd6)

1. **Attendance Logging in Firebase**
   - Images Stored in Firebase:
   
   ![image](https://github.com/user-attachments/assets/3476eb3f-0d4f-4169-808f-2e1a821b6f9b)

   - Student’s details and records Stored in data base:

   ![image](https://github.com/user-attachments/assets/eaa93f0e-0141-49f6-bf24-1e3166a3279a)
   
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



- **credentials:** "serviceAccountKey.json" // Change your credentials for here.
- **databaseURL:** "https://attendancemanagementcc-default-rtdb.firebaseio.com/",
- **storageBucket:** "attendancemanagementcc.appspot.com"
