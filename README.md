<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jashanpreet Singh | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code&display=swap" rel="stylesheet"/>
  <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css"/>
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
      max-width: 1100px;
      margin: 0 auto;
    }

    .section h2 {
      text-align: center;
      color: #38bdf8;
      font-size: 2rem;
    }

    .projects {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
      margin-top: 2rem;
    }

    .card {
      background: #1f1f1f;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 0 10px #000;
      max-width: 300px;
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

    table {
      margin: 2rem auto;
      text-align: center;
    }

    td {
      padding: 1rem;
    }

    img.icon {
      width: 40px;
      display: block;
      margin: 0 auto 0.5rem;
    }

    .github-stats {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1rem;
      margin-top: 2rem;
    }

    .github-stats img {
      max-width: 100%;
      border-radius: 10px;
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
    <h2>🛠 Tools & Technologies</h2>
    <table>
      <tr>
        <td><img class="icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg"/><br>React</td>
        <td><img class="icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/><br>Python</td>
        <td><img class="icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"/><br>JavaScript</td>
        <td><img class="icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/><br>HTML</td>
        <td><img class="icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/><br>CSS</td>
      </tr>
      <tr>
        <td><img class="icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg"/><br>MySQL</td>
        <td><img class="icon" src="https://camo.githubusercontent.com/8c779088a37e29fdc8fca5576357aa67c86f30041734226d17f70e150eececdf/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d6d6f6e676f6462"/><br>MongoDB</td>
        <td><img class="icon" src="https://camo.githubusercontent.com/33a88742a4c2007e41b467f181b79c7f68650b056f27ac9d38176995f68ad586/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d637070"/><br>C++</td>
        <td><img class="icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg"/><br>FastAPI</td>
        <td><img class="icon" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Photoshop.svg"/><br>Photoshop</td>
      </tr>
    </table>
  </section>

  <section class="section" data-aos="fade-up">
    <h2>📈 GitHub Stats</h2>
    <div class="github-stats">
      <img src="https://github-readme-stats.vercel.app/api?username=jashansings&show_icons=true&theme=dark" alt="GitHub Stats"/>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=jashansings&theme=dark" alt="GitHub Streak"/>
    </div>
  </section>

  <footer>
    <p>📫 Reach me: <a href="mailto:jashaniitb@gmail.com">jashaniitb@gmail.com</a></p>
    <p>🔗 <a href="https://linkedin.com/in/jashansings" target="_blank">LinkedIn</a> | <a href="https://github.com/jashansings" target="_blank">GitHub</a></p>
    <p>© 2025 Jashanpreet Singh</p>
  </footer>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({ once: true });
  </script>
</body>
</html>
