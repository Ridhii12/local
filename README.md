<h1>🚀 AI-Powered Digital Profile Analyzer</h1>

<p><strong>Profile Analyzer</strong> is an AI-powered web app that analyzes developer profiles across platforms like GitHub, LinkedIn, LeetCode, and Codeforces. It scrapes publicly available data and provides actionable insights using AI to help developers enhance their digital presence.</p>

<h2>🎯 Scope of the Project</h2>
<ul>
  <li>Evaluate and visualize GitHub and LinkedIn profile data.</li>
  <li>Scrape competitive programming platform statistics.</li>
  <li>Provide AI-based personalized suggestions to improve profiles.</li>
  <li>Help developers create a stronger presence for job hunting or networking.</li>
</ul>

<h2>⚙️ Features</h2>
<ul>
  <li>🔍 LinkedIn Scraper – Follower count, profile highlights.</li>
  <li>🐙 GitHub Analyzer – Repositories, stars, forks, languages.</li>
  <li>📈 LeetCode & Codeforces stats – Problems solved, rating, contests.</li>
  <li>🧠 AI-Powered Recommendations – Actionable improvement tips using OpenAI/Gemini.</li>
  <li>💻 User-friendly Frontend – Interactive and clean UI with React.</li>
  <li>🧪 Real-time Insights – Live scraping and profile summary generation.</li>
</ul>

<h2>📦 Prerequisites</h2>
<ul>
  <li><strong>Node.js</strong> (v14+)</li>
  <li><strong>npm</strong> (comes with Node)</li>
  <li><strong>OpenAI API Key</strong> (for recommendations)</li>
  <li>Optional: Codeforces/LeetCode public profile links</li>
</ul>

<h2>🧪 Getting Started</h2>
<ol>
  <li><strong>Clone the Repository</strong>
    <pre><code class="bash">git clone https://github.com/harshKhulbe07/Profile-Analyzer-.git
cd Profile-Analyzer-</code></pre>
  </li>
  <li><strong>Install Backend Dependencies</strong>
    <pre><code class="bash">cd backend
npm install
npm start</code></pre>
    <p>Backend will run on: <code>http://localhost:5000</code></p>
  </li>
  <li><strong>Install Frontend Dependencies</strong> (in a new terminal tab):
    <pre><code class="bash">cd frontend
npm install
npm start</code></pre>
    <p>Frontend will run on: <code>http://localhost:3000</code></p>
  </li>
  <li><strong>Add Environment Variables</strong> in <code>backend/.env</code>:
    <pre><code>PORT=5000
OPENAI_API_KEY=your_api_key_here</code></pre>
  </li>
</ol>

<h2>🧱 Project Structure</h2>
<pre><code>
Profile-Analyzer-/
├── backend/          # Node.js backend - APIs and scraping logic
│   ├── controllers/
│   ├── routes/
│   ├── utils/
│   └── index.js
├── frontend/         # React frontend - UI for user interaction
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
├── README.md
└── package.json
</code></pre>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li><strong>Frontend:</strong> React, Tailwind CSS, Axios</li>
  <li><strong>Backend:</strong> Node.js, Express, Puppeteer, Cheerio</li>
  <li><strong>Scraping:</strong> Puppeteer (LinkedIn), Cheerio (GitHub)</li>
  <li><strong>AI:</strong> OpenAI API / Gemini (planned)</li>
  <li><strong>Version Control:</strong> Git & GitHub</li>
</ul>

<h2>✨ Sample Use Case</h2>
<p>A developer visits the app → Inputs GitHub and LinkedIn profile links → Scraper fetches data → AI generates recommendations → User views their evaluation and personalized insights.</p>



<h2>🧑‍💻 Contributing</h2>
<ol>
  <li>Fork the repo</li>
  <li>Create a branch: <code>git checkout -b feature-name</code></li>
  <li>Commit changes: <code>git commit -m "add new feature"</code></li>
  <li>Push to your fork: <code>git push origin feature-name</code></li>
  <li>Submit a Pull Request</li>
</ol>

<h2>📄 License</h2>
<p>This project is licensed under the <strong>MIT License</strong>.</p>
<p>Created with ❤️ for the <strong>Dev Heat Hackathon</strong> 🚀</p>
