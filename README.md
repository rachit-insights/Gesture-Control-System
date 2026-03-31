# ✋ Gesture Control System

A Computer Vision-based project that enables users to control system functions like volume, brightness, and mouse actions using hand gestures captured through a webcam.

## 🧠 Overview
This project uses real-time hand tracking to detect and interpret gestures. By analyzing finger positions and distances, the system performs actions such as adjusting volume, controlling brightness, and moving the mouse. It provides a touchless and intuitive human-computer interaction experience.

## 🚀 Features
- Real-time hand tracking using webcam  
- Volume control using finger distance  
- Brightness control via gestures  
- Gesture-based mouse control  
- Fast and interactive system response  

## 🛠️ Technologies Used
- Python 3.x  
- OpenCV  
- MediaPipe  
- pycaw (Volume Control)  
- screen-brightness-control (Brightness)  
- pyautogui (Mouse Control)  

## 📁 Project Structure
```env
Gesture-Control-System/
├── handTrackingModule.py  # Module for hand landmark detection
├── VolumeControl.py       # Script to control system volume via gestures
├── BrightnessControl.py   # Script to control screen brightness via gestures
├── Gesture_Mouse.py       # Script to control mouse using hand gestures
├── requirements.txt       # Project requirements
└── README.md              # Project documentation
```
## ⚙️ Setup & Installation
1. Clone the Repository:
   ```bash
   git clone https://github.com/rachit-insights/Gesture-Control-System.git
   cd Gesture-Control-System
   ```
2. Create a Virtual Environment (Optional but recommended):
   ```bash
python -m venv venv
venv\Scripts\activate
   ```
3. Install Dependencies
   

## ⚙️ How It Works
1. Webcam captures live video  
2. MediaPipe detects hand landmarks  
3. Finger positions and distances are calculated  
4. Gestures are recognized  
5. Corresponding system actions are executed

## 🧪 Usage
- Volume Control:
  ```bash
  python Volume_Control.py
  ```
  Gesture: Bringing the thumb and index finger closer decreases the volume; moving them apart increases it.

- Brightness Control:
  ```bash
  python ScreenBrightnessControl.py
  ```
  Gesture: Similar to volume control; adjusts screen brightness based on the distance between thumb and index finger.

- Mouse Control:
  ```bash
  python Gesture_Control.py
  ```
  Gestures:
    - Move Cursor: Move your index finger to control the cursor.
    - Left Click: Bring the index and middle fingers close together.
## 🙏 Acknowledgements
This project was inspired by the outstanding tutorials and educational content from [Murtaza Hassan](https://www.murtazahassan.com/), whose work in practical computer vision and real-time AI applications has been instrumental in shaping this implementation.

Special thanks to the broader open-source community for libraries like MediaPipe, OpenCV, and other tools that make gesture-based interaction accessible and exciting to build.
