# Smart Face Recognition Attendance System

This project is a simple face recognition based attendance system made using Python and OpenCV.

The idea is to detect a person's face using webcam and mark attendance automatically instead of doing it manually.

---

## What this project does

- Detects faces using webcam
- Recognizes trained faces
- Marks attendance automatically
- Uses basic image dataset for training

---

## How to run

1. Clone the repo

```
git clone https://github.com/Mritunjay4442/Smart-Face-Recognition-Based-Attendance-System.git
```

2. Go to project folder

```
cd Smart-Face-Recognition-Based-Attendance-System
```

3. Install required libraries

```
pip install opencv-python numpy pillow
```

4. Run the file

```
python train.py
```

---

## Important things

- Make sure your dataset images are present
- Haarcascade XML file should be in folder
- If you get image not found error (like im0.jpg), check the file path

---

## Folder structure (basic)

```
project/
 ├── train.py
 ├── setup.py
 ├── haarcascade_frontalface_default.xml
 ├── dataset/
 └── build/
```

---

## Issues I faced

- PIL module error → fixed by installing pillow
- idna module missing → installed using pip
- image file not found → path issue
- git not working in terminal → used full path

---

## Tech used

- Python
- OpenCV
- NumPy
- Pillow

---

## Future improvements

- Better UI
- Database for attendance
- Web version of project
- More accurate face recognition

---

## About me

Mritunjay Singh  
BTech IT (Final Year)  
Still learning and building projects 🙂

---

If you found this useful, you can star the repo.
