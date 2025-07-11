<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>About Us - Sunnies Studios</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<style>
  body {
    font-family: 'Poppins', sans-serif;
    background-position: center;
    text-align: center;
  }

  .header-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    padding: 0.6rem 1rem;
  }

  .navbar {
    display: flex;
    gap: 0.6em;
    flex-wrap: wrap;
    justify-content: center;
  }

  .navbar a {
    padding: 0.5em 1em;
    text-decoration: none;
    font-weight: bold;
    color: black;
    transition: all 0.3s ease;
  }

  .navbar a:hover {
    text-decoration: underline;
  }

  .center-logo {
    flex-grow: 1;
    display: flex;
    justify-content: center;
    margin: 10px 0;
  }

  .center-logo img {
    width: 200px;
    height: auto;
  }

  .right-icons {
    display: flex;
    align-items: center;
    gap: 15px;
    justify-content: center;
  }

  .right-icons a {
    color: black;
  }

  .video-container video,
  .video-hero video {
    width: 100%;
    max-height: 600px;
    object-fit: cover;
    display: block;
  }

  .video-hero {
    position: relative;
    width: 100%;
    overflow: hidden;
  }

  .overlay-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    text-shadow: 1px 1px 10px rgba(0, 0, 0, 0.8);
    text-align: center;
    padding: 1rem;
  }

  .overlay-text h2 {
    font-size: 2.5rem;
    font-weight: bold;
  }

  .overlay-text p {
    font-size: 1.2rem;
  }

  .card {
    background-color: #e8e8e4;
    text-align: center;
  }

  .card .price {
    color: #b3a89b;
    text-align: right;
  }

  .card button {
    border: none;
    outline: 0;
    padding: 12px;
    color: black;
    background-color: white;
    cursor: pointer;
    width: 100%;
    font-size: 18px;
  }

  .card button:hover {
    opacity: 0.7;
  }

  .footer {
    text-align: left;
    padding: 1rem;
  }

  .footer p,
  .footer h5 {
    font-family: 'Poppins', sans-serif;
  }

  .footer .form-inline {
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    gap: 10px;
    flex-wrap: wrap;
  }

  .footer .form-inline .form-control {
    font-size: 0.9rem;
    padding: 0.3rem 0.6rem;
    width: 180px;
  }

  .footer .form-inline .btn {
    padding: 0.3rem 1rem;
    font-size: 0.9rem;
  }

  .hero-img {
    width: 100%;
    height: auto;
    display: block;
  }

  .about-brand {
  padding: 2rem 1rem;
  max-width: 1000px;
  margin: 0 auto;
  text-align: left;
}

.about-brand p {
  text-align: justify;
  line-height: 1.8;
  font-size: 1rem;
}


  @media (max-width: 768px) {
    .header-row {
      flex-direction: column;
      gap: 10px;
    }

    .navbar,
    .right-icons {
      justify-content: center;
    }

    .footer .form-inline {
      flex-direction: column;
      align-items: stretch;
    }

    .footer .form-inline .form-control,
    .footer .form-inline .btn {
      width: 100%;
    }

    .about-container .row {
      flex-direction: column;
      text-align: center;
    }

    .about-brand {
      padding: 1rem;
    }
  }
</style>

  <script>
    function addToCart(id, name, price) {
      let cart = JSON.parse(localStorage.getItem("cart")) || [];
      cart.push({ id, name, price, quantity: 1 });
      localStorage.setItem("cart", JSON.stringify(cart));
      alert(`${name} has been added to your cart.`);
    }
  </script>
</head>
<body>
  <div class="header-row">
    <div class="navbar">
      <a href="#Sun">Sun</a>
      <a href="#Optical">Optical</a>
      <a href="#Anti-Rad">Anti-Rad</a>
      <a href="#Readers">Readers</a>
    </div>
    <div class="center-logo">
      <a href="HOMEPAGE.html">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/dd/Sunnies_Studios_logo.png/1200px-Sunnies_Studios_logo.png?20201031004544" alt="Logo">
      </a>
    </div>
    <div class="right-icons">
      <a href="login.html"><i class="fas fa-user fa-lg"></i></a>
      <a href="cart.html"><i class="fas fa-shopping-cart fa-lg"></i></a>
    </div>
  </div>

  <img class="hero-img" src="https://cdn.shopify.com/s/files/1/0268/4141/5798/files/2024_JULY_30_SUNNIESFACE26604_copy_2aa_copy_desktop.jpg?v=1729654470" alt="Hero Banner">

<br>
<section id="about">
  <div class="about-brand">
  <div class="row align-items-center">
    <div class="col-md-5 p-4 text-md-start">
      <h2>About Us as a Brand</h2>
      <p>
        Sunnies Inc. was founded in 2013, first as a one-stop shop for sunglasses that soon expanded into a full-service optical that offers prescription eyewear. Driven by its mission to see beauty in everyday things, it has become a lifestyle brand that encompasses different facets of everyday including skincare, cosmetics, food, beverage, and flasks. By combining utility and aesthetics, Sunnies Inc. sees to it that you look good and feel good.
      </p>
    </div>
</section>

<section id="values">
    <div class="col-md-7 ps-md-5 text-center">
      <img src="https://sunniesstudios.com/cdn/shop/files/2024_JUN_11_SUNNIESFACE11854_1_copya.jpg?v=1729654468"
           alt="Sunnies Brand"
           class="img-fluid rounded shadow-sm" style="max-height: 450px; object-fit: cover;">
    
</section>
</div>
  </div>
</div>

<br>

<div class="about-brand">
  <div class="row align-items-center">
    <div class="col-md-7 pe-md-5 text-center">
      <img src="https://cdn.shopify.com/s/files/1/0268/4141/5798/files/2023_FEB_11_SUNNIESFACE0868_copyaa_copy_2_core_values.jpg?v=1729654501"
           alt="Sunnies Optical"
           class="img-fluid rounded shadow-sm" style="max-height: 450px; object-fit: cover;">
    </div>
    <div class="col-md-5 p-4 text-md-start">
      <h2>Our Core Values</h2>
      <p>
        At Sunnies, we are dedicated to being creative, committed, customer-focused, and continuously learning to develop products that look good and feel great on you. ​
      </p>
      
    </div>
  </div>
</div>

  <hr><br>
  <div class="footer">
    <p>&nbsp;&nbsp;&nbsp;Good stuff, straight to your inbox.</p>
    <h5>&nbsp;&nbsp;&nbsp;10% off your first eyewear in your purchase when you enter your email.</h5>
    <br>
    <div class="login-container">
      <form id="loginForm" class="form-inline">
        <input type="text" class="form-control" id="firstName" placeholder="Your name" required>
        <input type="email" class="form-control" id="address" placeholder="you@example.com" required>
        <button type="submit" class="btn btn-red">Subscribe</button>
      </form>
    </div>
    <br>
    <h6>© 2025, Sunnies Studios <a href="https://sunniesstudios.com/policies/terms-of-service">&nbsp;&nbsp;&nbsp;Terms & Conditions</a></h6>
  </div>
</body>
</html>
