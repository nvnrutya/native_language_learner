Native Language Learner 🌍📚
A language learning web platform designed to help preserve and promote native languages.
Built with a simple yet engaging interface, it enables users to learn, practice, and track progress in their chosen language.

🚀 Features
Interactive Word Display – Shows words/phrases in the target language.

Progress Tracking – Keeps a record of your learning journey.

Responsive Design – Works seamlessly on desktop and mobile.

Audio Pronunciation (TTS) – Uses Text-to-Speech APIs for accurate pronunciation.

User Authentication – Secure sign-up and login system.

Dynamic Content Loading – AJAX for smooth learning experience.

🛠️ Tech Stack
Frontend:

HTML5, CSS3, JavaScript (Vanilla)

Responsive design for mobile compatibility

Backend:

Node.js, Express.js

MongoDB for database storage

APIs & Services:

Text-to-Speech API for pronunciation

LocalStorage for optional offline progress

📂 Project Structure
csharp
Copy
Edit
native_language_learner/
│
├── public/         # Static files (HTML, CSS, JS)
├── routes/         # Express routes
├── models/         # MongoDB schemas
├── app.js          # Server entry point
├── package.json    # Project dependencies
└── README.md       # Project documentation
⚡ Installation & Setup
Clone the repository

bash
Copy
Edit
git clone https://github.com/nvnrutya/native_language_learner.git
cd native_language_learner
Install dependencies

bash
Copy
Edit
npm install
Configure environment variables

Create a .env file in the root directory and add:

ini
Copy
Edit
PORT=5000
MONGODB_URI=your_mongodb_connection_string
Run the application

bash
Copy
Edit
npm start
Open http://localhost:5000 in your browser.
