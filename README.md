<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pesona Wisata Religi Pekalongan</title>
    <style>
        body {
            font-family: 'Times New Roman', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6; 
        }

        .container {
            width: 80%;
            margin: auto;
        }

        header {
            background-color: #048f39;
            color: rgb(255, 255, 255);
            padding: 20px 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: rgb(255, 255, 255);
            text-decoration: none;
        }

        .hero {
            background-color: #ffffff;
            padding: 20px;
            text-align: center;
        }

        .grid {
            display: flex;
            flex-direction: column; /* Stack sections vertically */
            gap: 20px;
            margin-bottom: 20px;
        }

        .grid-item {
            display: flex; /* Use flexbox for side-by-side layout */
            align-items: center; /* Center items vertically */
            background-color: #f9f9f9; /* Light background for sections */
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1); /* Subtle shadow for depth */
        }

        .grid-item img {
            width: 300px; /* Fixed width for images */
            height: auto; /* Maintain aspect ratio */
            border-radius: 10px;
            margin-right: 20px; /* Space between image and text */
        }

        .contact {
            background-color: #e9ecef;
            padding: 20px;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Wisata Religi di Pekalongan</h1>
            <nav>
                <ul>
                    <li><a href="#home">Beranda</a></li>
                    <li><a href="#makam-wali">Makam Wali</a></li>
                    <li><a href="#masjid">Masjid</a></li>
                    <li><a href="#majelis-keagamaan">Majelis Keagamaan</a></li>
                    <li><a href="#kontak">Kontak</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <section id="home" class="hero">
            <h2>Temukan Keindahan Wisata Religi</h2>
            <p>Pekalongan menyimpan banyak destinasi wisata religi yang kaya akan nilai sejarah dan spiritual.</p>
        </section>

        <section id="makam-wali" class="grid">
            <div class="grid-item">
                <img src="makam_sapuro.jpg" alt="Makam Sapuro">
                <div>
                    <h2>Makam Sapuro</h2>
                    <p>Makam Sapuro dikenal sebagai tempat peristirahatan terakhir dari beberapa tokoh agama yang dihormati, termasuk Habib Ahmad bin Abdullah bin Tholib Alathas. Tempat ini banyak dikunjungi peziarah dan santri.
                        Makam ini terletak strategis dekat jalur pantura, sekitar 100 meter dari jalan Jendral Sudirman, sehingga mudah dijangkau oleh para peziarah. Lokasinya yang dekat dengan pusat kota menjadikannya sebagai salah satu tujuan wisata religi yang populer.
                    </p>
                </div>
            </div>
        </section>

        <section id="masjid" class="grid">
            <div class="grid-item">
                <img src="masjid_agung_al_jami.jpg" alt="Masjid Agung Al-Jami Pekalongan">
                <div>
                    <h2>Masjid Agung Al-Jami Pekalongan</h2>
                    <p>Masjid Agung Al-Jami' Pekalongan bukan hanya sekadar tempat ibadah, tetapi juga merupakan pusat budaya dan sejarah yang kaya akan nilai-nilai keagamaan yang terletak di alun-alun kota Pekalongan.
                        Masjid ini dibangun pada tahun 1852 oleh Raden Ario Wirio Tumengung Adi Negoro, yang merupakan bupati Pekalongan ketiga.
                        Awalnya, masjid ini dikenal sebagai Masjid Besar Pekalongan sebelum berganti nama menjadi Masjid Agung Al-Jami' pada tahun 1968 atas saran Habib Ali bin Ahmad Al-Athas.
                    </p>
                </div>
            </div>
        </section>

        <section id="majelis-keagamaan" class="grid">
            <div class="grid-item">
                <img src="kanzus_shalawat.jpg" alt="Kanzus Shalawat">
                <div>
                    <h2>Kanzus Shalawat</h2>
                    <p>Kanzus Sholawat di Pekalongan adalah sebuah majelis keagamaan yang berfokus pada kegiatan pengajian dan perayaan keagamaan, terutama peringatan Maulid Nabi Muhammad SAW. Majelis ini dipopulerkan oleh Habib Luthfi bin Yahya.
                        Perayaan Maulid di Kanzus Sholawat meliputi berbagai kegiatan seperti ziarah, pembacaan ratib, gambusan (pengajian), nikah maulid, pawai panjang jimat, dan puncak peringatan maulid akbar.
                        Kegiatan-kegiatan ini tidak hanya membawa semangat dakwah Islam tetapi juga sarat dengan nilai-nilai budaya yang islami.
                    </p>
                </div>
            </div>
        </section>

        <section id="kontak" class="contact">
            <h2>Kontak Kami</h2>
            <p>Email: salwafaiha27@gmail.com</p>
            <p>Instagram: salwafaihaa</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Pesona Wisata Religi Pekalongan. Semua hak dilindungi.</p>
    </footer>
</body>
</html>
