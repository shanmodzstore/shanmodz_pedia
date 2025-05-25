<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SHANMODZ AI STORE</title>
  <style>
    :root {
      --bg-color: #ffffff;
      --text-color: #333333;
      --primary-color: #6b46c1;
      --button-bg: #a78bfa;
      --button-text: #fff;
    }

    .dark {
      --bg-color: #1a202c;
      --text-color: #e2e8f0;
      --primary-color: #9f7aea;
      --button-bg: #6b46c1;
      --button-text: #fff;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    header {
      padding: 1rem 2rem;
      background-color: var(--primary-color);
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .header-left h1 {
      margin: 0;
      font-size: 1.5rem;
    }

    .header-subtitle {
      font-size: 0.9rem;
      opacity: 0.85;
    }

    .toggle-container {
      width: 50px;
      height: 25px;
      background-color: white;
      border-radius: 25px;
      display: flex;
      align-items: center;
      padding: 3px;
      cursor: pointer;
    }

    .dark .toggle-container {
      background-color: #4c51bf;
    }

    .toggle-circle {
      width: 20px;
      height: 20px;
      background-color: var(--primary-color);
      border-radius: 50%;
      transition: transform 0.3s;
    }

    .dark .toggle-circle {
      transform: translateX(25px);
      background-color: white;
    }

    main {
      padding: 2rem;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .services {
      display: grid;
      gap: 1.5rem;
      max-width: 1000px;
      width: 100%;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    }

    .card {
      background-color: var(--bg-color);
      border: 1px solid var(--primary-color);
      border-radius: 12px;
      padding: 1.5rem;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0,0,0,0.1);
    }

    .card h3 {
      margin-top: 0;
      font-size: 1.1rem;
      color: var(--primary-color);
    }

    .card p {
      font-size: 0.85rem;
    }

    .btn-whatsapp {
      display: inline-block;
      background-color: var(--button-bg);
      color: var(--button-text);
      padding: 0.5rem 1rem;
      border-radius: 6px;
      text-decoration: none;
      font-size: 0.85rem;
      margin-top: 1rem;
      text-align: center;
    }

    .btn-whatsapp:hover {
      opacity: 0.9;
    }

    footer {
      padding: 1rem;
      text-align: center;
      font-size: 0.8rem;
      background-color: #f3f3f3;
      color: #777;
    }

    .dark footer {
      background-color: #2d3748;
      color: #aaa;
    }

    a {
      color: var(--primary-color);
    }

    .contact-owner {
      margin-top: 3rem;
      text-align: center;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="header-left">
      <h1>SHANMODZ AI STORE</h1>
      <div class="header-subtitle">Top Up & PPOB Terpercaya</div>
    </div>
    <div class="toggle-container" onclick="toggleDarkMode()" title="Dark Mode">
      <div class="toggle-circle"></div>
    </div>
  </header>

  <main>
    <div class="services">
      <div class="card">
        <h3>Top Up Game</h3>
        <p>Mobile Legends, Free Fire, PUBG, dan lainnya. Proses cepat & terpercaya!</p>
        <a class="btn-whatsapp" href="https://wa.me/6282140533176?text=.menu" target="_blank">Order via WhatsApp</a>
      </div>

      <div class="card">
        <h3>Pulsa & Paket Data</h3>
        <p>Tersedia semua operator dengan harga bersahabat. Langsung isi dari rumah!</p>
        <a class="btn-whatsapp" href="https://wa.me/6282140533176?text=.menu" target="_blank">Order via WhatsApp</a>
      </div>

      <div class="card">
        <h3>Top Up E-Money</h3>
        <p>Isi saldo OVO, DANA, GoPay dan dompet digital lainnya secara instan.</p>
        <a class="btn-whatsapp" href="https://wa.me/6282140533176?text=.menu" target="_blank">Order via WhatsApp</a>
      </div>
    </div>

    <div class="contact-owner">
      <p>Jika terjadi kendala, silakan hubungi <a href="https://wa.me/6281330757006" target="_blank">Owner ShanModzZ Ai</a></p>
    </div>
  </main>

  <footer>
    &copy; 2025 SHANMODZ AI STORE - All rights reserved.
  </footer>

  <script>
    function toggleDarkMode() {
      document.documentElement.classList.toggle('dark');
    }
  </script>
</body>
</html>
