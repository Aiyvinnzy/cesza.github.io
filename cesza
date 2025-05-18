<html lang="id">
<head>
  <meta charset="UTF-8" />
  <title>Profile Aisyah Princesza X-3</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet" />
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(-45deg, #fcd4e0, #fce4ec, #ffe6f0, #f8c8dc); /* Warna pink seperti My Melody */
      background-size: 400% 400%;
      animation: gradientAnimation 30s ease infinite;
      color: #ffffff;
      text-align: center;
      transition: background-color 0.5s ease;
      position: relative;
      overflow-x: hidden;
    }

    body::before {
      content: "";
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(255, 255, 255, 0.15);
      pointer-events: none;
      z-index: 0;
    }

    @keyframes gradientAnimation {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }

    .marquee {
      background-color: white;
      color: #e91e63;
      padding: 15px 0;
      font-size: 26px;
      font-weight: 600;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      position: relative;
      z-index: 1;
    }

    .container {
      margin-top: 60px;
      display: flex;
      flex-direction: column;
      align-items: center;
      position: relative;
      z-index: 1;
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
      padding: 0 15px;
    }

    img.clickable {
      width: 200px;
      height: auto;
      margin: 25px;
      cursor: pointer;
      border-radius: 16px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      border: 2px solid white;
      position: relative;
      z-index: 1;
    }

    img.clickable:hover {
      transform: scale(1.05);
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.2);
    }

    .bio {
      position: relative;
      padding: 20px 25px;
      background: rgba(255, 255, 255, 0.25);
      border-radius: 15px;
      box-shadow: 0 8px 15px rgba(0,0,0,0.1);
      text-align: justify;
      color: #000000cc;
      font-weight: 300;
      line-height: 1.5;
      backdrop-filter: blur(8px);
      -webkit-backdrop-filter: blur(8px);
      margin-bottom: 80px;
    }

    .bio p {
      margin-bottom: 1em;
    }

    .instagram-logo {
      width: 90px;
      height: 90px;
      position: absolute;
      bottom: -60px;
      right: 15px; /* Dipindah dari left ke right */
      cursor: pointer;
      transition: transform 0.3s ease;
      background: rgba(255,255,255,0.7);
      border-radius: 50%;
      padding: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    }

    .instagram-logo:hover {
      transform: scale(1.2);
      background: rgba(255,255,255,0.9);
    }

    a {
      text-decoration: none;
    }

    .footer {
      margin-top: 60px;
      font-size: 14px;
      color: rgba(0, 0, 0, 0.7);
      position: relative;
      z-index: 1;
    }
  </style>
</head>
<body>

  <div class="marquee">
    <marquee>Selamat datang di Profile Aisyah Princesza ^_^</marquee>
  </div>

  <div class="container">
    <!-- Gambar PNG yang diklik untuk memutar audio -->
    <a href="https://imgur.com/rypGysW">
      <img
        src="https://i.imgur.com/rypGysW.jpg"
        title="Klik untuk mendengar suara"
        alt="Klik untuk mendengar suara"
        class="clickable"
        onclick="playAudio()"
      />
    </a>

    <div class="bio">
      <p>Perkenalkan nama lengkap saya Aisyah Princesza. Diberikan nama Princesza karena ibu dan kakak saya gemar menonton film Disney princess seperti Cinderella dan Aurora. Banyak pula yang menanggilku Cesza. Aku lahir di Jakarta pada bulan juli tanggal 12 tahun 2009. Untuk tahun ini, saya akan beranjak umur 16 tahun.
      </p>

      <p>Saya gemar belajar hal baru, termasuk belajar alat musik. Saya diajarkan bermain alat musik keyboard dan gitar oleh ibu saya. Ibu saya cukup mahir memainkan beberapa alat musik, jadi saya tidak perlu khawatir jika saya kebingungan saat bermain. Selain suka bermain alat musik, saya suka menonton film, terutama yang berasal dari Jepang. Dan saya gemar membaca buku, karena membuat rasa penasaran saya semakin besar, biasanya pada jam istirahat, saya pergi ke perpustakaan bersama teman saya.</p>

      <p>Selain itu, sudah beberapa kali saya pindah sekolah. Menjadi anak baru tidaklah mudah, tetapi saya berusaha beradaptasi dengan teman teman baru saya. Untuk sekarang, saya bersekolah di SMAN 27 Jakarta Pusat. Setelah lulus sekolah, saya berencana untuk berkuliah dan mengambil jurusan sastra inggris. Sekian biodata narasi tentang diri saya, terima kasih</p>

      <p class="footer">Terima kasih.</p>

      <!-- Instagram link -->
      <a href="https://www.instagram.com/aiysawako/" target="_blank" rel="noopener noreferrer" title="Instagram Aisyah Princesza">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Instagram_logo_2016.svg"
          alt="Instagram"
          class="instagram-logo"
        />
      </a>
    </div>
  </div>

  <!-- Audio -->
  <audio id="voiceAudio" src="Recording (6).mp3"></audio>

  <div class="footer">
    &copy; Aisyah Princesza X-3
  </div>

  <script>
    function playAudio() {
      const audio = document.getElementById('voiceAudio');
      audio.play();
    }
  </script>

</body>
</html>
