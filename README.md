# real-time-hand-tracking

This project uses OpenCV and MediaPipe to perform real-time hand tracking via webcam. It highlights a specific fingertip (e.g., pinky finger) when detected.

## Project Structure

```
real-time-hand-tracking/
├── main.py
├── hand_tracking_module.py
├── requirements.txt
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/SyazwanDev/real-time-hand-tracking.git
cd real-time-hand-tracking
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
# Activate the environment:
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python main.py
```

## Dependencies

- [OpenCV](https://pypi.org/project/opencv-python/)
- [MediaPipe](https://pypi.org/project/mediapipe/)

## Features

- Real-time hand tracking using webcam
- Highlights the pinky fingertip
- Draws hand landmarks and connections