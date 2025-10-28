# portfolio
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hafashimana Rene | Portfolio</title>
  <style>
    /* ===== BASIC STYLES ===== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #000;
      color: #fff;
      line-height: 1.6;
    }

    h1, h2, h3 {
      color: #00aaff;
    }

    a {
      text-decoration: none;
      color: #00aaff;
      transition: 0.3s;
    }

    a:hover {
      color: #66ccff;
    }

    /* ===== HEADER / HERO SECTION ===== */
    header {
      background: linear-gradient(to bottom right, #001f3f, #000);
      color: white;
      text-align: center;
      padding: 120px 20px;
      background-image: url('https://images.unsplash.com/photo-1521790361159-9b1d0aef7c45?auto=format&fit=crop&w=1350&q=80');
      background-size: cover;
      background-position: center;
      background-blend-mode: multiply;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 15px;
      animation: fadeIn 1.5s ease-in;
      text-shadow: 0 0 10px #00aaff;
    }

    header p {
      font-size: 1.3rem;
      opacity: 0.9;
      animation: fadeIn 2s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* ===== NAVIGATION ===== */
    nav {
      display: flex;
      justify-content: center;
      background-color: #111;
      position: sticky;
      top: 0;
      z-index: 1000;
      border-bottom: 1px solid #00aaff;
    }

    nav a {
      color: white;
      padding: 15px 20px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    nav a:hover {
      background-color: #00aaff;
      color: #000;
    }

    /* ===== SECTIONS ===== */
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    #about, #projects, #achievements, #contact {
      background: #111;
      margin: 40px 0;
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.7);
    }

    p {
      font-size: 1rem;
      color: #ccc;
    }

    /* ===== PROJECTS ===== */
    .project {
      background-color: #000;
      margin: 20px 0;
      padding: 20px;
      border-radius: 10px;
      border: 1px solid #00aaff;
      transition: 0.3s;
    }

    .project:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 20px #00aaff;
    }

    /* ===== ACHIEVEMENTS SLIDESHOW ===== */
    .slideshow-container {
      position: relative;
      max-width: 100%;
      height: 350px;
      margin-top: 20px;
      overflow: hidden;
      border-radius: 10px;
      border: 1px solid #00aaff;
    }

    .slide {
      display: none;
      width: 100%;
      height: 100%;
    }

    .slide img {
      width: 100%;
      height: 350px;
      object-fit: cover;
      border-radius: 10px;
    }

    .fade {
      animation: fade 1s ease-in-out;
    }

    @keyframes fade {
      from { opacity: 0.4; }
      to { opacity: 1; }
    }

    /* ===== CONTACT ===== */
    #contact a {
      display: inline-block;
      margin-right: 15px;
      font-weight: bold;
      color: #00aaff;
    }

    /* ===== FOOTER ===== */
    footer {
      background-color: #000;
      color: #999;
      text-align: center;
      padding: 25px;
      font-size: 0.9rem;
      border-top: 1px solid #00aaff;
    }

    footer p {
      color: #999;
    }

    /* ===== RESPONSIVE DESIGN ===== */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }
      header p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <!-- ===== HERO SECTION ===== -->
  <header>
    <h1>Hi, I'm Hafashimana Rene</h1>
    <p>Front-End Developer | Designer | Innovator</p>
  </header>

  <!-- ===== NAVIGATION ===== -->
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#achievements">Achievements</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- ===== ABOUT SECTION ===== -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I'm Hafashimana Rene, a passionate web developer and designer focused on building
      interactive, visually appealing, and responsive websites.  
      I enjoy combining creativity with code to deliver great digital experiences.
    </p>
  </section>

  <!-- ===== PROJECTS SECTION ===== -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>1. Personal Portfolio</h3>
      <p>A responsive website designed to showcase my skills and work experience.</p>
    </div>
    <div class="project">
      <h3>2. E-commerce Platform</h3>
      <p>A modern shopping interface with product search and responsive design.</p>
    </div>
    <div class="project">
      <h3>3. Task Management App</h3>
      <p>A JavaScript-based task manager to organize daily to-dos efficiently.</p>
    </div>
  </section>

  <!-- ===== ACHIEVEMENTS SECTION ===== -->
  <section id="achievements">
    <h2>My Achievements</h2>
    <p>Highlights of my journey and milestones achieved:</p>

    <div class="slideshow-container">
      <div class="slide fade">
        <img src="https://images.unsplash.com/photo-1521790361159-9b1d0aef7c45?auto=format&fit=crop&w=800&q=80" alt="Award Ceremony">
      </div>
      <div class="slide fade">
        <img src="https://images.unsplash.com/photo-1581092580502-3e3a4a2c4b69?auto=format&fit=crop&w=800&q=80" alt="Tech Presentation">
      </div>
      <div class="slide fade">
        <img src="https://images.unsplash.com/photo-1551836022-d5d88e9218df?auto=format&fit=crop&w=800&q=80" alt="Certificate">
      </div>
      <div class="slide fade">
        <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=800&q=80" alt="Coding Achievement">
      </div>
      <div class="slide fade">
        <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=800&q=80" alt="Teamwork Success">
      </div>
      <div class="slide fade">
        <img src="https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?auto=format&fit=crop&w=800&q=80" alt="Innovation Award">
      </div>
    </div>
  </section>

  <!-- ===== CONTACT SECTION ===== -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Let’s connect or collaborate! Reach me through:</p>
    <p>
      📧 <a href="mailto:investorrene608@gmail.com">investorrene608@gmail.com</a><br>
      💼 <a href="https://github.com/hafashimanarene" target="_blank">github.com/hafashimanarene</a><br>
      🌐 <a href="https://linkedin.com/in/hafashimanarene" target="_blank">linkedin.com/in/hafashimanarene</a>
    </p>
  </section>

  <!-- ===== FOOTER ===== -->
  <footer>
    <p>© 2025 Hafashimana Rene — All Rights Reserved.</p>
  </footer>

  <!-- ===== JAVASCRIPT FOR SLIDESHOW ===== -->
  <script>
    let slideIndex = 0;
    showSlides();

    function showSlides() {
      let slides = document.getElementsByClassName("slide");
      for (let i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      slideIndex++;
      if (slideIndex > slides.length) { slideIndex = 1 }
      slides[slideIndex-1].style.display = "block";
      setTimeout(showSlides, 3000); // Switch every 3 seconds
    }
  </script>
</body>
</html>
