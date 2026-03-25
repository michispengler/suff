---
title: The suff Page
--


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Awesome Club</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@2/css/pico.min.css">
    <style>
      :root {
    /* Main brand color */
    --pico-primary: #3b82f6; 
    --pico-primary-hover: #2563eb;
    --pico-primary-underline: rgba(59, 130, 246, 0.5);
    
    /* Rounded corners for a modern look */
    --pico-border-radius: 0.75rem;
  }

  /* Custom class for a gradient background on the hero */
  header {
    background: linear-gradient(135deg, rgba(59,130,246,0.1) 0%, rgba(255,255,255,1) 100%);
    padding: 4rem 0;
    border-bottom: 1px solid var(--pico-muted-border-color);
  }
</style>
</head>
<body>

    <nav class="container">
        <ul><li><strong>The [Club Name]</strong></li></ul>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#events">Events</a></li>
            <li><a href="#join" role="button">Join Us</a></li>
        </ul>
    </nav>

    <header class="container">
        <hgroup>
            <h1>Join the community of [Club Interest]</h1>
            <p>We meet every Tuesday to build, learn, and grow together.</p>
        </hgroup>
        <button>Learn More</button>
    </header>

    <main class="container">
        <section id="about">
            <h2>About Our Club</h2>
            <div class="grid">
                <div>
                    <h3>Our Mission</h3>
                    <p>Briefly describe why the club exists and what members get out of it.</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/400x250" alt="Club Photo">
                </div>
            </div>
        </section>

        <hr>

        <section id="events">
            <h2>Upcoming Events</h2>
            <article>
                <header><strong>Monthly Meetup</strong> - April 15th</header>
                Discussion on [Topic] and pizza! 
                <footer>Location: [Building/Room Name]</footer>
            </article>
        </section>

        <section id="join">
            <article>
                <h2>Ready to Join?</h2>
                <p>Fill out your details and we'll send you our newsletter!</p>
                <form action="https://formspree.io/f/YOUR_ID_HERE" method="POST">
                    <input type="text" name="name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Email Address" required>
                    <button type="submit">Submit Membership Request</button>
                </form>
            </article>
        </section>
    </main>

    <footer class="container">
        <small>© 2026 [Club Name] • Follow us on Instagram</small>
    </footer>

</body>
</html>
