<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clerivo Home Cleaning</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header / Navbar -->
    <header>
        <h1>Clerivo Home Cleaning</h1>
        <nav>
            <a href="#home">Beranda</a>
            <a href="#services">Layanan</a>
            <a href="#about">Tentang Kami</a>
            <a href="#contact">Kontak</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h2>Rumah Bersih, Hidup Nyaman</h2>
        <p>Layanan pembersihan rumah profesional dengan harga terjangkau.</p>
        <button onclick="alert('Terima kasih! Kami akan menghubungi Anda segera.')">Pesan Sekarang</button>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2>Layanan Kami</h2>
        <div class="service-container">
            <div class="service-card">
                <h3>Pembersihan Rumah</h3>
                <p>Menyapu, mengepel, dan membersihkan seluruh sudut rumah Anda.</p>
            </div>
            <div class="service-card">
                <h3>Pembersihan Dapur</h3>
                <p>Membersihkan area dapur, peralatan, dan permukaan kerja.</p>
            </div>
            <div class="service-card">
                <h3>Pembersihan Kamar Mandi</h3>
                <p>Menyeka, mendesinfeksi, dan menghilangkan noda membandel.</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>Tentang Kami</h2>
        <p>Clerivo Home Cleaning berdedikasi memberikan layanan kebersihan rumah terbaik dengan tenaga profesional dan harga bersahabat.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Kontak Kami</h2>
        <form onsubmit="return submitForm(event)">
            <input type="text" placeholder="Nama Anda" required>
            <input type="clerivobersihtanpakompromi@gmail.com" placeholder="Email Anda" required>
            <textarea placeholder="Pesan" required></textarea>
            <button type="submit">Kirim</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2026 Clerivo Home Cleaning. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
