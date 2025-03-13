<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Akshith Veerisetty</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f8f9fa;
      color: #2c3e50;
      line-height: 1.6;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 40px 20px;
      text-align: center;
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: 56px;
      color: #2c3e50;
      margin-bottom: 20px;
      animation: fadeIn 2s ease-in-out;
    }

    .header-image {
      width: 100%;
      max-width: 800px;
      height: auto;
      border-radius: 12px;
      margin: 20px 0;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      animation: slideIn 1.5s ease-in-out;
    }

    p {
      font-size: 18px;
      color: #4a5568;
      margin-bottom: 30px;
      animation: fadeIn 2.5s ease-in-out;
    }

    h2 {
      font-family: 'Playfair Display', serif;
      font-size: 32px;
      color: #34495e;
      margin-top: 40px;
      margin-bottom: 20px;
      animation: fadeIn 3s ease-in-out;
    }

    ul {
      list-style-type: none;
      padding: 0;
      animation: fadeIn 3.5s ease-in-out;
    }

    ul li {
      font-size: 18px;
      margin-bottom: 10px;
      color: #4a5568;
    }

    ul li strong {
      color: #2c3e50;
    }

    a {
      color: #2980b9;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #1c5980;
    }

    .contact-email {
      font-size: 18px;
      color: #4a5568;
      animation: fadeIn 4s ease-in-out;
    }

    .footer {
      margin-top: 50px;
      font-size: 16px;
      color: #34495e;
      animation: fadeIn 4.5s ease-in-out;
    }

    /* Animations */
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    @keyframes slideIn {
      from {
        transform: translateY(-20px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Akshith Veerisetty</h1>
    <img src="github-header-image.png" alt="Header Image" class="header-image">
    <p>
      Currently a B.Tech student at IIIT Sri City. I'm all about tech, creativity, and a good movie night. Outside of coding, I enjoy exploring new hobbies and staying curious.
    </p>

    <h2>Find Me Online</h2>
    <ul>
      <li><strong>Instagram</strong>: <a href="https://instagram.com/_akshith.v_">@_akshith.v_</a></li>
      <li><strong>LinkedIn</strong>: <a href="https://www.linkedin.com/in/akshith-veerisetty">@akshith-veerisetty</a></li>
      <li><strong>GitHub</strong>: <a href="https://github.com/akshith-cdr">@akshith-cdr</a></li>
    </ul>

    <h2>Random Facts About Me</h2>
    <ul>
      <li>I'm a night owl 🌙</li>
      <li>Podcasts = relaxation 🎧</li>
      <li>I'm obsessed with VR/AR tech 🌐</li>
    </ul>

    <h2>Contact Me</h2>
    <p class="contact-email">
      Feel free to drop me an email at <a href="mailto:veerisettyakshith@gmail.com">veerisettyakshith@gmail.com</a> or reach out on social media.
    </p>

    <p class="footer">Thanks for visiting!</p>
  </div>
</body>
</html>
