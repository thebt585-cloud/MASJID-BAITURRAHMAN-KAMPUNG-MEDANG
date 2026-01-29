<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>Masjid Baiturrahman Kampung Medang</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
:root{
  --primary:#0ea5e9;
  --dark:#0f172a;
  --light:#f8fafc;
}

*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

body{
  font-family:Poppins,sans-serif;
  background:#f1f5f9;
  color:#1e293b;
  font-size:14px;
  line-height:1.6;
}

/* HEADER */
header{
  background:linear-gradient(135deg,var(--primary),#38bdf8);
  color:#fff;
  padding:16px 12px;
  text-align:center;
}
header h1{
  font-size:16px;
  line-height:1.3;
}
header p{
  font-size:12px;
  opacity:.9;
}

/* NAV */
nav{
  display:flex;
  overflow-x:auto;
  background:#fff;
  border-bottom:1px solid #e5e7eb;
}
nav a{
  flex:0 0 auto;
  padding:10px 14px;
  font-size:12px;
  text-decoration:none;
  color:#334155;
  white-space:nowrap;
}
nav a:hover{
  background:#e0f2fe;
  color:#0284c7;
}

/* CONTENT */
.container{
  padding:12px;
}

.card{
  background:#fff;
  border-radius:12px;
  padding:14px;
  margin-bottom:12px;
  box-shadow:0 4px 12px rgba(0,0,0,.06);
}

.card h2{
  font-size:14px;
  margin-bottom:8px;
  color:#0284c7;
}

/* BADGE */
.badge{
  display:inline-block;
  background:#e0f2fe;
  color:#0369a1;
  padding:3px 8px;
  border-radius:999px;
  font-size:11px;
  margin:4px 4px 0 0;
}

/* BUTTON */
.btn{
  display:block;
  width:100%;
  text-align:center;
  background:var(--primary);
  color:#fff;
  padding:10px;
  border-radius:10px;
  text-decoration:none;
  font-weight:600;
  font-size:13px;
  margin-top:10px;
}

/* LIST */
.list li{
  list-style:none;
  padding:6px 0;
  border-bottom:1px dashed #e5e7eb;
  font-size:13px;
}

/* MAP */
iframe{
  width:100%;
  height:220px;
  border:0;
  border-radius:10px;
  margin-top:10px;
}

/* FOOTER */
footer{
  text-align:center;
  font-size:11px;
  padding:16px;
  color:#64748b;
}
</style>
</head>

<body>

<header>
  <h1>MASJID BAITURRAHMAN<br>KAMPUNG MEDANG</h1>
  <p>Pusat Ibadah & Edukasi Umat</p>
  <p>Jl. Kampung Medang, Pagedangan</p>
  <p>Tangerang – Banten</p>
</header>

<nav>
  <a href="#beranda">Beranda</a>
  <a href="#profil">Profil</a>
  <a href="#jadwal">Jadwal</a>
  <a href="#kegiatan">Kegiatan</a>
  <a href="#artikel">Artikel</a>
  <a href="#donasi">Donasi</a>
  <a href="#galeri">Galeri</a>
  <a href="#layanan">Layanan</a>
  <a href="#kontak">Kontak</a>
</nav>

<div class="container">

<section id="beranda" class="card">
<h2>🏠 Beranda</h2>
<p><b>Profil Singkat:</b> Masjid Baiturrahman sebagai pusat ibadah, dakwah, dan sosial umat.</p>

<p><b>🕒 Jadwal Sholat</b></p>
<div class="badge">Subuh 04.30</div>
<div class="badge">Dzuhur 12.00</div>
<div class="badge">Ashar 15.20</div>
<div class="badge">Maghrib 18.00</div>
<div class="badge">Isya 19.10</div>

<p style="margin-top:8px;font-size:12px">
<i>“Sebaik-baik manusia adalah yang paling bermanfaat.”</i>
</p>

<a href="#donasi" class="btn">💖 Donasi / Infaq</a>
</section>

<section id="profil" class="card">
<h2>🕌 Profil Masjid</h2>
<p><b>Sejarah:</b> Berdiri tahun 2010.</p>
<p><b>Visi:</b> Masjid makmur & umat berilmu.</p>

<ul class="list">
<li>Ketua DKM: H. Baehaqi</li>
<li>Sekretaris: Pak Piat</li>
<li>Bendahara: Pak Basri</li>
</ul>

<iframe src="https://maps.google.com/maps?q=masjid%20baiturrahman%20kampung%20medang&t=&z=15&output=embed"></iframe>
</section>

<section id="jadwal" class="card">
<h2>📅 Jadwal</h2>
<ul class="list">
<li>Imam Subuh: Ust. Sarmurdi</li>
<li>Muadzin: Pak Wawan</li>
<li>Sholat Jumat: 12.15 WIB</li>
</ul>
</section>

<section id="kegiatan" class="card">
<h2>📌 Kegiatan</h2>
<ul class="list">
<li>Kajian Rutin</li>
<li>TPA Anak</li>
<li>Pengajian Ibu-ibu</li>
<li>Bakti Sosial</li>
</ul>
</section>

<section id="donasi" class="card">
<h2>💰 Donasi</h2>
<p>Rekening: <b>BSI 123456789</b></p>
<p>QRIS: (Tambahkan gambar)</p>
</section>

<section id="kontak" class="card">
<h2>📱 Kontak</h2>
<p>WhatsApp: 0852427273511</p>
<p>Instagram: Masjid Baiturrahman</p>
<p>YouTube: Masjid Baiturrahman</p>
</section>

</div>

<footer>
© 2026 Masjid Baiturrahman Kampung Medang
</footer>

</body>
</html>
