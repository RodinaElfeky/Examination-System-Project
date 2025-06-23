📝 Online Exam Web Application

Welcome to the Online Exam System — a fully interactive, responsive, and dynamic web app designed to simulate real exam environments for students. It includes sign-up/login, randomized questions, live timer, answer tracking, marked questions, and a detailed results page — all packed into a beautiful UI!
🌟 Features

✅ User Registration & Validation
Secure sign-up form with real-time input validation for name, email, and password fields.

✅ Dynamic Exam Page

    Questions fetched from a remote JSON API

    Options auto-rendered and shuffled per question

    Mark questions for review (🚩 flag system)

    Navigate between questions with saved state

    Live countdown timer (⏰)

✅ Submission Logic

    Modal confirmation before final submission

    Score calculated and stored

    Automatically redirects to result page on time-out or manual submission

✅ Result Page with Feedback

    Personalized message with user name and exam date

    🎉 Confetti effect for passing score

    ❌ Time-out and failure messages with animations

    Clean and responsive UI with feedback messages and icons

🛠 Tech Stack

    HTML5 & CSS3

    JavaScript (Vanilla)

    LocalStorage API

    Canvas Confetti Library

    Google Fonts (Poppins)

    Font Awesome Icons

📁 Project Structure

/ExamApp
├── /LoginSignup/         # Sign up and validation logic
├── /ExamPage/            # Exam UI, question fetcher, timer
├── /ResultPage/          # Score summary and user feedback
├── assets/               # SVG icons, images
├── style.css             # Shared styles
├── script.js             # Dynamic JS functionality
└── README.md             # This file

🧠 How It Works

    Sign Up
    ➤ Validates input and stores user info in localStorage.

    Exam Page
    ➤ Loads randomized questions from API, tracks answers, enables flagging, and runs a countdown timer.

    Submission / Time-out
    ➤ On manual submission or timeout, score is calculated and stored.

    Result Page
    ➤ Shows a customized result message based on performance and time status, with confetti 🎊 for passing!

🚀 Demo

   
