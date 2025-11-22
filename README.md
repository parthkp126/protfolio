<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hi, I'm PARTH KAKLOTAR</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      background: radial-gradient(circle at 35% 50%, #26326e 0%, #0e1526 100%);
      color: #f3f6fd;
      font-family: 'Segoe UI', Arial, sans-serif;
      margin: 0;
      padding: 0;
      min-height: 100vh;
    }
    .hero-container {
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      gap: 48px;
      flex-wrap: wrap;
    }
    .profile-img-container {
      background: radial-gradient(circle at 60% 35%, #4754d3 45%, #222c5c 80%);
      border-radius: 50%;
      padding: 12px;
      width: 340px;
      height: 340px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 6px 24px rgba(32,42,73,0.50);
    }
    .profile-img {
      width: 310px;
      height: 310px;
      object-fit: cover;
      border-radius: 50%;
      border: 2px solid #888ed2;
      box-shadow: 0 4px 20px #28305880;
    }
    .hero-content {
      max-width: 600px;
      display: flex;
      flex-direction: column;
      gap: 24px;
    }
    .hero-content h1 {
      font-size: 3em;
      margin: 0;
      font-weight: bold;
      letter-spacing: 0.01em;
      color: #fff;
    }
    .hero-content h1 strong {
      color: #756bf3;
      text-decoration: underline;
      text-decoration-color: #554ec7;
    }
    .subtitle {
      font-size: 1.4em;
      color: #8ca2ff;
      font-weight: 600;
      margin-bottom: 12px;
    }
    .hero-content p {
      font-size: 1.2em;
      color: #f4f5fa;
    }
    .button-row {
      display: flex;
      gap: 28px;
      margin-top: 12px;
    }
    .hero-button {
      font-size: 1.14em;
      padding: 12px 32px;
      border-radius: 8px;
      border: none;
      background: #756bf3;
      color: white;
      font-weight: 600;
      box-shadow: 0 3px 16px #1e1e4670;
      cursor: pointer;
      transition: background 0.2s, color 0.2s;
    }
    .hero-button.secondary {
      background: transparent;
      color: #8ca2ff;
      border: 2px solid #756bf3;
    }
    .hero-button:hover {
      background: #554ec7;
      color: #fff;
    }
    .hero-button.secondary:hover {
      background: #756bf3;
      color: #fff;
    }
    @media (max-width: 1020px) {
      .hero-container { flex-wrap: wrap; gap: 16px; }
      .profile-img-container { width: 220px; height: 220px; }
      .profile-img { width: 190px; height: 190px; }
      .hero-content { max-width: 390px; }
      .hero-content h1 { font-size: 2em; }
    }
     @media (max-width: 700px) {
      .hero-container { flex-direction: column; gap: 0; min-height: 80vh; }
      .hero-content { align-items: center; }
    }
  </style>
</head>
<body>
  <div class="hero-container">
    <!-- Left: Your image in circle style -->
    <div class="profile-img-container">
      <img class="profile-img" src="image.jpg" alt="Parth Kaklotar profile">
    </div>
    <!-- Right: Hero text -->
    <div class="hero-content">
      <h1>Hi, I'm <strong>PARTH KAKLOTAR</strong></h1>
      <div class="subtitle">
        Full-Stack Developer | ML Engineer | AI Enthusiast
      </div>
      <p>
        Welcome to my portfolio! I'm passionate about building elegant solutions to complex problems. With expertise in web development and a keen eye for design, I create digital experiences that make a difference.
      </p>
      <div class="button-row">
        <a href="#projects"><button class="hero-button">View My Work</button></a>
        <a href="#contact"><button class="hero-button secondary">Get In Touch</button></a>
      </div>
    </div>
  </div>
</body>
</html>
