<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mahmoud Najmeh Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
      color: #333;
      text-align: center;
      padding: 50px 20px;
    }

    h1 {
      font-size: 3rem;
      color: #0A74DA;
      animation: fadeInDown 2s;
    }

    p {
      font-size: 1.25rem;
      margin-top: 10px;
      animation: fadeInUp 2s;
    }

    .section-title {
      font-size: 2rem;
      margin-top: 40px;
      color: #0A74DA;
    }

    .skills, .links {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin: 20px 0;
    }

    .icon {
      width: 50px;
      transition: transform 0.3s ease;
    }

    .icon:hover {
      transform: scale(1.2);
    }

    a {
      text-decoration: none;
      color: #0A74DA;
      font-weight: bold;
    }

    .button-link {
      display: inline-block;
      padding: 10px 20px;
      background-color: #0A74DA;
      color: white;
      border-radius: 5px;
      transition: background-color 0.3s;
      margin: 10px;
    }

    .button-link:hover {
      background-color: #005bb5;
    }

    /* Keyframe Animations */
    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <h1>👋 Hello! I'm Mahmoud Najmeh</h1>
  <p>Software Developer | Passionate about Coding & Innovation</p>

  <section>
    <h2 class="section-title">🚀 Currently Working On</h2>
    <p>Exploring cutting-edge technologies & frameworks, continuously learning modern software engineering practices.</p>
  </section>

  <section>
    <h2 class="section-title">🌱 Skills & Expertise</h2>
    <div class="skills">
      <img class="icon" src="https://skillicons.dev/icons?i=java" alt="Java">
      <img class="icon" src="https://skillicons.dev/icons?i=spring" alt="Spring Boot">
      <img class="icon" src="https://skillicons.dev/icons?i=postgresql" alt="PostgreSQL">
      <img class="icon" src="https://skillicons.dev/icons?i=react" alt="React">
      <img class="icon" src="https://skillicons.dev/icons?i=aws" alt="AWS">
      <img class="icon" src="https://skillicons.dev/icons?i=gcp" alt="GCP">
      <img class="icon" src="https://skillicons.dev/icons?i=github" alt="GitHub">
    </div>
  </section>

  <section>
    <h2 class="section-title">🔗 Connect with Me</h2>
    <div class="links">
      <a class="button-link" href="https://mn10101.github.io/portfolio-mn/" target="_blank">My Portfolio</a>
      <a class="button-link" href="https://www.linkedin.com/in/mahmoud-najmeh-b53172211" target="_blank">LinkedIn</a>
      <a class="button-link" href="https://www.xing.com/profile/Mahmoud_Najmeh031649/web_profiles" target="_blank">Xing</a>
      <a class="button-link" href="mailto:mn.de@outlook.com" target="_blank">Email Me</a>
    </div>
  </section>
</body>
</html>
