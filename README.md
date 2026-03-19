URL Shortener – MERN Stack

A fully functional URL Shortener Application built using the MERN Stack (MongoDB, Express, React, Node.js).
This app allows users to shorten long URLs and easily redirect to the original link.
It also tracks usage and provides clean UI for generating short URLs.

🚀 Features

🔗 Shorten any long URL

📁 Store URLs in MongoDB

↗️ Redirect short URL → original URL

📊 Click tracking (optional)

🎨 Modern UI built with React

⚡ Fast backend API with Express + Node.js

🌐 Supports environment variables (.env)

🛠️ Tech Stack
Frontend

React.js

Axios

Tailwind / CSS (choose based on your project)

Backend

Node.js

Express.js

MongoDB + Mongoose

ShortId / NanoId (for generating unique short URLs)

📁 Project Structure

URL_SHORTNER-using-MERN-Stack/

├── client/           # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
├── server/           # Node + Express backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── server.js
│   └── package.json
├── README.md
└── .gitignore

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Priyanshu87571/URL_SHORTNER-using-MERN-Stack.git
cd URL_SHORTNER-using-MERN-Stack

📌 Backend Setup
cd server
npm install


Create a .env file:

MONGO_URI=your_mongodb_connection_string
PORT=5000
BASE_URL=http://localhost:5000


Start backend:

npm start

🌐 Frontend Setup
cd client
npm install
npm start


Frontend will run on:

http://localhost:3000
