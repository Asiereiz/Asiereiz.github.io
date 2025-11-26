<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    /* Reset básico */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Arial', sans-serif;
      background: #f5f5f5; /* Fondo como antes */
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #1a1a1a;
      color: white;
      text-align: center;
      padding: 3rem 1rem;
      background-image: linear-gradient(to right, #1a1a1a, #333);
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #ccc;
    }

    nav {
      background: #333;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 0.5rem 1rem;
      border-radius: 8px;
      transition: background 0.3s;
    }

    nav a:hover {
      background: #555;
    }

    .container {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    section {
      background: white;
