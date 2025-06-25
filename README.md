<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jashanpreet Singh | Portfolio</title>
  <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css"/>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code&display=swap" rel="stylesheet"/>
  <style>
    body {
      margin: 0;
      font-family: 'Fira Code', monospace;
      background: #0f0f0f;
      color: #f5f5f5;
    }

    header, footer {
      padding: 1rem;
      text-align: center;
      background: #1a1a1a;
    }

    .hero {
      padding: 5rem 1rem;
      text-align: center;
    }

    .hero h1 {
      font-size: 3rem;
      color: #38bdf8;
    }

    .hero p {
      font-size: 1.2rem;
      margin-top: 1rem;
      color: #aaa;
    }

    .section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: 0 auto;
    }

    .section h2 {
      text-align: center;
      color: #38bdf8;
    }

    .projects, .tech-stack {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }

    .card {
      background: #1f1f1f;
      padding: 1rem;
      border-radius: 12px;
      box-shadow: 0 0 10px #000;
    }

    .card h3 {
      margin-top: 0;
      color: #fafafa;
    }

    .card p {
      color: #ccc;
    }

    a {
      color: #38bdf8;
      text-decoration: none;
    }

    footer p {
      margin: 0.5rem 0;
      color: #888;
    }

    img.icon {
      width: 40px;
      margin: 0.5rem;
    }

    .tech-icons {
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>Jashanpreet Singh</h1>
    <p>CSE @ IIT Bombay | Developer | Graph Algorithms Enthusiast</p>
  </header>

  <section class="hero" data-aos="fade-up">
    <h1>Hello! 👋</h1>
    <p>I’m Jashanpreet, a full-stack developer exploring real-world systems with clean UI and powerful backend logic. Currently working on recommendation engines using Graph Algorithms as part of <strong>Seasons of Code 2025</strong>.</p>
  </section>

  <section class="section" data-aos="fade-up">
    <h2>📂 Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Friend Suggestion System</h3>
        <p>Using FastAPI, React, and MySQL to suggest friends based on user connections via graph traversal algorithms. Backend APIs + full auth flow implemented.</p>
        <a href="https://github.com/jashansings/friend-suggestion-system" target="_blank">View Project →</a>
      </div>

      <div class="card">
        <h3>Client Management System</h3>
        <p>Handles client database operations with a clean UI, developed using Express + EJS + MongoDB. Features dashboard, forms, and search filters.</p>
        <a href="https://github.com/jashansings/client-management-system" target="_blank">View Project →</a>
      </div>
    </div>
  </section>

  <section class="section" data-aos="fade-up">
    <h2>🛠 Tech Stack</h2>
    <div class="tech-icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" class="icon" title="React" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" class="icon" title="FastAPI" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" class="icon" title="Python" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" class="icon" title="MySQL" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" class="icon" title="JavaScript" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" class="icon" title="HTML" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" class="icon" title="CSS" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" class="icon" title="Git" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" class="icon" title="GitHub" />
    </div>
  </section>

  <footer>
    <p>📫 Reach me: <a href="mailto:jashaniitb@gmail.com">jashaniitb@gmail.com</a></p>
    <p>🔗 <a href="https://linkedin.com/in/jashansings" target="_blank">LinkedIn</a> | <a href="https://github.com/jashansings" target="_blank">GitHub</a></p>
    <p>© 2025 Jashanpreet Singh</p>
  </footer>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html>
