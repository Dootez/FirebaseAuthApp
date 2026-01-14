# 🔐 Firebase Authentication App (Kotlin)

Android application developed in **Kotlin** that implements **user login and registration** using **Firebase Authentication**.  
This project was created as an academic practice, focusing on both functionality and **application security**.

---

## 📱 Features

- User registration with email and password
- User login using Firebase Authentication
- Navigation between Login and Register screens
- Authentication fully managed by Firebase
- Simple UI built with **Jetpack Compose**

---

## 🛠️ Technologies Used

- **Kotlin**
- **Android Studio**
- **Jetpack Compose**
- **Firebase Authentication**
- **Gradle (Kotlin DSL)**

---

## 🔥 Firebase

This project uses **Firebase Authentication** with the following method:

- Email / Password

All registered users are managed directly from the Firebase Console.

---

## 🔐 API KEY Security

In Android applications, the API KEY cannot be completely hidden because it is part of the client-side code.  
To protect it, the following security measures have been applied:

- API KEY restricted by:
  - Application package name
  - SHA-1 fingerprint
- API access limited only to Firebase services
- Secure password handling through Firebase Authentication (no passwords are stored in the app)

These measures prevent the API KEY from being used by unauthorized applications or environments.

---

## 🚀 Installation & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git

2. Open the project in Android Studio.

3. Add your google-services.json file inside the app/ directory.

4. Enable Email/Password authentication in Firebase Authentication.

5. Run the app on an emulator or physical device.

---

## 🧪 Testing

User registration tested successfully

Login with existing users verified

Users visible and managed in Firebase Console

---
📚 Academic Purpose

This project was developed as part of the Higher Technician in Multiplatform Application Development (DAM) program, with the goal of learning:

Mobile app authentication

Firebase integration

Security best practices in Android development

---

👨‍💻 Author

Eneko
Higher Technician in Multiplatform Application Development (DAM) Student

---

📄 License

Educational project – non-commercial use.
