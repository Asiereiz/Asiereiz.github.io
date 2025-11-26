<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Asiereiz Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #1a1a1a;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav {
      background: #333;
      padding: 1rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      max-width: 900px;
      margin: auto;
      padding: 2rem;
    }
    .card {
      background: white;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      margin-bottom: 2rem;
    }
    footer {
      background: #1a1a1a;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Portfolio</h1>
    <p>Showcasing my projects, skills, and experience</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
  <div class="container">

    <section id="about" class="card">
      <h2>About Me</h2>
      <p>Hello! I'm a technology enthusiast passionate about software development, intelligent systems, and optimization. I enjoy creating clean, efficient solutions and continuously learning new tools and techniques.</p>
    </section>

    <section id="projects" class="card">
      <h2>Projects</h2>
      <ul>
        <li><strong>Traffic Simulator Enhancement:</strong> Added console-mode features for speed tracking per road.</li>
        <li><strong>BalancedLSS Strategy:</strong> Implemented dynamic traffic light decision-making based on vehicle queue balance.</li>
        <li><strong>Fuzzy-PD Controller:</strong> Designed and analyzed a fuzzy logic control system for liquid-level regulation.</li>
        <li><strong>Expert System for PID Tuning:</strong> Automated PID improvement in MATLAB using rule‑based logic.</li>
      </ul>
    </section>

    <section id="contact" class="card">
      <h2>Contact</h2>
      <p>You can reach me at:</p>
      <p>Email: <strong>your_email@example.com</strong></p>
      <p>GitHub: <a href="https://github.com/Asiereiz">github.com/Asiereiz</a></p>
    </section>

  </div>

  <footer>
    <p>© 2025 Asiereiz — All Rights Reserved</p>
  </footer>
</body>
</html>
