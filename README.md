# 💬 Web Chat Application

A real-time web chat application built with modern web technologies. Users can join chat rooms, send instant messages, and communicate in real-time with others online.

## 🚀 Features

- Real-time messaging using WebSockets (Socket.IO)
- User authentication and login/logout
- Chat rooms for group conversations
- Message history per room
- Responsive UI for mobile and desktop

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript (React/Vanilla)
- **Backend:** Node.js, Express.js
- **Real-time Communication:** Socket.IO
- **Database:** MongoDB / Firebase / (optional)

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/web-chat-app.git
cd web-chat-app
2. Install Dependencies
bash
Copy
Edit
# Install backend dependencies
cd server
npm install

# (Optional) Install frontend dependencies
cd ../client
npm install
3. Run the Application Locally
Start the Backend Server
bash
Copy
Edit
cd server
node index.js
Start the Frontend (if using a frontend framework like React)
bash
Copy
Edit
cd ../client
npm start
If you're using a single-folder structure with vanilla HTML/CSS/JS, simply open index.html in a browser.

🔗 Usage
Open the app in your browser at http://localhost:3000 (or as specified).

Enter your name and join a chat room.

Start chatting in real time!

📁 Project Structure
pgsql
Copy
Edit
web-chat-app/
│
├── client/               # Frontend code
│   ├── public/
│   └── src/
├── server/               # Backend and Socket.IO setup
│   └── index.js
├── README.md
└── package.json


📌 Notes
Make sure MongoDB is running locally or update the DB connection string.

Ensure ports (like 3000 for frontend and 5000 for backend) are free or update in config.
