# Pharmacy-Management-System
🏥 A Pharmacy Management System built with Flutter and Firebase. Features real-time inventory tracking, proactive expiry alerts, and automated POS billing. Developed during the Google Android Developer Virtual Internship 2025-26.  Topics: flutter, firebase, android-development, pharmacy-management, dart, firestore, real-time-database                                                                                                                                                                                                                   
✨ Key Features
Secure Authentication: User login and registration powered by Firebase Auth (Email/Password or Google Sign-in).

Real-time Inventory: Live tracking of medicine stocks and expiry dates using Cloud Firestore.

Sales Tracking: Record transactions instantly with automated stock deduction.

Cloud Storage: Securely store medicine images and prescription scans using Firebase Storage.

Offline Support: Seamless performance even with intermittent internet connectivity via Firestore's local persistence.

Role-Based Access: Categorized access for Admin (Full control) and Staff (Sales only). 

🛠️ Tech Stack
Frontend: Flutter (Dart)

Backend/Database: Firebase Cloud Firestore

Authentication: Firebase Auth

Storage: Firebase Storage

⚙️ Installation & Setup
1. Quick Test (APK)
Download Pharmacy Management (1).apk from this repository.

Transfer the file to your Android device.

Enable "Install from Unknown Sources" in settings and install.

2. Developer Setup (Source Code)
Clone the Repo:

Bash
git clone https://github.com/AXELBLAZEEEE/Pharmacy-Management-System.git
cd Pharmacy-Management-System
Install Dependencies:

Bash
flutter pub get
Firebase Configuration:

Create a project in the Firebase Console.

Download your google-services.json and place it in the android/app/ directory.

Enable Email/Password Auth and Cloud Firestore.

Run the App:

Bash
flutter run
