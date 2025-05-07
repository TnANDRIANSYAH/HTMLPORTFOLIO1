# HTMLPORTFOLIO1
TUGAS 1
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Website Saya</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }
    header, section {
      margin-bottom: 40px;
    }
    nav {
      text-align: right;
    }
    nav a {
      margin-left: 15px;
      text-decoration: none;
      color: black;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    td, th {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: center;
    }
    .aboutme-title {
      text-align: center;
      font-weight: bold;
      font-size: 1.5em;
    }
    .portfolio-title {
      font-size: 1.3em;
      margin-top: 30px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

  <!-- Section 1: Menu -->
  <header>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Portofolio</a>
    </nav>
  </header>

  <!-- Section 2: Judul kiri, gambar kanan -->
  <section>
    <table>
      <tr>
        <td>
          <h2>Selamat Datang di Website Saya</h2>
          <p>Ini adalah contoh header dengan deskripsi. Buat ini menarik agar pengunjung betah di halaman anda.</p>
        </td>
        <td>
          <img src=https://th.bing.com/th/id/OIP.w0qWHQQkOu96YLuetR2VGQHaE8?w=239&h=188&c=7&r=0&o=5&cb=iwc1&pid=1.7>
        </td>
      </tr>
    </table>
  </section>

  <!-- Section 3: Biodata -->
  <section>
    <div class="aboutme-title">About Me</div>
    <table>
      <tr>
        <td>ANDRIANSYA</td>
        <td>SMA</td>
        <td>TRAAVELLING</td>
      </tr>
      <tr>
        <td>081808910414</td>
        <td>NOTHING</td>
        <td>NOTHING</td>
      </tr>
    </table>
  </section>

  <!-- Section 4: Portofolio -->
  <section>
    <div class="portfolio-title">Portofolio</div>
    <table>
      <tr>
        <td>
          <img src="https://th.bing.com/th/id/OIP.w0qWHQQkOu96YLuetR2VGQHaE8?w=239&h=188&c=7&r=0&o=5&cb=iwc1&pid=1.7"><br>
          Project 1<br>Deskripsi project 1
        </td>
        <td>
          <img src=https://th.bing.com/th/id/OIP.w0qWHQQkOu96YLuetR2VGQHaE8?w=239&h=188&c=7&r=0&o=5&cb=iwc1&pid=1.7"><br>
          Project 2<br>Deskripsi project 2
        </td>
        <td>
          <img src=https://th.bing.com/th/id/OIP.w0qWHQQkOu96YLuetR2VGQHaE8?w=239&h=188&c=7&r=0&o=5&cb=iwc1&pid=1.7><br>
          Project 3<br>Deskripsi project 3
        </td>
      </tr>
    </table>
  </section>

</body>
</html>
