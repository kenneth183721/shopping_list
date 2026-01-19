# Shopping List — Real-Time Flutter Grocery Tracker
A reactive mobile application built with Flutter that enables users to manage their shopping needs with instant cloud synchronization via Firebase.

[Live Demo](https://kenneth183721.github.io/shopping_list/)

- This is a Flutter mobile app project.
- Please reduce the width of the browser to simulate viewing at a phone scale.
  
## 🚀 Project Overview
Shopping List is designed for users who need a reliable, instant-sync tool for grocery management. The project focuses on integrating a NoSQL cloud backend (Firebase Realtime Database) to ensure that item additions and deletions are reflected across devices in real-time. This project highlights my ability to handle cloud integration, form validation, and reactive UI updates.

## 🛠 Tech Stack
- Framework: Flutter (Dart).
- Backend: Firebase Realtime Database.
- State Management: Reactive state updates using Flutter's built-in patterns.
- Data Handling: RESTful communication with Firebase via HTTP/JSON.

## 💡 Key Engineering Highlights
Real-Time Cloud Synchronization: Integrated Firebase Realtime Database  to handle instant data persistence. Implemented logic to ensure that whenever an item is added or removed, the local UI updates immediately through asynchronous listeners.

Dynamic Data Structuring: Developed a multi-category system where users can assign items to specific types (e.g., Dairy, Meat, Sweets) with quantity controls. This involved mapping JSON data from the cloud to custom Dart models.

Optimized CRUD Operations: Streamlined the Create and Delete workflows. Used efficient error handling to manage network latency, ensuring the UI remains responsive even during slow connections.
