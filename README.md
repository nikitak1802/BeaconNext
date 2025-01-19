# BeaconNext: Automated Attendance System using BLE Beacon Device
<br>
BeaconNext is an innovative attendance management system leveraging Bluetooth Low Energy (BLE) beacon technology. Designed for educational institutions and businesses, this project modernizes attendance tracking, providing a seamless, efficient, and secure solution that minimizes administrative burdens and promotes ecological sustainability.
<br>

# Features
- **Automated Attendance:** Tracks attendance effortlessly with BLE beacons in classrooms or meeting spaces. <br>
- **Real-Time Sync:** Attendance records are securely stored in MongoDB and synchronized with the cloud for instant access. <br>
- **User Authentication:** Secure login and session management using JWT Authentication and device ID restrictions. <br>
- **Mobile Application:** User-friendly Android app for students and teachers to interact with the system. <br>
- **Administrative Controls:** Administrators can manage user accounts, access detailed reports, and configure system parameters. <br>

# Benefits
- **Time-Efficient:** Reduces manual labor and errors associated with traditional attendance methods.
- **Environmentally Friendly:** Minimizes paper usage, promoting sustainability.
- **Enhanced Engagement:** Provides real-time feedback on attendance, fostering accountability.
- **Cost-Effective:** Utilizes affordable beacon technology for scalable implementation.

# Technology Stack
- **Frontend:** Android (Java, XML)
- **Backend:** Firebase (Authentication, Realtime Database, Cloud Functions)
- **Database:** MongoDB
- **Cloud:** Firebase Cloud Messaging, Cloud Storage
- **Hardware:** Bluetooth Low Energy (BLE) Beacons
- **Security:** JSON Web Tokens (JWT), Encryption Mechanisms

# System Architecture
The system follows a three-tier structure: <br>
- **BLE Beacons:** Deployed in classrooms to emit signals.
- **Mobile Applications:** For students and teachers to interact with attendance data.
- **Backend Server:** Processes data and generates reports.

# Installation and Usage

**Set Up BLE Beacons:**
- Place beacons in classrooms or meeting rooms.
- Configure beacon UUIDs securely.
<br>

**Install the Mobile App:**
- Download the Android app from the provided repository.
- Log in or create an account (student/teacher/administrator).
<br>

**Administrative Setup:**
- Configure lecture schedules and minimum attendance time.
- Monitor attendance data and generate reports via the admin portal.
<br>

**Use:**
- Students open the app within the lecture period to confirm their presence.
- Teachers track attendance and manage class data seamlessly.
