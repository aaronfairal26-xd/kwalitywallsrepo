# index.html
hackathon webstie kwality walls
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kwality Walls Ice Cream</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* General Styles */
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #ffe6f0; /* Pink theme background */
      color: #333;
    }

    h2, h1 {
      font-weight: 700;
    }

    .text-pink-dark {
      color: #d63384;
    }

    .text-pink {
      color: #ff4da6;
    }

    .bg-pink-light {
      background-color: #ffe6f0;
    }

    .btn-pink {
      background-color: #ff4da6;
      color: white;
    }

    .btn-pink:hover {
      background-color: #d63384;
    }

    .btn-outline-pink {
      border-color: #ff4da6;
      color: #ff4da6;
    }

    .btn-outline-pink:hover {
      background-color: #ff4da6;
      color: white;
    }

    .flavor-card {
      border: none;
      border-radius: 15px;
      transition: transform 0.3s;
    }

    .flavor-card:hover {
      transform: scale(1.05);
    }

    .price {
      font-weight: 600;
      color: #d63384;
      display: block;
      margin-top: 10px;
    }

    .chocolate-bg {
      background-color: #6b4226; /* Chocolate section background */
      color: white;
      padding: 2rem 1rem;
      border-radius: 15px;
    }

    footer {
      background-color: #ffe6f0;
      color: #d63384;
    }

    .section-padding {
      padding: 60px 0;
    }

    /* Contact Form */
    .contact-form input, .contact-form textarea {
      border-radius: 10px;
      border: 1px solid #ccc;
      padding: 10px;
      margin-bottom: 15px;
    }

    .contact-form button {
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <div class="container">
      <a class="navbar-brand text-pink fw-bold" href="#">Kwality Walls</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mainNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="mainNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#hero">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#flavors">Flavors</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About Us</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
          <li class="nav-item"><a class="btn btn-outline-pink ms-2" href="#store">Store Locator</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header id="hero" class="hero bg-pink-light py-5 text-center">
    <div class="container">
      <h1 class="display-4 fw-bold text-pink-dark">Kwality Walls Ice Cream</h1>
      <p class="lead text-muted">Savor the sweetest moments with our delicious flavors!</p>
      <a href="#flavors" class="btn btn-pink mt-3">Explore Flavors</a>
    </div>
  </header>

  <!-- Flavors Section -->
  <section id="flavors" class="container section-padding">
    <h2 class="text-center text-pink-dark mb-4">Our Flavors</h2>
    <div class="row g-4">
      <div class="col-md-3">
        <div class="card flavor-card chocolate-bg text-center">
          <img src="https://images.unsplash.com/photo-1544025162-d76694265947?q=80&w=800&auto=format&fit=crop" class="card-img-top rounded" alt="Chocolate">
          <div class="card-body">
            <h5 class="card-title">Classic Chocolate</h5>
            <p class="card-text">Rich & creamy cocoa.</p>
            <span class="price">₹45</span>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card flavor-card text-center">
          <img src="https://images.unsplash.com/photo-1606756791193-2b6ac0f67a8b?q=80&w=800&auto=format&fit=crop" class="card-img-top rounded" alt="Mango">
          <div class="card-body">
            <h5 class="card-title">Alphonso Mango</h5>
            <p class="card-text">Pure mango pulp.</p>
            <span class="price">₹50</span>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card flavor-card text-center">
          <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?q=80&w=800&auto=format&fit=crop" class="card-img-top rounded" alt="Strawberry">
          <div class="card-body">
            <h5 class="card-title">Strawberry Delight</h5>
            <p class="card-text">Fresh strawberry flavor.</p>
            <span class="price">₹50</span>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card flavor-card chocolate-bg text-center">
          <img src="https://images.unsplash.com/photo-1528449034469-5f8f7e1a2b2c?q=80&w=800&auto=format&fit=crop" class="card-img-top rounded" alt="Feast">
          <div class="card-body">
            <h5 class="card-title">Feast Choco</h5>
            <p class="card-text">Loaded with choco bits.</p>
            <span class="price">₹55</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about" class="container section-padding">
    <h2 class="text-center text-pink-dark mb-4">About Us</h2>
    <div class="row align-items-center">
      <div class="col-md-6">
        <img src="https://images.unsplash.com/photo-1582719478145-5a7b61801f6b?q=80&w=800&auto=format&fit=crop" class="img-fluid rounded" alt="About Us">
      </div>
      <div class="col-md-6">
        <p>Kwality Walls has been serving the best ice cream since <strong>1946</strong>. Our mission is to bring joy with every scoop, blending high-quality ingredients with innovative flavors to delight every taste bud.</p>
        <p>From classic chocolate to fruity delights, we ensure every bite is a moment to savor. Join us in celebrating sweetness and happiness!</p>
      </div>
    </div>
  </section>

  <!-- Contact Us Section -->
  <section id="contact" class="container section-padding">
    <h2 class="text-center text-pink-dark mb-4">Contact Us</h2>
    <div class="row justify-content-center">
      <div class="col-md-6">
        <form class="contact-form">
          <input type="text" class="form-control" placeholder="Your Name" required>
          <input type="email" class="form-control" placeholder="Your Email" required>
          <textarea class="form-control" rows="5" placeholder="Your Message" required></textarea>
          <button type="submit" class="btn btn-pink w-100">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <!-- Store Locator Section -->
  <section id="store" class="container section-padding">
    <h2 class="text-center text-pink-dark mb-4">Store Locator</h2>
    <div class="row g-3">
      <div class="col-md-4">
        <div class="card p-3 text-center">
          <h5>City Center Kiosk</h5>
          <p>MG Road — 10:00–22:00</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-3 text-center">
          <h5>College Canteen Stall</h5>
          <p>Near Gate 2 — 09:00–20:00</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-3 text-center">
          <h5>Mall Pop-up</h5>
          <p>Level 1 Atrium — 11:00–21:00</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-3">
    <p class="mb-0">Hackathon Demo — Kwality Walls Ice Cream | Established 1946</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
