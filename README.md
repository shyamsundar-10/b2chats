# b2chats
b2chats is a social media platform that allows users to create posts, like/unlike posts, comment on posts, and share posts. It features a dark/light mode, and users can view and edit their profile settings.

# Table of Contents
Features
Installation
Usage
Project Structure
Technologies
Screenshots
Contributing
License
Contact

# Features
1. User authentication with Firebase
2. Create, like, unlike, comment, and share posts
3. Dark/light mode toggle
4. Responsive design
5. Report posts

# Installation
Clone the repository and install dependencies for both the frontend and backend. Ensure you have a .env file in the backend directory with your MongoDB Atlas connection string.

# Usage
Start the backend server and the frontend development server, then open your browser to see the application in action.

# Project Structure
b2chats/
│

├── backend/

│   ├── models/

│   │   └── Post.js

│   ├── .env

│   ├── package.json

│   ├── server.js

│   └── ...

│

├── frontend/

│   ├── public/

│   ├── src/

│   │   ├── components/

│   │   │   ├── Home.js

│   │   │   ├── Post.js

│   │   │   ├── Settings.js

│   │   │   ├── NavBar.js

│   │   │   └── ...

│   │   ├── App.css

│   │   ├── App.js

│   │   ├── index.css

│   │   └── index.js

│   ├── package.json

│   └── ...

│

└── README.md

# Technologies
Frontend: React, Axios

Backend: Node.js, Express, Mongoose, MongoDB Atlas

Authentication: Firebase

Styling: CSS

Deployment: Netlify (Frontend), Heroku/other cloud providers (Backend)

# Screenshots

# License
This project is licensed under the MIT License.

# Contact
For any questions or feedback, please reach out to me.
