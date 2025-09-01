🚀 LinkedIn Clone

A full-stack LinkedIn clone built with modern web technologies, featuring user authentication, profile management, posts, connections, and real-time notifications.

✨ Features

🔐 Authentication – Secure login & signup with JWT

👤 Profiles – Manage user info, skills, and professional details

🤝 Connections – Send, accept, and reject connection requests

📝 Posts & Feed – Create posts, view feeds, interact with content

🔔 Notifications – Real-time alerts for activities

☁️ Cloud Storage – Seamless image and file hosting with Cloudinary

🛠 Tech Stack
Frontend

⚛️ React.js / Next.js (Specify your choice)

🎨 Tailwind CSS / Material UI for styling

Backend

🟢 Node.js & Express.js

🍃 MongoDB with Mongoose ORM

🔑 JWT Authentication & bcrypt

Integrations

🌩 Cloudinary – Image hosting

📧 Mailtrap / Nodemailer – Email services

🛡 Dotenv – Environment variables

🚀 Getting Started
# Clone repository
git clone https://github.com/your-username/linkedin-clone.git

# Navigate to project
cd linkedin-clone

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env

# Start development server
npm run dev

🔑 Environment Variables

Add these to a .env file in the root directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
MAILTRAP_USER=your_mailtrap_user
MAILTRAP_PASS=your_mailtrap_pass

📂 Project Structure
linkedin-clone/
 ├── backend/          # API, models, controllers
 ├── frontend/         # React app
 ├── .env              # Environment variables
 ├── package.json      # Dependencies
 └── README.md         # Documentation

📡 API Endpoints
Authentication

POST /api/auth/register → Create a new account

POST /api/auth/login → Log in and receive JWT token

User

GET /api/users/:id → Fetch user profile

PUT /api/users/:id → Update user info

Connections

POST /api/connections/request → Send connection request

POST /api/connections/accept → Accept request

Posts

POST /api/posts → Create a post

GET /api/posts/feed → Get feed

🌐 Deployment
Vercel (Frontend)
npm run build
vercel deploy

Render / Railway / Heroku (Backend)

Push backend to GitHub

Connect to Render/Heroku

Add environment variables

Deploy!

🤝 Contributing

Pull requests and feature suggestions are welcome!

📜 License

MIT License © 2025 Yash Puranik