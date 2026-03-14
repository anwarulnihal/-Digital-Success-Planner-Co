# -Digital-Success-Planner-Co
it will contain all the needs of website built
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital Success Planner Co</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    }

    body {
      background: #f9fafc;
      color: #1e293b;
      line-height: 1.6;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }

    /* Header */
    header {
      background: white;
      box-shadow: 0 4px 6px -1px rgba(0,0,0,0.05);
      padding: 20px 0;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .header-content {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .logo h1 {
      font-size: 1.8rem;
      font-weight: 700;
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .logo span {
      font-size: 0.9rem;
      display: block;
      color: #64748b;
      font-weight: 400;
    }

    nav a {
      margin-left: 30px;
      text-decoration: none;
      color: #475569;
      font-weight: 500;
      transition: color 0.2s;
    }

    nav a:hover {
      color: #3b82f6;
    }

    /* Hero */
    .hero {
      background: linear-gradient(135deg, #f0f9ff 0%, #e6f0fa 100%);
      padding: 60px 0;
      text-align: center;
      margin-bottom: 40px;
    }

    .hero h2 {
      font-size: 2.8rem;
      margin-bottom: 15px;
      color: #0f172a;
    }

    .hero p {
      font-size: 1.3rem;
      color: #334155;
      max-width: 700px;
      margin: 0 auto 30px;
    }

    .btn {
      display: inline-block;
      background: #3b82f6;
      color: white;
      padding: 12px 30px;
      border-radius: 40px;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.2s, transform 0.1s;
    }

    .btn:hover {
      background: #2563eb;
      transform: scale(1.02);
    }

    /* Products */
    .section-title {
      text-align: center;
      font-size: 2.2rem;
      margin: 50px 0 30px;
      color: #0f172a;
    }

    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      margin-bottom: 60px;
    }

    .product-card {
      background: white;
      border-radius: 20px;
      padding: 25px;
      box-shadow: 0 10px 25px -5px rgba(0,0,0,0.05);
      transition: transform 0.3s, box-shadow 0.3s;
      border: 1px solid #e9eef2;
      text-align: center;
    }

    .product-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 20px 30px -10px rgba(0,0,0,0.1);
    }

    .product-image {
      width: 100%;
      height: 200px;
      object-fit: contain;
      margin-bottom: 20px;
    }

    .product-title {
      font-size: 1.5rem;
      margin-bottom: 10px;
      color: #0f172a;
    }

    .product-description {
      color: #475569;
      margin-bottom: 20px;
      font-size: 0.95rem;
    }

    .product-price {
      font-size: 1.8rem;
      font-weight: 700;
      color: #3b82f6;
      margin-bottom: 20px;
    }

    .buy-btn {
      display: inline-block;
      background: #3b82f6;
      color: white;
      padding: 12px 30px;
      border-radius: 40px;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.2s;
      border: none;
      cursor: pointer;
      width: 100%;
      font-size: 1rem;
    }

    .buy-btn:hover {
      background: #2563eb;
    }

    /* Footer */
    footer {
      background: #1e293b;
      color: #cbd5e1;
      text-align: center;
      padding: 40px 0;
      margin-top: 60px;
    }

    footer p {
      margin-bottom: 10px;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .header-content {
        flex-direction: column;
        gap: 15px;
      }
      nav a {
        margin: 0 15px;
      }
      .hero h2 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="container header-content">
      <div class="logo">
        <h1>Digital Success Planner Co.</h1>
        <span>Plan your way to success</span>
      </div>
      <nav>
        <a href="#">Home</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h2>Your success starts with a plan</h2>
      <p>Digital planners, templates, and tools to organize your life and achieve your goals.</p>
      <a href="#products" class="btn">Browse Planners</a>
    </div>
  </section>

  <!-- Products Section -->
  <div class="container" id="products">
    <h2 class="section-title">Our Digital Planners</h2>
    <div class="products-grid">
      
      <!-- Product 1 -->
      <div class="product-card">
        <img src="https://via.placeholder.com/300x200/3b82f6/ffffff?text=Daily+Planner" alt="Daily Planner" class="product-image">
        <h3 class="product-title">Daily Success Planner</h3>
        <p class="product-description">A comprehensive daily planner to prioritize tasks, track habits, and reflect on your wins.</p>
        <div class="product-price">$12.99</div>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>

      <!-- Product 2 -->
      <div class="product-card">
        <img src="https://via.placeholder.com/300x200/8b5cf6/ffffff?text=Weekly+Planner" alt="Weekly Planner" class="product-image">
        <h3 class="product-title">Weekly Vision Planner</h3>
        <p class="product-description">Plan your week with intention, set big goals, and break them into actionable steps.</p>
        <div class="product-price">$9.99</div>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>

      <!-- Product 3 -->
      <div class="product-card">
        <img src="https://via.placeholder.com/300x200/10b981/ffffff?text=Goal+Tracker" alt="Goal Tracker" class="product-image">
        <h3 class="product-title">Goal Tracker Bundle</h3>
        <p class="product-description">Track your yearly, monthly, and weekly goals with these easy-to-use Notion templates.</p>
        <div class="product-price">$19.99</div>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>

      <!-- Product 4 -->
      <div class="product-card">
        <img src="https://via.placeholder.com/300x200/f59e0b/ffffff?text=Habit+Tracker" alt="Habit Tracker" class="product-image">
        <h3 class="product-title">Habit Mastery Kit</h3>
        <p class="product-description">Build life-changing habits with this printable habit tracker and reflection journal.</p>
        <div class="product-price">$7.99</div>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>

    </div>
  </div>

  <!-- Contact / Footer -->
  <footer id="contact">
    <div class="container">
      <p>📧 support@digitalsuccessplanner.com</p>
      <p>© 2025 Digital Success Planner Co. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>