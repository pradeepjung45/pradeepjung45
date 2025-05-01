<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pradeep Karki - Portfolio</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      font-family: "Segoe UI", sans-serif;
    }

    .profile-container {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1.5rem;
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 4px 24px rgba(0,0,0,0.08);
    }

    .header {
      text-align: center;
      padding: 1.5rem 0;
      border-bottom: 1px solid #eee;
    }

    .header h1 {
      font-size: 2.2em;
      color: #1a252f;
      margin: 0;
    }

    .header p {
      color: #4a5568;
      margin: 0.4em 0;
    }

    .section {
      padding: 1.5rem 0;
      border-bottom: 1px solid #eee;
    }

    .section:last-child {
      border-bottom: none;
    }

    h2 {
      color: #2c3e50;
      margin: 0 0 1rem;
      font-size: 1.4em;
      border-bottom: 2px solid #3498db;
      padding-bottom: 0.3em;
    }

    p {
      color: #34495e;
      line-height: 1.6;
      margin: 0.5em 0;
    }

    ul {
      margin: 0;
      padding-left: 1.2em;
      color: #34495e;
    }

    li {
      margin: 0.6em 0;
      line-height: 1.5;
    }

    .tools-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(70px, 1fr));
      gap: 1.2rem;
      justify-items: center;
      margin-top: 1rem;
    }

    .tool-icon {
      transition: transform 0.2s ease, filter 0.2s ease;
    }

    .tool-icon:hover {
      transform: scale(1.1);
      filter: brightness(1.1);
    }

    .social-icons {
      text-align: center;
    }

    .social-icons a {
      display: inline-block;
      margin: 0 0.8rem;
      transition: transform 0.2s ease;
    }

    .social-icons img {
      width: 40px;
      height: 40px;
      object-fit: contain;
      transition: transform 0.2s ease;
    }

    .social-icons a:hover img {
      transform: scale(1.2);
      filter: brightness(1.2);
    }

    .highlight-blue {
      border-color: #3498db !important;
    }

    .highlight-orange {
      border-color: #e67e22 !important;
    }

    .highlight-green {
      border-color: #2ecc71 !important;
    }

    .highlight-purple {
      border-color: #9b59b6 !important;
    }

    @media (max-width: 500px) {
      .tools-grid {
        grid-template-columns: repeat(4, 1fr);
      }
    }
  </style>
</head>
<body>
  <div class="profile-container">
    <!-- Header -->
    <div class="header">
      <h1>👨‍💻 Pradeep Karki</h1>
      <p>Software Developer | AI Enthusiast | Blockchain Explorer</p>
      <p style="font-style: italic; color: #76838f;">Based in Nepal 🏔️</p>
    </div>

    <!-- About Me -->
    <div class="section">
      <h2 class="highlight-blue">🚀 About Me</h2>
      <p>Passionate software developer building intelligent systems and decentralized solutions. Specializing in AI, blockchain, and full-stack development. Exploring Agentic AI Frameworks, Solana, and Anchor.</p>
      <p style="margin-top: 1em;">When not coding, you'll find me hiking Himalayas, experimenting with Nepali cuisine, or brainstorming projects over chai 🧋</p>
    </div>

    <!-- What I Do -->
    <div class="section">
      <h2 class="highlight-orange">🌟 What I Do</h2>
      <ul>
        <li>🧠 <strong>AI & ML</strong>: TensorFlow, Scikit-learn, LangChain</li>
        <li>🎨 <strong>Frontend</strong>: React, JavaScript, HTML/CSS</li>
        <li>⚙️ <strong>Backend</strong>: Node.js, Express, PostgreSQL</li>
        <li>⛓️ <strong>Blockchain</strong>: Solana, Anchor, Smart Contracts</li>
        <li>📦 <strong>Open Source</strong>: Building impactful solutions</li>
      </ul>
    </div>

    <!-- Languages & Tools -->
    <div class="section">
      <h2 class="highlight-green">🛠️ Languages & Tools</h2>
      <div class="tools-grid">
        <a href="https://www.cprogramming.com/" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" /></a>
        <a href="https://www.w3schools.com/css/" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" /></a>
        <a href="https://expressjs.com" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express.js" /></a>
        <a href="https://git-scm.com/" target="_blank" class="tool-icon"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" /></a>
        <a href="https://www.w3.org/html/" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" /></a>
        <a href="https://www.linux.org/" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" /></a>
        <a href="https://nodejs.org" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" /></a>
        <a href="https://pandas.pydata.org/" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="Pandas" /></a>
        <a href="https://www.postgresql.org" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" /></a>
        <a href="https://postman.com" target="_blank" class="tool-icon"><img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman" /></a>
        <a href="https://www.python.org" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" /></a>
        <a href="https://reactjs.org/" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" /></a>
        <a href="https://www.rust-lang.org" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" alt="Rust" /></a>
        <a href="https://scikit-learn.org/" target="_blank" class="tool-icon"><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="Scikit-learn" /></a>
        <a href="https://www.tensorflow.org" target="_blank" class="tool-icon"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" /></a>
        <a href="https://solana.com" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/solana/solana-original.svg" alt="Solana" /></a>
      </div>
    </div>

    <!-- Connect -->
    <div class="section">
      <h2 class="highlight-purple">📬 Connect</h2>
      <div class="social-icons">
        <a href="https://linkedin.com/in/pradeep-karki" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn"/></a>
        <a href="mailto:karkeepradeep654@gmail.com"><img src="https://img.icons8.com/color/48/000000/gmail.png" alt="Email"/></a>
        <a href="https://twitter.com/pradeepkarki" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/twitter/twitter-original.svg" alt="Twitter"/></a>
      </div>
      <p style="text-align: center; margin-top: 1em;">Let's discuss tech, mountains, or momos!</p>
    </div>

    <!-- Projects & Fun Fact -->
    <div class="section">
      <h2>🎯 Current Projects</h2>
      <ul>
        <li>🤖 AI Analytics Platform</li>
        <li>🪙 Solana dApp with Anchor</li>
        <li>🧠 Agentic AI Research</li>
      </ul>
    </div>

    <div class="section" style="background: #e8f5e9; text-align: center;">
      <p><strong>😄 Fun Fact:</strong> Coded a smart contract at 3,000m in the Himalayas!</p>
      <p style="margin-top: 0.8em; font-style: italic; color: #4a5568;">"Code is poetry - elegance meets precision"</p>
    </div>
  </div>
</body>
</html>
