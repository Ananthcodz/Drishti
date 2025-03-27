# Drishti - Automated Classroom Attendance System using Facial Recognition

<p align="center">
  <img src="https://github.com/user-attachments/assets/557ef2c1-373b-43a1-885f-3edeb44d7043" alt="Drishti Logo">
</p>

## Problem Statement
Drishti aims to develop an automated classroom attendance system integrated with a mobile application for seamless attendance management.

## Objectives
- Develop a robust face recognition algorithm.
- Deploy a network of two different cameras facing each other in each classroom to detect students entering and leaving.
- Enhance the system with additional functionality for improved accuracy and usability.
- Implement distance algorithms and other techniques to prevent proxy attendance.
- Design a mobile application with separate interfaces for students and faculty to track attendance.

## Setup Instructions

### Prerequisites
- Clone the repository.
- Install the required dependencies:
  ```bash
  pip install -r requirements.txt
  ```
- Ensure you have a working Python environment.

### Database Setup
1. Add a clear image of each required person's face to the `images` folder (used for face recognition database).
   - **Note:** The file names of the images must exactly match the names in the linked Google Spreadsheet.
2. Place the JSON file required to connect to your Google Spreadsheet in the `important` folder.
   - A basic template is provided for reference.

### Configuration
- Update the **port numbers** in `attendance_copy.py` at **lines 194 and 195** to match your system configuration.

### Running the System

1. Start the attendance tracking script:
   ```bash
   python attendance_copy.py
   ```

## Features
- **Automated Attendance:** Uses facial recognition to mark attendance.
- **Real-time Tracking:** Detects students entering and exiting classrooms.
- **Proxy Prevention:** Incorporates distance algorithms to prevent fraudulent attendance.
- **Mobile Integration:** Provides distinct interfaces for students and faculty.

## Future Enhancements
- Improve accuracy with AI-driven enhancements.
- Extend support for multiple classroom environments.
- Develop a more intuitive user interface for the mobile application.

---
For any issues or contributions, feel free to submit an issue or pull request to the repository.

