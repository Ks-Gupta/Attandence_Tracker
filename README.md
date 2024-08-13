# Face Recognition Based Attendance Monitoring System

## Overview

This project is a Face Recognition-Based Attendance Monitoring System built using Python and OpenCV. The system captures images of students, trains a face recognition model, and then uses this model to track attendance by recognizing faces in real-time. The application features a graphical user interface (GUI) built with Tkinter, allowing easy interaction for registering new students, capturing images, and tracking attendance.

## Features

- **Student Registration:** Register new students by capturing their images through the webcam.
- **Face Recognition:** Train a face recognition model based on registered students' images.
- **Attendance Tracking:** Automatically record attendance by recognizing faces in real-time.
- **Password Protection:** Change the password for accessing the system's functionalities.
- **Contact Support:** Easily contact support for any issues.

## Dependencies

- Python 3.x
- Tkinter
- OpenCV
- Numpy
- Pandas
- PIL (Pillow)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/attendance-system.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd attendance-system
    ```
3. **Install the required Python packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the application:**
    ```bash
    python attendance_system.py
    ```

2. **Main Features:**
   - **New Registration:**
     - Enter the student ID and name.
     - Click "Take Images" to capture images for the new student.
     - After capturing, click "Save Profile" to train the model.
   - **Track Attendance:**
     - Click on "Track Images" to start recognizing faces and marking attendance.
   - **Change Password:**
     - Go to the "Help" menu and select "Change Password" to update the system password.
   - **View Attendance:**
     - Attendance records can be viewed in the right panel of the application.

3. **Quit the Application:**
   - Use the "Exit" option in the "Help" menu to close the application.

## File Structure

- **attendance_system.py**: Main script for running the application.
- **haarcascade_frontalface_default.xml**: Pre-trained face detection model.
- **StudentDetails/**: Directory to store student details.
- **TrainingImage/**: Directory to store captured images.
- **TrainingImageLabel/**: Directory to store the trained model.
- **Attendance/**: Directory to store attendance records.


