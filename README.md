# 🎬 Movie Trailer Web App

A full-stack MERN web application developed in a six-member team during the QueenB Summer Camp.

The platform allows users to upload, search, filter, and view movie trailers, manage their own uploads, and interact with trailer content through a personalized user experience.

## 👩‍💻 My Contributions

- Developed functionality for validating new trailer submissions against existing database records to prevent duplicate entries.
- Worked with the MERN stack as part of the project's full-stack development environment.
- Independently learned and applied unfamiliar web development technologies within a limited project timeframe.

## ✨ Features

- **Upload Trailers**: Users can upload their favorite movie trailers.
- **View Trailers**: Browse through trailers uploaded by other users.
- **User Dashboard**: Each user has a dashboard where they can view, edit, or delete their uploaded trailers.
- **Authentication**: Users can sign up, log in, and manage their accounts, including a "Forgot Password" feature.
- **Search and Filtering**: Users can search and filter available trailers.
- **YouTube API Integration**: Trailers are presented through the YouTube API.

## Technology Stack

This project is built using the **MERN** stack:
- **MongoDB**: For database management.
- **Express.js**: For backend API development.
- **React.js**: For building the frontend user interface.
- **Node.js**: For server-side scripting.

## Project Structure

- `client/`: Contains the React frontend application.
- `server/`: Contains the Express backend application, including API routes and database models.

```bash
queenb-summer-project-team12
│
├── client/                 # React client
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       ├── styles/
│       ├── App.js
│       ├── index.js
│       └── package.json    # Client dependencies
│
├── server/                 # Node.js server
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── .env                # Environment variables
│   ├── server.js           # Main server file
│   └── package.json        # Server dependencies
│
├── README.md
└── package.json            # Root package.json for repo management
```

### Explanation
#### Root Directory
- queenb-summer-project-team12/: This is the root directory of the project.

#### Client Directory
- client/: Contains the React frontend application.
   - public/: Static files like index.html, images, and other assets that need to be served directly.
   - src/: Contains the source code for the React application.
      - components/: Reusable UI components such as buttons, forms, and other elements.
      - pages/: Page components that represent different routes in the application.
      - services/: Services for making API calls and handling business logic.
      - styles/: CSS and styling files for the application.
      - App.js: The main React component that sets up routing and renders the application.
      - index.js: The entry point for the React application, responsible for rendering the App component into the DOM.
      - package.json: Lists the client-side dependencies and scripts for managing the React application.
      
#### Server Directory
- server/: Contains the Node.js backend application.
   - controllers/: Contains the logic for handling API requests and responses.
   - models/: Mongoose models that define the data schema for MongoDB.
   - routes/: Defines the API endpoints and maps them to controller functions.
   - .env: Stores environment variables like database connection strings and server port.
   - server.js: The main server file that sets up Express, connects to the database, and starts the server.
   - package.json: Lists the server-side dependencies and scripts for managing the Node.js application.

