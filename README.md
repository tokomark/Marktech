<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <link rel="icon" href="img/logos.png" />

    <!-- Font Lexend Deca -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Michroma&family=Orbitron:wght@400;500;600;700;800;900&display=swap"
      rel="stylesheet"
    />

    <!-- Icon -->
    <script src="https://unpkg.com/feather-icons"></script>

    <link rel="stylesheet" href="css/style.css" />
    <title></title>
  </head>
  <body>
    <header>
      <div class="logo">
        <img src="img/mark.png" width="75" />
        <a href="">Mark Tech Corporation</a>
      </div>

      <nav id="navbar">
        <a href="#">Home</a>
        <a href="#planet">Visi</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
        <a id="login-menu" href="">Log In</a>
        <a id="login-menu" href="">Sign Up</a>
      </nav>

      <div class="extra-nav">
        <a href="login.html">Login</a>
        <a id="menu" href="#"><i data-feather="menu"></i></a>
      </div>
    </header>

    <main>
      <section id="hero" class="hero">
        <div class="content">
          <video src="video/earth.mp4" autoplay loop muted></video>

          <article>
            <h2>Mark Tech Corporation</h2>
            <p>
              Mark Tech Corporation adalah, <span>perusahaan yang bergerak di bidang jasa</span>
            </p>
            <div class="button-area">
            <a href="login.html"><span>Login</span></a>
          </div>
          </article>
        </div>
      </section>

      <!-- Section Planet -->
      <section class="planet" id="planet">
        <div class="title">
          <h2>Visi</h2>
          <p>
            Menjadi penyedia jasa teknologi terkemuka yang inovatif dan terpercaya,
            memberikan solusi digital terbaik untuk
            mendukung pertumbuhan bisnis dan transformasi digital di era modern.
          </p>
        </div>

        <div class="row">
          <div class="earth-rotate">
            <video src="video/earth-rotation.mp4" autoplay muted loop></video>
            <!-- <img src="gif/earth-rotation.gif" alt=""> -->
          </div>

          <aside class="description">
            <h3>Deskripsi Lengkap</h3>
            <p>
              Mark Tech Corporation adalah perusahaan yang bergerak di bidang jasa,
              berfokus pada solusi teknologi dan digital untuk membantu bisnis 
              dan individu dalam menghadapi tantangan di era modern.
              Dengan tim profesional berpengalaman dan teknologi terkini,
              Mark Tech Corporation berkomitmen untuk memberikan layanan inovatif yang berkualitas tinggi. 
              Mark Tech Corporation hadir untuk mendukung
              transformasi digital dengan layanan yang handal, aman, dan berkelanjutan.
            </p>
            <ul>
              <li>Name Company: Mark Tech Corporation</li>
              <li>Established Since: 2 Februari 2023</li>
              <li>Address: Jakarta.</li>
              <li>Country: Indonesia</li>
              <li>
                Bila ada kritik, saran maupun pertanyaan
                Jangan sungkan-sungkan buat hubungi kami ya dibagian bawah web ini
              </li>
            </ul>
            <a href="#"><span>See More!</span></a>
          </aside>
        </div>
      </section>

      <!-- Section About -->
      <section class="about" id="about">
        <div class="title">
          <h2>About Us</h2>
          <p>
            Menyediakan layanan teknologi inovatif dan berkualitas tinggi untuk mendukung transformasi digital,
            meningkatkan efisiensi bisnis, serta menciptakan solusi yang berkelanjutan dan bernilai bagi pelanggan.
          </p>
        </div>

        <div class="box-area">
          <div class="box">
            <div class="about-title">
              <h5>Platform Interaktif & User-Friendly ( Klik Disini) </h5>
            </div>
            <div class="about-description">
              <p>
                Dirancang dengan antarmuka yang mudah
                digunakan untuk pengalaman belajar
                yang nyaman dan efektif.
              </p>
            </div>
            <div class="about-button">
              <a href="#about"><span>Learn More</span></a>
            </div>
          </div>

          <div class="box">
            <div class="about-title">
              <h5>Materi Berkualitas & Terupdate ( Klik Disini) </h5>
            </div>
            <div class="about-description">
              <p>
                Menyediakan konten edukasi berbasis teknologi
                yang selalu diperbarui sesuai dengan
                tren industri dan kebutuhan pasar.
              </p>
            </div>
            <div class="about-button">
              <a href="#about"><span>Learn More</span></a>
            </div>
          </div>

          <div class="box">
            <div class="about-title">
              <h5>Sertifikasi Resmi & Kredibel (Klik Disini) </h5>
            </div>
            <div class="about-description">
              <p>
                Menawarkan sertifikat yang diakui
                sebagai bukti kompetensi bagi
                peserta yang menyelesaikan kursus.
              </p>
            </div>
            <div class="about-button">
              <a href="#about"><span>Learn More</span></a>
            </div>
          </div>

          <div class="box">
            <div class="about-title">
              <h5>Dukungan Instruktur & Komunitas (Klik Disini) </h5>
            </div>
            <div class="about-description">
              <p>
                Menyediakan mentor profesional serta 
                forum diskusi untuk meningkatkan
                interaksi dan kolaborasi antar peserta.
              </p>
            </div>
            <div class="about-button">
              <a href="#about"
                ><span><span>Learn More</span></span></a
              >
            </div>
          </div>
        </div>
      </section>

      <!-- Section Contact -->
      <section class="contact" id="contact">
        <div class="title">
          <h2>CONTACT</h2>
          <p>
            Mark Tech Corporation siap membantu Anda
            dengan solusi terbaik dan layanan profesional.
            Jangan ragu untuk menghubungi kami untuk informasi lebih lanjut!
          </p>
        </div>

        <div class="row">
          <form action="">
            <div class="half">
              <div class="item">
                <label for="name">NAME</label>
                <input spellcheck="false" type="text" id="name" />
              </div>
              <div class="item">
                <label for="email">EMAIL</label>
                <input spellcheck="false" type="text" id="email" />
              </div>
            </div>
            <div class="full">
              <label for="message">MESSAGE</label>
              <textarea spellcheck="false" name="" id="message"></textarea>
            </div>
            <div class="action">
              <input type="submit" value="Kirim Pesan" />
            </div>
          </form>

          <div class="line"></div>

          <aside>
            <img src="img/noel.png" alt="" />
          </aside>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer id="footer">
      <div class="social">
        <a href="#footer"><i data-feather="instagram"></i></a>
        <a href="#footer"><i data-feather="facebook"></i></a>
        <a href="#footer"><i data-feather="youtube"></i></a>
        <a href="#footer"><i data-feather="twitter"></i></a>
      </div>

      <div class="extra">
        <p>Corporation &copy; 2023</p>
      </div>
    </footer>

    <!-- Js -->
    <script src="js/script.js"></script>
    <script>
      feather.replace();
    </script>
  </body>
</html>
