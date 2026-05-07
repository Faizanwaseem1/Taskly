# Taskly 📝
**A blazing-fast, locally persistent task management app built with Flutter.**

Taskly is a streamlined productivity tool designed for speed and reliability. By leveraging a NoSQL local database, it provides a "zero-latency" experience where tasks are saved instantly without needing an internet connection.

---

## ✨ Features
- **Instant Persistence:** Uses Hive DB for high-performance local storage.
- **Dynamic UI:** Real-time interface updates using Flutter State Management.
- **Smart Formatting:** Automatic timestamping for every task.
- **Platform Agnostic:** Built to run smoothly on both Android and iOS.

---

## 🛠️ Technical Stack
- **Framework:** [Flutter](https://flutter.dev/)
- **Language:** [Dart](https://dart.dev/)
- **Database:** [Hive](https://pub.dev/packages/hive) (NoSQL)
- **State Management:** `setState` (Scoped for efficiency)

---

## 🏗️ Architecture & Logic
The project follows a clean **Model-View-Controller** approach to separate data from the UI:

- **Data Serialization:** Implemented `fromMap` and `toMap` patterns to convert raw Hive data into Dart Objects.
- **Async Handling:** Used `FutureBuilder` to manage the database connection lifecycle.
- **Custom Models:** A robust `Task` class handles content, timestamps, and completion status.



---



---

## 🚀 Getting Started

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/Faizanwaseem1/Taskly.git](https://github.com/Faizanwaseem1/Taskly.git)
