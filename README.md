<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raja Fotocopy Mendalo - Jilid Skripsi Cepat & Murah!</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        .hero {
            background: linear-gradient(135deg, #0033cc 0%, #0052ff 50%, #ff1493 100%);
            color: white;
            padding: 80px 20px 60px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 1px, transparent 1px);
            background-size: 50px 50px;
            animation: float 20s linear infinite;
        }

        @keyframes float {
            0% { transform: translate(0, 0); }
            100% { transform: translate(50px, 50px); }
        }

        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 900px;
            margin: 0 auto;
        }

        .logo {
            width: 140px;
            height: 140px;
            margin: 0 auto 20px;
            animation: bounce 2s ease-in-out infinite;
            filter: drop-shadow(0 10px 30px rgba(0,0,0,0.3));
        }
        
        .logo img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        h1 {
            font-size: 3em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .tagline {
            font-size: 1.4em;
            margin-bottom: 30px;
            font-weight: 300;
        }

        .promo-badge {
            display: inline-block;
            background: #ff1493;
            padding: 15px 30px;
            border-radius: 50px;
            font-size: 1.3em;
            font-weight: bold;
            margin: 20px 0;
            box-shadow: 0 5px 20px rgba(255,20,147,0.4);
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .cta-buttons {
            margin-top: 30px;
            display: flex;
            gap: 15px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn {
            padding: 15px 40px;
            border: none;
            border-radius: 50px;
            font-size: 1.1em;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            transition: all 0.3s ease;
        }

        .btn-primary {
            background: #25D366;
            color: white;
            box-shadow: 0 5px 20px rgba(37,211,102,0.4);
        }

        .btn-primary:hover {
            background: #1fb855;
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(37,211,102,0.5);
        }

        .btn-secondary {
            background: white;
            color: #0033cc;
            box-shadow: 0 5px 20px rgba(255,255,255,0.3);
        }

        .btn-secondary:hover {
            background: #f0f0f0;
            transform: translateY(-2px);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        .section-title {
            text-align: center;
            font-size: 2.5em;
            color: #0033cc;
            margin-bottom: 50px;
            position: relative;
            padding-bottom: 20px;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 4px;
            background: linear-gradient(90deg, #0033cc, #ff1493);
            border-radius: 2px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .service-card {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 5px 25px rgba(0,0,0,0.1);
            text-align: center;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,51,204,0.2);
            border-color: #0033cc;
        }

        .service-icon {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .service-card h3 {
            color: #0033cc;
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .service-card p {
            color: #666;
            line-height: 1.8;
        }

        .price {
            color: #ff1493;
            font-size: 1.3em;
            font-weight: bold;
            margin-top: 15px;
        }

        .gallery {
            padding: 60px 0;
            background: white;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .gallery-item {
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 25px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
            background: white;
        }

        .gallery-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,51,204,0.2);
        }

        .gallery-img {
            width: 100%;
            height: 250px;
            background: #f0f0f0;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3em;
            color: #0033cc;
        }

        .gallery-caption {
            padding: 20px;
        }

        .gallery-caption h4 {
            color: #0033cc;
            font-size: 1.3em;
            margin-bottom: 10px;
        }

        .gallery-caption p {
            color: #666;
            line-height: 1.6;
        }

        .features {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .feature-item {
            background: white;
            padding: 25px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            gap: 15px;
            box-shadow: 0 3px 15px rgba(0,0,0,0.08);
            transition: all 0.3s ease;
        }

        .feature-item:hover {
            transform: translateX(10px);
            box-shadow: 0 5px 20px rgba(255,20,147,0.2);
        }

        .feature-icon {
            font-size: 2em;
            min-width: 50px;
        }

        .location {
            background: #0033cc;
            color: white;
            text-align: center;
        }

        .map-info {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 20px;
            margin-top: 30px;
            backdrop-filter: blur(10px);
        }

        .map-info h3 {
            font-size: 1.8em;
            margin-bottom: 15px;
        }

        .map-info p {
            font-size: 1.2em;
            line-height: 1.8;
        }

        .contact {
            background: linear-gradient(135deg, #ff1493 0%, #ff69b4 100%);
            color: white;
            text-align: center;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .social-btn {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            padding: 12px 25px;
            background: rgba(255,255,255,0.2);
            border-radius: 50px;
            text-decoration: none;
            color: white;
            font-weight: bold;
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
        }

        .social-btn:hover {
            background: rgba(255,255,255,0.3);
            transform: scale(1.05);
        }

        footer {
            background: #1a1a1a;
            color: white;
            text-align: center;
            padding: 30px 20px;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .tagline {
                font-size: 1.1em;
            }
            
            .section-title {
                font-size: 1.8em;
            }

            .cta-buttons {
                flex-direction: column;
            }
            
            .btn {
                width: 100%;
                justify-content: center;
            }
        }

        .highlight {
            background: linear-gradient(120deg, #ffe66d 0%, #ffd93d 100%);
            padding: 3px 8px;
            border-radius: 5px;
            color: #333;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <div class="logo">
                <div style="width: 140px; height: 140px; background: white; border-radius: 20px; display: flex; align-items: center; justify-content: center; padding: 15px; box-shadow: 0 10px 30px rgba(0,0,0,0.3);">
                    <div style="font-size: 80px; font-weight: bold; color: #0033cc; font-family: Arial Black, sans-serif;">R</div>
                </div>
            </div>
            <h1>Raja Fotocopy Mendalo</h1>
            <p class="tagline">Solusi Lengkap Fotocopy, Jilid & Printing untuk Mahasiswa!</p>
            <div class="promo-badge">
                🎓 JILID SKRIPSI Rp20.000 - BISA DITUNGGU!
            </div>
            <div class="cta-buttons">
                <a href="https://wa.me/6285266653339?text=Halo%20Raja%20Fotocopy,%20saya%20mau%20order" class="btn btn-primary">
                    📱 Order via WhatsApp
                </a>
                <a href="#layanan" class="btn btn-secondary">
                    📋 Lihat Layanan
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="layanan" class="container">
        <h2 class="section-title">Layanan Kami</h2>
        <div class="services-grid">
            <div class="service-card">
                <div class="service-icon">📚</div>
                <h3>Jilid Skripsi/Tesis</h3>
                <p>Jilid skripsi, tesis, disertasi dengan hasil rapi dan berkualitas. Semua universitas!</p>
                <div class="price">Rp20.000</div>
                <p style="font-size: 0.9em; color: #ff1493; margin-top: 5px;">⚡ Bisa ditunggu!</p>
            </div>

            <div class="service-card">
                <div class="service-icon">📄</div>
                <h3>Fotocopy & Cetak</h3>
                <p>Fotocopy hitam-putih & warna. Cetak dokumen dengan mesin berkualitas tinggi.</p>
                <div class="price">Harga Terjangkau</div>
            </div>

            <div class="service-card">
                <div class="service-icon">🎨</div>
                <h3>Jilid Spiral & Buku</h3>
                <p>Jilid spiral untuk laporan, proposal, makalah. Jilid buku hard cover tersedia!</p>
                <div class="price">Rapi & Kuat</div>
            </div>

            <div class="service-card">
                <div class="service-icon">🪪</div>
                <h3>ID Card & Lanyard</h3>
                <p>Cetak ID card berkualitas dengan lanyard custom. Cocok untuk instansi & perusahaan.</p>
                <div class="price">Proses Cepat</div>
            </div>

            <div class="service-card">
                <div class="service-icon">🖼️</div>
                <h3>Poster & Banner</h3>
                <p>Cetak poster, banner, dan materi promosi dengan warna tajam dan hasil maksimal.</p>
                <div class="price">Kualitas HD</div>
            </div>

            <div class="service-card">
                <div class="service-icon">✏️</div>
                <h3>Perlengkapan ATK</h3>
                <p>Lengkap! Pulpen, kertas, map, sampai perlengkapan kantor tersedia di tempat kami.</p>
                <div class="price">Lengkap & Murah</div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery">
        <div class="container">
            <h2 class="section-title">Galeri Hasil Kerja Kami</h2>
            <p style="text-align: center; font-size: 1.2em; color: #666; margin-bottom: 40px;">
                Lihat berbagai hasil pekerjaan kami yang sudah dipercaya ribuan pelanggan!
            </p>
            <div class="gallery-grid">
                <div class="gallery-item">
                    <div class="gallery-img" style="background: linear-gradient(rgba(0,51,204,0.1), rgba(0,51,204,0.1)), url('data:image/svg+xml,%3Csvg xmlns=%27http://www.w3.org/2000/svg%27 viewBox=%270 0 400 300%27%3E%3Crect fill=%27%23f0f0f0%27 width=%27400%27 height=%27300%27/%3E%3Ctext x=%2750%25%27 y=%2750%25%27 dominant-baseline=%27middle%27 text-anchor=%27middle%27 font-family=%27Arial%27 font-size=%2724%27 fill=%27%230033cc%27%3E🪪 Lanyard %26 ID Card%3C/text%3E%3C/svg%3E'); background-size: cover; background-position: center;"></div>
                    <div class="gallery-caption">
                        <h4>Lanyard Custom</h4>
                        <p>Lanyard berkualitas dengan design custom untuk berbagai instansi</p>
                    </div>
                </div>

                <div class="gallery-item">
                    <div class="gallery-img" style="background: linear-gradient(rgba(0,51,204,0.1), rgba(0,51,204,0.1)), url('data:image/svg+xml,%3Csvg xmlns=%27http://www.w3.org/2000/svg%27 viewBox=%270 0 400 300%27%3E%3Crect fill=%27%23f0f0f0%27 width=%27400%27 height=%27300%27/%3E%3Ctext x=%2750%25%27 y=%2750%25%27 dominant-baseline=%27middle%27 text-anchor=%27middle%27 font-family=%27Arial%27 font-size=%2724%27 fill=%27%230033cc%27%3E📚 Jilid Skripsi%3C/text%3E%3C/svg%3E'); background-size: cover; background-position: center;"></div>
                    <div class="gallery-caption">
                        <h4>Jilid Skripsi & Disertasi</h4>
                        <p>Hasil jilid rapi dan berkualitas untuk berbagai universitas</p>
                    </div>
                </div>

                <div class="gallery-item">
                    <div class="gallery-img" style="background: linear-gradient(rgba(0,51,204,0.1), rgba(0,51,204,0.1)), url('data:image/svg+xml,%3Csvg xmlns=%27http://www.w3.org/2000/svg%27 viewBox=%270 0 400 300%27%3E%3Crect fill=%27%23f0f0f0%27 width=%27400%27 height=%27300%27/%3E%3Ctext x=%2750%25%27 y=%2750%25%27 dominant-baseline=%27middle%27 text-anchor=%27middle%27 font-family=%27Arial%27 font-size=%2724%27 fill=%27%230033cc%27%3E🏪 Toko Kami%3C/text%3E%3C/svg%3E'); background-size: cover; background-position: center;"></div>
                    <div class="gallery-caption">
                        <h4>Lokasi Strategis</h4>
                        <p>Depan Klinik UNJA, mudah diakses mahasiswa dan umum</p>
                    </div>
                </div>

                <div class="gallery-item">
                    <div class="gallery-img" style="background: linear-gradient(rgba(0,51,204,0.1), rgba(0,51,204,0.1)), url('data:image/svg+xml,%3Csvg xmlns=%27http://www.w3.org/2000/svg%27 viewBox=%270 0 400 300%27%3E%3Crect fill=%27%23f0f0f0%27 width=%27400%27 height=%27300%27/%3E%3Ctext x=%2750%25%27 y=%2750%25%27 dominant-baseline=%27middle%27 text-anchor=%27middle%27 font-family=%27Arial%27 font-size=%2724%27 fill=%27%230033cc%27%3E👥 Layanan Ramah%3C/text%3E%3C/svg%3E'); background-size: cover; background-position: center;"></div>
                    <div class="gallery-caption">
                        <h4>Tim Profesional</h4>
                        <p>Dilayani oleh tim yang berpengalaman dan ramah</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="container">
            <h2 class="section-title">Kenapa Pilih Kami?</h2>
            <div class="features-grid">
                <div class="feature-item">
                    <div class="feature-icon">⚡</div>
                    <div>
                        <strong>Proses Cepat</strong>
                        <p>Jilid skripsi bisa ditunggu, hasil kilat tanpa mengurangi kualitas!</p>
                    </div>
                </div>

                <div class="feature-item">
                    <div class="feature-icon">💰</div>
                    <div>
                        <strong>Harga Murah</strong>
                        <p>Harga terjangkau untuk mahasiswa, diskon untuk order dalam jumlah banyak!</p>
                    </div>
                </div>

                <div class="feature-item">
                    <div class="feature-icon">✨</div>
                    <div>
                        <strong>Kualitas Terjamin</strong>
                        <p>Hasil rapi, kuat, dan tahan lama. Mesin fotocopy warna tersedia!</p>
                    </div>
                </div>

                <div class="feature-item">
                    <div class="feature-icon">🏆</div>
                    <div>
                        <strong>Berpengalaman</strong>
                        <p>Sudah melayani ribuan mahasiswa & instansi dengan hasil memuaskan!</p>
                    </div>
                </div>

                <div class="feature-item">
                    <div class="feature-icon">🕒</div>
                    <div>
                        <strong>Buka Pagi-Malam</strong>
                        <p>Buka dari 06.30 - 22.00, siap melayani dari pagi hingga malam!</p>
                    </div>
                </div>

                <div class="feature-item">
                    <div class="feature-icon">📍</div>
                    <div>
                        <strong>Lokasi Strategis</strong>
                        <p>Depan Klinik UNJA, mudah dijangkau untuk mahasiswa dan umum!</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Location Section -->
    <section class="location">
        <div class="container">
            <h2 class="section-title" style="color: white;">Lokasi Kami</h2>
            <div class="map-info">
                <h3>📍 Raja Fotocopy Mendalo</h3>
                <p><strong>Alamat:</strong> Jalan Flamboyan, Depan Klinik UNJA<br>
                Mendalo, Jambi</p>
                <p style="margin-top: 20px;"><strong>⏰ Jam Operasional:</strong><br>
                <span class="highlight">Setiap Hari: 06.30 - 22.00 WIB</span></p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact">
        <div class="container">
            <h2 class="section-title" style="color: white;">Hubungi Kami Sekarang!</h2>
            <p style="font-size: 1.3em; margin-bottom: 30px;">
                Butuh jilid skripsi kilat? Order sekarang via WhatsApp!
            </p>
            <a href="https://wa.me/6285266653339?text=Halo%20Raja%20Fotocopy,%20saya%20mau%20order" class="btn btn-primary" style="font-size: 1.2em; padding: 18px 50px;">
                💬 Chat WhatsApp: 0852-6665-3339
            </a>
            
            <div class="social-links">
                <a href="https://instagram.com/rajafcmendalo" class="social-btn" target="_blank">
                    📸 Instagram: @rajafcmendalo
                </a>
                <a href="https://tiktok.com/@rajafcmendalo" class="social-btn" target="_blank">
                    🎵 TikTok: @rajafcmendalo
                </a>
            </div>

            <p style="margin-top: 40px; font-size: 1.1em;">
                <strong>Raja Fotocopy Mendalo</strong><br>
                <em>"Cepat, Murah & Berkualitas!"</em>
            </p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Raja Fotocopy Mendalo. All Rights Reserved.</p>
        <p style="margin-top: 10px; font-size: 0.9em;">Jilid Skripsi, Tesis, Disertasi - Fotocopy - ATK - Printing</p>
    </footer>
</body>
</html>
