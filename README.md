🌍 Career Compass

  🚀 A full-stack Career Compass that bridges the gap between job seekers and recruiters. It features user authentication, job browsing and filtering, company management, job posting, and application tracking.


## ✨ Features

✅ **User Roles** – Students (Job Seekers) & Recruiters (Company Admins)  

✅ **Authentication** – Secure signup/login with JWT & cookies  

✅ **Job Search** – Browse, filter, and search jobs by title, category & location  

✅ **Company Management** – Recruiters can register & manage company profiles  

✅ **Job Posting** – Recruiters can post and manage job listings  

✅ **Application Tracking** – Students can apply for jobs & track status  

✅ **Admin Dashboard** – Recruiters can view applicants & shortlist candidates  

✅ **Profile Management** – Update profile, add skills & upload resumes  


## Tech Stack

- **Frontend:** React, Redux Toolkit, Vite, Tailwind CSS, Radix UI, Axios
- **Backend:** Node.js, Express, MongoDB, Mongoose, Cloudinary (for file uploads)
- **Authentication:** JWT, Cookies
- **Deployment:** Vercel (Frontend), Render (Backend)

## Project Structure

```
backend/
  controllers/
  middlewares/
  models/
  routes/
  utils/
  .env
  index.js
  package.json

frontend/
  src/
    components/
    redux/
    hooks/
    utils/
    App.jsx
    index.css
  public/
  package.json
  tailwind.config.js
  vite.config.js
```

🚀 Getting Started

### Prerequisites

- Node.js (v16+)
- MongoDB instance (local or cloud)
- Cloudinary account (for file uploads)

⚙️ Backend Setup

1. Navigate to the `backend` folder:
    ```sh
    cd backend
    ```
2. Install dependencies:
    ```sh
    npm install
    ```
3. Create a `.env` file and add your environment variables:
    ```
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    CLOUDINARY_CLOUD_NAME=your_cloudinary_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    ```
4. Start the backend server:
    ```sh
    npm run dev
    ```

🎨 Frontend Setup

1. Navigate to the `frontend` folder:
    ```sh
    cd frontend
    ```
2. Install dependencies:
    ```sh
    npm install
    ```
3. Start the frontend development server:
    ```sh
    npm run dev
    ```

### Environment Variables

⚠️ Update API endpoints in `frontend/src/utils/constant.jsx` if running locally.

📸 Screenshots

<img width="1920" height="1200" alt="Screenshot (3426)" src="https://github.com/user-attachments/assets/fde82c20-7fee-46d7-a912-e125b67f6e70" />
<img width="1920" height="1200" alt="Screenshot (3427)" src="https://github.com/user-attachments/assets/16c44f42-44ee-4d50-a5e0-4d8c8ebe30dd" />

<img width="1920" height="1200" alt="Screenshot (3428)" src="https://github.com/user-attachments/assets/80f8d96c-aa8a-4136-bfc5-7d8a51038d1d" />

<img width="1920" height="1200" alt="Screenshot (3429)" src="https://github.com/user-attachments/assets/5ebe9846-f63a-4a75-9097-b7d1cb71b50f" />
<img width="1920" height="1200" alt="Screenshot (3430)" src="https://github.com/user-attachments/assets/a14baadf-237b-481c-b863-6e8fec07565b" />

<img width="1920" height="1200" alt="Screenshot (3431)" src="https://github.com/user-attachments/assets/35f3b9cd-1ba8-4c59-8dda-e1bc4c1f2815" />

<img width="1920" height="1200" alt="Screenshot (3432)" src="https://github.com/user-attachments/assets/8dae9b85-7e00-444e-8ee9-10e8a743609c" />

<img width="1920" height="1200" alt="Screenshot (3433)" src="https://github.com/user-attachments/assets/61623fdc-9cf7-4141-a9ea-cc5039b15603" />

<img width="1920" height="1200" alt="Screenshot (3434)" src="https://github.com/user-attachments/assets/1eaef6d8-41cf-43ec-970f-1e00d8e0efa0" />

<img width="1920" height="1200" alt="Screenshot (3435)" src="https://github.com/user-attachments/assets/12a1c543-fc67-41c5-a6cd-63519a6adc9a" />


<img width="1920" height="1200" alt="Screenshot (3436)" src="https://github.com/user-attachments/assets/e7228b0c-8991-42ad-b810-6651f359f532" />

<img width="1920" height="1200" alt="Screenshot (3437)" src="https://github.com/user-attachments/assets/92591d0a-24a0-4d93-8a71-c3d41c91ae62" />

<img width="1920" height="1200" alt="Screenshot (3445)" src="https://github.com/user-attachments/assets/2f45ff0e-f5bc-481c-b209-b6ed81024383" />

<img width="1920" height="1200" alt="Screenshot (3438)" src="https://github.com/user-attachments/assets/481e316e-bd0b-401f-b65a-557e91073152" />

<img width="1920" height="1200" alt="Screenshot (3439)" src="https://github.com/user-attachments/assets/b24e5675-eafd-444f-af2e-f7f6f6affe6c" />


<img width="1920" height="1200" alt="Screenshot (3440)" src="https://github.com/user-attachments/assets/347166fa-34c6-4ec9-ae86-8667596a58c3" />


<img width="1920" height="1200" alt="Screenshot (3441)" src="https://github.com/user-attachments/assets/5ce80508-79d1-416f-8fb8-0e41d03ea17d" />

<img width="1920" height="1200" alt="Screenshot (3442)" src="https://github.com/user-attachments/assets/3eb00282-76d6-46ef-900a-9fd021429881" />


<img width="1920" height="1200" alt="Screenshot (3443)" src="https://github.com/user-attachments/assets/259ead3e-9e6b-4a36-aa7d-a4ad86213a28" />


<img width="1920" height="1200" alt="Screenshot (3444)" src="https://github.com/user-attachments/assets/4d890cec-c77e-4686-9abd-013551607abc" />


<img width="1920" height="1200" alt="Screenshot (3445)" src="https://github.com/user-attachments/assets/8e27ae01-4151-4f6e-b064-2f7f86e98375" />


<img width="1920" height="1200" alt="Screenshot (3446)" src="https://github.com/user-attachments/assets/d9d15008-f814-43ad-91eb-d34e223abec6" />



##🌐 Deployment

 **Frontend ** → Vercel
 **Backend  ** → Render

**Career Compass** – Empowering your career journey!
