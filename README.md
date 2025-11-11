# aqeela-sandwichh
Sandwich Aqeela: Teman Setia di Setiap Saat. Baik untuk sarapan praktis, makan siang yang mengenyangkan, atau camilan sore yang lezat, Sandwich Aqeela selalu siap menemani Anda. Kemasannya yang praktis membuatnya mudah dibawa ke mana saja. Jadi, tunggu apa lagi? Segera nikmati Sandwich Aqeela dan rasakan kelezatannya!
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aqeela Sandwich 🍞</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background-color: #fff0f3;
      color: #4e342e;
    }

    header {
      background-color: #d7b19d;
      color: white;
      text-align: center;
      padding: 25px 10px;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
      letter-spacing: 2px;
    }

    nav {
      background-color: #f8d7da;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }

    nav a {
      text-decoration: none;
      color: #4e342e;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      text-align: center;
      padding: 50px 20px;
      background-color: #ffe6eb;
    }

    .hero img {
      width: 250px;
      border-radius: 20px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
    }

    .hero h2 {
      margin-top: 20px;
      color: #6d4c41;
    }

    .menu {
      max-width: 1000px;
      margin: 50px auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      padding: 0 20px;
    }

    .item {
      background-color: #fff8f9;
      border-radius: 15px;
      box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 20px;
      transition: transform 0.2s;
    }

    .item:hover {
      transform: translateY(-5px);
    }

    .item img {
      width: 200px;
      height: 200px;
      border-radius: 15px;
      object-fit: cover;
    }

    .item h3 {
      margin-top: 10px;
      color: #4e342e;
    }

    .price {
      color: #bf360c;
      font-weight: bold;
      margin: 8px 0;
    }

    .order-btn {
      background-color: #f48fb1;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.2s;
    }

    .order-btn:hover {
      background-color: #ec407a;
    }

    footer {
      background-color: #d7b19d;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Aqeela Sandwich 🍞</h1>
    <p>Sandwich Lezat, Sehat, dan Penuh Cinta!</p>
  </header>

  <nav>
    <a href="#menu">Menu</a>
    <a href="#tentang">Tentang Kami</a>
    <a href="#kontak">Kontak</a>
  </nav>

  <section class="hero">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/02/Sandwich.jpg" alt="Sandwich">
    <h2>Selamat datang di Aqeela Sandwich!</h2>
    <p>Nikmati berbagai pilihan sandwich lembut dengan bahan segar setiap hari 😋</p>
  </section>

  <section id="menu" class="menu">
    <div class="item">
      <img src="https://images.unsplash.com/photo-1565958011705-44e2116917ae?auto=format&fit=crop&w=600&q=80" alt="Sandwich Ayam">
      <h3>Sandwich Ayam</h3>
      <p class="price">Rp15.000</p>
      <button class="order-btn">Pesan Sekarang</button>
    </div>

    <div class="item">
      <img src="https://images.unsplash.com/photo-1606755962773-0b7b1b5e7b87?auto=format&fit=crop&w=600&q=80" alt="Sandwich Telur">
      <h3>Sandwich Telur</h3>
      <p class="price">Rp12.000</p>
      <button class="order-btn">Pesan Sekarang</button>
    </div>

    <div class="item">
      <img src="https://images.unsplash.com/photo-1603048297172-87d48fcbd164?auto=format&fit=crop&w=600&q=80" alt="Sandwich Tuna">
      <h3>Sandwich Tuna</h3>
      <p class="price">Rp18.000</p>
      <button class="order-btn">Pesan Sekarang</button>
    </div>
  </section>

  <section id="tentang" class="hero">
    <h2>Tentang Kami</h2>
    <p>
      Aqeela Sandwich berdiri dengan cinta untuk menghadirkan makanan sehat dan lezat.
      Kami hanya menggunakan bahan berkualitas, roti lembut, dan isian segar setiap hari.
    </p>
  </section>

  <section id="kontak" class="hero">
    <h2>Hubungi Kami</h2>
    <p>📍 Lokasi: Jl. Bahagia No. 5, Jakarta</p>
    <p>📞 WhatsApp: 0812-3456-7890</p>
    <p>📧 Email: aqeelasandwich@gmail.com</p>
  </section>

  <footer>
    <p>© 2025 Aqeela Sandwich. All rights reserved.</p>
  </footer>
</body>
</html>
