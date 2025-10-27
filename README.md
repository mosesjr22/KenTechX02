<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title style="color:red;">St.Kennedy Secondary School - Home</title>
  <style>
    :root{--accent:#0b6efd;--muted:#6b7280;--bg:#f8fafc}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; background:var(--bg); color:#0f172a}
    header{background:#fff; border-bottom:1px solid #e6e9ee}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    .nav{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .brand .logo{width:48px;height:48px;border-radius:8px;background:linear-gradient(135deg,var(--accent),#06b6d4);display:flex;align-items:center;justify-content:center;color:white;font-weight:700}
    nav ul{list-style:none;margin:0;padding:0;display:flex;gap:12px}
    nav a{display:inline-block;padding:8px 12px;border-radius:8px;text-decoration:none;color:var(--muted);font-weight:600}
    nav a:hover{background:#eef2ff;color:var(--accent)}
    .cta{padding:8px 12px;background:var(--accent);color:#fff;border-radius:8px;text-decoration:none}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr;gap:18px;padding:56px 0}
    .hero-content h1{font-size:32px;margin:0 0 8px}
    .hero-content p{margin:0;color:var(--muted)}
    .features{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:20px}
    .card{background:#fff;padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(12,16,24,0.06)}

    /* Footer */
    footer{margin-top:36px;background:#fff;border-top:1px solid #e6e9ee;padding:24px}
    .footer-grid{display:grid;grid-template-columns:1fr 1fr;gap:16px;max-width:1100px;margin:0 auto}
    .footer-links ul{list-style:none;padding:0;margin:0}
    .footer-links li{margin-bottom:8px}
    .footer-links a{text-decoration:none;color:var(--muted)}

    /* Responsive */
    @media(min-width:780px){
      .hero{grid-template-columns:1fr 420px}
      .hero-content h1{font-size:40px}
    }
    .big-image {
  width: 100%;      /* Makes it stretch across the page */
  height: auto;     /* Keeps aspect ratio */
  max-height: 100vh; /* (optional) ensures it doesn’t go beyond screen height */
  object-fit: cover; /* Ensures it covers nicely without distortion */
}

  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo">SKS</div>
        <div>
          <div style="font-weight:700;color: rgb(21, 0, 255);" >St Kennedy Mutomo Secondary School</div>
          <div style="font-size:12px;color:var(--muted);color: #0bfd27;">Toil. Tenacity. Faith.</div>
        </div>
      </div>

      <nav aria-label="Main navigation">
        <ul>
          <li><a href="kennedysecondary.html" style="color: red;">Home</a></li>
          <li><a href="about us.html" style="color: red;">About Us</a></li>
          <li><a href="academics.html" style="color: red;">Academics</a></li>
          <li><a href="admissions.html" style="color: red;">Admissions</a></li>
           <li><a href="applynow.html" style="color: red;">Apply now</a></li>
          <li><a href="gallery.html" style="color: red;">Gallery</a></li>
          <li><a href="contact.html" style="color: red;">Contact</a></li>
        </ul>
      </nav>

      <a class="cta" href="admissions.html">Apply</a>
    </div>
  </header>
   <img src="C:\Users\ADMIN\Downloads\red-buildings-households.jpg" alt="Big Image" class="big-image">

  <main class="container">
    <section class="hero">
      <div class="hero-content">
        <h1>Welcome to  St.Kennedy Secondary School</h1>
        <p>Building bright futures through a balanced curriculum, devoted staff, and a caring community.</p>

        <div class="features">
          <div class="card">
            <h3 style="margin-top:0;margin-bottom:6px;color:green;">Academic Programs</h3>
            <p style="margin:0;color:var(--muted)">A broad curriculum that prepares students for higher education and life.</p>
          </div>
          <div class="card">
            <h3 style="margin-top:0;margin-bottom:6px;color: green;">Student Life</h3>
            <p style="margin:0;color:var(--muted)">Clubs, sports and arts that develop leadership and teamwork.</p>
          </div>
          <div class="card">
            <h3 style="margin-top:0;margin-bottom:6px;color: green;">Support Services</h3>
            <p style="margin:0;color:var(--muted)">Counseling, tutoring and career guidance for every learner.</p>
          </div>
        </div>
      </div>

      <aside>
        <div class="card">
          <h3 style="margin-top:0;color: green;">News & Notices</h3>
          <ul style="margin:0;padding-left:18px;color:var(--muted)">
            <li>Term dates announced — check the Admissions page.</li>
            <li>Open day: Date to be published.</li>
            <li>Scholarships application coming soon.</li>
          </ul>
        </div>

        <div style="height:18px"></div>

        <div class="card">
          <h4 style="margin:0 0 15spx;color: green;" >Quick Links</h4>
          <nav class="footer-links">
            <ul>
              <li><a href="index.html"  style="color: blue;">Home</a></li>
              <li>c
              <li><a href="applynow.html" style="color: blue;">Apply now</a></li>
              <li><a href="contact.html" style="color: blue;">Contact</a></li>
            </ul>
          </nav>
        </div>
      </aside>
    </section>

    <!-- You asked that linked pages contain no content. The files linked above (about.html, academics.html, admissions.html,
         gallery.html and contact.html) should be created as separate files. Put your own content into those files. 
         Example: create an "about.html" with a top comment like: <!-- About Us content goes here --> -->
  </main>
  

  <footer>
    <div class="footer-grid">
      <div>
        <strong>St Kennedy Secondary School</strong>
        <p style="margin:6px 0 0;color:var(--muted)">P.O. Box 1234 — Nairobi, Kenya • Phone: +254 700 000000</p>
      </div>

      <div>
        <div style="font-weight:700;margin-bottom:8px">Quick Links</div>
        <div class="footer-links">
          <ul>
            <li><a href="about us.html" style="color: crimson;">About Us</a></li>
            <li><a href="academics.html" style="color: crimson;">Academics</a></li>
            <li><a href="admissions.html" style="color: crimson;">Admissions</a></li>
            <li><a href="applynow.html" style="color: crimson;">Apply now</a></li>
            <li><a href="gallery.html" style="color: crimson;">Gallery</a></li>
            <li><a href="contact.html" style="color: crimson;">Contact</a></li>

          </ul>
        </div>
      </div>
    </div>
  </footer>
</body>
</html>

