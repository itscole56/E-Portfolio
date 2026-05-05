<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Cole Seramur — Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet"/>
<style>
  :root {
    --cream: #f5f0e8;
    --ink: #1a1714;
    --gold: #b8975a;
    --gold-light: #d4b07a;
    --muted: #7a6f63;
    --rule: #d8cfc4;
    --bg: #faf7f2;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--ink);
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 18px;
    line-height: 1.7;
    overflow-x: hidden;
  }

  /* ── NOISE TEXTURE OVERLAY ── */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 0;
    opacity: 0.5;
  }

  /* ── NAV ── */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1.2rem 4rem;
    background: rgba(250,247,242,0.88);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--rule);
  }

  .nav-logo {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-weight: 300;
    font-size: 1rem;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--gold);
  }

  .nav-links {
    display: flex;
    gap: 2.5rem;
    list-style: none;
  }

  .nav-links a {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.7rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    text-decoration: none;
    transition: color 0.2s;
  }

  .nav-links a:hover { color: var(--gold); }

  /* ── HERO ── */
  #hero {
    min-height: 100vh;
    display: grid;
    grid-template-columns: 1fr 1fr;
    position: relative;
  }

  .hero-left {
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 8rem 4rem 4rem 5rem;
    position: relative;
  }

  .hero-left::after {
    content: '';
    position: absolute;
    right: 0; top: 15%; bottom: 15%;
    width: 1px;
    background: linear-gradient(to bottom, transparent, var(--gold), transparent);
  }

  .hero-eyebrow {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.68rem;
    letter-spacing: 0.3em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 1.5rem;
    opacity: 0;
    animation: fadeUp 0.8s 0.2s forwards;
  }

  .hero-name {
    font-size: clamp(3.5rem, 6vw, 5.5rem);
    font-weight: 300;
    line-height: 1.05;
    letter-spacing: -0.01em;
    opacity: 0;
    animation: fadeUp 0.8s 0.4s forwards;
  }

  .hero-name em {
    font-style: italic;
    color: var(--gold);
    display: block;
  }

  .hero-bio {
    margin-top: 2rem;
    font-size: 1.1rem;
    font-weight: 300;
    color: var(--muted);
    max-width: 38ch;
    line-height: 1.8;
    opacity: 0;
    animation: fadeUp 0.8s 0.6s forwards;
  }

  .hero-cta {
    margin-top: 3rem;
    display: flex;
    gap: 1.2rem;
    opacity: 0;
    animation: fadeUp 0.8s 0.8s forwards;
  }

  .btn-primary {
    padding: 0.75rem 2rem;
    background: var(--gold);
    color: var(--bg);
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.7rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    text-decoration: none;
    border: 1px solid var(--gold);
    transition: all 0.25s;
  }

  .btn-primary:hover {
    background: transparent;
    color: var(--gold);
  }

  .btn-outline {
    padding: 0.75rem 2rem;
    background: transparent;
    color: var(--muted);
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.7rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    text-decoration: none;
    border: 1px solid var(--rule);
    transition: all 0.25s;
  }

  .btn-outline:hover {
    border-color: var(--gold);
    color: var(--gold);
  }

  .hero-right {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 8rem 4rem 4rem;
    position: relative;
    overflow: hidden;
  }

  .hero-monogram {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: clamp(10rem, 20vw, 18rem);
    font-weight: 300;
    font-style: italic;
    color: transparent;
    -webkit-text-stroke: 1px var(--rule);
    line-height: 1;
    position: absolute;
    opacity: 0;
    animation: fadeIn 1.2s 1s forwards;
    user-select: none;
  }

  .hero-stats {
    position: relative;
    z-index: 2;
    display: flex;
    flex-direction: column;
    gap: 2rem;
    opacity: 0;
    animation: fadeUp 0.8s 1s forwards;
  }

  .stat-item {
    text-align: center;
    padding: 1.5rem 2.5rem;
    border: 1px solid var(--rule);
    background: rgba(250,247,242,0.6);
    backdrop-filter: blur(4px);
  }

  .stat-number {
    font-size: 2.8rem;
    font-weight: 300;
    color: var(--gold);
    line-height: 1;
    display: block;
  }

  .stat-label {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.65rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--muted);
    margin-top: 0.4rem;
    display: block;
  }

  /* ── SECTION SHARED ── */
  section {
    padding: 7rem 5rem;
    position: relative;
    z-index: 1;
  }

  .section-header {
    display: flex;
    align-items: center;
    gap: 1.5rem;
    margin-bottom: 4rem;
  }

  .section-number {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.65rem;
    color: var(--gold);
    letter-spacing: 0.2em;
  }

  .section-title {
    font-size: clamp(2rem, 3.5vw, 2.8rem);
    font-weight: 300;
    letter-spacing: -0.01em;
  }

  .section-title em { font-style: italic; color: var(--gold); }

  .section-rule {
    flex: 1;
    height: 1px;
    background: linear-gradient(to right, var(--rule), transparent);
  }

  /* ── ABOUT ── */
  #about {
    background: var(--cream);
    border-top: 1px solid var(--rule);
    border-bottom: 1px solid var(--rule);
  }

  .about-grid {
    display: grid;
    grid-template-columns: 1.2fr 1fr;
    gap: 5rem;
    align-items: start;
  }

  .about-text p {
    font-size: 1.15rem;
    font-weight: 300;
    color: var(--muted);
    line-height: 1.9;
    margin-bottom: 1.2rem;
  }

  .about-text p strong {
    color: var(--ink);
    font-weight: 400;
  }

  .about-sidebar {
    display: flex;
    flex-direction: column;
    gap: 2rem;
  }

  .sidebar-block {
    padding: 1.5rem;
    border-left: 2px solid var(--gold);
  }

  .sidebar-block-label {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.65rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 0.8rem;
    display: block;
  }

  .sidebar-block p {
    font-size: 0.95rem;
    color: var(--muted);
    line-height: 1.7;
  }

  /* ── EXPERIENCE ── */
  #experience { background: var(--bg); }

  .exp-list { display: flex; flex-direction: column; gap: 0; }

  .exp-item {
    display: grid;
    grid-template-columns: 200px 1fr;
    gap: 3rem;
    padding: 3rem 0;
    border-bottom: 1px solid var(--rule);
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s, transform 0.6s;
  }

  .exp-item.visible { opacity: 1; transform: translateY(0); }

  .exp-meta { padding-top: 0.2rem; }

  .exp-period {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.68rem;
    letter-spacing: 0.15em;
    color: var(--gold);
    display: block;
    margin-bottom: 0.5rem;
  }

  .exp-company {
    font-size: 0.85rem;
    color: var(--muted);
    font-weight: 300;
  }

  .exp-location {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.6rem;
    color: var(--rule);
    letter-spacing: 0.1em;
    margin-top: 0.3rem;
    display: block;
  }

  .exp-content {}

  .exp-role {
    font-size: 1.5rem;
    font-weight: 300;
    margin-bottom: 1rem;
    letter-spacing: -0.01em;
  }

  .exp-bullets {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
  }

  .exp-bullets li {
    font-size: 0.95rem;
    color: var(--muted);
    padding-left: 1.2rem;
    position: relative;
    line-height: 1.7;
  }

  .exp-bullets li::before {
    content: '—';
    position: absolute;
    left: 0;
    color: var(--gold);
    font-size: 0.7rem;
    top: 0.3rem;
  }

  /* ── EDUCATION ── */
  #education { background: var(--cream); border-top: 1px solid var(--rule); }

  .edu-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2rem;
  }

  .edu-card {
    padding: 2.5rem;
    border: 1px solid var(--rule);
    background: var(--bg);
    position: relative;
    overflow: hidden;
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s, transform 0.6s;
  }

  .edu-card.visible { opacity: 1; transform: translateY(0); }

  .edu-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(to right, var(--gold), var(--gold-light), transparent);
  }

  .edu-degree {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.65rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 0.8rem;
    display: block;
  }

  .edu-school {
    font-size: 1.4rem;
    font-weight: 300;
    margin-bottom: 0.3rem;
  }

  .edu-detail {
    font-size: 0.88rem;
    color: var(--muted);
    line-height: 1.7;
    margin-top: 0.8rem;
  }

  .edu-period {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.62rem;
    color: var(--muted);
    letter-spacing: 0.15em;
    margin-top: 1rem;
    display: block;
  }

  /* ── SKILLS ── */
  #skills { background: var(--bg); }

  .skills-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
  }

  .skill-group {
    padding: 2rem;
    border: 1px solid var(--rule);
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s, transform 0.6s;
  }

  .skill-group.visible { opacity: 1; transform: translateY(0); }

  .skill-group-title {
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.65rem;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 1.2rem;
    display: block;
  }

  .skill-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }

  .skill-tag {
    font-size: 0.85rem;
    color: var(--muted);
    border: 1px solid var(--rule);
    padding: 0.3rem 0.8rem;
    font-weight: 300;
    transition: all 0.2s;
  }

  .skill-tag:hover {
    border-color: var(--gold);
    color: var(--gold);
  }

  /* ── HONORS ── */
  #honors {
    background: var(--ink);
    color: var(--cream);
  }

  #honors .section-title { color: var(--cream); }
  #honors .section-rule { background: linear-gradient(to right, rgba(184,151,90,0.4), transparent); }

  .honors-list {
    display: flex;
    flex-direction: column;
    gap: 0;
  }

  .honor-item {
    display: flex;
    align-items: center;
    gap: 2rem;
    padding: 1.8rem 0;
    border-bottom: 1px solid rgba(255,255,255,0.07);
    opacity: 0;
    transform: translateX(-20px);
    transition: opacity 0.6s, transform 0.6s;
  }

  .honor-item.visible { opacity: 1; transform: translateX(0); }

  .honor-icon {
    width: 36px; height: 36px;
    border: 1px solid var(--gold);
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
    color: var(--gold);
    font-size: 0.8rem;
  }

  .honor-text {
    font-size: 1.1rem;
    font-weight: 300;
    color: var(--cream);
  }

  /* ── CONTACT ── */
  #contact {
    background: var(--cream);
    border-top: 1px solid var(--rule);
    text-align: center;
  }

  .contact-inner {
    max-width: 600px;
    margin: 0 auto;
  }

  .contact-headline {
    font-size: clamp(2.5rem, 4vw, 3.5rem);
    font-weight: 300;
    line-height: 1.2;
    margin-bottom: 1.5rem;
  }

  .contact-headline em { font-style: italic; color: var(--gold); }

  .contact-sub {
    font-size: 1rem;
    color: var(--muted);
    margin-bottom: 3rem;
    font-weight: 300;
  }

  .contact-links {
    display: flex;
    justify-content: center;
    gap: 1.5rem;
    flex-wrap: wrap;
  }

  .contact-link {
    display: flex;
    align-items: center;
    gap: 0.6rem;
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.72rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    text-decoration: none;
    padding: 0.9rem 1.8rem;
    border: 1px solid var(--rule);
    transition: all 0.25s;
  }

  .contact-link:hover {
    border-color: var(--gold);
    color: var(--gold);
  }

  /* ── FOOTER ── */
  footer {
    background: var(--ink);
    color: rgba(255,255,255,0.3);
    text-align: center;
    padding: 2rem;
    font-family: 'Cormorant Garamond', Georgia, serif;
    font-size: 0.65rem;
    letter-spacing: 0.15em;
    position: relative;
    z-index: 1;
  }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  @keyframes fadeIn {
    from { opacity: 0; }
    to   { opacity: 1; }
  }

  /* ── RESPONSIVE ── */
  @media (max-width: 900px) {
    nav { padding: 1rem 2rem; }
    .nav-links { gap: 1.5rem; }
    #hero { grid-template-columns: 1fr; min-height: auto; }
    .hero-left { padding: 7rem 2rem 2rem; }
    .hero-left::after { display: none; }
    .hero-right { display: none; }
    section { padding: 5rem 2rem; }
    .about-grid { grid-template-columns: 1fr; gap: 2.5rem; }
    .exp-item { grid-template-columns: 1fr; gap: 0.5rem; }
    .edu-grid { grid-template-columns: 1fr; }
    .skills-grid { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <span class="nav-logo">C. Seramur</span>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#education">Education</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-left">
    <span class="hero-eyebrow">Business &amp; Management</span>
    <h1 class="hero-name">
      Cole<br>
      <em>Seramur</em>
    </h1>
    <p class="hero-bio">
      Purdue University student, entrepreneur, and emerging business leader with a track record of creating real value — from restoring properties to organizing events for a 95-member professional fraternity chapter.
    </p>
    <div class="hero-cta">
      <a href="#experience" class="btn-primary">View Experience</a>
      <a href="#contact" class="btn-outline">Get in Touch</a>
    </div>
  </div>

  <div class="hero-right">
    <div class="hero-monogram">CS</div>
    <div class="hero-stats">
      <div class="stat-item">
        <span class="stat-number">$80K+</span>
        <span class="stat-label">Property Profit Generated</span>
      </div>
      <div class="stat-item">
        <span class="stat-number">95</span>
        <span class="stat-label">Chapter Members Led</span>
      </div>
      <div class="stat-item">
        <span class="stat-number">3+</span>
        <span class="stat-label">Years of Management Experience</span>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="section-header">
    <span class="section-number">01</span>
    <h2 class="section-title">About <em>Me</em></h2>
    <div class="section-rule"></div>
  </div>
  <div class="about-grid">
    <div class="about-text">
      <p>
        I'm a <strong>General Management student at Purdue University's Daniels School of Business</strong>, driven by a hands-on approach to business that started long before college. Through family real estate, I learned to manage projects, people, and budgets under real stakes — generating over $80,000 in property profit by the time I enrolled at Purdue.
      </p>
      <p>
        I'm drawn to the intersection of leadership, operations, and ethical decision-making. Whether I'm planning a formal event for a 95-member professional fraternity, collaborating with Purdue faculty on the Working Wellness Committee, or studying business law in <strong>Prague</strong>, I bring the same energy: organized, adaptable, and always outcome-focused.
      </p>
      <p>
        Outside the classroom and boardroom, you'll find me on the tennis or pickleball court, tending to my plants, baking sourdough, or finding new music.
      </p>
    </div>
    <div class="about-sidebar">
      <div class="sidebar-block">
        <span class="sidebar-block-label">Currently</span>
        <p>BS General Management, Purdue University — Class of 2028</p>
      </div>
      <div class="sidebar-block">
        <span class="sidebar-block-label">Based In</span>
        <p>West Lafayette, IN (Valparaiso, IN)</p>
      </div>
      <div class="sidebar-block">
        <span class="sidebar-block-label">Honors</span>
        <p>Dean's List 2024–2025 · Handel Scholarship Recipient</p>
      </div>
      <div class="sidebar-block">
        <span class="sidebar-block-label">Interests</span>
        <p>Tennis · Pickleball · Sourdough · Music · Botany · Fish</p>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <div class="section-header">
    <span class="section-number">02</span>
    <h2 class="section-title">Professional <em>Experience</em></h2>
    <div class="section-rule"></div>
  </div>
  <div class="exp-list">

    <div class="exp-item">
      <div class="exp-meta">
        <span class="exp-period">Mar 2025 – Present</span>
        <div class="exp-company">Delta Sigma Pi</div>
        <span class="exp-location">West Lafayette, IN</span>
      </div>
      <div class="exp-content">
        <div class="exp-role">Vice President of Fraternal Affairs</div>
        <ul class="exp-bullets">
          <li>Manages fraternal events that promote brotherhood and inclusivity within a 95-member chapter</li>
          <li>Planned the chapter's annual Formal Rose Dance, overseeing a full $4,000 event budget</li>
          <li>Provides an open communication channel to advocate for the interests and wellbeing of chapter members</li>
        </ul>
      </div>
    </div>

    <div class="exp-item">
      <div class="exp-meta">
        <span class="exp-period">May 2022 – 2025</span>
        <div class="exp-company">Seramur Properties</div>
        <span class="exp-location">Valparaiso, IN</span>
      </div>
      <div class="exp-content">
        <div class="exp-role">Project & Property Manager</div>
        <ul class="exp-bullets">
          <li>Renovated and restored multiple properties, generating over $80,000 in total profit</li>
          <li>Managed professional contractors, ensuring projects met residential codes and deadlines</li>
          <li>Directed a team of four employees — tracking hours, demonstrating tasks, and documenting progress</li>
          <li>Made construction and renovation decisions balancing time, resources, and budget constraints</li>
          <li>Provided administrative support including phone communications, errands, and listing publications</li>
        </ul>
      </div>
    </div>

    <div class="exp-item">
      <div class="exp-meta">
        <span class="exp-period">Aug 2025 – Present</span>
        <div class="exp-company">Daniels School of Business</div>
        <span class="exp-location">West Lafayette, IN</span>
      </div>
      <div class="exp-content">
        <div class="exp-role">Founding Member — Working Wellness Committee</div>
        <ul class="exp-bullets">
          <li>Collaborates with Purdue staff to coordinate engaging events for Daniels School of Business students</li>
          <li>Contributes ethical and professional insights to the school's official content and initiatives</li>
        </ul>
      </div>
    </div>

  </div>
</section>

<!-- EDUCATION -->
<section id="education">
  <div class="section-header">
    <span class="section-number">03</span>
    <h2 class="section-title"><em>Education</em></h2>
    <div class="section-rule"></div>
  </div>
  <div class="edu-grid">

    <div class="edu-card">
      <span class="edu-degree">B.S. General Management</span>
      <div class="edu-school">Purdue University</div>
      <div style="font-size:0.85rem;color:var(--muted);margin-top:0.2rem;">Daniels School of Business</div>
      <p class="edu-detail">Relevant coursework in Data &amp; AI Tools for Business, Foundations of Accounting, Business Ethics, and Business Law. Active member of Delta Sigma Pi professional fraternity and the Working Wellness Committee.</p>
      <span class="edu-period">Aug 2024 – May 2028 · West Lafayette, IN</span>
    </div>

    <div class="edu-card">
      <span class="edu-degree">Study Abroad</span>
      <div class="edu-school">Prague, Czech Republic</div>
      <div style="font-size:0.85rem;color:var(--muted);margin-top:0.2rem;">Purdue University Program</div>
      <p class="edu-detail">Completed a 4-week immersive program in Business Law &amp; Ethics, exploring Central European markets, post-communist economies, and international business practices through site visits and cultural engagement.</p>
      <span class="edu-period">Summer 2025 · Prague, Czech Republic</span>
    </div>

  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="section-header">
    <span class="section-number">04</span>
    <h2 class="section-title">Skills &amp; <em>Capabilities</em></h2>
    <div class="section-rule"></div>
  </div>
  <div class="skills-grid">

    <div class="skill-group">
      <span class="skill-group-title">Soft Skills</span>
      <div class="skill-tags">
        <span class="skill-tag">Communication</span>
        <span class="skill-tag">Organization</span>
        <span class="skill-tag">Teamwork</span>
        <span class="skill-tag">Adaptability</span>
        <span class="skill-tag">Confidence</span>
        <span class="skill-tag">Leadership</span>
      </div>
    </div>

    <div class="skill-group">
      <span class="skill-group-title">Technical & Hard Skills</span>
      <div class="skill-tags">
        <span class="skill-tag">Property Management</span>
        <span class="skill-tag">Excel</span>
        <span class="skill-tag">Public Speaking</span>
        <span class="skill-tag">Budget Management</span>
        <span class="skill-tag">Contractor Management</span>
      </div>
    </div>

    <div class="skill-group">
      <span class="skill-group-title">Trades & Operations</span>
      <div class="skill-tags">
        <span class="skill-tag">Electrical</span>
        <span class="skill-tag">Plumbing</span>
        <span class="skill-tag">Painting</span>
        <span class="skill-tag">Construction</span>
        <span class="skill-tag">Renovation</span>
      </div>
    </div>

  </div>
</section>

<!-- HONORS -->
<section id="honors">
  <div class="section-header">
    <span class="section-number">05</span>
    <h2 class="section-title"><em>Honors</em> &amp; Recognition</h2>
    <div class="section-rule"></div>
  </div>
  <div class="honors-list">
    <div class="honor-item">
      <div class="honor-icon">★</div>
      <span class="honor-text">Dean's List — Purdue University, 2024–2025</span>
    </div>
    <div class="honor-item">
      <div class="honor-icon">◆</div>
      <span class="honor-text">Handel Scholarship Recipient</span>
    </div>
    <div class="honor-item">
      <div class="honor-icon">◎</div>
      <span class="honor-text">Varsity Tennis — Valparaiso High School</span>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="contact-inner">
    <h2 class="contact-headline">Let's <em>connect.</em></h2>
    <p class="contact-sub">Whether it's an opportunity, a conversation, or a collaboration — I'd love to hear from you.</p>
    <div class="contact-links">
      <a href="mailto:cseramur@purdue.edu" class="contact-link">
        ✉ cseramur@purdue.edu
      </a>
      <a href="https://linkedin.com/in/cole-seramur" target="_blank" class="contact-link">
        ↗ LinkedIn
      </a>
      <a href="tel:2195085349" class="contact-link">
        ☏ (219) 508-5349
      </a>
    </div>
  </div>
</section>

<footer>
  © 2025 Cole William Seramur · Built with intention
</footer>

<script>
  // Scroll-triggered animations
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry, i) => {
      if (entry.isIntersecting) {
        setTimeout(() => {
          entry.target.classList.add('visible');
        }, entry.target.dataset.delay || 0);
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('.exp-item, .edu-card, .skill-group, .honor-item').forEach((el, i) => {
    el.dataset.delay = (i % 4) * 100;
    observer.observe(el);
  });
</script>
</body>
</html>
