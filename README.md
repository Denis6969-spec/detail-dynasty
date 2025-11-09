<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Detail Dynasty</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #0d0d0d;
      color: #fff;
      line-height: 1.6;
    }

    a {
      color: #f1c40f;
      text-decoration: none;
    }

    /* Header */
    header {
      text-align: center;
      padding: 100px 20px 60px;
      background: linear-gradient(135deg, #000000, #333333);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header img {
      width: 160px;
      margin-bottom: 20px;
    }

    header h1 {
      font-size: clamp(2rem, 5vw, 2.5rem);
      letter-spacing: 1px;
      color: #f1c40f;
    }

    header p {
      font-size: clamp(1rem, 2.5vw, 1.2rem);
      color: #ccc;
      margin-top: 10px;
    }

    .cta-button {
      display: inline-block;
      margin-top: 25px;
      padding: 14px 30px;
      background-color: #f1c40f;
      color: #000;
      font-weight: 700;
      border-radius: 8px;
      transition: all 0.3s ease;
    }

    .cta-button:hover {
      background-color: #e0b90f;
      transform: translateY(-3px);
    }

    /* Sections */
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      color: #f1c40f;
      font-size: clamp(1.5rem, 4vw, 2rem);
      margin-bottom: 40px;
    }

    /* Services */
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .service-box {
      background: #1c1c1c;
      padding: 30px;
      border-radius: 12px;
      flex: 1 1 250px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
      text-align: center;
      transition: all 0.3s ease;
    }

    .service-box:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.6);
    }

    .service-box h3 {
      color: #f1c40f;
      margin-bottom: 15px;
      font-size: 1.3rem;
    }

    .service-box p {
      color: #ccc;
      font-size: 1rem;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 40px 20px;
      background-color: #000;
      border-top: 1px solid #222;
      color: #ccc;
    }

    footer p {
      margin: 8px 0;
    }

    /* Responsive Adjustments */
    @media (max-width: 600px) {
      header {
        padding: 80px 20px 40px;
      }

      .service-box {
        flex: 1 1 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="ChatGPT Image Nov 8, 2025, 11_06_58 PM.png" alt="Detail Dynasty Logo" />
    <h1>Detail Dynasty</h1>
    <p>Come get your car cleaned by the kings of Detail Dynasty</p>
    <a href="#services" class="cta-button">See Our Services</a>
  </header>

  <main>
    <section id="services">
      <h2>Our Services</h2>
      <div class="services">
        <div class="service-box">
          <h3>Interior Detailing</h3>
          <p>Deep cleaning and conditioning of seats, carpets, and panels to restore a fresh, new feel inside your vehicle.</p>
        </div>
        <div class="service-box">
          <h3>Exterior Detailing</h3>
          <p>Hand wash, wax, and polish for a mirror finish that brings out your car’s true shine.</p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p><strong>Phone:</strong> <a href="tel:6189192677">618-919-2677</a></p>
    <p><strong>Locations:</strong> Fairfield, Louisville, & Cisne, Illinois</p>
    <p>&copy; 2025 Detail Dynasty. All rights reserved.</p>
  </footer>
</body>
</html>
