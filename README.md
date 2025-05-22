# NaanMudhalvan-Project


Personalized Content Recommender Chatbot
A simple AI-powered chatbot that offers personalized content recommendations based on user interests. This project features a web-based frontend (index.html) and a Flask-based backend (app.py).

🧠 Features
Understands user-stated interests (e.g., "I'm interested in technology, health").
Offers tailored content suggestions across categories like Technology, Sports, Health, and Entertainment.
Simple and interactive chat-based UI.
Built with HTML/CSS/JS (frontend) and Flask (backend).
📁 Project Structure
. ├── index.html # Frontend UI ├── app.py # Flask backend server

🚀 Getting Started
Prerequisites
Python 3.x
Flask
Installation
Clone this repository: bash git clone https://github.com/yourusername/content-recommender-chatbot.git cd content-recommender-chatbot

Install dependencies:

bash pip install flask flask-cors

Run the Flask app:

bash python app.py

Open index.html in your browser or serve it via a local HTTP server.

📦 API Endpoint
/chat – POST
Request:

json { "user_id": "user_001", "message": "I'm interested in technology, health" }

Response:

json { "response": "Got it! You're interested in technology, health." }

📌 Example Flow
User: "I'm interested in technology, health"
Bot: "Got it! You're interested in technology, health."
User: "Can you recommend me something?"
Bot: "Here are some recommendations: ..."
🛠️ Future Improvements
NLP-based intent recognition.
Persistent user profiles.
Multilingual support.
🙌 Acknowledgments
Inspired by the need for smarter customer engagement and personalized recommendations.

🙌 Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
