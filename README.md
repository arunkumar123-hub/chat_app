<!-- README.md HTML Template for Real-Time Chat App MERN Project -->

<h1 align="center">💬 Real-Time Chat Application</h1>

<p align="center">
  A full-stack Real-Time Chat Application built using the MERN Stack and Socket.IO.
</p>

<hr>

<h2>🚀 Features</h2>

<ul>
  <li>🔐 User Authentication & Authorization</li>
  <li>💬 Real-Time Messaging</li>
  <li>🟢 Online/Offline User Status</li>
  <li>📷 Image Sharing Support</li>
  <li>🔔 Instant Notifications</li>
  <li>📱 Fully Responsive UI</li>
  <li>⚡ Fast Communication with Socket.IO</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>

<table>
  <tr>
    <th>Frontend</th>
    <th>Backend</th>
    <th>Database</th>
    <th>Realtime</th>
  </tr>
  <tr>
    <td>React.js</td>
    <td>Node.js</td>
    <td>MongoDB</td>
    <td>Socket.IO</td>
  </tr>
  <tr>
    <td>Tailwind CSS</td>
    <td>Express.js</td>
    <td>Mongoose</td>
    <td>WebSockets</td>
  </tr>
</table>

<hr>

<h3>Setup Environment Variables</h3>

<p>Create a <code>.env</code> file inside the server folder and add:</p>

<pre>
MONGODB_URI="your mongodb url"
JWT_SECRET="your secret"

CLOUDINARY_CLOUD_NAME="your cloudinary cloud name"
CLOUDINARY_API_KEY="your api key"
CLOUDINARY_API_SECRET="your api key secret"
</pre>

<p>Create a <code>.env</code> file inside the client folder and add:</p>

<pre>
VITE_BACKEND_URL = "your backend url"
</pre>

<h3>Run the Project</h3>

<pre>
# Run backend server
cd server
npm run server

# Run frontend
cd client
npm run dev
</pre>

<hr>

<h2>🔗 Live Demo</h2>

<p align="center">
  <a href="https://chat-app-henna-five-61.vercel.app/" target="_blank">
    🌐 Click Here to View Live Project
  </a>
</p>

<hr>

<h2>🔌 Socket Events</h2>

<ul>
  <li><code>connection</code> - User Connected</li>
  <li><code>disconnect</code> - User Disconnected</li>
  <li><code>sendMessage</code> - Send New Message</li>
  <li><code>receiveMessage</code> - Receive Message Instantly</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
  <b>Arun Kumar</b><br>
  MERN Stack Developer
</p>

<hr>

<h2>⭐ Support</h2>

<p>
  If you like this project, give it a ⭐ on GitHub!
</p>
