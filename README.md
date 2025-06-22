<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mickey Alemayehu | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    :root {
      --primary-color: #2c3e50;
      --secondary-color: #3498db;
      --background-color: #f0f2f5;
      --text-color: #34495e;
      --card-background: #ffffff;
      --shadow-color: rgba(0, 0, 0, 0.1);
    }

    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      background-color: var(--background-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 0 2rem;
    }

    header {
      background: linear-gradient(45deg, #2c3e50, #34495e);
      color: white;
      padding: 4rem 2rem;
      text-align: center;
      clip-path: polygon(0 0, 100% 0, 100% 90%, 0 100%);
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      font-weight: 800;
    }

    header ul {
      list-style: none;
      padding: 0;
      margin: 1rem 0;
      font-size: 1.1rem;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }

    header p {
      margin-top: 1.5rem;
      font-size: 1.2rem;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }

    .social-links {
      margin-top: 2rem;
    }

    .social-links a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    .social-links a:hover {
      color: var(--secondary-color);
    }

    main {
        padding-top: 4rem;
        padding-bottom: 4rem;
    }

    .skills {
      text-align: center;
    }

    .skills h2 {
      font-size: 2.5rem;
      margin-bottom: 3rem;
      font-weight: 800;
      color: var(--primary-color);
    }

    .skills-category {
      background: var(--card-background);
      margin-bottom: 2.5rem;
      padding: 2.5rem;
      border-radius: 15px;
      box-shadow: 0 5px 20px var(--shadow-color);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .skills-category:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 25px var(--shadow-color);
    }

    .skills-category h3 {
      margin-top: 0;
      margin-bottom: 2rem;
      color: var(--primary-color);
      font-size: 1.5rem;
    }

    .skills-grid {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2.5rem;
    }

    .skill-item {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 0.75rem;
        width: 100px;
        text-align: center;
    }

    .skill-item img {
      width: 60px;
      height: 60px;
      object-fit: contain;
      transition: transform 0.3s ease;
    }

    .skill-item img:hover {
      transform: scale(1.15);
    }
    
    .skill-item span {
        font-size: 0.9rem;
        font-weight: 600;
    }

    .contact {
      background: var(--card-background);
      padding: 3rem;
      border-radius: 15px;
      box-shadow: 0 5px 20px var(--shadow-color);
      text-align: center;
      margin-top: 3rem;
    }

    .contact h2 {
      font-size: 2.5rem;
      margin-bottom: 2rem;
      font-weight: 800;
      color: var(--primary-color);
    }

    .contact p {
      font-size: 1.1rem;
      margin-bottom: 2.5rem;
      color: var(--text-color);
    }

    .contact-links {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2rem;
    }

    .contact-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 0.75rem;
      padding: 1.5rem;
      border-radius: 10px;
      background: var(--background-color);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      min-width: 120px;
    }

    .contact-item:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px var(--shadow-color);
    }

    .contact-item i {
      font-size: 2rem;
      color: var(--secondary-color);
    }

    .contact-item a {
      text-decoration: none;
      color: var(--text-color);
      font-weight: 600;
      font-size: 0.9rem;
    }

    .contact-item a:hover {
      color: var(--secondary-color);
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 3rem;
    }

    @media (max-width: 768px) {
        header {
            padding: 3rem 1rem;
            clip-path: polygon(0 0, 100% 0, 100% 95%, 0 100%);
        }
        header h1 {
            font-size: 2.5rem;
        }
        .container {
            padding: 0 1.5rem;
        }
        main {
            padding-top: 3rem;
            padding-bottom: 3rem;
        }
        .skills-grid {
            gap: 1.5rem;
        }
        .contact {
            padding: 2rem;
        }
        .contact-links {
            gap: 1rem;
        }
    }
  </style>
</head>
<body>
  <header>
    <h1>Mickey Alemayehu</h1>
    <ul>
      <li>
        I am a third-year Computer Science student at Addis Ababa University.
      </li>
      <li>
        I am currently a backend development student at ALX.
      </li>
    </ul>
    <p>I'm passionate about technology and eager to learn, build, and collaborate on impactful software projects.</p>
    <div class="social-links">
      <a href="mailto:michaelzewdu1996@gmail.com">Email</a>
      <a href="https://www.linkedin.com/in/michaelzewdu" target="_blank">LinkedIn</a>
      <a href="https://www.instagram.com/mickey_innit/" target="_blank">Instagram</a>
      <a href="https://github.com/MickeyAlemayehu" target="_blank">GitHub</a>
    </div>
  </header>

  <main>
    <div class="container">
      <section class="skills">
        <h2>Tech Stack</h2>

        <div class="skills-category">
          <h3>Frontend</h3>
          <div class="skills-grid">
            <div class="skill-item">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" title="HTML5" />
              <span>HTML5</span>
            </div>
            <div class="skill-item">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" title="CSS3" />
              <span>CSS3</span>
            </div>
            <div class="skill-item">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" />
              <span>JavaScript</span>
            </div>
          </div>
        </div>

        <div class="skills-category">
          <h3>Backend</h3>
          <div class="skills-grid">
            <div class="skill-item">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP" title="PHP" />
              <span>PHP</span>
            </div>
            <div class="skill-item">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" title="Java" />
              <span>Java</span>
            </div>
            <div class="skill-item">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring" title="Spring" />
              <span>Spring</span>
            </div>
          </div>
        </div>

        <div class="skills-category">
          <h3>Databases</h3>
          <div class="skills-grid">
            <div class="skill-item">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" title="MySQL" />
              <span>MySQL</span>
            </div>
          </div>
        </div>

        <div class="skills-category">
          <h3>Tools</h3>
          <div class="skills-grid">
            <div class="skill-item">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git" />
              <span>Git</span>
            </div>
            <div class="skill-item">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" alt="Postman" title="Postman" />
              <span>Postman</span>
            </div>
            <div class="skill-item">
              <img src="https://raw.githubusercontent.com/thunder-client/thunderclient-logo/main/logo.png" alt="Thunder Client" title="Thunder Client" />
              <span>Thunder Client</span>
            </div>
          </div>
        </div>
      </section>

      <section class="contact">
        <h2>Get In Touch</h2>
        <p>Feel free to reach out to me for collaborations, opportunities, or just to say hello!</p>
        <div class="contact-links">
          <div class="contact-item">
            <i class="fas fa-envelope"></i>
            <a href="mailto:michaelzewdu1996@gmail.com">Email</a>
          </div>
          <div class="contact-item">
            <i class="fab fa-linkedin"></i>
            <a href="https://www.linkedin.com/in/michaelzewdu" target="_blank">LinkedIn</a>
          </div>
          <div class="contact-item">
            <i class="fab fa-instagram"></i>
            <a href="https://www.instagram.com/mickey_innit/" target="_blank">Instagram</a>
          </div>
          <div class="contact-item">
            <i class="fab fa-github"></i>
            <a href="https://github.com/MickeyAlemayehu" target="_blank">GitHub</a>
          </div>
        </div>
      </section>
    </div>
  </main>
</body>
</html>
![image](https://github.com/user-attachments/assets/23e31e20-155c-495b-b9a6-aedd53f3f7b7)
