
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>World of Natural Sciences</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #0f172a;
      color: #e2e8f0;
    }

    header {
      background: linear-gradient(90deg, #3b82f6, #6366f1);
      padding: 60px 20px;
      text-align: center;
      color: #fff;
    }

    header h1 {
      margin: 0;
      font-size: 2.8em;
    }

    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      padding: 40px 20px;
    }

    .card {
      background-color: #1e293b;
      border-left: 5px solid #3b82f6;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: scale(1.02);
    }

    h2 {
      margin-top: 0;
      color: #93c5fd;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #1e3a8a;
      color: #cbd5e1;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to the World of Natural Sciences</h1>
    <p>Unlock the secrets of the universe through science.</p>
  </header>

  <main>
    <section class="card">
      <h2>Biology</h2>
      <p>Study life in all its forms — from microscopic cells to vast ecosystems.</p>
    </section>
    <section class="card">
      <h2>Chemistry</h2>
      <p>Explore the composition of matter and the interactions that shape our world.</p>
    </section>
    <section class="card">
      <h2>Physics</h2>
      <p>Dive into the laws of nature that govern energy, motion, space, and time.</p>
    </section>
    <section class="card">
      <h2>Earth Science</h2>
      <p>Understand our planet — its structure, weather systems, and dynamic processes.</p>
    </section>
  </main>

  <footer>
    &copy; 2025 Natural Sciences Hub. All rights reserved.
  </footer>
</body>
</html>
