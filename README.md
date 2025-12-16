<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Toko Sembako Berkah</title>
  <style>
    /* Reset & Base */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f9f9f9;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    /* Header */
    header {
      background-color: #2c3e50;
      color: white;
      padding: 1rem 0;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .navbar h1 {
      font-size: 1.8rem;
    }
    .navbar ul {
      display: flex;
      list-style: none;
    }
    .navbar ul li {
      margin-left: 20px;
    }
    .navbar ul li a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }
    .navbar ul li a:hover {
      color: #1abc9c;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(135deg, #3498db, #2c3e50);
      color: white;
      padding: 60px 20px;
      text-align: center;
      border-radius: 0 0 20px 20px;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 700px;
      margin: 0 auto;
    }

    /* Produk */
    .products {
      margin: 60px 0;
    }
    .products h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #2c3e50;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }
    .product-card {
      background: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product-card h3 {
      margin: 10px 0;
    }
    .product-card p {
      color: #666;
    }
    .price {
      font-weight: bold;
      color: #e74c3c;
      font-size: 1.2rem;
    }

    /* Kontak */
    .contact {
      background: #ecf0f1;
      padding: 40px 0;
      margin: 60px 0;
      border-radius: 10px;
    }
    .contact h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .contact-info {
      text-align: center;
      font-size: 1.1rem;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px 0;
      color: #7f8c8d;
      font-size: 0.9rem;
    }

    /* Responsif */
    @media (max-width: 600px) {
      .navbar ul {
        display: none;
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
    <div class="container navbar">
      <h1>Toko Sembako Berkah</h1>
      <ul>
        <li><a href="#home">Beranda</a></li>
        <li><a href="#products">Produk</a></li>
        <li><a href="#contact">Kontak</a></li>
      </ul>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="container">
      <h2>Selamat Datang di Toko Sembako Berkah!</h2>
      <p>Kami menyediakan kebutuhan pokok berkualitas dengan harga terjangkau. Buka setiap hari pukul 07.00–21.00.</p>
    </div>
  </section>

  <!-- Produk -->
  <section id="products" class="container products">
    <h2>Produk Unggulan Kami</h2>
    <div class="product-grid">
      <div class="product-card">
        <h3>Beras Premium</h3>
        <p>5 kg | Pulen & wangi</p>
        <p class="price">Rp 65.000</p>
      </div>
      <div class="product-card">
        <h3>Minyak Goreng</h3>
        <p>2 L | Kemasan baru</p>
        <p class="price">Rp 28.000</p>
      </div>
      <div class="product-card">
        <h3>Gula Pasir</h3>
        <p>1 kg | Putih bersih</p>
        <p class="price">Rp 14.500</p>
      </div>
      <div class="product-card">
        <h3>Telur Ayam</h3>
        <p>1 kg (±16 butir)</p>
        <p class="price">Rp 26.000</p>
      </div>
    </div>
  </section>

  <!-- Kontak -->
  <section id="contact" class="contact">
    <div class="container">
      <h2>Hubungi Kami</h2>
      <div class="contact-info">
        <p>📍 Jl. Merdeka No. 45, Kota Bandung</p>
        <p>📱 WhatsApp: <a href="https://wa.me/6281234567890">0812-3456-7890</a></p>
        <p>🕒 Buka: Setiap hari pukul 07.00–21.00</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      &copy; 2025 Toko Sembako Berkah. Semua hak dilindungi.
    </div>
  </footer>

</body>
</html>

