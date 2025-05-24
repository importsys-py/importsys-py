<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Profilo di import_sys</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Fira+Code&family=Montserrat:wght@400;700&display=swap');

    body {
      background: #0f2027;  /* gradient dark */
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #e0e6f3;
      font-family: 'Montserrat', sans-serif;
      margin: 0;
      padding: 2rem;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    h1 {
      font-family: 'Fira Code', monospace;
      font-weight: 700;
      font-size: 2.8rem;
      margin-bottom: 0.2rem;
      text-align: center;
      color: #4ee1ff;
      text-shadow: 0 0 8px #00bfff;
    }

    code {
      background: #222d35;
      padding: 0.1rem 0.5rem;
      border-radius: 5px;
      font-weight: 700;
      color: #6ef7ff;
    }

    h3 {
      max-width: 600px;
      font-weight: 400;
      font-size: 1.1rem;
      text-align: center;
      color: #a6b8c9;
      line-height: 1.5;
      margin-top: 0;
      margin-bottom: 2rem;
      font-style: italic;
    }

    .gif-container {
      margin: 1rem 0 3rem 0;
      width: 150px;
      height: 150px;
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 0 20px #00bfff80;
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    .section-title {
      font-size: 2rem;
      font-weight: 700;
      color: #59c9ff;
      margin-bottom: 0.7rem;
      text-align: center;
      text-shadow: 0 0 5px #59c9ff88;
    }

    p, ul {
      max-width: 650px;
      font-size: 1rem;
      line-height: 1.6;
      color: #c3d3e8;
      text-align: center;
      margin-bottom: 2rem;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin: 0.5rem 0;
      padding-left: 1.2rem;
      position: relative;
      text-align: left;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
      color: #9bdcff;
      font-weight: 500;
      cursor: default;
    }

    ul li::before {
      content: "🚀";
      position: absolute;
      left: 0;
      top: 0;
    }

    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      margin-bottom: 2rem;
    }

    .tech-stack a {
      display: inline-block;
      filter: drop-shadow(0 0 2px #00bfffaa);
      transition: transform 0.3s ease;
    }

    .tech-stack a:hover {
      transform: scale(1.1);
    }

    .contact {
      display: flex;
      justify-content: center;
      gap: 1rem;
      margin-top: 2rem;
    }

    .contact a img {
      height: 40px;
      filter: drop-shadow(0 0 4px #00bfffaa);
      transition: transform 0.3s ease;
    }

    .contact a:hover img {
      transform: scale(1.2);
    }

    footer {
      margin-top: 3rem;
      font-style: italic;
      color: #58c9ffbb;
      font-weight: 600;
      text-align: center;
    }
  </style>
</head>
<body>

  <h1>Hi there, I'm Alessandro (aka <code>import_sys</code>) 👋</h1>
  <h3>
    🎓 15 y/o High School Student in Computer Science<br />
    📅 Birthday: May 23rd 🕒<br />
    🌍 Based in Sicily, Italy 🇮🇹<br />
    👨‍💻 Passionate about coding bots, software and AI systems<br />
    🧠 I <em>love</em> experimenting with Artificial Intelligence<br />
    📐 Math & Physics enthusiast — because every code needs its formulas! ⚛️
  </h3>

  <div class="gif-container">
    <img src="https://media.giphy.com/media/f9tL1l6RWZ3b9qQq7F/giphy.gif" alt="Hacker typing code" width="150" height="150" />
  </div>

  <h2 class="section-title">🚀 Main Projects</h2>
  <p>For now zero projects... but watch this space! 👀</p>

  <h2 class="section-title">🧠 Tech Stack</h2>
  <div class="tech-stack">
    <a href="https://www.python.org/" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
    </a>
    <a href="https://www.java.com/" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java"/>
    </a>
    <a href="https://en.wikipedia.org/wiki/C_(programming_language)" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" alt="C"/>
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
    </a>
    <a href="https://www.mysql.com/" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
    </a>
    <a href="https://www.sqlite.org/index.html" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
    </a>
    <a href="https://mariadb.org/" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" alt="MariaDB"/>
    </a>
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode"/>
    </a>
    <a href="https://www.jetbrains.com/idea/" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/-IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white" alt="IntelliJ IDEA"/>
    </a>
  </div>

  <h2 class="section-title">🎯 Goals</h2>
  <ul>
    <li>Learn and master <strong>Python</strong>, <strong>MySQL</strong> and <strong>MariaDB</strong></li>
    <li>Improve <strong>Java</strong> and <strong>C</strong> programming skills</li>
    <li>Dive into <strong>AI</strong>, <strong>Machine Learning</strong>, and <strong>Deep Learning</strong></li>
    <li>Create awesome <strong>bots</strong>, <strong>software</strong>, and <strong>websites</strong></li>
    <li>Build and publish cool <strong>AI projects</strong> (with PyTorch in the future 🔥)</li>
    <li>Develop and release a secure <strong>Minecraft mod</strong></li>
    <li>Grow my GitHub portfolio with meaningful, useful projects</li>
  </ul>

  <h2 class="section-title">📬 Contact Me</h2>
  <div class="contact">
    <a href="https://t.me/importsyss" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/Telegram-0088CC?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
    </a>
    <a href="https://discord.com/users/1106645819811184754" target="_blank" rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/>
    </a>
  </div>

  <footer>
    🧠 "Intelligence is not knowing everything, it's being able to learn anything."
  </footer>

</body>
</html>
