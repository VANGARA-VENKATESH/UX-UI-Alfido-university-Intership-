# UX-UI-wireframe-Task-1-Alfido-university-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Wireframe Landing Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header, footer {
      background: #ddd;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: space-between;
      padding: 10px 40px;
      background: #ccc;
    }
    nav a {
      text-decoration: none;
      color: #000;
      margin: 0 10px;
    }
    .hero {
      padding: 60px 20px;
      text-align: center;
      background: #e0e0e0;
    }
    .features {
      display: flex;
      justify-content: space-around;
      padding: 40px 20px;
    }
    .feature-box {
      width: 30%;
      background: #ffffff;
      padding: 20px;
      border: 1px dashed #aaa;
      text-align: center;
    }
    .cta {
      padding: 40px;
      background: #d0d0d0;
      text-align: center;
    }
    button {
      padding: 10px 20px;
      background: #bbb;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <h1>Wireframe Co.</h1>
  </header>

  <nav>
    <div>Logo</div>
    <div>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </div>
  </nav>

  <section class="hero">
    <h2>Main Headline</h2>
    <p>Short description about the product or service.</p>
    <button>Get Started</button>
  </section>

  <section class="features">
    <div class="feature-box">Feature 1</div>
    <div class="feature-box">Feature 2</div>
    <div class="feature-box">Feature 3</div>
  </section>

  <section class="cta">
    <h3>Ready to try?</h3>
    <button>Sign Up Now</button>
  </section>

  <footer>
    &copy; 2025 Wireframe Co. All rights reserved.
  </footer>

</body>
</html>
