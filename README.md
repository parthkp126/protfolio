<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Parth Kaklotar — Portfolio</title>
  <meta name="description" content="Portfolio of Parth Kaklotar — Web developer, projects and contact."/>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="topbar">
    <div class="wrap">
      <div class="brand">
        <a href="#" class="brand-name">Parth <span class="last">Kaklotar</span></a>
      </div>
      <nav class="mainnav">
        <a href="#home">Home</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main>
    <section id="home" class="hero wrap">
      <div class="hero-left">
        <h1>Hi, I'm <strong>Parth Kaklotar</strong></h1>
        <p class="subtitle">Web Developer • Student • Frontend enthusiast</p>
        <p class="lead">I build responsive websites and small web apps using HTML, CSS and JavaScript. Here are some projects I made.</p>
        <p class="hero-cta">
          <a class="btn" href="#projects">View Projects</a>
          <a class="btn ghost" href="#contact">Contact</a>
        </p>
      </div>
      <div class="hero-right">
        <!-- Put your profile photo in images/profile.jpg -->
        <img src="images/profile.jpg" alt="Parth Kaklotar" class="profile">
      </div>
    </section>

    <section id="skills" class="section wrap">
      <h2>Skills</h2>
      <div class="skills-grid">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">React</div>
        <div class="skill">Git & GitHub</div>
        <div class="skill">Responsive Design</div>
      </div>
    </section>

    <section id="projects" class="section wrap alt">
      <h2>Projects</h2>
      <p class="section-note">Click a project to open live demo or code (replace links below with yours).</p>
      <div class="projects-grid">
        <!-- Project card example — copy / duplicate for more -->
        <article class="project">
          <a href="#" target="_blank" rel="noopener">
            <img src="images/proj1.png" alt="Project 1 screenshot">
          </a>
          <div class="proj-body">
            <h3>Portfolio Website</h3>
            <p class="proj-desc">A modern portfolio built with HTML & CSS. Responsive and fast.</p>
            <p class="proj-meta">Tech: HTML • CSS • JS</p>
            <p class="proj-links"><a href="#" target="_blank">Live</a> • <a href="#" target="_blank">Code</a></p>
          </div>
        </article>

        <article class="project">
          <a href="#" target="_blank" rel="noopener">
            <img src="images/proj2.png" alt="Project 2 screenshot">
          </a>
          <div class="proj-body">
            <h3>Task Manager</h3>
            <p class="proj-desc">Small task app using DOM and localStorage to save tasks.</p>
            <p class="proj-meta">Tech: JavaScript • HTML • CSS</p>
            <p class="proj-links"><a href="#" target="_blank">Live</a> • <a href="#" target="_blank">Code</a></p>
          </div>
        </article>
        <!-- add more project articles as needed -->
      </div>
    </section>

    <section id="about" class="section wrap">
      <h2>About</h2>
      <div class="about-grid">
        <div class="about-text">
          <p><strong>Parth Kaklotar</strong> — Computer Engineering student and web developer. I enjoy building accessible user interfaces and learning modern front-end tools.</p>
          <p>Education: Computer Engineering (Student). Location: India.</p>
          <p><a class="btn" href="resume.pdf" target="_blank">Download Resume</a></p>
        </div>
        <aside class="about-aside">
          <p><strong>Email</strong></p>
          <p><a href="mailto:parthkaklotar544@gmail.com">parthkaklotar544@gmail.com</a></p>
          <p><strong>GitHub</strong></p>
          <p><a href="https://github.com/parthkp126" target="_blank">github.com/parthkp126</a></p>
        </aside>
      </div>
    </section>

    <section id="contact" class="section wrap alt">
      <h2>Contact</h2>
      <p class="section-note">Send me a short message</p>
      <form class="contact-form" onsubmit="alert('This form is a demo. Configure Formspree or Netlify for real messages.'); return false;">
        <label>
          Name
          <input type="text" name="name" required placeholder="Your name">
        </label>
        <label>
          Email
          <input type="email" name="email" required placeholder="you@example.com">
        </label>
        <label>
          Message
          <textarea name="message" rows="5" required placeholder="Write your message..."></textarea>
        </label>
        <button class="btn" type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer class="foot">
    <div class="wrap">
      <p>© <span id="year"></span> Parth Kaklotar — Built with HTML &amp; CSS</p>
    </div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
