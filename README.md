<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mein Unternehmen</title>
  <link rel="stylesheet" href="style.css" />
  <script defer src="script.js"></script>
</head>
<body>
  <header>
    <div class="logo">MeinUnternehmen</div>
    <nav id="navbar">
      <ul>
        <li><a href="#hero">Start</a></li>
        <li><a href="#about">Über uns</a></li>
        <li><a href="#services">Leistungen</a></li>
        <li><a href="#team">Team</a></li>
        <li><a href="#gallery">Galerie</a></li>
        <li><a href="#contact">Kontakt</a></li>
      </ul>
      <div id="menu-toggle">☰</div>
    </nav>
  </header>

  <section id="hero">
    <h1>Willkommen bei <span>MeinUnternehmen</span></h1>
    <p>Wir schaffen Lösungen für Ihre Zukunft.</p>
    <a href="#contact" class="btn">Kontakt aufnehmen</a>
  </section>

  <section id="about">
    <h2>Über uns</h2>
    <p>Wir sind ein innovatives Unternehmen, das sich auf moderne Dienstleistungen und nachhaltige Lösungen spezialisiert hat.</p>
  </section>

  <section id="services">
    <h2>Unsere Leistungen</h2>
    <div class="service-grid">
      <div class="service-card">💼 <h3>Beratung</h3><p>Professionelle Unternehmensberatung.</p></div>
      <div class="service-card">⚙️ <h3>Technik</h3><p>Modernste Technologie und IT-Services.</p></div>
      <div class="service-card">🌍 <h3>Nachhaltigkeit</h3><p>Ökologisch verantwortungsbewusste Projekte.</p></div>
    </div>
  </section>

  <section id="team">
    <h2>Unser Team</h2>
    <div class="team-grid">
      <div class="team-member"><img src="https://via.placeholder.com/150" alt=""><h3>Anna Müller</h3><p>CEO</p></div>
      <div class="team-member"><img src="https://via.placeholder.com/150" alt=""><h3>Max Schmidt</h3><p>CTO</p></div>
      <div class="team-member"><img src="https://via.placeholder.com/150" alt=""><h3>Laura Becker</h3><p>Marketing</p></div>
    </div>
  </section>

  <section id="gallery">
    <h2>Galerie</h2>
    <div class="gallery-grid">
      <img src="https://via.placeholder.com/300x200" alt="">
      <img src="https://via.placeholder.com/300x200" alt="">
      <img src="https://via.placeholder.com/300x200" alt="">
    </div>
  </section>

  <section id="testimonials">
    <h2>Kundenstimmen</h2>
    <blockquote>„Tolles Team und hervorragender Service!“ – <strong>Sabine K.</strong></blockquote>
    <blockquote>„Schnell, professionell, zuverlässig.“ – <strong>Thomas R.</strong></blockquote>
  </section>

  <section id="contact">
    <h2>Kontakt</h2>
    <form id="contact-form">
      <input type="text" id="name" placeholder="Name" required>
      <input type="email" id="email" placeholder="E-Mail" required>
      <textarea id="message" placeholder="Nachricht" required></textarea>
      <button type="submit">Senden</button>
    </form>
    <p id="form-status"></p>
  </section>

  <footer>
    <p>© 2025 MeinUnternehmen – Alle Rechte vorbehalten</p>
    <div class="socials">
      <a href="#">🌐</a>
      <a href="#">💼</a>
      <a href="#">📸</a>
    </div>
  </footer>
</body>
</html>
