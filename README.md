# Face Recognition Attendance System

This is a Python-based Face Recognition Attendance System that automates the process of marking attendance using facial recognition technology. It utilizes the `face_recognition` library to detect and recognize faces through a webcam and logs the attendance into a CSV file.

## 📌 Features

- Real-time face recognition using webcam
- Attendance marking with date and time
- Stores attendance in CSV format
- Simple and clean codebase for easy understanding
- Jupyter Notebook included for step-by-step explanation

## 🛠️ Tech Stack

- Python 3
- OpenCV
- face_recognition
- NumPy
- Pandas
- Jupyter Notebook

## 📁 Project Structure

```
Face_Recognition-Attendance_System/
│
├── program.py                         # Main script to run the attendance system
├── Code.ipynb                         # Jupyter Notebook version of the implementation
├── PY-REPORT[1].pdf                   # Final report describing the project
├── Automated-Attendance-System.pptx  # PowerPoint presentation for the project
├── Attendance.csv                     # Automatically generated file storing attendance
└── README.md                          # Project description and instructions
```

## ⚙️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/balaji-mallepalli/Face_Recognition-Attendance_System.git
   cd Face_Recognition-Attendance_System
   ```

2. **Install dependencies:**
   ```bash
   pip install opencv-python face_recognition numpy pandas
   ```

3. **Run the script:**
   ```bash
   python program.py
   ```

4. **Add known faces:**
   - Store reference images of people inside a folder (e.g., `images/`) before running the program.
   - Make sure filenames are named after the person (e.g., `john_doe.jpg`).

## 📝 Output

- When a known face is recognized, their name along with the current date and time is added to `Attendance.csv`.
- Faces not recognized will be ignored.

## 📚 Documentation

For detailed explanation and demo, refer to:

- `Code.ipynb` – walkthrough of the code and logic
- `PY-REPORT[1].pdf` – project report
- `Automated-Attendance-System.pptx` – presentation slides

## 🙏 Acknowledgements

- [face_recognition](https://github.com/ageitgey/face_recognition)
- [OpenCV](https://opencv.org/)
- Inspired by practical needs of automating attendance in educational institutions and workplaces.

---

> 📌 *Note: This project is for educational/demo purposes. For deployment in real-time applications, additional enhancements (like database storage, UI, error handling, and security) are recommended.*
