<h1>Mystigo 🌍</h1>

<p><b>Mystigo</b> is a full-stack travel discovery web app that helps users explore <b>hidden gems and offbeat destinations</b> with dynamic content, maps, and real-time data integration.</p>

<hr>

<h2>🚀 Live Demo</h2>
<p>👉 This project is hosted here : <b><a href="">Click me</a></b></p>

<hr>

<h2>🛠️ Steps to Run on Localhost</h2>

<h3>1. Clone & Unzip the repository</h3>
<pre>
git clone https://github.com/Sekhar098/Mystigo.git
cd Mystigo
</pre>

<h3>2. Import Database</h3>
<p>Import the <b>Mystigo DB</b> into your <b>MongoDB</b>.</p>

<h3>3. Create <code>.env</code> File</h3>
<p>Define the following environment variables inside a <code>.env</code> file:</p>

<pre>
PORT=
MONGO_URI=
CORS=*
ACCESS_TOKEN_SECRET=
ACCESS_TOKEN_EXPIRY=
REFRESH_TOKEN_SECRET=
REFRESH_TOKEN_EXPIRY=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
CLOUDINARY_URL=
GEOAPIFY_API_KEY=
</pre>

<h3>4. Install Dependencies</h3>
<pre>
npm install
</pre>

<h3>5. Run the Development Server</h3>
<pre>
npm run dev
</pre>

<hr>

<h2>⚠️ Note</h2>
<ul>
  <li>Make sure to properly configure your <b>API keys</b> in the <code>.env</code> file before running the project.</li>
  <li>The project runs on the defined <b>PORT</b> (default: 5000).</li>
</ul>
