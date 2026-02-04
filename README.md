<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portofolio | Taufiq Hidayatullah</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <style>
    * {box-sizing: border-box; margin: 0; padding: 0}
    body {font-family: 'Poppins', sans-serif; background: #f4f6f8; color: #333; line-height: 1.6}
    a {text-decoration: none}

    header {
      background: linear-gradient(135deg, #1f3c68, #274c9c);
      color: #fff;
      padding: 80px 20px;
      text-align: center;
    }
    header h1 {font-size: 42px; margin-bottom: 10px}
    header p {font-size: 18px; opacity: 0.9}

    section {max-width: 1100px; margin: auto; padding: 60px 20px}
    h2 {font-size: 28px; color: #1f3c68; margin-bottom: 30px; text-align: center}

    .about {max-width: 800px; margin: auto; text-align: center}

    .grid {display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 25px}
    .card {
      background: #fff;
      padding: 25px;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
      transition: transform .3s, box-shadow .3s;
    }
    .card:hover {transform: translateY(-8px); box-shadow: 0 20px 40px rgba(0,0,0,0.12)}

    .card h3 {color: #274c9c; margin-bottom: 8px}
    .date {font-size: 14px; color: #777; margin-bottom: 10px}

    ul {padding-left: 20px}

    .skills span {
      display: inline-block;
      margin: 6px;
      padding: 10px 16px;
      border-radius: 30px;
      background: linear-gradient(135deg, #1f3c68, #274c9c);
      color: #fff;
      font-size: 14px;
    }

    .contact {
      background: linear-gradient(135deg, #1f3c68, #274c9c);
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }
    .contact p {font-size: 18px; margin: 8px 0}

    footer {
      background: #0f1f38;
      color: #aaa;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <h1>Taufiq Hidayatullah</h1>
  <p>Sales • Marketing • Media Sosial • Manajemen Tim</p>
</header>

<section>
  <h2>Tentang Saya</h2>
  <div class="about">
    <p>Saya adalah profesional muda dengan pengalaman di bidang penjualan, pemasaran, dan operasional, khususnya di industri otomotif dan logistik. Terbiasa bekerja dengan target, memimpin tim, serta membangun strategi pemasaran konvensional maupun digital.</p>
  </div>
</section>

<section>
  <h2>Pengalaman Kerja</h2>
  <div class="grid">
    <div class="card">
      <h3>Kepala Pos Penjualan – Yamaha NEQ Sidayu</h3>
      <div class="date">April 2025 – November 2025</div>
      <ul>
        <li>Mengelola seluruh operasional pos penjualan</li>
        <li>Memimpin dan membina tim sales</li>
        <li>Menyusun strategi penjualan dan pencapaian target</li>
        <li>Pengawasan stok, transaksi, dan pelayanan pelanggan</li>
      </ul>
    </div>

    <div class="card">
      <h3>Sales & Marketing – Yamaha Motor</h3>
      <div class="date">September 2023 – Maret 2025</div>
      <ul>
        <li>Penjualan unit motor Yamaha</li>
        <li>Promosi konvensional dan digital</li>
        <li>Pemasaran melalui media sosial</li>
      </ul>
    </div>

    <div class="card">
      <h3>Staff Processing – J&T Cargo</h3>
      <div class="date">Juni 2022 – Juli 2023</div>
      <ul>
        <li>Monitoring proses loading paket</li>
        <li>Validasi dan pengolahan data</li>
        <li>Koordinasi dengan gudang</li>
      </ul>
    </div>
  </div>
</section>

<section>
  <h2>Pendidikan</h2>
  <div class="grid">
    <div class="card">
      <h3>SMKN 2 Surabaya</h3>
      <div class="date">Teknik Otomotif | 2019 – 2022</div>
    </div>
    <div class="card">
      <h3>Honda Class Education</h3>
      <div class="date">2021 – 2022</div>
    </div>
  </div>
</section>

<section>
  <h2>Keahlian</h2>
  <div class="card skills" style="text-align:center">
    <span>Sales & Marketing</span>
    <span>Manajemen Tim</span>
    <span>Media Sosial</span>
    <span>Public Speaking</span>
    <span>Microsoft Office</span>
    <span>Fotografi</span>
    <span>Videografi</span>
    <span>Editing Video</span>
  </div>
</section>

<section class="contact">
  <h2 style="color:#fff">Kontak</h2>
  <p>📞 0819-1041-8032</p>
  <p>✉️ tigaserangakai@gmail.com</p>
</section>

<footer>
  <p>© 2026 Taufiq Hidayatullah • Portfolio Website</p>
</footer>

</body>
</html>
