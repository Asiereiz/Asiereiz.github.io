<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Simple Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f0f0f0;
      color: #333;
    }
    header {
      background: #222;
      color: white;
      text-align: center;
      padding: 2rem;
    }
    nav {
      background: #333;
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      max-width: 800px;
      margin: auto;
      padding: 2rem;
    }
    section {
      background: white;
      padding: 1.5rem;
      border-radius: 10px;
      margin-bottom: 1.5rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <p>Welcome to my simple portfolio</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="about">
      <h2>About Me</h2>
      <p>Hi! I'm a developer interested in creating simple and clean solutions.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <ul>
        <li>Project 1</li>
        <li>Project 2</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <strong>example@example.com</strong></p>
    </section>
  </div>

  <footer>
    <p>© 2025 — All Rights Reserved</p>
  </footer>
</body>
</html>
