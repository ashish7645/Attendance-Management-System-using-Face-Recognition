# Attendance Management System using Face Recognition
The Face Recognition Attendance Management System

## Summary
A Python-based program called the **Attendance Management System** uses facial recognition technologies to automate the tracking of student attendance. OpenCV is used in this project for face detection and identification, while Tkinter is used to create an intuitive graphical user interface. It has functions for effectively monitoring attendance records, real-time facial recognition, and taking pictures for training.


---

## Features: **Face Recognition**: Marks pupils' attendance and automatically recognises their faces.
**Image Capture**: Take pictures and save them so the recognition model may be trained.
The option to manually fill up attendance data is available under **Manual Attendance**.
- **CSV Export**: Create CSV-formatted attendance reports.
**Database Integration**: Use a MySQL database to keep track of attendance.

---

The technologies utilised are as follows: **Python**, **OpenCV**, **Tkinter**, **NumPy**, **Pandas**, **MySQL**, and **Pillow**.
---
## Setup

Clone the repository ```bash ### 1.

cd attendance-management-system ``` git clone https://github.com/yourusername/attendance-management-system.git

### 2. Install Packages Needed
Install the required dependencies after making sure Python is installed on your system:
The command "bash pip install -r requirements.txt" ```

### 3. Set Up MySQL Database: To store attendance records, create a MySQL database.
- As necessary, update the code's database connection information.

#4. Get the Haarcascade
Place the Haarcascade XML file in the project directory after downloading it from the [OpenCV GitHub repository](https://github.com/opencv/opencv).

---
## Application

### 1. Capture Images: Open the GUI by running `main_Run.py`.
Enter the name and enrolment number of the student.
- To take pictures of their faces, click **"Take Images"**.

### 2. Train the Model: To train the facial recognition model, click **"Train Images"** after taking pictures.

### 3. Automatic Attendance: To begin the webcam-based facial recognition procedure, select **"Automatic Attendance"**.

### 4. Manual Attendance: To manually fill up attendance records, select the **"Manually Fill Attendance"** option.

### 5. Examine Students Who Have Registered To see the list of enrolled students and their information, navigate to the admin panel.
---
## Directory Structure
```plaintext
Attendance Management System using Face Recognition/
│
├── TrainingImage/               # Directory to store training images
├── TrainingImageLabel/          # Directory to save trained model
├── StudentDetails/              # Directory to save student details CSV
├── Attendance/                  # Directory to save attendance records
├── haarcascade_frontalface_default.xml  # Haarcascade file for face detection
├── requirements.txt             # Required Python packages
├── main_Run.py                  # Main application file
├── training.py                  # Script for training the face recognition model
├── testing.py                   # Script for testing face recognition
├── mini_app.py                  # Simple GUI application for capturing images
├── app.py                       # Streamlit app for attendance visualization
└── README.md                    # Project documentation
```
## Contributing We welcome your contributions! Feel free to fork the repository and send a pull request if you have ideas for new features or enhancements.

---

## Permit
For further information, check the [LICENSE](LICENSE) file. This project is licensed under the MIT License.

---

## Recognitions
We are especially grateful to:
- **OpenCV** for facial recognition and detecting features.
- For GUI development, use **Tkinter**.
For data analysis and manipulation, use **NumPy** and **Pandas**.
**MySQL** for database administration.

---
For any questions or issues, feel free to contact **[your email]**.

