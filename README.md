# Job Portal

This project is a full-stack Job Portal Website built using the MERN (MongoDB, Express.js, React, Node.js) stack. It provides a comprehensive platform for both **Recruiters** and **Students**, offering distinct functionalities tailored to their respective needs. The application emphasizes secure authentication, robust API testing, and efficient data management to deliver a reliable and scalable job search and posting experience.

## ✨ Features

### For Recruiters:
* **Job Posting:** Create and publish new job listings with detailed descriptions, requirements, and application deadlines.
* **Application Management:** View and manage applications received for their posted jobs.
* **Job Listing Management:** Edit or delete their existing job postings.

### For Students:
* **Job Browsing:** Explore available job listings based on various criteria such as skills, location, and job type.
* **Job Application:** Apply for jobs that match their skills and interests.
* **Application Tracking:** View the status of their submitted applications.

### General Features:
* **Secure Authentication:** Implemented JWT (JSON Web Tokens) for secure user registration, login, and access to protected routes.
* **Role-Based Access Control (RBAC):** Ensures that specific functionalities (e.g., posting jobs, applying for jobs) are accessible only to authorized user roles.
* **Persistent Data Storage:** All user data, job listings, and applications are securely stored in MongoDB Atlas, a cloud-hosted NoSQL database.

## 🚀 Technologies Used

* **Frontend:**
    * **React.js:** For building dynamic, responsive, and intuitive user interfaces.
* **Backend:**
    * **Node.js:** The JavaScript runtime environment for server-side logic.
    * **Express.js:** A fast, unopinionated, minimalist web framework for Node.js, used for building robust APIs.
* **Database:**
    * **MongoDB:** A NoSQL database for flexible and scalable data storage.
    * **MongoDB Atlas:** Cloud-hosted database service for high availability and easy management.
* **Authentication:**
    * **JSON Web Tokens (JWT):** For secure, stateless authentication and authorization.
* **API Testing:**
    * **Postman:** Extensively used for testing all backend APIs (GET, POST, PUT, PATCH, DELETE) and ensuring robust error handling and edge case management.

## 🛠️ Installation and Setup

To get a local copy of the project up and running, follow these simple steps.

### Prerequisites

* Node.js (LTS version recommended)
* npm (Node Package Manager)
* MongoDB Atlas account (or a local MongoDB instance)

### Backend Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/aanandmrh222/Job-Portal](https://github.com/aanandmrh222/Job-Portal)
    cd Job-Portal/backend
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Create a `.env` file** in the `backend` directory and add your environment variables:
    ```
    PORT=5000
    MONGO_URI=your_mongodb_atlas_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```
    * Replace `your_mongodb_atlas_connection_string` with your actual MongoDB Atlas connection string.
    * Replace `your_jwt_secret_key` with a strong, random string for JWT signing.
4.  **Start the backend server:**
    ```bash
    npm run dev
    ```

### Frontend Setup

1.  **Navigate to the frontend directory:**
    ```bash
    cd ../frontend
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Create a `.env` file** in the `frontend` directory (if your backend is not running on `http://localhost:5000`):
    ```
    REACT_APP_BACKEND_URL=http://localhost:5000 # Adjust if your backend runs on a different port/URL
    ```
4.  **Start the frontend development server:**
    ```bash
    npm run dev
    ```

The application should now be accessible at `http://localhost:3000` (frontend) and the backend API at `http://localhost:5000`.

## 💡 Learning Outcomes

This project significantly enhanced my skills and provided strong hands-on experience in:

* **Full-Stack Application Development:** Building a complete web application from frontend to backend using the MERN stack.
* **API Design and Testing:** Designing RESTful APIs and thoroughly testing them with Postman, including handling edge cases and error scenarios.
* **Authentication and Authorization:** Implementing secure JWT-based authentication and role-based access control.
* **Database Integration:** Seamlessly integrating MongoDB Atlas with the backend for efficient data storage and retrieval.
* **Scalable Application Architecture:** Gaining insights into building scalable and maintainable web applications.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to fork the repository and create a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request
