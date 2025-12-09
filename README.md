<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Global Gadgets — Gold & Silver</title>
  <meta name="description" content="Global Gadgets — premium gold & silver themed gadgets. Contact us to learn more." />
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="header" role="banner">
    <div class="header-inner container">
      <div class="brand">Global Gadgets</div>
      <nav class="nav" role="navigation" aria-label="Main navigation">
        <a href="#hero">Home</a>
        <a href="#services">Products</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main>
    <section id="hero" class="hero section" aria-labelledby="hero-title">
      <div class="container">
        <h1 id="hero-title">Global Gadgets — Gold & Silver</h1>
        <p>Premium gadgets with an elegant gold & silver theme. Explore our products and reach out using the contact form.</p>
        <div class="cta-buttons">
          <a class="btn btn-primary" href="#contact">Contact Us</a>
          <a class="btn btn-secondary" href="#services">View Products</a>
        </div>
      </div>
    </section>

    <section id="services" class="section container" aria-labelledby="services-title">
      <h2 id="services-title" class="small">Featured</h2>
      <div class="grid services-grid" role="list">
        <article class="card" role="listitem">
          <h3>Gold Edition Headphones</h3>
          <p>Top-tier sound and luxury finish. Limited stock available.</p>
        </article>
        <article class="card" role="listitem">
          <h3>SilverSmart Watch</h3>
          <p>Elegant design, health tracking, and long battery life.</p>
        </article>
        <article class="card" role="listitem">
          <h3>Premium Charging Dock</h3>
          <p>Fast charging with a refined metallic look for any desk.</p>
        </article>
      </div>
    </section>

    <section id="contact" class="section container" aria-labelledby="contact-title">
      <h2 id="contact-title">Contact Us</h2>

      <form id="contact-form" class="form" novalidate>
        <div role="status" aria-live="polite" id="form-status" class="small" style="min-height:1.2em;"></div>

        <label for="name">Name</label>
        <input id="name" name="name" class="input" type="text" required placeholder="Your full name" />

        <label for="email">Email</label>
        <input id="email" name="email" class="input" type="email" required placeholder="you@example.com" />

        <label for="message">Message</label>
        <textarea id="message" name="message" class="input" required rows="6" placeholder="How can we help?"></textarea>

        <div style="display:flex;gap:10px;align-items:center;">
          <button id="submit-btn" class="btn btn-primary" type="submit">Send Message</button>
          <button id="clear-btn" class="btn btn-secondary" type="button">Clear</button>
          <span id="last-saved" class="small" aria-hidden="true" style="margin-left:auto;opacity:.85"></span>
        </div>
      </form>
    </section>
  </main>

  <footer class="footer" role="contentinfo">
    <div class="inner container">
      <div class="kv"><strong>Global Gadgets</strong> &copy; <span id="year"></span></div>
      <div class="small">Made with care • Accessible • Deployable</div>
    </div>
  </footer>

  <script>
    // small script to set current year
    document.addEventListener('DOMContentLoaded', function(){ var y=document.getElementById('year'); if(y) y.textContent = new Date().getFullYear(); });
  </script>
  <script src="scripts.js" defer></script>
</body>
</html>
