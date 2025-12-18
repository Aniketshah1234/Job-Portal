Job Portal – MERN Stack Application

A full-stack Job Portal web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
This platform allows job seekers to search and apply for jobs and recruiters/admins to post and manage job listings.

🚀 Features
👤 Authentication & Authorization
1.User registration & login (JWT based)
2.Role-based access (Job Seeker / Recruiter / Admin)
3.Secure password hashing using bcrypt
💼 Job Management
1.Post new job openings
2.Update & delete job posts
3.View all available jobs
4.Search and filter jobs
📄 Applications
1.Job seekers can apply for jobs
2.Recruiters can view applicants
3.Resume upload support (Cloudinary)
🧩 Other Features
RESTful APIs
1.MongoDB database with Mongoose
2.Environment variable support
3.Modular backend structure
4.Modern React frontend (Vite)
🛠 Tech Stack
Frontend
React.js
Vite
Tailwind CSS
Backend
Node.js
Express.js
MongoDB
Mongoose
JWT (Authentication)
Nodemon
📂 Project Structure
jobportal-yt-main/
│
├── backend/
│   ├── routes/
│   │   ├── user.route.js
│   │   ├── job.route.js
│   │   ├── company.route.js
│   │   └── application.route.js
│   ├── utils/
│   │   ├── db.js
│   │   ├── cloudinary.js
│   │   └── datauri.js
│   ├── index.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
│
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/job-portal-mern.git
cd job-portal-mern

2️⃣ Backend Setup
cd backend
npm install

Create a .env file inside backend:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret


Run backend server:

npm run dev


Backend will run at:

http://localhost:5000

3️⃣ Frontend Setup

Open a new terminal:

cd frontend
npm install
npm run dev


Frontend will run at:

http://localhost:5173

🔑 API Overview (Sample)
Method	Endpoint	Description
POST	/api/user/register	Register user
POST	/api/user/login	Login user
POST	/api/job/create	Create job
GET	/api/job/all	Get all jobs
POST	/api/application/apply	Apply for job
🌐 Deployment
Frontend
Vercel
Netlify
Backend
Render
Railway
Cyclic
AWS EC2

⚠️ Note: GitHub Pages does not support backend (Node.js).

📌 Future Enhancements
Admin dashboard
Job recommendations
Email notifications
Analytics & reports
Resume parsing

👨‍💻 Author

Aniket Shah
B.Tech | MERN Stack Developer
GitHub: https://github.com/Aniketshah1234
