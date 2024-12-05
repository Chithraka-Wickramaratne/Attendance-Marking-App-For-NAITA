# NAITA Attendance Tracker App

This is an **Android Attendance Tracker** app designed for lecturers at the **National Apprentice and Industrial Training Authority (NAITA)**. The app leverages **NFC Technology** to allow lecturers to mark attendance for students quickly and easily. It also provides a feature to view students' attendance status.

---

## Features 🚀

### Lecturer Features
- **Login**:
  - Lecturers can log in securely using their email and password.
- **Mark Attendance**:
  - Lecturers can mark students' attendance using their mobile device with NFC capabilities.
- **View Attendance Status**:
  - Lecturers can view the attendance status of all students, including the number of days attended and missed.

### NFC Technology Integration
- **NFC-enabled Device**:
  - Lecturers can use NFC tags to mark attendance by scanning the student’s NFC card or ID.
- **Real-time Sync**:
  - Attendance records are automatically synced to **Firebase** in real-time.

### Firebase Integration
- **Firebase Authentication**:
  - Used for secure login and registration.
- **Firebase Firestore**:
  - Stores attendance records and student data.
- **Real-time Updates**:
  - Attendance data is updated in real-time on Firebase, ensuring accurate tracking.

---

## Technologies Used 🛠️

- **Android**: Java-based app development.
- **NFC Technology**: To scan NFC tags for marking attendance.
- **Firebase**: For user authentication and storing attendance data in Firestore.
  - **Firebase Authentication**: Secure login for lecturers.
  - **Firebase Firestore**: Real-time database for attendance and student records.
- **Android Studio**: IDE for Android development.

---

## Setup Instructions 📝

### Prerequisites
1. **Android Studio** (latest version).
2. **Firebase** account for project setup.
3. **NFC-enabled Android device** to test the NFC functionality.
4. **Java SDK** (version 8 or later).

---

### Installation Steps

#### 1. Clone the Repository
```bash
git clone https://github.com/Chithraka-Wickramaratne/Attendance-Marking-App-For-NAITA.git
cd naita
```

#### 2. Build the App
1. Open the project in **Android Studio**.
2. Sync the project with Gradle files to ensure all dependencies are resolved.
3. Build and run the app on an NFC-enabled Android device.

#### 3. Test the App
1. **Login**: Use the credentials of a registered lecturer to log in.
2. **Mark Attendance**: Scan a student's NFC card to mark their attendance.
3. **View Attendance**: View the attendance status for students in the respective course.

---

## Usage Instructions 📘

### Lecturer Dashboard
1. **Login**: Enter your email and password to access the dashboard.
2. **Mark Attendance**: 
   - Use your mobile device’s NFC feature to scan student NFC cards.
   - Attendance will be automatically recorded.
3. **View Attendance Status**: 
   - Navigate to the attendance status page to view the list of students and their attendance details.

---

## Challenges Faced & Solutions 💡

- **NFC Integration**: 
  - NFC technology required careful handling of device permissions and proper reading of NFC tags. This was achieved through Android's `NfcAdapter` class.
- **Firebase Authentication**:
  - Managing user authentication securely was challenging. Firebase Authentication made it easier to implement login functionality with email and password.
- **Real-time Data Sync**:
  - Ensuring real-time data sync with Firebase was implemented by leveraging Firebase Firestore's real-time capabilities.

---

## Contact 📧
For any queries or suggestions, feel free to contact:
- **Email**: `wickramaratnechithraka@gmail.com`
