<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KAYA İNŞAAT | Antalya Tadilat & Tamirat</title>
  <meta name="description" content="Kaya İnşaat — Antalya tadilat ve tamirat işleri, uzman Selman Kaya. Güvenilir, kaliteli ve zamanında teslim.">
  <meta name="keywords" content="Antalya tadilat, Antalya tamirat, inşaat, Selman Kaya, Kaya İnşaat">
  <style>
    * {margin:0; padding:0; box-sizing: border-box; font-family: Arial, sans-serif;}
    body {color: #fff; line-height: 1.6;}
    header {
      position: relative;
      background: url('assets/img/bg.jpg') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: left;
      padding: 0 20px;
    }
    header::before {
      content: "";
      position: absolute;
      top:0; left:0; right:0; bottom:0;
      background: rgba(0,0,0,0.6);
    }
    header .content {
      position: relative;
      z-index: 1;
      max-width: 700px;
    }
    header h1 {font-size: 48px; margin-bottom: 20px; font-weight: bold;}
    header p {font-size: 22px; margin-bottom: 30px;}
    header a {
      background: #f1c40f;
      color: #000;
      padding: 12px 25px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 6px;
    }
    nav {
      position: fixed;
      top: 0; left: 0;
      width: 100%;
      background: rgba(0,0,0,0.7);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 40px;
      z-index: 10;
    }
    nav .logo {font-size: 20px; font-weight: bold; color: #f1c40f;}
    nav ul {list-style: none; display: flex;}
    nav ul li {margin-left: 20px;}
    nav ul li a {color: #fff; text-decoration: none; font-size: 16px;}
    section {padding: 80px 40px; text-align: center;}
    section h2 {font-size: 32px; margin-bottom: 20px; color:#333;}
    section p {color: #555; font-size: 18px; max-width: 800px; margin: auto;}
    #projeler .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
      gap: 20px; margin-top: 30px;
    }
    .card {
      background: #fff;
      color: #333;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }
    .card img {width: 100%; height: 180px; object-fit: cover;}
    .card h3 {margin: 15px;}
    .card p {margin: 0 15px 15px;}
    footer {
      background: #222;
      color: #aaa;
      padding: 20px;
      text-align: center;
    }
    footer a {color: #f1c40f; text-decoration: none;}
  </style>
</head>
<body>

  <nav>
    <div class="logo">KAYA İNŞAAT</div>
    <ul>
      <li><a href="#hakkimizda">Hakkımızda</a></li>
      <li><a href="#projeler">Projeler</a></li>
      <li><a href="#iletisim">İletişim</a></li>
    </ul>
  </nav>

  <header>
    <div class="content">
      <h1>Hayalleriniz ve ihtiyaçlarınız için Antalya’nın uzmanı</h1>
      <p>Selman Kaya önderliğinde kaliteli tadilat & tamirat hizmetleri</p>
      <a href="#iletisim">İletişime Geçin</a>
    </div>
  </header>

  <section id="hakkimizda">
    <h2>Hakkımızda</h2>
    <p>Antalya’da 15 yılı aşkın deneyime sahip Kaya İnşaat, uzman Selman Kaya liderliğinde tadilat ve tamirat projelerinde güvenilir hizmet sunar. Müşteri memnuniyetini öncelik edinerek, modern çözümler ve kaliteli işçilikle yaşam alanlarınızı yenileriz.</p>
  </section>

  <section id="projeler">
    <h2>Projelerimiz</h2>
    <div class="cards">
      <div class="card">
        <img src="assets/img/mutfak.jpg" alt="Mutfak tadilatı">
        <h3>Mutfak Yenileme</h3>
        <p>Modern tasarımlarla mutfağınızı baştan yaratıyoruz.</p>
      </div>
      <div class="card">
        <img src="assets/img/banyo.jpg" alt="Banyo tadilatı">
        <h3>Banyo Tadilatı</h3>
        <p>Dayanıklı malzeme ve estetik görünüm ile konforlu banyolar.</p>
      </div>
      <div class="card">
        <img src="assets/img/villa.jpg" alt="Villa tadilatı">
        <h3>Villa & Daire</h3>
        <p>Tüm yaşam alanlarınız için kapsamlı tadilat çözümleri.</p>
      </div>
    </div>
  </section>

  <section id="iletisim">
    <h2>İletişim</h2>
    <p>Telefon: <a href="tel:+905555555555">+90 555 555 55 55</a></p>
    <p>WhatsApp: <a href="https://wa.me/905555555555">Hemen yazın</a></p>
    <p>E-posta: <a href="mailto:info@kaya-insaat.com">info@kaya-insaat.com</a></p>
  </section>

  <footer>
    © 2025 KAYA İNŞAAT — Antalya | <a href="#iletisim">İletişime Geç</a>
  </footer>

</body>
</html>
