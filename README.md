# Resume-Builder
Resume Builder Application A full-stack web app that helps users effortlessly create professional resumes. Built with Express.js for the backend and React.js for the frontend, it allows users to input personal details, work experience, education, and skills, then generates a customized, downloadable resume in various formats.

Quick Start Guide
Follow these steps to set up and run the project:

1. Set Up Environment Variables
Open the .env.example file.
Replace placeholders with your actual KEYS/SECRETS/URLs.
Rename the file to .env.
2. Install Dependencies
Server Dependencies:
bash
Copy code
npm install
Client Dependencies:
bash
Copy code
npm run client-install
3. Run the Application
Run Both Client and Server Concurrently:
bash
Copy code
npm run dev
Run Only the Express Server:
bash
Copy code
npm run server
Run Only the React Client:
bash
Copy code
npm run client
4. Default Ports
Server: http://localhost:5000
Client: http://localhost:3000
5. Changing the Server Port
To change the server port, update the proxy setting in the package.json file located in the client folder.
