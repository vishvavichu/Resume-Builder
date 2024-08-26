# Resume-Builder
Resume Builder Application A full-stack web app that helps users effortlessly create professional resumes. Built with Express.js for the backend and React.js for the frontend, it allows users to input personal details, work experience, education, and skills, then generates a customized, downloadable resume in various formats.

<h2>Quick Start Guide</h2>

<p>Follow these steps to set up and run the project:</p>

<h3>1. Set Up Environment Variables</h3>
<ul>
    <li>Open the <code>.env.example</code> file.</li>
    <li>Replace placeholders with your actual <code>KEYS/SECRETS/URLs</code>.</li>
    <li>Rename the file to <code>.env</code>.</li>
</ul>

<h3>2. Install Dependencies</h3>
<ul>
    <li><strong>Server Dependencies:</strong></li>
    <pre><code>npm install</code></pre>
    <li><strong>Client Dependencies:</strong></li>
    <pre><code>npm run client-install</code></pre>
</ul>

<h3>3. Run the Application</h3>
<ul>
    <li><strong>Run Both Client and Server Concurrently:</strong></li>
    <pre><code>npm run dev</code></pre>
    <li><strong>Run Only the Express Server:</strong></li>
    <pre><code>npm run server</code></pre>
    <li><strong>Run Only the React Client:</strong></li>
    <pre><code>npm run client</code></pre>
</ul>

<h3>4. Default Ports</h3>
<ul>
    <li><strong>Server:</strong> <a href="http://localhost:5000">http://localhost:5000</a></li>
    <li><strong>Client:</strong> <a href="http://localhost:3000">http://localhost:3000</a></li>
</ul>

<h3>5. Changing the Server Port</h3>
<p>To change the server port, update the <code>proxy</code> setting in the <code>package.json</code> file located in the client folder.</p>
