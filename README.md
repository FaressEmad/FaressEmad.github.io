<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fares Emad | Portfolio</title>
  <style>
    body {
      font-family: "Courier New", monospace;
      margin: 0;
      padding: 0;
      background: #0d1117;
      color: #c9d1d9;
    }
    header {
      background: #161b22;
      padding: 3rem 1rem;
      text-align: center;
      border-bottom: 2px solid #30363d;
    }
    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid #58a6ff;
      margin-bottom: 1rem;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #58a6ff;
    }
    header p {
      font-size: 1.2rem;
      color: #8b949e;
    }
    nav {
      text-align: center;
      background: #161b22;
      padding: 0.8rem;
      border-bottom: 1px solid #30363d;
    }
    nav a {
      color: #58a6ff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    section h2 {
      color: #79c0ff;
      border-left: 4px solid #58a6ff;
      padding-left: 10px;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .project-card {
      background: #161b22;
      border-radius: 8px;
      padding: 1rem;
      border: 1px solid #30363d;
      transition: transform 0.2s, border 0.2s;
    }
    .project-card:hover {
      transform: scale(1.03);
      border: 1px solid #58a6ff;
    }
    .buttons {
      margin-top: 1rem;
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
      justify-content: center;
    }
    .btn {
      text-decoration: none;
      padding: 10px 18px;
      border-radius: 5px;
      font-weight: bold;
      transition: 0.3s;
      color: white;
    }
    .btn-email { background: #d73a49; }
    .btn-linkedin { background: #0a66c2; }
    .btn-github { background: #24292f; }
    .btn:hover { opacity: 0.85; }
    footer {
      text-align: center;
      background: #161b22;
      color: #8b949e;
      padding: 1rem;
      margin-top: 2rem;
      border-top: 1px solid #30363d;
    }
    /* Terminal-like animation */
    .typing {
      border-right: 3px solid #58a6ff;
      white-space: nowrap;
      overflow: hidden;
      width: 0;
      animation: typing 4s steps(30, end) forwards, blink 0.75s step-end infinite;
      display: inline-block;
    }
    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }
    @keyframes blink {
      50% { border-color: transparent; }
    }
  </style>
</head>
<body>
  <header>
    <!-- Replace with your own photo -->
    <img src="myphoto.jpg" alt="Fares Emad">
    <h1>&lt;Fares Emad /&gt;</h1>
    <p><span class="typing">Data Scientist</span></p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
  <h2>About Me</h2>
  <p>
    Hello! I’m <span style="color:#58a6ff;">Fares Emad</span>, a passionate learner and aspiring <strong>Data Scientist</strong>.  
    My journey into data science began when I discovered how data could uncover hidden patterns and help solve real-world problems.  
  </p>
  <p>
    I started exploring tools like <strong>Python, SQL, and Power BI</strong>, and soon realized that data science is more than just numbers —  
    it’s about <em>telling stories with data</em>, making informed decisions, and building solutions that create impact.  
  </p>
  <p>
    I’m especially fascinated by how data science connects different fields — from healthcare and education to business and technology.  
    My passion is to keep learning, experimenting, and turning raw data into meaningful insights.  
  </p>
  <p>
    Outside of coding and analytics, I enjoy <span style="color:#79c0ff;">continuous self-learning</span>, teamwork,  
    and sharing knowledge with others. My ultimate goal is to use data to solve problems that truly matter.  
  </p>
</section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>🏥 Hospital Data Project</h3>
        <p>Built a system to analyze hospital records and improve efficiency.</p>
      </div>
      <div class="project-card">
        <h3>📊 Sales Dashboard</h3>
        <p>Created a Power BI dashboard to visualize sales trends & seasonality.</p>
      </div>
      <div class="project-card">
        <h3>🎓 Student Performance Prediction</h3>
        <p>Used ML to predict student scores from study hours with Python.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <div class="buttons">
      <a class="btn btn-email" href="mailto:fares.emad.abdelnaby@gmail.com">📧 Email</a>
      <a class="btn btn-linkedin" href="https://www.linkedin.com/in/faresemad4106/" target="_blank">💼 LinkedIn</a>
      <a class="btn btn-github" href="https://github.com/FaressEmad" target="_blank">🐱 GitHub</a>
    </div>
  </section>

  <footer>
    <p>© 2025 &lt;Fares Emad /&gt;. All rights reserved.</p>
  </footer>
</body>
</html>
