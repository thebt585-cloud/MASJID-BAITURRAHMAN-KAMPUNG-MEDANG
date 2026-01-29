<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>Masjid Baiturrahman Kampung Medang</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  max-width:100%;
}
html,body{
  width:100%;
  overflow-x:hidden;
  font-family:Poppins,sans-serif;
  background:#f1f5f9;
  color:#1e293b;
  font-size:14px;
  scroll-behavior:smooth;
}

/* HEADER */
header{
  background:#0ea5e9;
  color:#fff;
  text-align:center;
  padding:14px 10px;
}
header h1{font-size:15px;line-height:1.3}
header p{font-size:12px;opacity:.9}

/* NAV */
nav{
  display:flex;
  overflow-x:auto;
  background:#fff;
  border-bottom:1px solid #e5e7eb;
}
nav::-webkit-scrollbar{display:none}
nav a{
  flex-shrink:0;
  padding:10px 12px;
  font-size:12px;
  text-decoration:none;
  color:#334155;
  white-space:nowrap;
}

/* CONTENT */
.container{padding:10px}

/* CARD */
.card{
  background:#fff;
  border-radius:10px;
  padding:12px;
  margin-bottom:10px;
  box-shadow:0 3px 8px rgba(0,0,0,.06);
}
.card h2{
  font-size:14px;
  color:#0284c7;
  margin-bottom:6px;
}
.card p{font-size:13px}

/* BADGE */
.badge{
  display:inline-block;
  font-size:11px;
  padding:3px 7px;
  border-radius:20px;
  background:#e0f2fe;
  color:#0369a1;
  margin:3px 3px 0 0;
}

/* LIST */
.list li{
  list-style:none;
  font-size:13px;
  padding:6px 0;
  border-bottom:1px dashed #e5e7eb;
}

/* BUTTON */
.btn{
  display:block;
  width:100%;
  margin-top:8px;
  padding:9px;
  text-align:center;
  background:#0ea5e9;
  color:#fff;
  text-decoration:none;
  font-size:13px;
  font-weight:600;
  border-radius:8px;
}

/* MAP */
.map{
  width:100%;
  height:210px;
  border:0;
  border-radius:8px;
  margin-top:8px;
}

/* FOOTER */
footer{
  text-align:center;
  font-size:11px;
  padding:14px 8px;
  color:#64748b;
}
</style>
</head>

<body>

<header>
  <h1>MASJID BAITURRAHMAN KAMPUNG MEDANG<br>Jalan Kp. Medang Kel. Medang Kec.Pagedangan</h1>
  <p>TANGERANG – BANTEN</p>
  <p>Pusat Ibadah & Edukasi Umat</p>
</header>

<nav>
  <a href="#beranda">Beranda</a>
  <a href="#profil">Profil</a>
  <a href="#jadwal">Jadwal</a>
  <a href="#kegiatan">Kegiatan</a>
  <a href="#donasi">Donasi</a>
  <a href="#kontak">Kontak</a>
</nav>

<div class="container">

<!-- BERANDA -->
<section id="beranda" class="card">
<h2>🏠 Beranda</h2>
<p>Masjid Baiturrahman adalah pusat ibadah dan kegiatan umat.</p>

<p style="margin-top:6px"><b>🕒 Jadwal Sholat Hari Ini</b></p>
<div id="sholat"></div>

<a href="#donasi" class="btn">💖 Donasi / Infaq</a>
</section>

<!-- PROFIL -->
<section id="profil" class="card">
<h2>🕌 Profil Masjid</h2>
<p>Berdiri sejak 2010 sebagai pusat ibadah warga Kampung Medang.</p>

<ul class="list">
<li>Ketua DKM: H. Baehaqi</li>
<li>Sekretaris: Pak Piat</li>
<li>Bendahara: Pak Basri</li>
</ul>

<iframe
  class="map"
  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.287826019407!2d106.6396624!3d-6.2762826!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69fb8f08b2a1b5%3A0x9d8d9d2f1e4d9c4a!2sMasjid%20Baiturrahman!5e0!3m2!1sid!2sid!4v1700000000000"
  loading="lazy">
</iframe>

<a class="btn" target="_blank"
href="https://www.google.com/maps/search/?api=1&query=Masjid+Baiturrahman+Kampung+Medang">
📍 Buka di Google Maps
</a>
</section>

<!-- KEGIATAN -->
<section id="kegiatan" class="card">
<h2>📌 Kegiatan</h2>
<ul class="list">
<li>Kajian Rutin</li>
<li>TPA Anak</li>
<li>Pengajian Ibu-ibu</li>
<li>Bakti Sosial</li>
</ul>
</section>

<!-- DONASI -->
<section id="donasi" class="card">
<h2>💰 Donasi</h2>
<p>Rekening Masjid: <b>BSI 123456789</b></p>
<p>QRIS: (Tambahkan gambar)</p>
</section>

<!-- KONTAK -->
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

<!-- JADWAL SHOLAT OTOMATIS ONLINE -->
<script>
fetch("https://api.aladhan.com/v1/timingsByCity?city=Tangerang&country=Indonesia&method=11")
.then(res=>res.json())
.then(data=>{
  const t=data.data.timings;
  document.getElementById("sholat").innerHTML=`
    <span class="badge">Subuh ${t.Fajr}</span>
    <span class="badge">Dzuhur ${t.Dhuhr}</span>
    <span class="badge">Ashar ${t.Asr}</span>
    <span class="badge">Maghrib ${t.Maghrib}</span>
    <span class="badge">Isya ${t.Isha}</span>
  `;
})
.catch(()=>{
  document.getElementById("sholat").innerHTML="<small>Gagal memuat jadwal sholat</small>";
});
</script>

</body>
</html>
