🚀 JobPortal - Full-Stack MERN ApplicationA dynamic and responsive job recruitment platform built with the MERN Stack (MongoDB, Express, React, Node.js). This application connects job seekers with employers, allowing for seamless job postings, applications, and profile management.🛠️ Tech StackFrontendReact.js – UI ComponentsTailwind CSS – StylingRedux Toolkit – State ManagementLucide React – IconsBackendNode.js & Express.js – Server & APIMongoDB & Mongoose – Database & SchemaJWT (JSON Web Token) – AuthenticationBcryptjs – Password HashingCloudinary – Image/Logo HostingDataURI – File processing✨ FeaturesUser Roles: Separate workflows for Job Seekers and Recruiters.Authentication: Secure Sign-up/Login with JWT and cookie-based sessions.Job Management: Recruiters can post, edit, and delete job listings.Application System: Students can search for jobs, filter by category/location, and apply.Profile Management: Upload profile photos and resumes (integrated with Cloudinary).Admin Dashboard: Recruiters can view all applicants for a specific job and change application status (Pending/Accepted/Rejected).📂 Project StructurePlaintextjobportal-yt-main/
├── backend/            # Express server, API routes, and DB logic
│   ├── controllers/    # Request handlers
│   ├── models/         # Mongoose schemas
│   ├── routes/         # API endpoints
│   ├── utils/          # Cloudinary, DB connection, DataURI
│   └── index.js        # Entry point
├── frontend/           # React application (Vite-based)
│   ├── src/
│   │   ├── components/ # Reusable UI components
│   │   ├── redux/      # Store and Slices
│   │   └── pages/      # Main views (Home, Jobs, Browse)
└── .env                # Environment variables (not tracked by Git)
🚀 Getting Started1. PrerequisitesNode.js installedMongoDB Atlas account (or local MongoDB)Cloudinary account (for image uploads)2. InstallationClone the repository:Bashgit clone https://github.com/your-username/jobportal.git
cd jobportal
Setup Backend:Bashcd backend
npm install
Setup Frontend:Bashcd ../frontend
npm install
3. Environment VariablesCreate a .env file in the backend folder and add the following:Code snippetPORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUD_NAME=your_cloudinary_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret
4. Running the AppStart Backend:Bash# Inside the backend folder
npm run dev
Start Frontend:Bash# Inside the frontend folder
npm run dev
🔗 API Endpoints (Samples)MethodEndpointDescriptionPOST/api/v1/user/registerRegister a new userPOST/api/v1/user/loginUser loginPOST/api/v1/job/postPost a new job (Recruiter only)GET/api/v1/job/getGet all jobsPOST/api/v1/application/apply/:idApply for a specific job🤝 ContributingContributions are welcome! Please fork the repo and submit a pull request.📄 LicenseThis project is licensed under the ISC License.Would you like me to help you write the specific controller logic for your job application routes or assist with setting up the Cloudinary configuration?Job Portal Project OverviewThis video provides a comprehensive guide on building a full-stack MERN project, which is highly relevant to the structure and features of your job portal.
