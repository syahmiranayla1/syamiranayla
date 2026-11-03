<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Profil Pribadi - Nama Anda</title>
<style>
  :root {
    --primary: #2563eb;
    --dark: #1e293b;
    --light: #f1f5f9;
    --card: #ffffff;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: "Segoe UI", Arial, sans-serif;
    background: var(--light);
    color: var(--dark);
    line-height: 1.6;
  }
  header {
    background: linear-gradient(135deg, #2563eb, #7c3aed);
    color: #fff;
    text-align: center;
    padding: 50px 20px 40px;
  }
  header img.profil {
    width: 140px; height: 140px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px solid #fff;
    background: #cbd5e1;
    margin-bottom: 15px;
  }
  header h1 { font-size: 2rem; }
  header p { opacity: .9; }
  nav {
    background: var(--dark);
    position: sticky; top: 0; z-index: 10;
    text-align: center;
  }
  nav a {
    display: inline-block;
    color: #fff;
    text-decoration: none;
    padding: 14px 22px;
    transition: background .2s;
  }
  nav a:hover { background: var(--primary); }
  main { max-width: 1000px; margin: 0 auto; padding: 30px 20px; }
  section {
    background: var(--card);
    border-radius: 14px;
    padding: 28px;
    margin-bottom: 28px;
    box-shadow: 0 2px 10px rgba(0,0,0,.07);
  }
  section h2 {
    color: var(--primary);
    margin-bottom: 18px;
    padding-bottom: 8px;
    border-bottom: 3px solid var(--light);
  }
  table { width: 100%; border-collapse: collapse; }
  td { padding: 10px 8px; border-bottom: 1px solid #e2e8f0; vertical-align: top; }
  td:first-child { width: 200px; font-weight: 600; }
  .hobi { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 16px; }
  .hobi div {
    background: var(--light);
    border-radius: 12px;
    padding: 20px;
    text-align: center;
    transition: transform .2s;
  }
  .hobi div:hover { transform: translateY(-4px); }
  .hobi .ikon { font-size: 2.2rem; display: block; margin-bottom: 6px; }
  .galeri { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 16px; }
  .galeri img, .galeri video {
    width: 100%; height: 200px;
    object-fit: cover;
    border-radius: 12px;
    background: #cbd5e1;
  }
  .galeri figure { margin: 0; }
  .galeri figcaption { text-align: center; font-size: .9rem; margin-top: 6px; color: #64748b; }
  h3.sub { margin: 24px 0 12px; }
  .video-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 18px; }
  .video-grid video { width: 100%; border-radius: 12px; background: #000; }
  footer { text-align: center; padding: 25px; color: #64748b; font-size: .9rem; }
  @media (max-width: 600px) {
    td:first-child { width: 120px; }
    nav a { padding: 12px 12px; }
  }
</style>
</head>
<body>

<header>
  <img class="profil" src="foto/profil.jpg" alt="Foto Profil">
  <h1>Nama Lengkap Anda</h1>
  <p>Pelajar / Mahasiswa / Pekerja &mdash; Kota Anda</p>
</header>

<nav>
  <a href="#biodata">Biodata</a>
  <a href="#hobi">Hobi</a>
  <a href="#galeri">Galeri</a>
</nav>

<main>

  <!-- BIODATA -->
  <section id="biodata">
    <h2>📋 Biodata Pribadi</h2>
    <table>
      <tr><td>Nama Lengkap</td><td>syahmira maulida nayla</td></tr>
      <tr><td>Nama Panggilan</td><td>syahmira</td></tr>
      <tr><td>Tempat, Tanggal Lahir</td><td>Kota, 30 april 2005 </td></tr>
      <tr><td>Jenis Kelamin</td><td>Laki-laki / Perempuan</td></tr>
      <tr><td>Agama</td><td>islam </td></tr>
      <tr><td>Alamat</td><td>Jl.jeruk gg kestela 7</td></tr>
      <tr><td>Pendidikan</td><td>universitas lambung mangkurat </td></tr>
      <tr><td>Email</td><td>syahmiranayla1@gmail.com</td></tr>
      <tr><td>No. HP</td><td>089523756607</td></tr>
      <tr><td>Cita-cita</td><td>menjadi wanita kaya raya </td></tr>
    </table>
  </section>

  <!-- HOBI -->
  <section id="hobi">
    <h2>🎯 Hobi</h2>
    <div class="hobi">
      <div><span class="ikon">📚</span>Membaca</div>
      <div><span class="ikon">🎵</span>Mendengarkan Musik</div>
      <div><span class="ikon">⚽</span>Olahraga</div>
      <div><span class="ikon">📷</span>Fotografi</div>
      <div><span class="ikon">🎮</span>Bermain Game</div>
    </div>
  </section>

  <!-- GALERI -->
  <section id="galeri">
    <h2>🖼️ Galeri</h2>

    <h3 class="sub">Foto</h3>
    <div class="galeri">
      <figure><img src="foto/foto1.jpg" alt="Foto 1"><figcaption>Foto 1</figcaption></figure>
      <figure><img src="foto/foto2.jpg" alt="Foto 2"><figcaption>Foto 2</figcaption></figure>
      <figure><img src="foto/foto3.jpg" alt="Foto 3"><figcaption>Foto 3</figcaption></figure>
      <figure><img src="foto/foto4.jpg" alt="Foto 4"><figcaption>Foto 4</figcaption></figure>
    </div>

    <h3 class="sub">Video</h3>
    <div class="video-grid">
      <figure>
        <video controls preload="metadata">
          <source src="video/video1.mp4" type="video/mp4">
          Browser Anda tidak mendukung video.
        </video>
        <figcaption>Video 1</figcaption>
      </figure>
      <figure>
        <video controls preload="metadata">
          <source src="video/video2.mp4" type="video/mp4">
          Browser Anda tidak mendukung video.
        </video>
        <figcaption>Video 2</figcaption>
      </figure>
    </div>
  </section>

</main>

<footer>
  &copy; 2026 Nama Lengkap Anda. Semua hak dilindungi.
</footer>

</body>
</html>
