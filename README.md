# Online Quiz System

## Overview
The **Online Quiz System** is a web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) to facilitate the conduction of quizzes for students. The platform includes essential features such as timers, instant result displays, and question randomization, ensuring an engaging and fair experience for participants.

---

## Features
- **User Authentication:** Secure login and registration for students and admins.
- **Quiz Management:**
  - Add, update, and delete quiz questions (Admin feature).
  - Randomized question order for each student.
- **Timer Functionality:** Automatic quiz submission when the timer runs out.
- **Instant Results:** Real-time display of quiz results after submission.
- **Responsive Design:** Compatible with desktops, tablets, and smartphones.

---

## Technologies Used
### Frontend
- **React.js**: For building a dynamic and responsive user interface.
- **HTML & CSS**: For structuring and styling the application.
- **JavaScript**: For implementing interactivity and frontend logic.

### Backend
- **Node.js**: For server-side logic and API handling.
- **Express.js**: For routing and middleware management.
- **MongoDB**: For storing user data, quiz questions, and results.

---

## Installation and Setup

### Prerequisites
- Node.js installed on your system.
- MongoDB database setup (local or cloud).

### Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/online-quiz-system.git
   cd online-quiz-system
   ```

2. **Install Dependencies:**
   - For Backend:
     ```bash
     cd backend
     npm install
     ```
   - For Frontend:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Setup Environment Variables:**
   Create a `.env` file in the `backend` directory with the following:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Start the Application:**
   - Backend:
     ```bash
     cd backend
     npm start
     ```
   - Frontend:
     ```bash
     cd ../frontend
     npm start
     ```

5. **Access the Application:**
   Open your browser and navigate to `http://localhost:3000`.

---

## Usage
1. **Admin Panel:**
   - Login with admin credentials.
   - Add or manage quiz questions.

2. **Student Quiz:**
   - Login or register as a student.
   - Select a quiz to participate in.
   - Answer questions within the timer.
   - View results instantly after submission.

---

## Folder Structure
```
project-root
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── server.js
├── frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── utils
│   │   └── App.js
└── README.md
```

---

## Future Enhancements
- Leaderboard to track top-performing students.
- Support for multiple question types (e.g., MCQs, True/False, Descriptive).
- Integration of email notifications for results.
- Analytics for quiz performance trends.

---

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments
- The MERN stack community for their extensive documentation and support.
- Open-source libraries and tools that made this project possible.

