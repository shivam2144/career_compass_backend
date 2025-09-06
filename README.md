# Career Compass

Career Compass is a full-stack job portal web application that connects job seekers with recruiters. It features user authentication, job browsing and filtering, company management, job posting, and application tracking.

## Features

- **User Roles:** Student (job seeker) and Recruiter (company admin)
- **Authentication:** Signup, login, and protected routes
- **Job Search:** Browse, filter, and search jobs by title, location, and category
- **Company Management:** Recruiters can register and manage companies
- **Job Posting:** Recruiters can post and manage job listings
- **Application Tracking:** Students can apply for jobs and track their applications
- **Admin Dashboard:** Recruiters can view applicants and shortlist candidates
- **Profile Management:** Users can update their profile, skills, and upload resumes

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

## Getting Started

### Prerequisites

- Node.js (v16+)
- MongoDB instance (local or cloud)
- Cloudinary account (for file uploads)

### Backend Setup

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

### Frontend Setup

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

- Update API endpoints in `frontend/src/utils/constant.jsx` if running locally.

## Screenshots

_Add screenshots or GIFs here to showcase the UI and features._

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

## License

This project is licensed under the MIT License.

---

**Career Compass** – Empowering your career journey!
