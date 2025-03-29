# project-demo
Software Engineering Project
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Timeless Handicrafts</title>

    

    <!-- Bootstrap CSS -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"/>
    <!-- External CSS -->
    <link href="project.css" rel="stylesheet" />
    <script src="project.css"></script>
  </head>
  <body>
<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="navbar">
  <div class="container">
    <!-- Logo as an image on the left side -->
    <a class="navbar-brand" href="#">
      <img src="logo.png" alt="Timeless Handicrafts" style="height: 40px; padding-right: 12.5px;">Timeless Handicrafts
    </a>
    
    <!-- Burger menu on the left -->
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link active" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#explore">Explore</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#Products">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#About">About Us</a>
        </li>
      </ul>
      <div class="ms-lg-3">
        <a href="signin.html" class="btn btn-signin me-2">Sign In</a>
        <a href="signup.html" class="btn btn-signup">Sign Up</a>
      </div>
    </div>
  </div>
</nav>

    <!-- Hero Section -->
<section class="hero-section">
  <div class="container text-center text-white">
    <h1 class="display-3 hero-heading">Timeless Handicrafts</h1>
    <p class="lead hero-description">
      Discover the art of craftsmanship with our handcrafted treasures, made with love and dedication.
    </p>
    <a href="#explore" class="btn btn-primary btn-lg hero-btn">Explore Our Products</a>
  </div>
</section>


    <!-- Categories Section -->
    <div class="container category-section" id="explore">
      <h2 class="text-center mb-5">Explore Our Categories</h2>
      <div class="row justify-content-center g-4">
        <div class="col-md-3 col-sm-6">
          <div class="card category-card">
            <img
              src="https://t4.ftcdn.net/jpg/04/23/45/93/360_F_423459396_Nqt2Pwc2wnhu3f7DHMAiuZWzmRY6D3tR.jpg"
              class="card-img-top"
              alt="Sewing"
            />
            <div class="card-body text-center">
              <p class="category-title">Sewing</p>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-sm-6">
          <div class="card category-card">
            <img
              src="https://media.istockphoto.com/id/932128896/photo/shaping-wood.jpg?s=612x612&w=0&k=20&c=7szI2PN9_8tQeQpTrAqeRrrjTqguBfjMOsYMtC2mmL0="
              class="card-img-top"
              alt="Woodwork"
            />
            <div class="card-body text-center">
              <p class="category-title">Wood Handicrafts</p>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-sm-6">
          <div class="card category-card">
            <img
              src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg84K4TxkcVEJIhvG-iqk8h7uCR5vhlOxKKmEaB9xs2DOFH4pckK71IfeCnFk9eh_0IsCttZLIZbmtMx6u_-TDHLcf2g6Ot6KdmdXDTUvgfm_q2KCgKQ0eCrTaprIpeWNRkZD4i9o0n-Zg/w400-h222/potters+wheel.jpg"
              class="card-img-top"
              alt="Pottery"
            />
            <div class="card-body text-center">
              <p class="category-title">Pottery</p>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-sm-6">
          <div class="card category-card">
            <img
              src="https://imgs.search.brave.com/uYI5I1AnTHa_caspJSYWwMdeVahehUJ2Luoq-ajeXDU/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly93d3cu/dGhlc3BydWNlY3Jh/ZnRzLmNvbS90aG1i/L01GOUdwQnZpNmNl/ZjdRS3hILTZCMzJ0/V2dWcz0vMzE1eDIw/OC9maWx0ZXJzOm5v/X3Vwc2NhbGUoKTpt/YXhfYnl0ZXMoMTUw/MDAwKTpzdHJpcF9p/Y2MoKS9wZW5ndWlu/Z3JvdXAtNWFkYmE1/NmUzMDM3MTMwMDM3/ZTg0Zjk1LmpwZw"
              class="card-img-top"
              alt="Paper Handicrafts"
            />
            <div class="card-body text-center">
              <p class="category-title">Paper Handicrafts</p>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-sm-6">
          <div class="card category-card">
            <img
              src="https://imgs.search.brave.com/BKn05ZhZlYp4kcB18mwY-LDw2isobJIftRA2de4AeDI/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pbWFn/ZXMuc3F1YXJlc3Bh/Y2UtY2RuLmNvbS9j/b250ZW50L3YxLzVh/YjE1ZGJmNWI0MDli/MjJhYmMzNGQ1OS8x/NjEyODA2MDA1MTIy/LVNSM0Q3VzhPTExR/WDZHQzRRVkxSL01p/bmkrS2Vuc2xleStG/bG9yYWwrMS5qcGc"
              class="card-img-top"
              alt="Recycled Crafts"
            />
            <div class="card-body text-center">
              <p class="category-title">Recycled Crafts</p>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-sm-6">
          <div class="card category-card">
            <img
              src="https://imgs.search.brave.com/vWuIvN8HmVGH6vRm0m46-ru5XyOAPcuGEqb28M9_MnY/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9idWRo/c2hpdi5jb20vY2Ru/L3Nob3AvZmlsZXMv/SW5TaG90LTIwMjQx/MjA1XzExMTgzMjI3/My5qcGc_dj0xNzMz/Mzc4MDQwJndpZHRo/PTUzMw"
              class="card-img-top"
              alt="Brass Handicrafts"
            />
            <div class="card-body text-center">
              <p class="category-title">Brass Handicrafts</p>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-sm-6">
          <div class="card category-card">
            <img
              src="https://imgs.search.brave.com/g6SxWvOZUmXREygFbBeBaU83Bg19H3yMVzr85-W09M8/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly93d3cu/YmhhbmRhcmltYXJi/bGVncm91cC5jb20v/d3AtY29udGVudC91/cGxvYWRzLzIwMjQv/MDgvNy0zLTEwMjR4/NzY4LmpwZw"
              class="card-img-top"
              alt="Rock Handicrafts"
            />
            <div class="card-body text-center">
              <p class="category-title">Rock Handicrafts</p>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-sm-6">
          <div class="card category-card">
            <img
              src="https://imgs.search.brave.com/JrtPYLz-r72-AMZTKHk8Mv1jLTfqk-KiZhs7nfkWU3k/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pLmV0/c3lzdGF0aWMuY29t/LzQ2OTU4NjM2L3Iv/aWwvODZlMmU4LzUz/NjQwMzc1MTcvaWxf/NjAweDYwMC41MzY0/MDM3NTE3X2V4MXku/anBn"
              class="card-img-top"
              alt="Bamboo Handicrafts"/>
              <div class="card-body text-center">
                <p class="category-title">Bamboo Handicrafts</p>
              </div>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Featured product -->
      <section class="product-section" id="Products">
        <h2 class="text-center mb-5">Featured Products</h2>
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-md-4">
              <div class="card">
                <img
                  src="https://images1.novica.net/pictures/9/p228428_2_800.jpg"
                  class="card-img-top"
                  alt="Handcrafted Vase"
                />
                <div class="card-body">
                  <h5 class="card-title">Handcrafted Vase</h5>
                  <p class="card-text" id="product1-text">
                    Beautifully crafted vase with intricate details and design.
                    This unique piece is hand-painted with delicate brushwork that
                    will brighten any space
                    <span id="dots1">...</span>
                    <span id="more1" style="display: none">
                      and add a personal touch to your home decor. Perfect for any
                      setting, whether it's a modern apartment or a traditional
                      home.
                    </span>
                  </p>
                  <a href="#" class="btn btn-primary" onclick="toggleText(1)"
                    >View Details</a
                  >
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div class="card">
                <img
                  src="https://www.the-citizenry.com/cdn/shop/products/Rivi_Storage_Basket_Large_3.jpg?format=webp&v=1656087164&width=1000"
                  alt="Handwoven Basket"
                  class="card-img-top"
                />
                <div class="card-body">
                  <h5 class="card-title">Handwoven Basket</h5>
                  <p class="card-text" id="product2-text">
                    A timeless piece for your home or office. Handwoven with care,
                    this basket is perfect for storing small items or as a
                    decorative centerpiece
                    <span id="dots2">...</span>
                    <span id="more2" style="display: none">
                      Made from sustainable materials, it's both eco-friendly and
                      durable. Great for organizing and adding an earthy touch to
                      any room.
                    </span>
                  </p>
                  <a href="#" class="btn btn-primary" onclick="toggleText(2)"
                    >View Details</a
                  >
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div class="card">
                <img
                  src="https://www.martinandmacarthur.com/cdn/shop/products/SEAC_30070C_BF27_HERO_Web_720x.jpg?v=1619720562"
                  alt="Wooden Sculpture"
                  class="card-img-top"
                />
                <div class="card-body">
                  <h5 class="card-title">Wooden Sculpture</h5>
                  <p class="card-text" id="product3-text">
                    Unique wooden sculpture hand-carved with precision. A great
                    addition to any art lover's collection, this piece tells its
                    own story
                    <span id="dots3">...</span>
                    <span id="more3" style="display: none">
                      Every detail is meticulously carved to create a visually
                      striking piece that embodies both craftsmanship and
                      artistry.
                    </span>
                  </p>
                  <a href="#" class="btn btn-primary" onclick="toggleText(3)"
                    >View Details</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
  
      <!-- About Us Section -->
      <section class="about-section" id="About">
        <div class="container text-center">
          <h2>About Us</h2>
          <p>
            At Timeless Handicrafts, we honor the art of craftsmanship. Our
            products, handcrafted by skilled artisans from around the world, blend
            tradition with modern design. Each piece tells its own unique story,
            carrying a legacy forward.
          </p>
        </div>
      </section>
  
      <!-- Footer Container -->
      <div class="footer-container">
        <div class="footer-content container">
          <div class="footer-contact">
            <h3>Get in Touch</h3>
            <p>
              <i class="ion-ios-home-outline"></i> 2020 Willshire Glen, Out of
              Alpharetta, GA-30009
            </p>
            <p><i class="ion-ios-telephone-outline"></i> (+00) 121 025 0214</p>
            <p>
              <i class="ion-ios-email-outline"></i>
              <a href="#">info@example.com</a>
            </p>
          </div>
  
          <div class="footer-info">
            <h3>Information</h3>
            <ul>
              <li><a href="#">Delivery</a></li>
              <li><a href="#">Legal Notice</a></li>
              <li><a href="#">Terms &amp; Conditions</a></li>
              <li><a href="#">About Us</a></li>
              <li><a href="#">Secure Payment</a></li>
            </ul>
          </div>
  
          <div class="footer-accounts">
            <h3>Accounts</h3>
            <ul>
              <li><a href="signin.html">Sign In</a></li>
              <li><a href="#">View Cart</a></li>
              <li><a href="#">My Wishlist</a></li>
              <li><a href="#">Track My Order</a></li>
              <li><a href="#">Help</a></li>
            </ul>
          </div>
  
          <div class="footer-support">
            <h3>Support</h3>
            <ul>
              <li><a href="#">Contact Us</a></li>
              <li><a href="#">Shipping &amp; Tax</a></li>
              <li><a href="#">Return Policy</a></li>
              <li><a href="#">Affiliates</a></li>
              <li><a href="#">Legal Notice</a></li>
            </ul>
          </div>
        </div>
      </div>
  
      <!-- Footer Section -->
      <footer class="footer">
        <div class="container text-center">
          <p>&copy; 2025 Timeless Handicrafts. All Rights Reserved.</p>
        </div>
      </footer>
  
      <!-- Bootstrap JS -->
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
    </body>
  </html>
  
