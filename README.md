<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Excelora</title>
    <link href="https://assets.onecompiler.app/4359cvpkx/4365vb2ft/Desain%20tanpa%20judul_20250115_172411_0000.png" rel="icon">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Roboto', sans-serif;
        }

        body {
            background-color: #000000;
            color: #e0e0e0;
            line-height: 1.6;
            scroll-behavior: smooth;
        }

        header {
             height: 100vh;
    background: url('https://assets.onecompiler.app/4359cvpkx/43786wyjh/Desain%20tanpa%20judul%20(5).png') center/cover no-repeat;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
    background-size: cover;
    background-position: center;
}

        header h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.5rem;
            margin-bottom: 2rem;
        }

        header a {
            color: #fbc02d;
            text-decoration: none;
            font-weight: bold;
            border: 2px solid #fbc02d;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        header a:hover {
            background-color: #fbc02d;
            color: #121212;
        }

        nav {
    position: sticky;
    top: 0;
    background: rgba(255, 0, 242, 0.6);
    z-index: 1000;
    padding: 0.8rem 2rem;
}

nav ul {
    display: flex;
    justify-content: flex-start; /* Letakkan menu di sebelah kiri */
    padding: 2rem;
    list-style: none;
    margin: 0; /* Pastikan tidak ada margin tambahan */
}

        section {
            padding: 4rem 2rem;
        }

        .about {
            display: flex;
            align-items: center;
            gap: 2rem;
            flex-wrap: wrap;
        }

        .about img {
            max-width: 300px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .about-text {
            flex: 1;
            text-align: left;
        }

        .about h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: #fbc02d;
        }

        .about p {
            margin-bottom: 1rem;
        }

        footer {
            background: #1e1d32;
            text-align: center;
            padding: 2rem;
            color: #e0e0e0;
        }

        footer a {
            color: #fbc02d;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #fffdfd;
            padding: 10px;
            text-align: left;
            color: rgb(255, 255, 255);
        }
        th {
            background-color: #ffffff;
            color: rgb(0, 0, 0);
        }
        tr:nth-child(even) {
            background-color: #0a0a0a;
        }
        
       .contact {
    background: #000000;
    border-radius: 10px;
    padding: 1rem 2rem; /* Mengurangi padding atas dan bawah */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 20px; /* Memberi jarak antara tabel dan kotak kontak */
}

.contac {
    text-align: center;
    width: 100%;
    max-width: 600px; /* Menyesuaikan lebar kotak */
    padding: 1rem; /* Mengurangi padding dalam kotak */
}

.contact img {
            max-width: 180px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }


    /* Tambahkan animasi untuk elemen yang muncul saat di-scroll */
    .hidden {
        opacity: 0;
        transform: translateY(20px);
        transition: opacity 0.6s ease-out, transform 0.6s ease-out;
    }

    .visible {
        opacity: 1;
        transform: translateY(0);
    }
    
    /* Styling untuk ikon media sosial */
.social-media {
    display: block; /* Menampilkan ikon secara vertikal */
    margin-top: 20px; /* Memberi jarak setelah nomor telepon */
    text-align: center; /* Menyusun ikon di tengah */
}

.social-icon {
    width: 40px; /* Ukuran ikon */
    height: 40px;
    display: inline-block; /* Menyusun ikon secara horizontal */
    margin: 10px; /* Memberikan jarak antar ikon */
    transition: transform 0.3s ease, opacity 0.3s ease; /* Efek transisi saat hover */
}

.social-icon:hover {
    transform: scale(1.1); /* Membesarkan ikon saat hover */
    opacity: 0.8; /* Memberi efek transparansi saat hover */
}

        .visible {
            opacity: 1;
            transform: translateY(0);
        }
        @keyframes logoAnimation {
    0% {
        transform: scale(0.5);
        opacity: 0;
    }
    100% {
        transform: scale(1);
        opacity: 1;
    }
}

header .logo {
    display: block;
    margin: 1rem auto;
    width: 230px; /* Adjust the width of the logo */
    height: auto;
    animation: logoAnimation 1s ease-out forwards;
    opacity: 0;
}
@media (max-width: 768px) {
            .about {
                flex-direction: column;
                text-align: center;
            }

            .about img {
                margin-bottom: 1rem;
            }

            .about-text {
                text-align: center;
            }
        }

    </style>
</head>
<body>
    <nav>
      <h2>Excelora</h2>
    </nav>
    
    <header>
        <div>
            <img src="https://assets.onecompiler.app/4359cvpkx/4365vb2ft/Desain%20tanpa%20judul_20250115_172411_0000.png" alt="Logo" class="logo">
            <h1>EXCELORA</h1>
            <p>Hi, Welcome to X-1</p>
            <a href="#about" id="explore-btn">About Excelora</a>
        </div>
    </header>

    <section id="about" class="about hidden">
        <img src="https://assets.onecompiler.app/4359cvpkx/4365vb2ft/Desain%20tanpa%20judul_20250115_172411_0000.png" alt="Excelora Logo">
        <div class="about-text hidden">
            <h2>About Excelora</h2>
              <p>Excelora adalah salah satu kelas di SMA Negeri 2 Kota Madiun, lebih tepatnya ( X-1 ).</p>
              <p>SMAN 2 Madiun memiliki tradisi turun-temurun dalam sistem pengelompokan kelas. Setiap kelas dari tingkat X, XI, dan XII dengan nomor urut yang sama digabungkan menjadi sebuah kelompok, yang disebut kelompok kelas "P." Sebagai contoh, kelas X-1 termasuk dalam kelompok P1, yang terdiri dari kelas X-1, XI-1, dan XII-1.
                Kelompok P1 memiliki tema khusus berupa "kopi," yang telah menjadi ciri khasnya dan dipertahankan dari generasi ke generasi sebagai bagian dari tradisi kelas urutan 1.</p>
              <p>Excelora terinspirasi dari kata Excelsa, jenis kopi langka dengan cita rasa unik, dan Explore, yang melambangkan semangat menjelajahi. Nama ini mencerminkan semangat menemukan hal-hal baru dan memperluas wawasan, sama seperti kopi Excelsa yang menawarkan pengalaman rasa yang jarang ditemukan.</p>
              <p>Excelora mengusung tema kelas "Wonka" dari film Willy Wonka, menghadirkan nuansa fantasi dengan palet warna pink, ungu, putih, dan hitam. Nuansa ini menciptakan kesan ceria, hangat, dan penuh harapan. Logo Excelora juga tak kalah unik. Berbentuk permen dengan menyerupai manusia bertopi, logo ini, dari sudut pandang tertentu, membentuk kata "Excelora."</p>
        </div>
    </section>

    <section id="projects" class="projects hidden">
        <h2>Daftar Siswa</h2>
        <div class="container hidden">
          <table>
            <thead>
                <tr>
                    <th>No</th>
                    <th>Nama Lengkap</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>1</td><td>AGUS IMANUEL OMEGA</td></tr>
                <tr><td>2</td><td>ALDY DILUPUERA</td></tr>
                <tr><td>3</td><td>ALEXANDRA AULIA WARDANA</td></tr>
                <tr><td>4</td><td>ALLENA PRISELLIA SEPTIANE</td></tr>
                <tr><td>5</td><td>ANDI TAZKIA EKA PUTRI</td></tr>
                <tr><td>6</td><td>ARDION ARGANTA</td></tr>
                <tr><td>7</td><td>ARIBAHZAHRA FATHIYA SYIFA</td></tr>
                <tr><td>8</td><td>AYLA INNAYA RIHASTARA</td></tr>
                <tr><td>9</td><td>BRAZEELLE BELLICIA GIZCA KUSUMA</td></tr>
                <tr><td>10</td><td>DHANESWARA TEGAR TRIYONO</td></tr>
                <tr><td>11</td><td>DHONY RASYA SALVADITYA</td></tr>
                <tr><td>12</td><td>DISTA EDRIA AFRIANTA</td></tr>
                <tr><td>13</td><td>ESTERRINA ASTRIDTIAR ANTIKA</td></tr>
                <tr><td>14</td><td>FARDAN HAFISZ</td></tr>
                <tr><td>15</td><td>FILIA YAFA SHALOMITA IMANUELA</td></tr>
                <tr><td>16</td><td>FISKA WIDYANA AWIDDAH WIBAWA</td></tr>
                <tr><td>17</td><td>GEOVAN APRILA TRISTYANANDA</td></tr>
                <tr><td>18</td><td>HANIN ULINNUHA AL KOMARI</td></tr>
                <tr><td>19</td><td>ISNAINI EDI PRATIWI</td></tr>
                <tr><td>20</td><td>JEREMY FILBERT HANDOYO</td></tr>
                <tr><td>21</td><td>JESYCA CEYSAR AURAPUTRI</td></tr>
                <tr><td>22</td><td>KAYLA MARETA JURIT SYAPUTRI</td></tr>
                <tr><td>23</td><td>KEZIA EMMANUELLA WIJAYA PUTRI</td></tr>
                <tr><td>24</td><td>MARIA SHELVIANA ANGELICA</td></tr>
                <tr><td>25</td><td>MAXELL MARVELLOUS SANTOSO</td></tr>
                <tr><td>26</td><td>MUHAMMAD BIMA ARYA DEWA</td></tr>
                <tr><td>27</td><td>MUHAMMAD FATIHUL ISLAM</td></tr>
                <tr><td>28</td><td>MURNI SHINTYA NUR AIDA</td></tr>
                <tr><td>29</td><td>NESHA AZZAHRASAZIA ALFATHDISAS</td></tr>
                <tr><td>30</td><td>NITYASA ERINNA PARAMESTI</td></tr>
                <tr><td>31</td><td>RACHELA BILQIS TYAS SAPUTRI</td></tr>
                <tr><td>32</td><td>RADIT FATURAHMAN ANDIVA</td></tr>
                <tr><td>33</td><td>RAHIDHA RINGGANDHANI</td></tr>
                <tr><td>34</td><td>RASYDAN MUHAMMAD ATHIR</td></tr>
                <tr><td>35</td><td>RAYHAN ANELGA SYANDANA NUGROS</td></tr>
                <tr><td>36</td><td>REHUEL FIRMAN TIO SITUMEANG</td></tr>
                <tr><td>37</td><td>SALSABILA AFIDAH MAHARANI</td></tr>
                <tr><td>38</td><td>VAREL TRI MARYANTO</td></tr>
                <tr><td>39</td><td>YABEZ RANGGA YUDITHIA SIMANJUN</td></tr>
                <tr><td>40</td><td>ZAHRA NUR FANISA</td></tr>
            </tbody>
        </table>
      </div>
    </section>

    <section id="contact" class="contact hidden">
      <div class="contac hidden">
        <h2>Kontak Kami</h2>
        <p>Terimakasih telah mengunjungi Website kami.</p>
         <img src="https://assets.onecompiler.app/4359cvpkx/4365vb2ft/Desain%20tanpa%20judul_20250115_172411_0000.png" alt="Excelora Logo">
        <p>Jl. Biliton No.24, Madiun Lor, Kec. Manguharjo,</p>
        <p>Kota Madiun, Jawa Timur 63122</p>
        <a href="https://www.instagram.com/excelorax1?igsh=MXE4cmZhMGdmcHRqeQ==" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" class="social-icon">
            </a>
      </div>
    </section>

    <footer>
        <div class="copyright">
            &copy; Designed by <strong>Excelora class</strong>.
        </div> 
    </footer>

    <script>
      // Menambahkan animasi saat tombol 'About Excelora' diklik
const exploreBtn = document.getElementById('explore-btn');
const aboutSection = document.getElementById('about');

exploreBtn.addEventListener('click', function (e) {
    e.preventDefault(); // Menghindari perilaku default anchor tag (scroll langsung)
    
    // Set initial state (elemen disembunyikan)
    aboutSection.style.opacity = 0;
    aboutSection.style.transform = 'translateY(20px)';
    
    // Memicu animasi dengan memberikan transisi
    setTimeout(function() {
        aboutSection.style.transition = 'opacity 0.6s ease-out, transform 0.6s ease-out';
        aboutSection.style.opacity = 1;
        aboutSection.style.transform = 'translateY(0)';
    }, 100); // Delay sedikit agar transisi bisa diterapkan
     
    // Scroll ke bagian 'about' dengan smooth scroll
    aboutSection.scrollIntoView({ behavior: 'smooth' });
});

    // Seleksi semua elemen dengan class "hidden"
    const hiddenElements = document.querySelectorAll('.hidden');

    // Intersection Observer untuk mengawasi elemen yang masuk ke viewport
    const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.classList.add('visible'); // Tambahkan class "visible"
                observer.unobserve(entry.target); // Hentikan pengawasan setelah terlihat
            }
        });
    }, { threshold: 0.1 });

    // Awasi setiap elemen yang memiliki class "hidden"
    hiddenElements.forEach(el => observer.observe(el));
</script>

</body>
</html>
