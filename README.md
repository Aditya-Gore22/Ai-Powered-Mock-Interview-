# Ai-Powered-Mock-Interview-

🎯 Mock Interview Web App
This is a full-featured Mock Interview System built with HTML, CSS, JavaScript, PHP, and MySQL. It simulates real interview environments using webcam, microphone, AI-based evaluation, and speech-to-text conversion. The system helps users practice job-specific interview questions and receive feedback instantly.

🚀 Features<br>

        🎯 Select job role and generate AI-based interview questions (Gemini API)
        
        🎤 Record answers using microphone (Web Speech API for speech-to-text)
        
        🎥 Live webcam preview (face detection for presence monitoring)
        
        🧠 Real-time AI evaluation of answers (Gemini API with custom prompt)
        
        📊 Rating & feedback stored per question
        
        📁 Secure session handling and database storage (XAMPP-based)
        
        💾 Monaco Editor for coding questions (if applicable)

🧱 Tech Stack <br>

        Frontend: HTML, CSS, JavaScript
        
        Backend: PHP (without Composer)
        
        Database: MySQL (XAMPP)
        
        APIs: Gemini 2.0 Flash for question generation and evaluation
        
        AI Tools: Web Speech API, Gemini AI

🗃️ Database Tables <br>

      interviews – Stores mock questions and job details
      
      userAnswer – Stores answers, ratings, and feedback
      
      📸 Interview Experience
      Live webcam check with 3-strike face detection rule
      
      One-by-one question navigation
      
      Answer recording and auto-validation (min 10 words)

📦 How to Run<br>

    1.  Clone the repo and set up XAMPP.
      
    2.  Import the database schema provided.
      
    3.  Add your Gemini API key in the PHP files.
      
    4.  Start the Apache server and navigate to localhost.
