<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0" />
  <link rel="stylesheet" href="style3.css" />
</head>
<body>
  <!-- THEME TOGGLE -->
  <button id="theme-toggle" aria-label="Toggle theme">🌙</button>

  <!-- NAV BAR -->
  <header>
    <nav class="navbar">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
      <a href="#admin">Admin</a>
    </nav>
  </header>

  <!-- HOME -->
  <section id="home" class="container">
    <h1>Hi, I’m M.shubham</h1>
    <p> hello welcome to my page
        <BR>
        <A href="https://www.instagram.com/m.shubham000?igsh=bm1jbDZzbDVvYng5"> @ INSTAGRAM </A>
        <BR>
         <A href="https://youtube.com/@roll_no_101?si=hyRqCsMAcLVGHsGQ"> @ YOUTUBE</A>
        <BR>
            <A href="https://github.com/shubham143dot"> @ GITHUB</A>
            <BR>
                <A href="https://www.linkedin.com/in/m-shubham-335614328?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"> @ LINKEDIN</A>
        </p>
  </section>

  <!-- ABOUT -->
  <section id="about" class="container">
    <h2>About Me</h2>
    <p> STATE- WEST BENGAL.
        <BR>
        <BR>
        CITY-  KHARAGPUR.
        <BR>
        <BR>
        EDUCATION BACKGROUND - 12 CLASS PASSOUT(WITH HUMANITIES STREAM).
        <BR>
        <BR>
        HOBBIES - PLAYING ESPORTS GAMES , COODING , COOKING , MOBILE PHOTOGRAPHY.  
        <BR>
        <BR>
         SKILLS - HTML , CSS , JAVASCRIPT , C , C++ , KOTLIN.  
         <BR>
         <BR>
          SPEAKING LANGUAGES - HINDI , ENGLISH , BENGALI , TELUGU(MOTHER TONGUE) , FRENCH.
          <BR>
            <BR>
                AIM(GOAL) - TO BECOME A SUCESSFUL ENTREPRENEUR IN THE FIELD OF APP DEVELOPMENT.         
        </p>
  </section>

  <!-- PORTFOLIO -->
  <section id="portfolio" class="container">
    <h2>Portfolio</h2>
    <div class="projects-grid">
      <!-- Repeat this card for each project -->
      <article class="project-card">
        <h3>Project One</h3>
        <p>Short description.</p>
        <a href="#">View ↗</a>
      </article>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="container">
    <h2>Contact Me</h2>
    <form id="contact-form">
      <label>
        Name
        <input type="text" id="name" required />
      </label>
      <label>
        Email
        <input type="email" id="email" required />
      </label>
      <label>
        Message
        <textarea id="message" rows="4" required></textarea>
      </label>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- ADMIN -->
  <section id="admin" class="container">
    <h2>Admin Panel</h2>
    <!-- Login Form -->
    <div id="login-panel">
      <label>
        Username
        <input type="text" id="admin-user" />
      </label>
      <label>
        Password
        <input type="password" id="admin-pass" />
      </label>
      <button id="login-btn">Login</button>
      <p id="login-error" class="error"></p>
    </div>

    <!-- Responses List (initially hidden) -->
    <div id="responses-panel" class="hidden">
      <h3>User Submissions</h3>
      <ul id="responses-list"></ul>
    </div>
  </section>

  <footer class="container">
    <p>&copy; 2025 Your Name. All Rights Reserved.</p>
  </footer>
  <!-- load EmailJS SDK -->
<script src="https://cdn.emailjs.com/sdk/2.3.2/email.min.js"></script>
<script>
  // initialize with your user ID
  emailjs.init('gXlkW5ipvdk4t9ttT');
</script>
<script src="script.js"></script>

  
</body>
</html>
        <BR>
         <A href="https://youtube.com/@roll_no_101?si=hyRqCsMAcLVGHsGQ"> @ YOUTUBE</A>
        <BR>
            <A href="https://github.com/shubham143dot"> @ GITHUB</A>
            <BR>
                <A href="https://www.linkedin.com/in/m-shubham-335614328?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"> @ LINKEDIN</A>
        </p>
  
          <BR>
            <BR>
                AIM(GOAL) - TO BECOME A SUCESSFUL ENTREPRENEUR IN THE FIELD OF APP DEVELOPMENT.         
        </p>
  
      <button type="submit">Send Message</button>
  
 
