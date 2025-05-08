<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Portofolio Saya</title>
  <style>
    table {
      width: 100%;
      border-collapse: collapse;
    }

    td, th {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: center;
      vertical-align: top;
    }

    .menu {
      background-color: #f0f0f0;
      font-weight: bold;
      text-align: center;
    }

    .header-section img {
      max-width: 100%;
      height: auto;
    }

    .about-me {
      background-color: #f9f9f9;
    }

    .portfolio img {
      max-width: 100%;
      height: auto;
    }

    .section-title {
      font-size: 1.5em;
      font-weight: bold;
      padding: 10px 0;
      background-color: #ddd;
    }
  </style>
</head>
<body>

<!-- Section 1: Menu -->
<table class="menu">
  <tr>
    <td>Home</td>
    <td>Tentang Saya</td>
    <td>Portofolio</td>
    <td>Kontak</td>
  </tr>
</table>

<!-- Section 2: Header dengan dua kolom -->
<table class="header-section">
  <tr>
    <td>
      <p>Ini adalah contoh header dengan dua kolom. Kolom kiri berisi teks seperti ini.</p>
      <button>Pelajari Lebih Lanjut</button>
    </td>
    <td>
      <img src="https://via.placeholder.com/300x200.png?text=Gambar+Header" alt="Gambar Header">
    </td>
  </tr>
</table>

<!-- Section 3: Biodata -->
<table class="about-me">
  <tr><td colspan="6" class="section-title">About Me</td></tr>
  <tr><td colspan="6">A brief introduction about myself</td></tr>
  <tr>
    <td>Full Name<br>Aji Pamungkas</td>
    <td>Education<br>Universitas XYZ</td>
    <td>Pekerjaan<br>Web Developer</td>
    <td>Contact<br>email@example.com</td>
    <td>Hobi<br>Desain & Coding</td>
    <td>Alamat<br>Jakarta, Indonesia</td>
  </tr>
</table>

<!-- Section 4: Portofolio -->
<table class="portfolio">
  <tr><td colspan="3" class="section-title">Portofolio</td></tr>
  <tr>
    <td>
      <img src="https://via.placeholder.com/200x150.png?text=Proyek+1" alt="Proyek 1">
      <div>Proyek 1<br>Deskripsi proyek 1.</div>
    </td>
    <td>
      <img src="https://via.placeholder.com/200x150.png?text=Proyek+2" alt="Proyek 2">
      <div>Proyek 2<br>Deskripsi proyek 2.</div>
    </td>
    <td>
      <img src="https://via.placeholder.com/200x150.png?text=Proyek+3" alt="Proyek 3">
      <div>Proyek 3<br>Deskripsi proyek 3.</div>
    </td>
  </tr>
</table>

</body>
</html>