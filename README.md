<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
</head>
<body style="font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height:1.6; max-width: 900px; margin: 0 auto; padding: 20px;">
  <h1>📝 Online Exam Web Application</h1>

  <p>
    A fully responsive and interactive online exam platform designed for students to simulate real exam conditions with a modern UI, dynamic questions, a timer, and personalized results!
  </p>

  <h2>🌟 Features</h2>
  <ul>
    <li>✅ <strong>Sign-Up & Validation:</strong> Real-time input validation with email and password checks.</li>
    <li>✅ <strong>Dynamic Question Rendering:</strong> Fetched from an external API, auto-shuffled, and rendered with radio buttons.</li>
    <li>🚩 <strong>Mark Questions:</strong> Flag questions for review with sidebar navigation.</li>
    <li>⏱️ <strong>Live Timer:</strong> Automatically submits exam when time is up.</li>
    <li>📊 <strong>Auto Grading & Result Page:</strong> Score evaluation, pass/fail messages, and timeout detection.</li>
    <li>🎉 <strong>Confetti Effects:</strong> For passing students, with animated visual celebration.</li>
  </ul>

  <h2>🛠 Tech Stack</h2>
  <ul>
    <li><strong>Frontend:</strong> HTML5, CSS3, JavaScript (Vanilla)</li>
    <li><strong>API:</strong> Mocki.io for fetching dynamic question sets</li>
    <li><strong>UI:</strong> Font Awesome, Google Fonts (Poppins)</li>
    <li><strong>Storage:</strong> LocalStorage API for storing session data</li>
    <li><strong>Effects:</strong> canvas-confetti for celebration animation</li>
  </ul>

  <h2>🧠 How It Works</h2>
  <ol>
    <li><strong>Sign-Up:</strong> User registers with validated fields; data stored in LocalStorage.</li>
    <li><strong>Exam Page:</strong> Questions are fetched via API, user selects answers, flags questions, and timer runs.</li>
    <li><strong>Submit/Timeout:</strong> On submit or time expiry, answers are scored and saved to LocalStorage.</li>
    <li><strong>Result Page:</strong> Displays message based on score, shows grade, name, and exam date.</li>
  </ol>

  <h2>🚀 Try It Out</h2>
  <p><strong>To run locally:</strong></p>

</body>
</html>
