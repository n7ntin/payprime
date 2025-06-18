<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Play Prime - Sports Store</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background: url('https://source.unsplash.com/1600x400/?sports') no-repeat center center;
      background-size: cover;
      color: #fff;
      padding: 100px 0;
      text-align: center;
    }
    .product-card {
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 15px;
      margin-bottom: 20px;
      text-align: center;
    }
    .footer {
      background: #343a40;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Play Prime</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
      data-bs-target="#navbarNav" aria-controls="navbarNav"
      aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Shop</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Cart</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<section class="hero">
  <div class="container">
    <h1>Welcome to Play Prime</h1>
    <p>Your one-stop shop for premium sports equipment</p>
    <a href="#" class="btn btn-primary">Shop Now</a>
  </div>
</section>

<!-- Products -->
<section class="container my-5">
  <h2 class="mb-4 text-center">Featured Products</h2>
  <div class="row">
    <div class="col-md-3">
      <div class="product-card">
        <img src="https://source.unsplash.com/200x200/?badminton" class="img-fluid mb-2" alt="Product">
        <h5>Badminton Racket</h5>
        <p>₹1200</p>
        <a href="#" class="btn btn-sm btn-success">Buy Now</a>
      </div>
    </div>
    <div class="col-md-3">
      <div class="product-card">
        <img src="https://source.unsplash.com/200x200/?cricket" class="img-fluid mb-2" alt="Product">
        <h5>Cricket Bat</h5>
        <p>₹2500</p>
        <a href="#" class="btn btn-sm btn-success">Buy Now</a>
      </div>
    </div>
    <div class="col-md-3">
      <div class="product-card">
        <img src="https://source.unsplash.com/200x200/?football" class="img-fluid mb-2" alt="Product">
        <h5>Football</h5>
        <p>₹800</p>
        <a href="#" class="btn btn-sm btn-success">Buy Now</a>
      </div>
    </div>
    <div class="col-md-3">
      <div class="product-card">
        <img src="https://source.unsplash.com/200x200/?tennis" class="img-fluid mb-2" alt="Product">
        <h5>Tennis Racket</h5>
        <p>₹1500</p>
        <a href="#" class="btn btn-sm btn-success">Buy Now</a>
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="footer">
  <div class="container">
    <p>&copy; 2025 Play Prime. All rights reserved.</p>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
