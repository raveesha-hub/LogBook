# 📘 Project Log Book Management System

A modern and responsive **Project Log Book Management System** developed using HTML, CSS, JavaScript, and Firebase.

This web application helps project teams record their daily activities, track individual contributions, and monitor overall project progress in one centralized platform.

## 🚀 Features

- **User Authentication** – Secure user registration and login using Firebase Authentication.
- **Dashboard** – View project activity and progress statistics.
- **Add Work Logs** – Record daily tasks and project activities.
- **Team Activity** – View work updates submitted by all team members.
- **My Updates** – View your personal work history.
- **Edit & Delete Logs** – Manage your own work log entries.
- **Work Status Tracking** – Track tasks as In Progress, Completed, or On Hold.
- **Search & Filter** – Find work logs by member, date, or status.
- **File Attachments** – Upload screenshots and documents as work evidence.
- **Real-Time Updates** – View changes using Firebase Cloud Firestore.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and responsive design |
| JavaScript | Application functionality |
| Firebase Authentication | User authentication |
| Cloud Firestore | Database management |
| Firebase Storage | File and image uploads |

## 📂 Project Structure

```text
Project-LogBook/
│
├── index.html
├── style.css
├── app.js
├── firestore.rules
├── storage.rules
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project

```bash
cd Project-LogBook
```

### 3. Configure Firebase

1. Create a project in the [Firebase Console](https://console.firebase.google.com/).
2. Register a new Web Application.
3. Enable Email/Password Authentication.
4. Create a Cloud Firestore database.
5. Enable Firebase Storage if file attachments are required.

### 4. Connect Firebase

Open the Firebase Console.
Select your Firebase project.
Go to Project Settings → General.
Find your registered Web App.
Copy the Firebase configuration.
Open app.js and replace the placeholder configuration with your Firebase project configuration.

Note: Do not include private credentials, such as Firebase Service Account private keys, in your GitHub repository.

### 5. Configure Security Rules

- Copy the contents of `firestore.rules` into Firebase Firestore Rules.
- Copy the contents of `storage.rules` into Firebase Storage Rules.
- Publish the rules.

### 6. Run the Application

Use the VS Code Live Server extension to run `index.html`.

Alternatively, run:

```bash
python -m http.server 5500
```

Open your browser and visit:

```text
http://localhost:5500
```

## 🔐 Security

- Firebase Authentication is used to authenticate users.
- Firestore Security Rules restrict users from editing or deleting other members' work logs.
- Storage Security Rules restrict file uploads to each user's own folder.
- Only authenticated users can access shared project logs.

**Note:** For a private team deployment, configure an invitation or member approval system to prevent unauthorized account registration.

## 🎯 Project Objectives

- Maintain a centralized record of project activities.
- Improve teamwork and collaboration.
- Track individual member contributions.
- Monitor project progress efficiently.
- Maintain transparency among team members.

## 🔮 Future Improvements

- Admin and Member role management.
- Project invitation system.
- Export reports as PDF.
- Advanced project analytics.
- Notification system.
- Weekly and monthly progress reports.

## 👨‍💻 Developer

Developed as a team project to simplify project activity tracking and improve team collaboration.

## 📄 License

This project is available for educational and learning purposes.
