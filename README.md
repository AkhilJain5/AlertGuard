# AlertGuard - Drowsiness Detection System

## Overview

AlertGuard is a drowsiness detection system that uses computer vision techniques to monitor a user's facial features and alert them if signs of drowsiness are detected. This system employs the dlib library for facial landmark detection and analysis, along with computer vision and image processing libraries for real-time monitoring.

## Prerequisites

Before using AlertGuard, ensure you have the following prerequisites installed:

- Python 3.x
- Pip (Python package installer)

Install the required libraries using the following command:

```bash
pip install opencv-python numpy dlib imutils pygame
```
## Setup Instructions

1. **Download Code:**
   - Clone or download the AlertGuard repository:
     ```bash
     git clone <repository-link>
     ```
   - Or download the ZIP file from [GitHub](<repository-link>) and extract it.

2. **Download Shape Predictor 68 Landmarks File:**
   - Download the shape predictor 68 landmarks file from [Kaggle](https://www.kaggle.com/datasets/sajikim/shape-predictor-68-face-landmarks/data).

3. **Organize Files:**
   - Move the downloaded shape predictor file (usually named `shape_predictor_68_face_landmarks.dat`) to the project directory.

4. **Update File Paths:**
   - Open the AlertGuard code file (e.g., `alertguard.py`) in a text editor.
   - Locate and update the file paths for the shape predictor file according to your system.

5. **Install Dependencies:**
   - Install the required libraries using the following command:
     ```bash
     pip install opencv-python numpy dlib imutils pygame
     ```

6. **Run the Code:**
   - Execute the AlertGuard code by running the main script:
     ```bash
     python alertguard.py
     ```

7. **Monitor Drowsiness:**
   - The AlertGuard system will start monitoring your facial features in real-time.
   - If signs of drowsiness are detected, the system will trigger an alert to notify the user.

##  Additional Notes:
   - Customize the system parameters in the code for optimal performance.
   - Adjust camera settings if using an external camera.
   - Ensure proper lighting conditions for accurate facial feature detection.
