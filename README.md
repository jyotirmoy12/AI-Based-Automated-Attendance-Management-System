# Face Recognition Attendance System

Real -Time Automated attendance system using facial recognition with Python and OpenCV. Captures attendance with timestamps and exports to CSV.

## Requirements

```bash
opencv-python
numpy
face-recognition
```

## Setup

1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Create 'Training_images' folder and add one clear face photo per person
4. Run: `main.py`

## Usage

- System auto-detects faces from webcam
- Matches with training images
- Logs attendance in CSV with timestamp
- Press Enter to exit

## Project Structure
```
├── Training_images/     # Training face images
├── Attendance.csv       # Attendance records
└── main.py             # Main script
```

## Features

- Real-time face detection
- Automatic attendance logging
- CSV export
- Duplicate entry prevention
