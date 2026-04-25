<h1>SnapClass - AI-Powered Attendance System</h1>
<h2>Overview</h2>
This is an AI-Powered Attendance System that uses face recognition to automate attendance with real-time tracking, improved accuracy, and actionable insights. This project showcases practical AI integration with modern web technologies to create an efficient, scalable solution for classrooms and organizations.

<h2>Table of Contents</h2>
<li>Overview</li>
<li>Tech Stack</li>
<li>Features</li>
<li>Installation</li>
<li>Usage</li>
<li>Deployment</li>
<li>License</li>
<h2>Tech Stack</h2>
<h3>Frontend</h3>
<li>HTML</li>
<li>CSS</li>
<h3>Backend</h3>
<li>Flask</li>
<h3>Database</h3>
<li>Supabase</li>
<h3>Deployment</h3>
<li>Streamlit</li>
<h3>Development Tools</h3>
<li>Visual Studio Code</li>
<li>Git</li>
<li>GitHub</li>
<h3>Features</h3>
<li>Face Recognition-based attendance</li>
<li>Real-time tracking and instant updates</li>
<li>Secure data handling</li>
<li>User-friendly dashboard for teachers/admins</li>
<li>Attendance analytics and insights</li>
<li>Continuous deployment on Vercel</li>
<h2>Installation</h2>
To run SnapClass locally, follow these steps:

<h3>1. Clone the repository:</h3>

<div class="bg-light p-3 rounded border">
  <pre class="mb-0">
    <code>git clone https://github.com/yourusername/snapclass.git</code></pre>
</div>

<h3>2. Navigate to the project directory:</h3>

<div class="bg-light p-3 rounded border">
  <pre class="mb-0">
    <code>cd SnapClass</code></pre>
</div>

<h3>3. Install the dependencies:</h3>

<div class="bg-light p-3 rounded border">
  <pre class="mb-0">
    <code>pip install streamlit</code></pre>
</div>
<h3>4. Set up environment variables:</h3>

Create a .env file in the root directory and configure the following variables:

<div class="bg-light p-3 rounded border">
  <pre class="mb-0">
    <code>SUPABASE_URL=&lt;your_supabase_url&gt;</code></pre>
</div>
<div class="bg-light p-3 rounded border">
  <pre class="mb-0">
    <code>SUPABASE_KEY</code></pre>
</div>

<h3>5. Run the development server:</h3>

<div class="bg-light p-3 rounded border">
  <pre class="mb-0">
    <code>streamlit run app.py</code></pre>
</div>
<h3>6. Open your browser and navigate to:</h3>

<div class="bg-light p-3 rounded border">
  <pre class="mb-0">
    <code>http://localhost:8501</code></pre>
</div>
<h2>Usage</h2>
Once the application is running, you can:

<h3><li>Login / Register:</h3>Create an account or log in to your existing account as a teacher or student.</li>
<h3><li>View Subjects:</h3>Get real-time updates on subjects.</li>
<h3><li>Take Attendance:</h3>Take attendance through FaceID or Voice input.</li>
<h3><li>View Attendance Records:</h3> Check your attendance records.</li>

<h2>Deployment</h2>
SnapClass is deployed on Streamlit. For deployment, ensure you have the Streamlit CLI configured.
Ensure your Streamlit credentials and services are properly set up for deployment.

<h2>License</h2>
All rights reserved.
