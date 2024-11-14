MERN Job Portal Project

A full-stack job portal application built with the MERN stack (MongoDB, Express, React, Node.js) that allows users to search, apply, and manage job postings. It includes an admin panel to manage users, jobs, and applications efficiently. This project aims to provide a real-world application experience for developers, focusing on backend functionality, user authentication, and job management.
Features

    User Authentication: Secure login and registration for both job seekers and recruiters.
    Job Management: Create, update, and delete job postings with comprehensive search and filter options.
    Application Tracking: Allows users to apply for jobs and track their application status.
    Admin Panel: Admins can manage users, companies, job listings, and applications from a dedicated panel.
    File Uploads: Users can upload resumes and other necessary documents through Multer.
    State Management: Redux Toolkit is used to manage global state for smooth interactions across the application.

Technology Stack

    Frontend: React.js, Vite, Tailwind CSS
    Backend: Node.js, Express.js
    Database: MongoDB Atlas
    State Management: Redux Toolkit
    File Uploads: Multer for handling file uploads


Installation

    Clone the Repository:

git clone https://github.com/yourusername/job-portal.git

Install Dependencies: Navigate to both backend and frontend folders and run:

npm install

Set up Environment Variables: Create a .env file in the backend directory and add the following:

MONGO_URL=<Your MongoDB connection string>
PORT=8000
SECRET_KEY=<Your secret key>

Run the Application: In the backend folder, start the server:

npm start

In the frontend folder, start the React application:

    npm run dev

Folder Structure

    backend/ - Contains server code, API routes, and controllers.
        controllers/ - Logic for managing users, jobs, applications, and companies.
        models/ - MongoDB schemas for database models.
        routes/ - API endpoints for different functionalities.
    frontend/ - Contains React application code, components, and pages.
        src/components/ - Reusable UI components.
        src/pages/ - Main pages like Job List, Job Details, Admin Dashboard.


To create a clear and detailed README file for your MERN Job Portal project, here’s a well-structured outline that explains each aspect effectively:
MERN Job Portal Project

A full-stack job portal application built with the MERN stack (MongoDB, Express, React, Node.js) that allows users to search, apply, and manage job postings. It includes an admin panel to manage users, jobs, and applications efficiently. This project aims to provide a real-world application experience for developers, focusing on backend functionality, user authentication, and job management.
Features

    User Authentication: Secure login and registration for both job seekers and recruiters.
    Job Management: Create, update, and delete job postings with comprehensive search and filter options.
    Application Tracking: Allows users to apply for jobs and track their application status.
    Admin Panel: Admins can manage users, companies, job listings, and applications from a dedicated panel.
    File Uploads: Users can upload resumes and other necessary documents through Multer.
    State Management: Redux Toolkit is used to manage global state for smooth interactions across the application.

Technology Stack

    Frontend: React.js, Vite, Tailwind CSS
    Backend: Node.js, Express.js
    Database: MongoDB Atlas
    State Management: Redux Toolkit
    File Uploads: Multer for handling file uploads

Installation

    Clone the Repository:

git clone https://github.com/yourusername/job-portal.git

Install Dependencies: Navigate to both backend and frontend folders and run:

npm install

Set up Environment Variables: Create a .env file in the backend directory and add the following:

MONGO_URL=<Your MongoDB connection string>
PORT=8000
SECRET_KEY=<Your secret key>

Run the Application: In the backend folder, start the server:

npm start

In the frontend folder, start the React application:

    npm run dev

Folder Structure

    backend/ - Contains server code, API routes, and controllers.
        controllers/ - Logic for managing users, jobs, applications, and companies.
        models/ - MongoDB schemas for database models.
        routes/ - API endpoints for different functionalities.
    frontend/ - Contains React application code, components, and pages.
        src/components/ - Reusable UI components.
        src/pages/ - Main pages like Job List, Job Details, Admin Dashboard.

Screenshots
 ![image](https://github.com/user-attachments/assets/a70d8812-e4eb-4170-838d-8fcd6c6bb230)
![image](https://github.com/user-attachments/assets/d4c4245c-f72f-4efc-b1b1-2f744efc5e64)
![image](https://github.com/user-attachments/assets/3031d18a-357a-4a65-9e99-a87efa076d2f)
![image](https://github.com/user-attachments/assets/9d697bd9-be96-48bd-801d-966ae64dfb06)


Future Enhancements

    Notifications: Implement job alerts and notifications for users.
    User Profiles: Allow users to edit profiles and save job preferences.
    Company Reviews: Enable users to review and rate companies.
