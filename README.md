<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>TR Visual Photography</title>
  <meta name="description" content="Portrait & lifestyle photographer based in Nebraska. Booking sessions for seniors, couples, and families." />
  <link rel="stylesheet" href="styles.css" />
</head>

<body>
  <header class="nav">
    <div class="container nav-inner">
      <a class="logo" href="#top">TR Visual Photography</a>
      <nav class="links">
        <a href="#work">Work</a>
        <a href="#pricing">Pricing</a>
        <a href="#about">About</a>
        <a href="#contact" class="btn small">Book</a>
      </nav>
    </div>
  </header>

  <main id="top">
    <section class="hero">
      <div class="container hero-inner">
        <div>
          <p class="tag">Nebraska • Portrait • Lifestyle</p>
          <h1>Photos that feel like you.</h1>
          <p class="sub">
            Senior, couples, and family sessions with a warm, natural look—edited with care and delivered fast.
          </p>
          <div class="cta">
            <a class="btn" href="#contact">Inquire + Book</a>
            <a class="btn ghost" href="#work">View Portfolio</a>
          </div>

          <ul class="bullets">
            <li>Outdoor + in-home sessions</li>
            <li>Digital gallery delivery</li>
            <li>Omaha / Elkhorn + surrounding areas</li>
          </ul>
        </div>

        <div class="hero-card">
          <div class="hero-image" role="img" aria-label="Featured photo placeholder"></div>
          <div class="hero-card-text">
            <p><strong>Now booking:</strong> Spring sessions</p>
            <p class="muted">Limited weekend spots available.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="work" class="section">
      <div class="container">
        <div class="section-head">
          <h2>Featured Work</h2>
          <p class="muted">Replace these placeholders with your images.</p>
        </div>

        <div class="grid">
          <div class="ph"></div><div class="ph"></div><div class="ph"></div>
          <div class="ph"></div><div class="ph"></div><div class="ph"></div>
        </div>

        <div class="center">
          <a class="btn ghost" href="#contact">Ask about a session</a>
        </div>
      </div>
    </section>

    <section id="pricing" class="section alt">
      <div class="container">
        <div class="section-head">
          <h2>Pricing</h2>
          <p class="muted">Simple, transparent packages. (Edit these to match your actual rates.)</p>
        </div>

        <div class="cards">
          <article class="card">
            <h3>Mini Session</h3>
            <p class="price">$150</p>
            <ul>
              <li>20 minutes</li>
              <li>15 edited photos</li>
              <li>1 location</li>
              <li>Online gallery</li>
            </ul>
          </article>

          <article class="card featured">
            <div class="badge">Most Popular</div>
            <h3>Standard Session</h3>
            <p class="price">$275</p>
            <ul>
              <li>60 minutes</li>
              <li>40+ edited photos</li>
              <li>Up to 2 outfits</li>
              <li>Online gallery</li>
            </ul>
          </article>

          <article class="card">
            <h3>Deluxe</h3>
            <p class="price">$400</p>
            <ul>
              <li>90 minutes</li>
              <li>70+ edited photos</li>
              <li>Up to 2 locations</li>
              <li>Priority turnaround</li>
            </ul>
          </article>
        </div>
      </div>
    </section>

    <section id="about" class="section">
      <div class="container about">
        <div class="about-photo" aria-hidden="true"></div>
        <div>
          <h2>Hi, I’m Katrina Roth.</h2>
          <p>
            I’m a Nebraska-based photographer specializing in portraits and lifestyle sessions. I’m all about
            making sessions feel easy, fun, and true to you—then delivering edits that look natural, clean,
            and timeless.
          </p>
          <p class="muted">
            Want a vibe check? Tell me your vision and I’ll help with locations, outfits, and timing.
          </p>
        </div>
      </div>
    </section>

    <section id="contact" class="section alt">
      <div class="container">
        <div class="section-head">
          <h2>Contact</h2>
          <p class="muted">Email or DM—either works. Add your real links below.</p>
        </div>

        <div class="contact">
          <div class="contact-card">
            <h3>Inquiries</h3>
            <p><strong>Email:</strong> <a href="mailto:trina228000@gmail.com">trina228000@gmail.com</a></p>
            <p><strong>Instagram:</strong> <a href="#" aria-label="Instagram link">yourhandle</a></p>
            <p><strong>Location:</strong> Elkhorn / Omaha, Nebraska</p>
          </div>

          <form class="contact-form" onsubmit="return false;">
            <label>
              Name
              <input type="text" placeholder="Your name" />
            </label>
            <label>
              Email
              <input type="email" placeholder="you@email.com" />
            </label>
            <label>
              What are you looking for?
              <textarea rows="4" placeholder="Session type, date, vibe, location ideas…"></textarea>
            </label>
            <button class="btn" type="button" onclick="alert('Connect this form to a service like Formspree to receive submissions.')">
              Send
            </button>
            <p class="tiny muted">Tip: connect this form to Formspree / Netlify Forms to receive messages.</p>
          </form>
        </div>
      </div>
    </section>

    <footer class="footer">
      <div class="container footer-inner">
        <p class="muted">© <span id="year"></span> TR Visual Photography</p>
        <div class="links">
          <a href="#top">Back to top</a>
        </div>
      </div>
    </footer>
  </main>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
