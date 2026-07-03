<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ravi | Web Developer</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", Tahoma, sans-serif;
    }

    body {
      background-color: #0f172a;
      color: #e5e7eb;
      line-height: 1.6;
    }

    a {
      color: #38bdf8;
      text-decoration: none;
    }

    header {
      background: linear-gradient(135deg, #1e3a8a, #020617);
      padding: 70px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.8rem;
    }

    header h2 {
      font-weight: 400;
      margin-top: 10px;
      color: #cbd5f5;
    }

    header p {
      margin-top: 15px;
      color: #94a3b8;
    }

    section {
      max-width: 1000px;
      margin: auto;
      padding: 60px 20px;
    }

    h3 {
      font-size: 1.8rem;
      margin-bottom: 25px;
      border-left: 5px solid #38bdf8;
      padding-left: 12px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 20px;
    }

    .card {
      background: #020617;
      border: 1px solid #1e293b;
      padding: 20px;
      border-radius: 10px;
    }

    .card h4 {
      margin-bottom: 10px;
      color: #38bdf8;
    }

    ul {
      padding-left: 20px;
    }

    footer {
      background: #020617;
      text-align: center;
      padding: 30px;
      color: #94a3b8;
      font-size: 0.9rem;
    }

    .contact p {
      margin: 8px 0;
    }

    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 18px;
      border-radius: 6px;
      background: #38bdf8;
      color: #020617;
      font-weight: 600;
    }
  </style>
</head>

<body>

<header>
  <h1>Ravi</h1>
  <h2>Web Developer</h2>
  <p>Student | India</p>
</header>

<section>
  <h3>👨‍💻 About Me</h3>
  <p>
    I am a passionate student and aspiring <strong>Web Developer</strong> with a strong interest in building
    responsive, user-friendly websites. I enjoy working with modern web technologies and continuously
    improving my skills through hands-on practice and projects.
  </p>
</section>

<section>
  <h3>🧠 Skills</h3>
  <div class="grid">
    <div class="card">
      <h4>Programming</h4>
      <ul>
        <li>C++</li>
        <li>JavaScript</li>
      </ul>
    </div>

    <div class="card">
      <h4>Frontend</h4>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
      </ul>
    </div>

    <div class="card">
      <h4>Database</h4>
      <ul>
        <li>MySQL</li>
      </ul>
    </div>

    <div class="card">
      <h4>Tools</h4>
      <ul>
        <li>Git & GitHub</li>
        <li>Linux</li>
      </ul>
    </div>
  </div>
</section>

<section>
  <h3>🚀 Projects</h3>
  <div class="card">
    <p>
      Currently working on web development projects to strengthen frontend and backend fundamentals.
      More professional projects will be added soon.
    </p>
  </div>
</section>

<section class="contact">
  <h3>📫 Contact</h3>
  <p>📧 Email: <a href="mailto:bycgamechanger-pixel@gmail.com">bycgamechanger-pixel@gmail.com</a></p>
  <p>🐙 GitHub: <a href="https://github.com/" target="_blank">github.com</a></p>

  <a class="btn" href="mailto:bycgamechanger-pixel@gmail.com">Contact Me</a>
</section>

<footer>
  © 2026 Ravi • Web Developer
</footer>

</body>
</html>
