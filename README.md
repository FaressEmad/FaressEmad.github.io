<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fares Emad | Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f9;
      color: #333;
    }
    header {
      background: #222;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }
    nav {
      text-align: center;
      background: #444;
      padding: 0.5rem;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .project-card {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .project-card:hover {
      transform: scale(1.03);
    }
    footer {
      text-align: center;
      background: #222;
      color: white;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Fares Emad</h1>
    <p>Data Enthusiast | Developer | Learner</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Hi, I’m Fares! I have a strong interest in Data Science, Data Engineering, 
      and Business Intelligence. I enjoy building meaningful solutions with tools like Python, SQL, 
      and Power BI. I also value teamwork, leadership, and continuous learning.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Hospital Data Project</h3>
        <p>Built a data-driven system to analyze hospital records and improve efficiency.</p>
      </div>
      <div class="project-card">
        <h3>Sales Dashboard</h3>
        <p>Created a Power BI dashboard to visualize sales trends and seasonal analysis.</p>
      </div>
      <div class="project-card">
        <h3>Student Performance Prediction</h3>
        <p>Used Python and machine learning to predict student scores from study hours.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:fares@example.com">fares@example.com</a></p>
    <p>LinkedIn: <a href="#">linkedin.com/in/fares</a></p>
    <p>GitHub: <a href="#">github.com/fares</a></p>
  </section>

  <footer>
    <p>© 2025 Fares Emad. All rights reserved.</p>
  </footer>
</body>
</html>
