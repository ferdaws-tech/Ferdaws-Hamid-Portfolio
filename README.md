@@ -0,0 +1,126 @@
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Open Graph Meta Tags -->
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="A student in Sydney, Australia, passionate about Afghan cuisine and web development. Aspiring to become a doctor.">
<meta property="og:image" content="https://yourwebsite.github.io/images/profile.jpg">
<meta property="og:url" content="https://yourwebsite.github.io/">
<meta property="og:type" content="website">
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Professional Portfolio of [Your Name]" />
  <title>[Your Name] - Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "name": "Ferdaws Hamid",
      "gender": "Male",
      "jobTitle": "Student",
      "url": "https://yourwebsite.github.io/",
      "address": {
        "@type": "PostalAddress",
        "addressLocality": "Sydney",
        "addressCountry": "Australia"
      },
      "height": "1.73 cm",
      "alumniOf": "Your School or College",
      "knowsAbout": ["Web Development", "Afghan Cuisine"],
      "knowsLanguage": ["English", "Dari"],
      "sameAs": [
        "https://www.linkedin.com/in/your-profile",
        "https://github.com/yourgithub"
      ]
    }
    </script>
  <!-- Fonts and Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  
  <!-- Open Graph Meta Tags for Social Media Preview -->
  <meta property="og:title" content="[Your Name] - Professional Portfolio" />
  <meta property="og:description" content="Explore the professional portfolio of [Your Name], showcasing skills, achievements, and contact information." />
  <meta property="og:image" content="[Link to Your Image]" />
  <meta property="og:url" content="https://username.github.io" />
</head>
<body>
  <header>
    <div class="container">
      <h1>[Ferdaws] [Hamid]</h1>
      <p>[Student]</p>
    </div>
  </header>
  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
  <section id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>
        <li>🎓 Education: Currently a student based in Sydney, Australia, with a passion for learning and exploring diverse skills.</li>
        <li>🍳 Culinary Skills: Experienced in cooking and creating flavorful dishes inspired by Afghanistan and traditional Afghan cuisine.</li>
        <li>💻 Web Development Expertise: Proficient in HTML, CSS, JavaScript, and Bootstrap, with hands-on experience in building responsive and modern websites.</li>
        <li>🎯 Future Goals: Aspiring to become a doctor, combining dedication and hard work to achieve excellence in the medical field.</li>
        <li>🌟 Key Strengths: Creativity, adaptability, and a results-driven mindset.</li>
    </p>
      <ul>
        <li><strong>Full Name:</strong> [Ferdaws Hamid]</li>
        <li><strong>Height:</strong> 1.73 cm</li>
        <li><strong>Age:</strong> [14]</li>
        <li><strong>Gender:</strong> [Male]</li>
        <li><strong>Location:</strong> [Sydney, Australia]</li>
      </ul>
    </div>
  </section>
  <section id="skills">
    <div class="container">
      <h2>Skills</h2>
      <ul>
        <li>[🍳 Culinary Skills: Experienced in cooking and creating flavorful dishes inspired by Afghanistan and traditional Afghan cuisine.]</li>
        <li>[💻 Web Development Expertise: Proficient in HTML, CSS, JavaScript, and Bootstrap, with hands-on experience in building responsive and modern websites.]</li>
        <li>[Not included yet!]</li>
        <li>[Not included yet!]</li>
      </ul>
    </div>
  </section>
  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:ferdowshamidhamid@gmail.com">ferdowshamidhamid@gmail.com</a></p>
      <p>Phone: [Not included yet!]</p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/username">[Not included yet!]</a></p>
    </div>
  </section>
  <footer>
    <p>© 2025 [Ferdaws]. All rights reserved.</p>
  </footer>
 
  <script>
const menuToggle = document.querySelector('.menu-toggle');
const navMenu = document.querySelector('nav ul');
menuToggle.addEventListener('click', () => {
  navMenu.classList.toggle('active');
  menuToggle.classList.toggle('open'); // Add animation for toggle button
});
  </script>
</body>
</html>
‎style.css
+229
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,229 @@
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    color: #333;
    background: #f4f4f9;
  }
  
  .container {
    width: 90%;
    max-width: 1100px;
    margin: 0 auto;
    padding: 20px 0;
  }
  
  /* Header Styles */
  header {
    background: linear-gradient(135deg, #6b73ff 0%, #000dff 100%);
    color: #fff;
    padding: 40px 0;
    text-align: center;
  }
  
  header h1 {
    font-size: 3rem;
    font-weight: 700;
  }
  
  header p {
    font-size: 1.2rem;
  }
  
  /* Navigation Styles */
  nav {
    background: #fff;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    padding: 10px 0;
    position: relative;
  }
  
  nav ul {
    display: flex;
    justify-content: center;
    align-items: center;
    list-style: none;
  }
  
  nav ul li {
    margin: 0 15px;
  }
  
  nav a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s ease;
  }
  
  nav a:hover {
    color: #6b73ff;
  }
  
  /* Responsive Menu Button */
  .menu-toggle {
    display: none;
    flex-direction: column;
    cursor: pointer;
    position: absolute;
    top: 10px;
    right: 15px;
    z-index: 10;
  }
  
  .menu-toggle div {
    width: 25px;
    height: 3px;
    background: #333;
    margin: 5px;
    transition: all 0.3s ease;
  }
  
  .menu-toggle.open div:nth-child(1) {
    transform: rotate(45deg) translate(5px, 5px);
  }
  .menu-toggle.open div:nth-child(2) {
    opacity: 0;
  }
  .menu-toggle.open div:nth-child(3) {
    transform: rotate(-45deg) translate(5px, -5px);
  }
  
  nav ul.active {
    display: flex;
  }
  
  /* Section Styles */
  section {
    padding: 40px 20px;
    margin: 20px 0;
    background: #fff;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
  }
  
  section h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    border-bottom: 2px solid #6b73ff;
    display: inline-block;
  }
  
  section ul li {
    margin: 10px 0;
    font-size: 1.1rem;
  }
  
  /* Contact Section */
  #contact a {
    color: #6b73ff;
    text-decoration: none;
  }
  
  #contact a:hover {
    text-decoration: underline;
  }
  
  /* Footer Styles */
  footer {
    text-align: center;
    padding: 20px 0;
    background: #6b73ff;
    color: #fff;
  }
  
  footer p {
    font-size: 1rem;
  }
  
  footer nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
  }
  
  footer nav ul li {
    margin: 0 10px;
  }
  
  footer nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  footer nav ul li a:hover {
    text-decoration: underline;
  }
  
  /* Responsive Design */
  @media (max-width: 768px) {
    header h1 {
      font-size: 2.5rem;
    }
  
    header p {
      font-size: 1rem;
    }
  
    section h2 {
      font-size: 1.5rem;
    }
  
    nav ul {
      flex-direction: column;
      position: absolute;
      top: 50px;
      right: 0;
      background: #fff;
      width: 100%;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      padding: 10px 0;
      display: none;
    }
  
    nav ul.active {
      display: flex;
    }
  
    nav ul li {
      margin: 10px 0;
      text-align: center;
    }
  
    .menu-toggle {
      display: flex;
    }
  
    section {
      padding: 20px 15px;
    }
  }
  
  @media (max-width: 480px) {
    header h1 {
      font-size: 2rem;
    }
  
    header p {
      font-size: 0.9rem;
    }
  
    section h2 {
      font-size: 1.3rem;
    }
  
    section ul li {
      font-size: 1rem;
    }
  
    footer p {
      font-size: 0.9rem;
    }
  }
  
