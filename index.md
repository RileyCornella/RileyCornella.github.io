
---
layout: page
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=EB+Garamond:wght@400;500;600;700&display=swap');

  /* Overall website styling */
  body, p, h1, h2, h3, div, a, li {
    color: #302d26 !important;
    font-family: 'EB Garamond', Garamond, Georgia, serif !important;
    font-size: 20px !important;
    line-height: 1.6 !important;
  }

  body {
    background-color: #f7f5ef !important;
  }

  h1 {
    font-size: 2.6rem !important;
  }

  h2 {
    font-size: 2rem !important;
    margin-top: 35px !important;
    color: #59634c !important;
  }

  /* Navigation tabs */
  .top-nav {
    display: flex;
    justify-content: flex-end;
    gap: 30px;
    padding: 12px 25px;
    background-color: #e8e6dc;
    margin-top: -30px;
  }

  .top-nav a {
    text-decoration: none;
    color: #59634c !important;
    font-size: 21px !important;
    font-weight: 600;
  }

  .top-nav a:hover {
    color: #9a7957 !important;
  }

  /* Hero image and name */
  .hero {
    width: 100vw;
    height: 380px;
    position: relative;
    left: 50%;
    margin-left: -50vw;
    overflow: hidden;
    margin-top: 0;
  }

  .hero img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center 75%;
  }

  .hero-name {
    position: absolute;
    bottom: 35px;
    left: 8%;
    color: white !important;
    font-size: 4rem !important;
    font-weight: 600;
    text-shadow: 2px 2px 8px rgba(0,0,0,0.6);
  }

  /* Profile section */
  .profile {
    display: flex;
    gap: 30px;
    align-items: center;
    margin-top: 40px;
    margin-bottom: 30px;
  }

  .profile img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    border-radius: 6px;
    flex-shrink: 0;
  }

  /* Footer/contact section */
  .contact-footer {
    background-color: #e8e6dc;
    margin-top: 60px;
    padding: 25px 35px;
    text-align: center;
    border-top: 3px solid #899078;
  }

  .contact-footer h2 {
    margin-top: 0 !important;
  }

  .contact-footer a {
    color: #59634c !important;
    text-decoration: none;
  }

  /* Mobile adjustments */
  @media (max-width: 600px) {
    .hero {
      height: 280px;
    }

    .hero-name {
      font-size: 2.7rem !important;
      left: 5%;
    }

    .profile {
      flex-direction: column;
      align-items: flex-start;
    }

    .profile img {
      width: 160px;
      height: 160px;
    }

    .top-nav {
      gap: 20px;
    }
  }
</style>

<!-- Navigation -->
<div class="top-nav">
  <a href="index.html">Home</a>
  <a href="CV.html">CV</a>
</div>

<!-- Header image -->
<div class="hero">
  <img src="images/sylvanlake.jpg" alt="Sylvan Lake field area">
  <div class="hero-name">Riley Cornella</div>
</div>

<!-- Profile -->
<div class="profile">
  <img src="images/profilepic.jpg" alt="Riley Cornella">

  <div>
    <p>Hi! I am a master's student in the Department of Geology and Geophysics at the University of Wyoming.</p>

    <p><strong>Advisor:</strong> Dr. Ken Sims</p>
  </div>
</div>

<!-- Research -->
## Research

My research involves using machine learning to identify economically viable mineral deposits, and evaluating non-traditional stable isotopes to see whether they can be used to vector towards these deposits.

<!-- Contact footer -->
<div class="contact-footer">
  <h2>Contact</h2>

  <p>
    <a href="mailto:rcornel7@uwyo.edu">rcornel7@uwyo.edu</a>
  </p>

  <p>
    <a href="https://www.uwyo.edu/geolgeophys/" target="_blank">
      University of Wyoming – Department of Geology and Geophysics
    </a>
  </p>
</div>
