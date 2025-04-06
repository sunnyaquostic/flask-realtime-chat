# 🔥 Advanced Real-Time Chat App

A full-featured real-time chat application built with **Flask** and **Socket.IO**, featuring multiple chat rooms, private messaging, and active user tracking. It runs entirely in-memory and is perfect for learning, small group discussions, or as a foundation for larger systems.

---

## 🚀 Features

- ✅ Real-time communication with Socket.IO
- ✅ Multiple chat rooms (General, Code with Josh, etc.)
- ✅ Private messaging with `@username` syntax
- ✅ Active user list that updates live
- ✅ Join/leave notifications
- ✅ Room switching with preserved message history (in-memory)
- ✅ Clean UI & user experience
- ✅ Guest usernames generated automatically
- ✅ Supports CORS configuration and proxy headers

---

## 📸 Screenshots

> (Optional: Add screenshots or screen recordings here)

---

## 🛠 Tech Stack

- **Backend**: Python, Flask, Flask-SocketIO
- **Frontend**: HTML, CSS, Vanilla JS
- **Socket Transport**: WebSockets (via Socket.IO)
- **Session Management**: Flask session
- **Templating**: Jinja2

---

## 🧪 Setup Instructions

### 📦 Requirements

- Python 3.8+
- `pip` (Python package manager)

### 🔧 Installation

```bash
# Clone the repo
git clone https://github.com/sunnyaquostic/flask-realtime-chat.git
cd flask-realtime-chat

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

⚙️ Run the App
python app.py
Or using Flask’s CLI:

export FLASK_APP=app.py

flask run
Then open your browser to:
http://localhost:5000

📁 Project Structure

├── app.py
├── templates/
│   └── index.html
├── static/
│   ├── chat.js
│   └── styles.css
├── requirements.txt
└── README.md
🌐 Environment Variables (Optional)
You can set environment variables for customization:


export SECRET_KEY="your_secret"
export FLASK_DEBUG=True
export CORS_ORIGINS="http://localhost:5000"

🙌 Acknowledgements
Flask

Flask-SocketIO

Socket.IO

