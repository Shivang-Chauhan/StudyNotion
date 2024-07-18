# StudyNotion

Welcome to StudyNotion! This repository contains the code for a full-stack educational technology website built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The website provides a platform for students and educators to connect, share resources, and engage in interactive learning experiences.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User Authentication**: Secure user registration and login with JWT authentication.
- **Course Management**: Educators can create, update, and delete courses.
- **Enrollment**: Students can enroll in courses and track their progress.
- **Interactive Content**: Support for videos, quizzes, and assignments.
- **Discussion Forums**: Community-driven forums for students and educators to interact.
- **Profile Management**: Users can manage their profiles and view their course history.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

### Frontend

- **React.js**: A JavaScript library for building user interfaces.
- **Redux.js**: A predictable state container for JavaScript apps.
- **Axios**: Promise-based HTTP client for the browser and Node.js.
- **Tailwind CSS**: Frontend framework for developing responsive and mobile-first websites.

### Backend

- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing user data, courses, and more.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.
- **JWT**: JSON Web Tokens for secure user authentication.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Shivang-Chauhan/StudyNotion.git
    cd StudyNotion
    ```

2. **Install dependencies for both client and server:**

    ```bash
    # Navigate to the client directory and install dependencies
    npm install

    # Navigate to the server directory and install dependencies
    cd ./server
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the `server` directory and add the following environment variables:

    ```env
    MAIL_HOST = smtp.gmail.com
    MAIL_USER = your_mail_id
    MAIL_PASS = your_mail_passkey
    JWT_SECRET = your_jwt_secret_string
    FOLDER_NAME = your_cloudinary_folder_string
    RAZORPAY_KEY = your_razorpay_key
    RAZORPAY_SECRET = your_razorpay_secret
    CLOUD_NAME = your_cloud_name
    API_KEY = your_cloudinary_api_key
    API_SECRET = your_cloudinary_api_secret
    MONGODB_URL = your_mongodb_url
    PORT = 4000
    ```

    Create a `.env` file in the `root` directory and add the following environment variables:

    ```env
    REACT_APP_BASE_URL = your_react_app_base_url
    RAZORPAY_KEY = your_razorpay_key
    ```

4. **Run the development server:**

    ```bash
    # In the server directory
    nodemon index.js
    ```

    ```bash
    # In the client directory
    npm start
    ```

    The backend server will run on `http://localhost:4000` and the frontend will run on `http://localhost:3000`.

## Usage

- **Register/Login**: Create an account or log in with existing credentials.
- **Browse Courses**: Explore available courses and enroll in those of interest.
- **Manage Courses**: If you are an educator, create and manage your courses.
- **Interactive Learning**: Participate in quizzes, watch educational videos, and submit assignments.
- **Community Interaction**: Engage with other users through discussion forums.


## Screenshots

Here are some screenshots of the Website:

### Home Page
<img width="1439" alt="Screenshot 2024-07-18 at 6 24 14 PM" src="https://github.com/user-attachments/assets/0b35d36e-5b78-4898-91aa-1b4ef76199a3">

### Course List
<img width="1440" alt="Screenshot 2024-07-18 at 6 26 30 PM" src="https://github.com/user-attachments/assets/21c612bb-ffbf-46f4-b19a-feed81db0472">

### Course Detail
<img width="1440" alt="Screenshot 2024-07-18 at 6 27 08 PM" src="https://github.com/user-attachments/assets/1589b11b-d702-4a76-bcb9-268a38433655">

### User Profile
<img width="1440" alt="Screenshot 2024-07-18 at 6 28 04 PM" src="https://github.com/user-attachments/assets/484c2504-b050-473b-8a0f-3cebc8b23840">


## Contributing

We welcome contributions to enhance the project! To contribute, please follow these steps:

1. **Fork the repository.**
2. **Create a new branch**: `git checkout -b feature/your-feature-name`
3. **Make your changes.**
4. **Commit your changes**: `git commit -m 'Add some feature'`
5. **Push to the branch**: `git push origin feature/your-feature-name`
6. **Open a pull request.**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or suggestions, please contact:

- **Name**: Shivang Chauhan
- **Email**: chauhanshivang012@gmail.com

Thank you for visiting StudyNotion!

---
