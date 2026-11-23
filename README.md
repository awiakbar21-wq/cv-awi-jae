# cv-awi-jae
Website CV Profesional Awi Akbar Jaelani

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV | Awi Akbar Jaelani</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #f3f6fc;
  color: #202b3c;
  line-height: 1.7;
}

header {
  background: #101d35;
  color: white;
  padding: 18px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  z-index: 10;
}

.logo {
  font-size: 22px;
  font-weight: bold;
  color: #55b5ff;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 22px;
  font-size: 14px;
}

nav a:hover {
  color: #55b5ff;
}

.hero {
  min-height: 490px;
  background: linear-gradient(120deg,#101d35,#174b79);
  color: white;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 70px 10%;
  flex-wrap: wrap;
  gap: 30px;
}

.hero-text {
  max-width: 570px;
}

.hero h1 {
  font-size: 42px;
  margin: 12px 0;
}

.hero h1 span {
  color: #55b5ff;
}

.hero p {
  color: #d5e5f5;
}

.tag {
  color: #55b5ff;
  font-weight: bold;
  letter-spacing: 2px;
}

.profile {
  width: 210px;
  height: 210px;
  border-radius: 50%;
  border: 5px solid #55b5ff;
  object-fit: cover;
  background: #dce8f5;
}

.btn {
  display: inline-block;
  margin-top: 25px;
  padding: 12px 24px;
  border-radius: 8px;
  background: #55b5ff;
  color: #101d35;
  text-decoration: none;
  font-weight: bold;
  transition: .3s;
}

.btn:hover {
  background: white;
  transform: translateY(-3px);
}

section {
  padding: 65px 10%;
}

.section-title {
  text-align: center;
  font-size: 29px;
  color: #142b4c;
  margin-bottom: 35px;
}

.card {
  background: white;
  padding: 28px;
  border-radius: 14px;
  box-shadow: 0 5px 20px rgba(0,0,0,.06);
  margin-bottom: 20px;
}

.card h3 {
  color: #174b79;
  margin-bottom: 12px;
}

.info {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 15px;
}

.info p {
  padding: 12px;
  background: #f3f6fc;
  border-radius: 8px;
}

.skills {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.skills span {
  background: #e2f1ff;
  color: #14548b;
  padding: 10px 17px;
  border-radius: 20px;
  font-weight: bold;
  font-size: 14px;
}

.contact {
  text-align: center;
  background: #101d35;
  color: white;
}

.contact .section-title {
  color: white;
}

.contact p {
  margin: 10px;
}

footer {
  text-align: center;
  padding: 20px;
  background: #091326;
  color: #aebbd0;
  font-size: 13px;
}

@media(max-width:700px) {
  header {
    flex-direction: column;
    gap: 12px;
  }

  nav a {
    margin: 0 6px;
    font-size: 12px;
  }

  .hero {
    text-align: center;
    justify-content: center;
    padding: 55px 7%;
  }

  .hero h1 {
    font-size: 32px;
  }

  .profile {
    width: 170px;
    height: 170px;
  }

  .info {
    grid-template-columns: 1fr;
  }

  section {
    padding: 50px 7%;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">AWI JAELANI.</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">Profil</a>
    <a href="#education">Pendidikan</a>
    <a href="#skills">Keahlian</a>
    <a href="#contact">Kontak</a>
  </nav>
</header>

<div class="hero" id="home">
  <div class="hero-text">
    <div class="tag">PERSONAL CURRICULUM VITAE</div>
    <h1>Halo, Saya <span>Awi Akbar Jaelani</span></h1>
    <p>
      Siswa Teknik Komputer dan Jaringan (TKJ)
      yang memiliki minat dalam dunia teknologi,
      komputer, jaringan, dan pengembangan digital.
    </p>
    <a href="#about" class="btn">Lihat Profil Saya</a>
  </div>

  <!-- Ganti URL FOTO dengan foto pribadi -->
  <img class="profile"
  src="https://placehold.co/400x400/174b79/ffffff?text=FOTO+AWI"
  alt="Foto Awi Akbar Jaelani">
</div>

<section id="about">
  <h2 class="section-title">Tentang Saya</h2>
  <div class="card">
    <h3>Profil Pribadi</h3>
    <p>
      Saya adalah seorang pelajar SMK Karya Guna 2 Bekasi
      jurusan Teknik Komputer dan Jaringan. Saya tertarik
      mempelajari teknologi informasi, perangkat komputer,
      serta sistem jaringan komputer.
    </p>
    <br>
    <div class="info">
      <p><b>Nama:</b> Awi Akbar Jaelani</p>
      <p><b>Tempat Lahir:</b> Bekasi</p>
      <p><b>Tanggal Lahir:</b> 6 Mei 2009</p>
      <p><b>Alamat:</b> Desa Kanayakan, Bojongmangu, Bekasi</p>
      <p><b>Telepon:</b> 085779255089</p>
      <p><b>Email:</b> barjae06@gmail.com</p>
    </div>
  </div>
</section>

<section id="education">
  <h2 class="section-title">Pendidikan</h2>
  <div class="card">
    <h3>SMK Karya Guna 2 Bekasi</h3>
    <p>Jurusan: Teknik Komputer dan Jaringan (TKJ)</p>
    <p>Jenjang: Sekolah Menengah Kejuruan</p>
  </div>
</section>

<section id="skills">
  <h2 class="section-title">Keahlian</h2>
  <div class="card">
    <div class="skills">
      <span>Komputer Dasar</span>
      <span>Microsoft Office</span>
      <span>Jaringan Komputer</span>
      <span>Instalasi Sistem Operasi</span>
      <span>HTML & CSS</span>
      <span>Troubleshooting Dasar</span>
    </div>
  </div>
</section>

<section>
  <h2 class="section-title">Tujuan Karier</h2>
  <div class="card">
    <p>
      Saya ingin terus mengembangkan kemampuan di bidang
      teknologi informasi, khususnya jaringan komputer
      dan pengembangan website, serta mendapatkan pengalaman
      baru untuk mempersiapkan diri memasuki dunia kerja.
    </p>
  </div>
</section>

<section class="contact" id="contact">
  <h2 class="section-title">Hubungi Saya</h2>
  <p>Email: barjae06@gmail.com</p>
  <p>Telepon: 085779255089</p>
  <a class="btn"
  href="https://wa.me/6285779255089">
  Hubungi via WhatsApp
  </a>
</section>

<footer>
  © 2026 Awi Akbar Jaelani | Personal CV Website
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Portofolio dan Curriculum Vitae Awi Akbar Jaelani, siswa Teknik Komputer dan Jaringan.">
<title>Awi Akbar Jaelani | Personal Portfolio</title>

<style>
:root {
  --bg: #0b1425;
  --panel: #121f35;
  --blue: #39a9ff;
  --white: #f5f8ff;
  --muted: #a9b8ce;
  --border: rgba(255,255,255,.09);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: var(--bg);
  color: var(--white);
  line-height: 1.7;
}

a {
  text-decoration: none;
  color: inherit;
}

header {
  height: 75px;
  padding: 0 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: rgba(11,20,37,.94);
  border-bottom: 1px solid var(--border);
  position: sticky;
  top: 0;
  z-index: 100;
  backdrop-filter: blur(15px);
}

.logo {
  font-size: 22px;
  font-weight: 800;
  color: var(--blue);
}

nav {
  display: flex;
  gap: 27px;
  align-items: center;
}

nav a {
  font-size: 14px;
  color: var(--muted);
  transition: .3s;
}

nav a:hover,
nav a.active {
  color: var(--blue);
}

.menu-btn {
  display: none;
  background: none;
  color: white;
  border: 0;
  font-size: 27px;
  cursor: pointer;
}

.hero {
  min-height: 650px;
  padding: 90px 10%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 55px;
  background:
    radial-gradient(circle at 85% 35%, #173f67 0, transparent 35%),
    linear-gradient(120deg,#0b1425,#102440);
}

.hero-content {
  max-width: 650px;
}

.eyebrow {
  color: var(--blue);
  font-size: 13px;
  font-weight: bold;
  letter-spacing: 3px;
}

.hero h1 {
  font-size: clamp(36px,5vw,58px);
  line-height: 1.2;
  margin: 20px 0;
}

.hero h1 span {
  color: var(--blue);
}

.hero p {
  color: var(--muted);
  max-width: 560px;
}

.hero-buttons {
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
  margin-top: 30px;
}

.btn {
  display: inline-block;
  padding: 12px 23px;
  border-radius: 8px;
  font-weight: bold;
  font-size: 14px;
  transition: .3s;
  cursor: pointer;
  border: 1px solid var(--blue);
}

.btn-primary {
  background: var(--blue);
  color: #071629;
}

.btn-outline {
  color: var(--blue);
}

.btn:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 25px rgba(57,169,255,.2);
}

.photo-wrap {
  flex-shrink: 0;
  padding: 9px;
  border-radius: 50%;
  border: 2px solid var(--blue);
  box-shadow: 0 0 45px rgba(57,169,255,.2);
}

.profile {
  width: 240px;
  height: 240px;
  border-radius: 50%;
  object-fit: cover;
  background: var(--panel);
}

section {
  padding: 90px 10%;
  scroll-margin-top: 75px;
}

.section-heading {
  margin-bottom: 38px;
}

.section-heading small {
  color: var(--blue);
  letter-spacing: 3px;
  font-weight: bold;
}

.section-heading h2 {
  font-size: 32px;
  margin-top: 8px;
}

.section-heading p {
  color: var(--muted);
}

.grid {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 22px;
}

.card {
  background: var(--panel);
  border: 1px solid var(--border);
  border-radius: 15px;
  padding: 27px;
  transition: .3s;
}

.card:hover {
  transform: translateY(-5px);
  border-color: var(--blue);
}

.card h3 {
  margin-bottom: 13px;
  color: var(--blue);
}

.card p {
  color: var(--muted);
  font-size: 14px;
}

.info-row {
  display: flex;
  justify-content: space-between;
  gap: 12px;
  border-bottom: 1px solid var(--border);
  padding: 11px 0;
  font-size: 14px;
}

.info-row span:first-child {
  color: var(--muted);
}

.info-row span:last-child {
  text-align: right;
}

.education-card {
  border-left: 4px solid var(--blue);
}

.education-card .year {
  color: var(--blue);
  font-size: 13px;
  font-weight: bold;
}

.skills {
  display: flex;
  flex-wrap: wrap;
  gap: 13px;
}

.skill {
  background: #193657;
  border: 1px solid rgba(57,169,255,.25);
  padding: 12px 18px;
  border-radius: 9px;
  color: #cdeaff;
  font-size: 14px;
}

.project-icon {
  font-size: 34px;
  margin-bottom: 15px;
}

.project-label {
  color: var(--blue);
  font-size: 11px;
  letter-spacing: 1px;
  font-weight: bold;
  margin-bottom: 8px;
}

.contact {
  text-align: center;
  background: linear-gradient(130deg,#102440,#0b1425);
}

.contact .section-heading {
  margin-bottom: 15px;
}

.contact p {
  color: var(--muted);
}

.contact .btn {
  margin-top: 25px;
}

footer {
  padding: 25px 10%;
  text-align: center;
  color: var(--muted);
  font-size: 13px;
  border-top: 1px solid var(--border);
}

.back-top {
  position: fixed;
  bottom: 25px;
  right: 25px;
  background: var(--blue);
  color: #071629;
  border: 0;
  border-radius: 50%;
  width: 45px;
  height: 45px;
  font-size: 21px;
  cursor: pointer;
  display: none;
  z-index: 50;
}

.back-top.show {
  display: block;
}

.reveal {
  opacity: 0;
  transform: translateY(25px);
  transition: opacity .7s, transform .7s;
}

.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}

@media(max-width:800px) {
  header {
    padding: 0 6%;
  }

  .menu-btn {
    display: block;
  }

  nav {
    display: none;
    position: absolute;
    top: 75px;
    left: 0;
    width: 100%;
    background: #101d35;
    padding: 20px;
    flex-direction: column;
    gap: 18px;
    border-bottom: 1px solid var(--border);
  }

  nav.open {
    display: flex;
  }

  .hero {
    flex-direction: column-reverse;
    text-align: center;
    padding: 65px 7%;
  }

  .hero-buttons {
    justify-content: center;
  }

  .profile {
    width: 185px;
    height: 185px;
  }

  .grid {
    grid-template-columns: 1fr;
  }

  section {
    padding: 65px 7%;
  }

  .section-heading h2 {
    font-size: 27px;
  }
}

@media print {
  body {
    background: white;
    color: #17253b;
  }

  header, .hero-buttons, .back-top, .contact, footer {
    display: none !important;
  }

  .hero {
    min-height: auto;
    background: white;
    color: #17253b;
    padding: 25px;
  }

  .hero p, .card p, .section-heading p {
    color: #333;
  }

  section {
    padding: 20px;
  }

  .card {
    background: white;
    border: 1px solid #ccc;
    color: #17253b;
    break-inside: avoid;
  }

  .card h3 {
    color: #174b79;
  }

  .reveal {
    opacity: 1;
    transform: none;
  }

  .photo-wrap {
    box-shadow: none;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">AWI JAELANI.</div>

  <button class="menu-btn" id="menuBtn"
  aria-label="Buka menu">☰</button>

  <nav id="nav">
    <a href="#home" class="active">Home</a>
    <a href="#about">Profil</a>
    <a href="#education">Pendidikan</a>
    <a href="#skills">Keahlian</a>
    <a href="#projects">Proyek</a>
    <a href="#contact">Kontak</a>
  </nav>
</header>

<main>

<div class="hero" id="home">
  <div class="hero-content reveal">
    <div class="eyebrow">PERSONAL PORTFOLIO & CV</div>

    <h1>Halo, Saya <span>Awi Akbar Jaelani</span></h1>

    <p>
      Pelajar Teknik Komputer dan Jaringan (TKJ)
      yang tertarik pada teknologi informasi,
      jaringan komputer, dan pengembangan website.
      Saya terus belajar dan mengembangkan kemampuan
      untuk masa depan.
    </p>

    <div class="hero-buttons">
      <a href="#about" class="btn btn-primary">
        Lihat Profil
      </a>

      <button class="btn btn-outline"
      onclick="window.print()">
        Simpan CV PDF
      </button>
    </div>
  </div>

  <div class="photo-wrap reveal">
    <!-- GANTI URL INI DENGAN FOTO PROFIL -->
    <img class="profile"
    src="https://placehold.co/400x400/173f67/ffffff?text=AWI"
    alt="Foto profil Awi Akbar Jaelani">
  </div>
</div>

<section id="about">
  <div class="section-heading reveal">
    <small>01 — ABOUT ME</small>
    <h2>Tentang Saya</h2>
    <p>Kenali profil dan informasi pribadi saya.</p>
  </div>

  <div class="grid">
    <div class="card reveal">
      <h3>Profil Pribadi</h3>
      <p>
        Saya merupakan siswa SMK Karya Guna 2 Bekasi
        jurusan Teknik Komputer dan Jaringan.
        Saya memiliki ketertarikan dalam dunia
        teknologi dan ingin terus meningkatkan
        kemampuan di bidang komputer.
      </p>
    </div>

    <div class="card reveal">
      <h3>Informasi Pribadi</h3>

      <div class="info-row">
        <span>Nama</span>
        <span>Awi Akbar Jaelani</span>
      </div>

      <div class="info-row">
        <span>Tempat Lahir</span>
        <span>Bekasi</span>
      </div>

      <div class="info-row">
        <span>Tanggal Lahir</span>
        <span>6 Mei 2009</span>
      </div>

      <div class="info-row">
        <span>Domisili</span>
        <span>Bekasi, Jawa Barat</span>
      </div>

      <div class="info-row">
        <span>Jurusan</span>
        <span>TKJ</span>
      </div>
    </div>
  </div>
</section>

<section id="education">
  <div class="section-heading reveal">
    <small>02 — EDUCATION</small>
    <h2>Riwayat Pendidikan</h2>
    <p>Perjalanan pendidikan saya.</p>
  </div>

  <div class="card education-card reveal">
    <div class="year">PENDIDIKAN SAAT INI</div>
    <h3>SMK Karya Guna 2 Bekasi</h3>
    <p>
      Jurusan Teknik Komputer dan Jaringan (TKJ).
      Mempelajari dasar komputer, sistem jaringan,
      perangkat keras, serta teknologi informasi.
    </p>
  </div>
</section>

<section id="skills">
  <div class="section-heading reveal">
    <small>03 — MY SKILLS</small>
    <h2>Keahlian Saya</h2>
    <p>Bidang yang sedang saya pelajari dan kembangkan.</p>
  </div>

  <div class="card reveal">
    <div class="skills">
      <div class="skill">Komputer Dasar</div>
      <div class="skill">Microsoft Office</div>
      <div class="skill">Jaringan Komputer</div>
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">Instalasi Sistem Operasi</div>
      <div class="skill">Troubleshooting Dasar</div>
      <div class="skill">Konfigurasi Jaringan Dasar</div>
    </div>
  </div>
</section>

<section id="projects">
  <div class="section-heading reveal">
    <small>04 — MY PROJECTS</small>
    <h2>Proyek Pembelajaran</h2>
    <p>Contoh bidang proyek yang berkaitan dengan pembelajaran TKJ.</p>
  </div>

  <div class="grid">

    <div class="card reveal">
      <div class="project-icon">🌐</div>
      <div class="project-label">WEB DEVELOPMENT</div>
      <h3>Website CV Pribadi</h3>
      <p>
        Pengembangan website portofolio pribadi
        menggunakan HTML dan CSS sebagai media
        untuk memperkenalkan profil diri.
      </p>
    </div>

    <div class="card reveal">
      <div class="project-icon">🖥️</div>
      <div class="project-label">COMPUTER NETWORKING</div>
      <h3>Pembelajaran Jaringan</h3>
      <p>
        Mempelajari konfigurasi jaringan komputer,
        pengalamatan IP, gateway, dan dasar
        administrasi perangkat jaringan.
      </p>
    </div>

  </div>
</section>

<section>
  <div class="section-heading reveal">
    <small>05 — CAREER GOALS</small>
    <h2>Tujuan Karier</h2>
  </div>

  <div class="card reveal">
    <p>
      Saya ingin terus mengembangkan kemampuan
      dalam bidang teknologi informasi, terutama
      jaringan komputer dan pengembangan website.
      Saya juga ingin mendapatkan pengalaman,
      pengetahuan, dan keterampilan baru untuk
      mempersiapkan diri menghadapi dunia kerja.
    </p>
  </div>
</section>

<section class="contact" id="contact">
  <div class="section-heading reveal">
    <small>06 — CONTACT</small>
    <h2>Mari Terhubung</h2>
    <p>
      Terima kasih telah mengunjungi website
      portofolio saya.
    </p>
  </div>

  <a class="btn btn-primary"
  href="mailto:barjae06@gmail.com">
    ✉ Hubungi Melalui Email
  </a>
</section>

</main>

<footer>
  © 2026 Awi Akbar Jaelani.
  Personal Portfolio Website.
</footer>

<button class="back-top" id="backTop"
aria-label="Kembali ke atas">↑</button>

<script>
const menuBtn = document.getElementById("menuBtn");
const nav = document.getElementById("nav");

menuBtn.addEventListener("click", () => {
  nav.classList.toggle("open");
  menuBtn.textContent =
    nav.classList.contains("open") ? "×" : "☰";
});

document.querySelectorAll("nav a").forEach(link => {
  link.addEventListener("click", () => {
    nav.classList.remove("open");
    menuBtn.textContent = "☰";
  });
});

// Animasi saat halaman digulir
const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add("visible");
    }
  });
}, { threshold: 0.12 });

document.querySelectorAll(".reveal").forEach(el => {
  observer.observe(el);
});

// Tombol kembali ke atas
const backTop = document.getElementById("backTop");

window.addEventListener("scroll", () => {
  backTop.classList.toggle("show", window.scrollY > 400);

  let current = "";

  document.querySelectorAll("main section, .hero").forEach(section => {
    if (window.scrollY >= section.offsetTop - 120) {
      current = section.id;
    }
  });

  document.querySelectorAll("nav a").forEach(link => {
    link.classList.toggle(
      "active",
      link.getAttribute("href") === "#" + current
    );
  });
});

backTop.addEventListener("click", () => {
  window.scrollTo({ top: 0, behavior: "smooth" });
});
</script>

</body>
</html>
