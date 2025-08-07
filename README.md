# TweetApp-UI

Frontend (React) for TweetApp project.

## Features

- User can post, view, like, reply, and delete tweets
- User registration and login (JWT-secured via backend)
- Simple, clean UI for TweetApp frontend

## Getting Started

### Prerequisites

- Node.js and npm installed
- Backend API running (ensure backend TweetApp is running)

### Installation

```bash
npm install
```

Running the App
Start the React development server:

bash
Copy
Edit
```bash
npm start
```

Open http://localhost:3000 in your browser to view the app.

The page will reload on edits. You can also see lint errors in the console.


#Project Structure 
```bash 
TweetApp-UI/
├── public/            # Static files and index.html
├── src/               # React source files
│   ├── components/    # React components
│   ├── pages/         # Different app pages/screens
│   ├── services/      # API calls
│   └── App.js         # Main app component
├── package.json       # npm dependencies and scripts
└── README.md          # Project documentation
``
Notes

Connects to backend API for authentication and tweet management.
Backend runs at: http://localhost:8090 



