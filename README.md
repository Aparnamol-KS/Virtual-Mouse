# Virtual-Mouse 🖱️

This project implements a virtual mouse using OpenCV, PyAutoGUI, and MediaPipe. The virtual mouse allows users to control the cursor and perform actions such as clicking and scrolling based on hand gestures.

----

## Features
+ The index finger controls the movement of the mouse cursor.
+ A click is triggered when the distance between the thumb and index finger becomes small.
+ The scroll action is performed when the distance between the middle finger and thumb decreases.

---

## Tech stack
+ Python 
+ OpenCV
+ PyAutoGUI
+ MediaPipe

---

## How to Use
+  Clone the repository or download the project files.
+  Install the required dependencies by running:
```
pip install -r requirements.txt
```
+ Once the dependencies are installed, run the script:
```
python virtual_mouse.py
```
+ The webcam will activate, and hand gestures will be detected. The index finger will control the cursor, and the thumb and index finger gesture will simulate a click.

  
