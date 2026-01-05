# Job Portal Application

A full-stack **MERN Job Portal** enabling job seekers and recruiters to interact seamlessly.

## Project Structure

### Backend
- **controllers/**: Business logic for Users, Jobs, Companies, Applications  
- **middlewares/**: JWT authentication, file uploads using Multer  
- **models/**: MongoDB schemas with Mongoose  
- **routes/**: API endpoints  
- **utils/**: Cloudinary config, DB connection, data utilities  
- **index.js**: Server entry point

### Frontend
- **src/**: React components & pages  
- **public/**: Static assets  
- **package.json**: Dependencies  
- **tailwind.config.js** & **vite.config.js**: Styling & bundler config

## Key Features
- Full-stack MERN application  
- JWT-based Role-Based Access Control (RBAC) for Admin/Recruiters and Job Seekers  
- Resume/profile image upload using Cloudinary + Multer  
- Redux Toolkit for global state management  
- Responsive UI using Tailwind CSS & Radix UI  
- Optimized database queries with Mongoose

## Tech Stack
- Frontend: React 18, Tailwind CSS, Redux Toolkit  
- Backend: Node.js, Express, MongoDB, Mongoose  
- Authentication: JWT, bcrypt  
- Media Handling: Cloudinary, Multer

## Setup Instructions
```bash
# Clone repo
git clone https://github.com/ujjawalkumar19/Project-Job-Portal.git
cd Project-Job-Portal

# Backend
cd backend
npm install
npm start

# Frontend
cd ../frontend
npm install
npm run dev
