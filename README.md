
# Face Recognition Attendance System

This Python script uses face recognition to track attendance and logs it into a CSV file.

## Features

- Recognizes faces of known individuals from images.
- Logs attendance with timestamps in a CSV file for each day.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- face_recognition (`pip install face-recognition`)
- numpy (`pip install numpy`)

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shyanil/face_recognition.git
   cd face_recognition
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare face images:**
   - Add JPEG images of individuals to recognize in the `faceReconization` folder.

4. **Run the script:**
   ```bash
   python attendance_system.py
   ```

5. **Usage:**
   - The script captures video from your default camera (usually webcam).
   - It detects faces in real-time and checks them against the provided images.
   - Recognized faces are marked as "Present" in a CSV file named according to the current date (`dd-mm-yyyy.csv`).

6. **Keyboard Commands:**
   - Press `q` to quit the program.



