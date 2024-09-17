# RollCall Application using Face Recognition
This is a Python-based RollCall application that leverages SIFT (Scale-Invariant Feature Transform) for face recognition and uses Tkinter for a simple graphical user interface (GUI). The system is designed to automate the attendance process by identifying employees through facial recognition and logging their entry details (name, time, and date) into a database.

# Features:
- Face Detection: The application captures the image of a person standing in front of a camera and uses SIFT to detect and extract unique facial features.
- Employee Identification: If the person is an employee, the system matches the captured face against a pre-existing database and identifies them.
- Attendance Logging: Once identified, the system logs the employee's name, time, and date of entry into a database for attendance tracking.
- Graphical User Interface: The application is equipped with a Tkinter GUI to provide an intuitive and user-friendly interface.
# How It Works:
 1-The employee stands in front of the camera at a specified distance.
 2-The application detects the face and extracts unique facial features using the SIFT algorithm.
 3-If a match is found in the employee database, the person's name is identified.
 4-The system records the employee's name along with the timestamp and date in the database for future reference.

 # Technologies Used:
- Python: Core programming language.
- SIFT Algorithm: Used for detecting and matching key facial features for face recognition.
- OpenCV: (If used) For handling camera input and image processing.
- Tkinter: For the graphical user interface (GUI).

# Prerequisites:    
- Python 3.x
- OpenCV
- Tkinter
- Database (SQLite/MySQL or others)
