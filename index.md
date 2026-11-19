<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio | Cybersecurity & Powerlifting</title>
  <style>
    /* Basic Reset & Typography */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      line-height: 1.6;
      color: #e5e7eb;
      background-color: #0f172a;
    }

    a {
      color: #38bdf8;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Navigation */
    header {
      background: rgba(15, 23, 42, 0.95);
      border-bottom: 1px solid #1e293b;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    nav {
      max-width: 920px;
      margin: 0 auto;
      padding: 1rem 1.5rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-weight: 700;
      font-size: 1.2rem;
      color: #f8fafc;
      letter-spacing: 0.5px;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }

    .nav-links a {
      color: #94a3b8;
      font-weight: 500;
      font-size: 0.95rem;
    }

    .nav-links a:hover {
      color: #38bdf8;
      text-decoration: none;
    }

    /* Layout Containers */
    main {
      max-width: 920px;
      margin: 0 auto;
      padding: 0 1.5rem;
    }

    section {
      padding: 4rem 0;
      border-bottom: 1px solid #1e293b;
    }

    section:last-of-type {
      border-bottom: none;
    }

    h1 {
      font-size: 2.5rem;
      color: #f8fafc;
      margin-bottom: 0.75rem;
      line-height: 1.2;
    }

    h2 {
      font-size: 1.75rem;
      color: #f8fafc;
      margin-bottom: 1.25rem;
    }

    .badge {
      display: inline-block;
      background: #1e293b;
      color: #38bdf8;
      border: 1px solid #334155;
      padding: 0.25rem 0.75rem;
      border-radius: 999px;
      font-size: 0.85rem;
      font-weight: 600;
      margin-bottom: 1rem;
    }

    /* Hero Section */
    .hero {
      padding: 5.5rem 0;
    }

    .hero p {
      font-size: 1.15rem;
      color: #94a3b8;
      max-width: 640px;
      margin-bottom: 1.75rem;
    }

    .btn-group {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-block;
      background: #0284c7;
      color: #ffffff;
      padding: 0.75rem 1.5rem;
      border-radius: 6px;
      font-weight: 600;
    }

    .btn:hover {
      background: #0369a1;
      text-decoration: none;
    }

    .btn-outline {
      background: transparent;
      border: 1px solid #334155;
      color: #e2e8f0;
    }

    .btn-outline:hover {
      background: #1e293b;
      text-decoration: none;
    }

    /* Cards & Grids */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: #1e293b;
      border: 1px solid #334155;
      border-radius: 8px;
      padding: 1.5rem;
    }

    .card h3 {
      margin-bottom: 0.5rem;
      color: #f8fafc;
    }

    .card p {
      color: #94a3b8;
      font-size: 0.95rem;
      margin-bottom: 1rem;
    }

    /* Powerlifting Stats & Links */
    .stats-bar {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem;
      margin-bottom: 1.5rem;
    }

    .stat-box {
      background: #1e293b;
      border: 1px solid #334155;
      border-radius: 8px;
      padding: 1.25rem;
      text-align: center;
    }

    .stat-box .number {
      font-size: 1.75rem;
      font-weight: 700;
      color: #38bdf8;
    }

    .stat-box .label {
      font-size: 0.85rem;
      color: #94a3b8;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }

    .link-card {
      display: block;
      background: #1e293b;
      border: 1px solid #334155;
      border-radius: 8px;
      padding: 1.25rem 1.5rem;
      color: #f8fafc;
      transition: border-color 0.2s ease;
    }

    .link-card:hover {
      border-color: #38bdf8;
      text-decoration: none;
    }

    .link-card span {
      display: block;
      font-size: 0.9rem;
      color: #94a3b8;
      margin-top: 0.25rem;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 2rem 1.5rem;
      color: #64748b;
      font-size: 0.9rem;
      border-top: 1px solid #1e293b;
      background: #0f172a;
    }
  </style>
</head>
<body>

  <!-- Header & Navigation -->
  <header>
    <nav>
      <a href="#" class="logo">[Your Name]</a>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#cybersec">Cybersecurity</a></li>
        <li><a href="#powerlifting">Powerlifting</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <!-- Hero Section -->
    <section class="hero">
      <span class="badge">Ngee Ann Polytechnic &bull; Year 1</span>
      <h1>Hi, I'm [Your Name].<br>Cybersecurity Student &amp; Powerlifter.</h1>
      <p>Currently pursuing a Diploma in Cybersecurity &amp; Digital Forensics at Ngee Ann Polytechnic. Outside of labs and CTFs, I train in strength sports and recently hit a 500 kg SBD novice total.</p>
      <div class="btn-group">
        <a href="#cybersec" class="btn">Explore Cyber Work</a>
        <a href="#powerlifting" class="btn btn-outline">View Lifting Highlights</a>
      </div>
    </section>

    <!-- About Section -->
    <section id="about">
      <h2>About Me</h2>
      <p style="color: #cbd5e1; margin-bottom: 1rem;">
        I am a Year 1 student at <strong>Ngee Ann Polytechnic (School of InfoComm Technology)</strong> passionate about defensive security, network infrastructure, and digital forensics.
      </p>
      <p style="color: #cbd5e1;">
        Whether I am hardening a Linux server or preparing for a heavy deadlift attempt, I enjoy disciplined, incremental progress and solving hard problems under pressure.
      </p>
    </section>

    <!-- Cybersecurity Section -->
    <section id="cybersec">
      <h2>Cybersecurity &amp; Labs</h2>
      <div class="grid">
        <article class="card">
          <h3>Home Lab &amp; Networking</h3>
          <p>Building virtualized environments to practice packet analysis, firewall rules, and Linux system administration.</p>
          <a href="#">View Setup Notes &rarr;</a>
        </article>
        <article class="card">
          <h3>CTF Writeups</h3>
          <p>Documenting solutions for beginner-to-intermediate Capture The Flag challenges across web exploitation, OSINT, and cryptography.</p>
          <a href="#">Read Writeups &rarr;</a>
        </article>
        <article class="card">
          <h3>Python Security Scripts</h3>
          <p>Writing lightweight automation scripts for log parsing, port scanning, and basic network diagnostics during Year 1 coursework.</p>
          <a href="#">GitHub Repo &rarr;</a>
        </article>
      </div>
    </section>

    <!-- Powerlifting Section -->
    <section id="powerlifting">
      <h2>Powerlifting &bull; 500 kg SBD Novice</h2>
      <p style="color: #94a3b8; margin-bottom: 1.5rem;">
        Highlights from my novice competition milestone, hitting a 500 kg total across Squat, Bench Press, and Deadlift.
      </p>

      <!-- Stats Breakdown -->
      <div class="stats-bar">
        <div class="stat-box">
          <div class="number">[XXX] kg</div>
          <div class="label">Squat</div>
        </div>
        <div class="stat-box">
          <div class="number">[XXX] kg</div>
          <div class="label">Bench Press</div>
        </div>
        <div class="stat-box">
          <div class="number">[XXX] kg</div>
          <div class="label">Deadlift</div>
        </div>
        <div class="stat-box">
          <div class="number">500 kg</div>
          <div class="label">SBD Novice Total</div>
        </div>
      </div>

      <!-- Direct href Links to Your Instagram Post -->
      <div class="grid">
        <a href="https://instagram.com" target="_blank" rel="noopener noreferrer" class="link-card">
          <strong>Slide 1 &bull; Squat Highlight &nearr;</strong>
          <span>View competition clip and photos on Instagram</span>
        </a>
        <a href="https://instagram.com" target="_blank" rel="noopener noreferrer" class="link-card">
          <strong>Slide 2 &bull; Bench Press Highlight &nearr;</strong>
          <span>View competition clip and photos on Instagram</span>
        </a>
        <a href="https://instagram.com" target="_blank" rel="noopener noreferrer" class="link-card">
          <strong>Slide 3 &bull; Deadlift &amp; 500 Total &nearr;</strong>
          <span>View competition clip and photos on Instagram</span>
        </a>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Get In Touch</h2>
      <p style="color: #94a3b8;">Open to connecting with fellow NP students, cybersecurity enthusiasts, and lifters.</p>
      <p style="margin-top: 1rem; color: #cbd5e1;">
        <strong>Email:</strong> <a href="mailto:your.email@example.com">your.email@example.com</a><br>
        <strong>Socials:</strong> 
        <a href="https://instagram.com" target="_blank" rel="noopener noreferrer">Instagram</a> &bull; 
        <a href="#">GitHub</a> &bull; 
        <a href="#">LinkedIn</a>
      </p>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 [Your Name] &bull; Ngee Ann Polytechnic</p>
  </footer>

</body>
</html>
