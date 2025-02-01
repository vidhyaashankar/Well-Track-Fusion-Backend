---
# Well-Track-Fusion Health Tracker

## Steps to Launch the Project

Follow the steps below to run the project locally. These instructions are designed to help even those with little or no software development experience.

### Prerequisites
Before you begin, ensure you have the following software installed on your machine:

1. **Node.js**: This is a JavaScript runtime used for building the server.
   - **Installation**:
     - Go to the [Node.js website](https://nodejs.org/).
     - Download the LTS version (recommended for most users).
     - Follow the installation instructions for your operating system.

2. **npm**: This is the package manager for JavaScript, which comes bundled with Node.js.

### 1. Download the Project
1. Click on the green "Code" button and select "Download ZIP."
2. Extract the downloaded ZIP file to a folder on your computer. You can name this folder `well-track-fusion`.

### 2. Set Up the Project Structure
Ensure your project folder structure looks like this:

```
well-track-fusion/
├── client/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── package-lock.json
└── server/
    ├── controllers/
    ├── models/
    ├── routes/
    ├── utils/
    ├── package.json
    ├── package-lock.json
    └── server.js

```

- Move the contents of the extracted ZIP file (the `server` folder contents) into the `server` folder of your project.

### 3. Start the Frontend (React Client) 
(Check out this GitHub repository for Frontend/contents of client folder: [Well-Track-Fusion-Backend](https://github.com/vidhyaashankar/Well-Track-Fusion-Frontend))
1. Open your terminal (Command Prompt, PowerShell, or Terminal).
2. Navigate to the project folder `well-track-fusion`:
   ```bash
   cd path/to/well-track-fusion
   ```
3. Navigate to the `client` folder:
   ```bash
   cd client
   ```
4. Install dependencies (only needed the first time):
   ```bash
   npm install
   ```
5. Start the React development server:
   ```bash
   npm start
   ```

The React app should now be running on `http://localhost:3000`.

### 4. Start the Backend (Node.js Server) 
(Check out this GitHub repository for Backend/contents of server folder: [Well-Track-Fusion-Backend](https://github.com/vidhyaashankar/Well-Track-Fusion-Backend))
1. Open a **new terminal**.
2. Navigate to the project folder `well-track-fusion`:
   ```bash
   cd path/to/well-track-fusion
   ```
3. Navigate to the `server` folder:
   ```bash
   cd server
   ```
4. Install dependencies (only needed the first time):
   ```bash
   npm install
   ```
5. Start the Node.js server:
   ```bash
   node server.js
   ```

The backend server should now be running on `http://localhost:5000` (or as specified in your code).

### Notes
- Ensure both the frontend and backend servers are running simultaneously for full functionality.
- Refer to `roadmap.md` for additional project details and future plans.

---
