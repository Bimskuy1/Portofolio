<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portfolio Bimma</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

</head>
<body>
  <header>
    <nav>
      <div class="logo">Portofolio</div>
      <ul class="nav-links">
        <li><a class="active" href="#">Home</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main class="hero">
    <div class="text-section">
      <h1>Hi, I'm <span class="typing"></span></h1>
      <p>
        Saya seorang mahasiswa <strong> Ahli di bidang Blogger dan frontend developer </strong>, mampu bekerja dengan tim.
      </p>
      <div class="social-icons">
        <a href="https://www.instagram.com/makarimrs?igsh=MTZicDk2Y3hsenRtcg==" target="_blank">
          <img src="ig.png" alt="Instagram" />
        </a>
        <a href="https://youtube.com/@bimmawahyu8775?si=DdG55jWVXxbzVzx7_" target="_blank">
          <img src="youtube.png" alt="YouTube" />
        </a>
        <a href="www.linkedin.com/in/bimma-wahyu-makarim-2259292ba" target="_blank">
          <img src="linkedin.png" alt="LinkedIn" />
        </a>
      </div>

      <div class="buttons">
        <a href="https://wa.me/qr/SDE5WQCSOUJ6C1" target="_blank" class="btn">Kontak</a>
        <a href="CV-Bimma Wahyu Makarim.pdf" download class="btn outline">Download CV</a>
      </div>


<div class="image-section">
  <div class="profile-pic-container">
    <!-- Foto Profil -->
    <img src="Gua.jpg" alt="Profile" class="profile-img" />

    <!-- Icon Skill -->
    <div class="skill-icons">
      <img src="figma.png" alt="Figma" class="icon float-figma" />
      <img src="sql.png" alt="SQL" class="icon float-sql" />
    </div>
  </div>
</div>

<style>
  .profile-pic-container {
    position: relative;
    width: 200px;
    height: 200px;
    margin: auto;
  }

  .profile-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
  }

  .skill-icons {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    overflow: visible;
  }

  .skill-icons img.icon {
    position: absolute;
    width: 40px;
    height: 40px;
    object-fit: contain;
    background: transparent;
    border: none;
    padding: 0;
  }

  /* Posisi icon sekeliling profil */
  .float-js    { top: -70px; left: 90%; transform: translateX(-50%); }
  .float-figma { top: 70%; left: 320px; transform: translateY(-50%); }
  .float-php   { bottom: -50px; left: 70%; transform: translateX(-50%); }
  .float-sql   { top: 30%; left: 0px; transform: translateY(-50%); }

  /* Animasi Floating Dinamis */
  @keyframes floatCrazy {
    0%   { transform: translate(0, 0) rotate(0deg); }
    25%  { transform: translate(3px, -5px) rotate(5deg); }
    50%  { transform: translate(-3px, -3px) rotate(-5deg); }
    75%  { transform: translate(-2px, 3px) rotate(3deg); }
    100% { transform: translate(0, 0) rotate(0deg); }
  }

  .float-js    { animation: floatCrazy 3s ease-in-out infinite; }
  .float-figma { animation: floatCrazy 4s ease-in-out infinite; }
  .float-php   { animation: floatCrazy 3.5s ease-in-out infinite; }
  .float-sql   { animation: floatCrazy 4.2s ease-in-out infinite; }
</style>

    </div>
  </main>

  <!-- EXPERIENCE SECTION -->
  <section id="experience" class="experience-section">
    <h2>My <span>Experience</span></h2>
    <p class="description">
      Sebagai mahasiswa aktif yang mengikuti banyak organisasi, <br>
       saya terus mengembangkan kemampuan diri melalui kolaborasi, pengalaman lapangan, dan tanggung jawab kepemimpinan.
    </p>

    <div class="experience-cards">
      <!-- Card 1 -->
      <div class="card">
        <div class="icon blue">💻</div>
        <h3>Himpunan Mahasiswa</h3>
        <p class="company">Divisi Sumber Daya Manusia</p>
        <p class="info">2023 - Present • Informatika • <span class="badge">Anggota</span></p>
        <p >Bertanggung jawab dalam mengatur mengelola seluruh hal yang berkaitan dengan calon Anggota, mulai dari perekrutan, pelatihan, pengembangan, hingga pengelolaan hubungan kerja..</p>
        <div class="tech">
        </div>
        <ul class="Kegiatan Besar">
          <li>✅ Kaderisasi calon anggota Himpunan Informatika 2024</li>
          <li>✅ Funday Informatika 2024</li>
          <li>✅ Hima Goes To School ke SMKN 7 Bandar Lampung</li>
          <li>✅ Malam Keakraban Hima Informatika 2023</li>
          <li>✅ LDK "Latihan Dasar kepemimpinan" Hima Informatika 2024</li>
        </ul>
      </div>

      <!-- Card 2 -->
      <div class="card highlight">
        <div class="icon blue">💼</div>
        <h3>Badan Eksekutif Mahasiswa</h3>
        <p class="info">2025 - Present • FTIK • <span class="badge">Ketua Umum</span></p>
        <p>Mengelola dan melaksanakan program kerja BEM FTIK yang berfokus pada aspirasi mahasiswa, edukasi, dan kegiatan sosial. Aktif berkolaborasi dengan organisasi kampus / Himpunan Mahasiswa serta pihak eksternal untuk menciptakan lingkungan kampus yang progresif.</p>
        <div class="tech">
        </div>
                <ul class="achievements">
          <li>✅ Berbagi kepada Korban Bencana Banjir</li>
          <li>✅ Outbound BEM FTIK </li> 
          <li>✅ Bakti Sosial Ramadhan BEM FTIK 2025</li>
          <li>✅ Buka Bersama BEM FTIK 2025</li>
          <li>✅ Tekno Competition BEM FTIK 2025/International Competition 2025</li>
        </ul>
      </div>


      <!-- Card 4 -->
      <div class="card">
        <div class="icon blue">👨‍💻</div>
        <h3>UKMI Arrahman Teknokrat</h3>
        <p class="company">Biro Dana Usaha</p>
        <p class="info">2023 - Present • UTI • <span class="badge">Kepala Biro</span></p>
        <p>Mengelola Pemasukan Organisasi dari berjualan snack, baju, merchandise, dll. serta berkontribusi di berbagai kegiatan dalam UKMI Arrahman Teknokrat </p>
        <div class="tech">
        </div>
        <ul class="Kegiatan Besar">
          <li>✅ Lomba Gebyar Ramadhan tahun 2023</li>
          <li>✅ Lomba Gebyar Ramadhan tahun 2024</li> 
          <li>✅ Lomba Pentas Islami ke 17 tahun 2023</li>
          <li>✅ Lomba Pentas Islami ke 18 tahun 2024</li>
        </ul>
      </div>
    </div>
  </section>

<section id="education" class="education-section" style="text-align: center;">
  <h2><span>Riwayat</span> Pendidikan</h2>
  <p>Perjalanan pendidikan saya menunjukkan perkembangan yang konsisten dalam memahami dan menguasai bidang ilmu komputer serta pengembangan web.</p>

  <!-- Formal Education -->
  <h3 style="margin-top: 40px;">Pendidikan</h3>
  <div class="card" style="max-width: 600px; margin: 20px auto; text-align: left;">
    <h3>SMA</h3>
    <span class="sub">Ilmu Pengetahuan Alam - MAN 2 Bandar Lampung</span>
    <p class="meta">📅 2020 - 2023 | 📍 Bandar Lampung, Lampung</p>
    <div class="badges">
<span class="badge green" style="color: white;">Graduated</span>
    </div>
    <p>Fokus di pengetahuan dasar</p>
    <div class="courses">
      <strong>Key Courses:</strong>
      <p>Akidah Akhlak, SKI, Qur'an Hadis, Mata Pelajaran Umum</p>
    </div>
  </div>

  <div class="card" style="max-width: 600px; margin: 20px auto; text-align: left;">
    <h3>S1</h3>
    <span class="sub">Informatika - Universitas Teknokrat Indonesia</span>
    <p class="meta">📅 2023 - 2027 | 📍 Bandar Lampung , Lampung</p>
    <div class="badges">
<span class="badge blue" style="color: white;">Nilai : 3.33/4.00</span>
<span class="badge green" style="color: white;">Semester 5</span>
    </div>
    <p>Sedang melaksanakan perkuliahan semester 5, dan menguasai berbagai bidang.</p>
    <div class="courses">
      <strong>Keahlian:</strong>
      <p>UIUX Desain, Frontend Developer, Desain grafis, 3D Desain</p>
    </div>
  </div>

  <!-- Certifications -->
  <h3 style="margin-top: 40px;">Pengalaman</h3>
  <div class="card-container" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 20px;">
    <div class="cert-card">
      <div class="icon-circle"><i class="fas fa-microphone-alt"></i></div>
      <h3>Ketua Pelaksana Kaderisasi 1 Hima Informatika 2025</h3>
      <p>Himpunan Mahasiswa</p>
      <span class="year">2025</span>
    </div>

    <div class="cert-card">
      <div class="icon-circle"><i class="fas fa-university"></i></div>
      <h3>Ketua Pelaksana Launching BBQ Gelombang ke 2</h3>
      <p>UKMI Arrahman Teknokrat</p>
      <span class="year">2024 - 2025</span>
    </div>

    <div class="cert-card">
      <div class="icon-circle"><i class="fas fa-chalkboard-teacher"></i></div>
      <h3>Ketua Umum</h3>
      <p>Badan Eksekutif Mahasiswa Fakultas Teknik dan Ilmu komputer</p>
      <span class="year">2025 - 2026</span>
    </div>

  </div>
</section>

<section id="contact" class="contact-section">
  <h2 class="section-title"><span>Contact</span> Me</h2>
  <p>Hubungi saya melalui kontak berikut atau kirimkan pesan langsung</p>


  <div class="contact-container">
    <!-- Kontak Kiri -->
    <div class="contact-info">
      <div class="contact-card">
        <div class="contact-header">
          <div class="icon-circle"><i class="fas fa-envelope"></i></div>
          <h3>Email</h3>
        </div>
        <p>bimmawahyu167@gmail.com</p>
      </div>

      <div class="contact-card">
        <div class="contact-header">
          <div class="icon-circle"><i class="https://wa.me/qr/SDE5WQCSOUJ6C1"></i></div>
          <h3>WhatsApp</h3>
        </div>
        <p>0898-0999-045</p>
      </div>

      <div class="contact-card">
        <div class="contact-header">
          <div class="icon-circle"><i class="fas fa-map-marker-alt"></i></div>
          <h3>Lokasi</h3>
        </div>
        <p>Desa Sukajaya Lempasing, Teluk Pandan, Pesawaran ,Lampung</p>
      </div>

    <!-- Form Kanan -->
    <div class="contact-form">
      <form id="wa-form">
        <input type="text" id="name" placeholder="Nama Anda" required>
        <input type="email" id="email" placeholder="Email Anda" required>
        <textarea id="message" rows="5" placeholder="Pesan Anda..." required></textarea>
        <button type="submit">Kirim ke WhatsApp</button>
      </form>
    </div>
  </div>
</section>



  <script src="script.js"></script>
</body>

<footer class="footer-section">
  <div class="footer-container">
    <div class="footer-card">
      <h3>Bimma Portfolio</h3>
      <p>Terima kasih telah mengunjungi portofolio saya. Sampai jumpa di project selanjutnya!</p>
    </div>
    <div class="footer-card">
      <h4>Contact</h4>
      <ul>
        <li><i class="fas fa-envelope"></i> bimmawahyu167@gmail.com</li>
        <li><i class="fab fa-whatsapp"></i> +628980999045</li>
        <li><i class="fas fa-map-marker-alt"></i> Desa Sukajaya Lempasing, Teluk Pandan, Pesawaran,Lampung</li>
        <li><i class="fab fa-linkedin"></i> www.linkedin.com/in/bimma-wahyu-makarim-2259292ba</li>
      </ul>
    </div>
    <div class="footer-card">
  <h3>Follow Me</h3>
  <div class="social-icons">
    <a href="#" class="social-link instagram" aria-label="Instagram">
      <i class="fab fa-instagram"></i>
    </a>
    <a href="#" class="social-link youtube" aria-label="YouTube">
      <i class="fab fa-youtube"></i>
    </a>
    <a href="#" class="social-link linkedin" aria-label="LinkedIn">
      <i class="www.linkedin.com/in/bimma-wahyu-makarim-2259292ba"></i>
    </a>
  </div>
</div>


    </div>
  </div>
  <div class="footer-bottom">
    <p>&copy; 2025 Bimma Wahyu Makarim.</p>
  </div>
</footer>


</html>
