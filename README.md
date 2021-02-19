# Desain-Web-CSS-Native
Tugas Pemrograman Web & Perangkat Bergerak
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Web Responsive</title>
    <link rel="stylesheet" href="ngetes.css">
</head>

<body>

    <div class="badan-utama">

        <header>
            <h2>Solaria</h2>
            <p>Your Culinary Journey</p>
        </header>

        <nav class="navigasi">
            <ul>
                <li><a class="active" href="#home">Home</a></li>
                <li><a href="#berita">Menu</a></li>
                <li><a href="#promosi">Promotion</a></li>
                <li><a href="#foto">Gallery</a></li>
                <li><a href="#kontak">Contact Us</a></li>
            </ul>
        </nav>

        <div class="banner">
            <img src="data:image/png;base64,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"
                alt="Solaria">
        </div>

        <div class="menu-kiri">
            <div class="kotak">
                <h3>Pemesanan</h3>
                <p>
                    Jika anda ingin memesan, Silahkan isi form Pemesanan yang sudah tersedia. Dengan cara klik 
                    tombol yang ada di bawah ini.
                </p>

                <a class="tombol tombol-pesan" href="#">Pesan</a>
            </div>
        </div>

        <div class="menu-tengah">
            <div class="kotak">
                <h3>Express Bowl Ikan Mayo</h3>
                <span class="tanggal-posting">
                    Diposting pada 11.00 WIB, 19 Februari 2021
                </span>

                <img src="https://solariaresto.co.id/wp-content/uploads/2020/11/Express-Bowl-Ikan-Mayo-Solaria-175x175.png"
                    alt="Express Bowl Ikan Mayo">

                <p>
                   Express Bowl Ikan Mayo adalah nasi yang dikemas dengan mangkok, kemudian ditambahkan fried fish dan disiram 
                   dengan saos mayonaise.
                </p>

                <a class="tombol tombol-lengkap" href="#">Selengkapnya</a>
            </div>
        </div>

        <div class="menu-kanan">
            <div class="kotak">
                <h3>Jadwal Buka</h3>
                <img src="https://solariaresto.co.id/wp-content/uploads/2020/11/02.-Nasi-Goreng-Spesial-Solaria.png"
                    alt="Nasi Goreng Spesial">

                <h4 align="center">Jadwal Buka</h4>
                <center>
                    <p>Senin-Minggu 08.00 WIB - 22.00 WIB</p>
                </center>
            </div>


            <div class="kotak">
                <h3>Menu Lainnya</h3>

                <nav class="menu-artikel">
                    <ul>
                        <li><a href="#">Menu Express Bowl</a></li>
                        <li><a href="#">Menu Spesial</a></li>
                        <li><a href="#">Menu Paket</a></li>
                        <li><a href="#">Spesial Drink & Minuman</a></li>
                    </ul>
                </nav>
            </div>
        </div>

        <footer>
            @copyright 2021|| by Ziya
        </footer>

    </div>

</body>

</html>
