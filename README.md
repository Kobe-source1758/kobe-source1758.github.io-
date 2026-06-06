# 📱 Family Circle - Feedback Tracker

[![Flutter Version](https://img.shields.io/badge/Flutter-v3.22+-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![Firebase Engine](https://img.shields.io/badge/Firebase-Firestore%20%26%20Auth-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Family Circle** is a cross-platform mobile application designed to empower users to securely report child safety concerns and submit structural app feedback. Built using Flutter and backed by Google Firebase, the app features robust, real-time data sync, secure user authentication, and fully optimized Firestore compound queries.

---

## ✨ Features

* 🔒 **Secure Authentication:** User sign-in/sign-up handled natively via Firebase Auth.
* 📬 **Direct Feedback pipeline:** Submit text-based feedback tied directly to the user's encrypted unique ID (`uid`).
* 🕒 **Real-Time History:** A dynamic, timestamp-sorted stream (`StreamBuilder`) that allows users to monitor their past submissions chronologically.
* 🛡️ **Safety Compliant:** Integrated mechanisms to meet Google Play's strict Child Sexual Abuse Material (CSAE) reporting criteria.

---

## 🛠️ Tech Stack & Architecture

* **Frontend Framework:** Flutter (Dart)
* **Backend Database:** Cloud Firestore (NoSQL)
* **Authentication:** Firebase Auth
* **State Management:** Streams & ChangeNotifiers

---

## 🚀 Getting Started

Follow these steps to clone the repository, link your personal Firebase instance, and run the app locally.

### Prerequisites

Ensure you have the following software installed on your machine:
* [Flutter SDK](https://docs.flutter.dev/get-started/install) (v3.22.0 or higher)
* [Dart SDK](https://dart.dev/get-started/sdk)
* [Firebase CLI](https://firebase.google.com/docs/cli) (Required for configuration generation)
* An Android/iOS Emulator or a physical testing device.

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/family-circle.git](https://github.com/yourusername/family-circle.git)
cd family-circle
