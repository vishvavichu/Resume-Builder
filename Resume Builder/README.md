Quick Start Guide
To get started, follow these steps:

Set Up Environment Variables:

Check the sample .env.example file, which contains placeholders for environment variables.
Replace the placeholders with your actual KEYS/SECRETS/URLs.
Rename the file to .env.
Install Server Dependencies:

bash
Copy code
npm install
Install Client Dependencies:

bash
Copy code
npm run client-install
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
Default Ports:
Server: Runs on http://localhost:5000
Client: Runs on http://localhost:3000
Changing the Server Port:
If you want to change the server port from 5000 to another port (e.g., 4000), update the proxy setting in the package.json file located in the client folder.