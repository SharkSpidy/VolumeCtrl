# Volume Control With Computer Vision!

### Project Description
Control your system volume like a Jedi — just by moving your fingers!
No buttons, no knobs — just the power of your hand.

### The Problem
Reaching for the volume button is sooo 2020.(Not That Im Lazy!)
Why use muscles when you can use gestures?

### The Solution
This track user's hand using a webcam, measure the distance between your fingers, and translate that into smooth(ish) volume control. It's like magic, but with math.


## Technical Details
### Technologies/Components Used
##### For Software:
    Languages: Python
    Frameworks: OpenCV, MediaPipe
    Libraries: pycaw (for audio control), numpy, comtypes
    Tools: Visual Studio Code, Python virtual environments

##### For Hardware:
    Main Component: Webcam (internal/external)
    Specs: 720p or better for best results
    Tools Required: Your fingers 


### Implementation
##### Installation
```bash
# Create a virtual environment (optional but recommended)
python -m venv .venv
source .venv/bin/activate      # On Windows: .venv\Scripts\activate

# Install dependencies
pip install opencv-python mediapipe pycaw numpy comtypes
```
##### Run  
```bash
python main.py
```


### Project Documentation
For Software:
- `main.py` — Main program for hand tracking and volume control  
- `HandTrackingModule.py` — Custom wrapper around MediaPipe for easier hand landmark detection  
- `.venv/` — Python virtual environment (not required to be pushed to GitHub)  


# Screenshots
![Screenshot1](https://github.com/SharkSpidy/VolumeCtrl/blob/main/Media/Screenshot%202025-04-22%20184934.png)

![Screenshot2](https://github.com/SharkSpidy/VolumeCtrl/blob/main/Media/Screenshot%202025-04-22%20185013.png)

![Screenshot3](https://github.com/SharkSpidy/VolumeCtrl/blob/main/Media/Screenshot%202025-04-22%20185055.png)

### Project Demo
# Video
![Video](https://github.com/SharkSpidy/VolumeCtrl/blob/main/Media/Screen%20Recording%202025-04-22%20183115.mp4)

---
Made with ❤️ by Joe (https://github.com/SharkSpidy)
