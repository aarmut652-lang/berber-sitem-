

<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Furkan'ın Berber Salonu</title>

    <style>
        * {
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            margin: 0;
            background: #111;
            color: white;
            font-family: Arial, sans-serif;
        }

        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 28px;
            padding: 22px;
            border-bottom: 1px solid #d4af37;
        }

        .menu a {
            color: white;
            text-decoration: none;
        }

        .menu a:hover {
            color: #d4af37;
        }

        .hero {
            padding: 70px 20px;
            text-align: center;
            background: linear-gradient(135deg, #111, #29220e);
        }

        h1, h2 {
            color: #d4af37;
        }

        h1 {
            font-size: clamp(30px, 5vw, 48px);
        }

        .hero p {
            color: #ddd;
            line-height: 1.7;
        }

        .bolum {
            max-width: 1000px;
            margin: auto;
            padding: 40px 20px;
            text-align: center;
        }

        .hizmetler, .galeri {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 25px;
        }

        .kart {
            background: #222;
            border: 1px solid #d4af37;
            border-radius: 12px;
            padding: 25px;
            width: 250px;
        }

        .fiyat {
            color: #d4af37;
            font-size: 24px;
            font-weight: bold;
        }

        .foto {
            width: 280px;
            max-width: 100%;
        }

        .galeri img {
            width: 100%;
            height: 240px;
            object-fit: cover;
            border-radius: 12px;
            border: 1px solid #444;
        }

        .whatsapp {
            display: inline-block;
            background: #25D366;
            color: #111;
            padding: 15px 24px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 15px;
        }

        .whatsapp:hover {
            background: #1da851;
            color: white;
        }

        footer {
            text-align: center;
            padding: 25px;
            border-top: 1px solid #444;
            color: #aaa;
        }

        @media (max-width: 600px) {
            .hero {
                padding: 45px 16px;
            }

            .kart {
                width: 100%;
                max-width: 320px;
            }

            .foto {
                width: 100%;
            }
        }
    </style>
</head>

<body>

    <nav class="menu">
        <a href="#anasayfa">Ana Sayfa</a>
        <a href="#hizmetler">Hizmetler</a>
        <a href="#galeri">Galeri</a>
        <a href="#iletisim">İletişim</a>
    </nav>

    <header class="hero" id="anasayfa">
        <h1>Furkan'ın Berber Salonu</h1>
        <p>Tarzını keşfet. Bakımını bize bırak.</p>
        <p>Profesyonel saç kesimi ve sakal tasarımı.</p>
        <a class="whatsapp" href="#iletisim">Bize Ulaş</a>
    </header>

    <section class="bolum" id="hizmetler">
        <h2>Hizmetlerimiz</h2>

        <div class="hizmetler">
            <div class="kart">
                <h2>Saç Kesimi</h2>
                <p>Tarzına uygun saç kesimi.</p>
                <p class="fiyat">400 TL</p>
            </div>

            <div class="kart">
                <h2>Sakal Tasarımı</h2>
                <p>Özenli sakal bakımı.</p>
                <p class="fiyat">150 TL</p>
            </div>

            <div class="kart">
                <h2>Saç + Sakal</h2>
                <p>Birlikte bakım hizmeti.</p>
                <p class="fiyat">500 TL</p>
            </div>
        </div>
    </section>

    <section class="bolum" id="galeri">
        <h2>Salonumuzdan Kareler</h2>

        <div class="galeri">
            <div class="foto">
                <img src="https://images.unsplash.com/photo-1503951914875-452162b0f3f1?auto=format&fit=crop&w=800&q=80"
                     alt="Berber salonu">
            </div>

            <div class="foto">
                <img src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?auto=format&fit=crop&w=800&q=80"
                     alt="Saç kesimi">
            </div>

            <div class="foto">
                <img src="https://images.unsplash.com/photo-1599351431202-1e0f0137899a?auto=format&fit=crop&w=800&q=80"
                     alt="Berber bakımı">
            </div>
        </div>
    </section>

    <section class="bolum" id="iletisim">
        <h2>Bize Ulaş</h2>
        <p>Randevu ve bilgi için WhatsApp üzerinden iletişime geç.</p>

        <a class="whatsapp"
           href="https://wa.me/905551234567"
           target="_blank"
           rel="noopener noreferrer">
            WhatsApp'tan Bize Ulaş
        </a>

        <p>Telefon: Örnek numara</p>
    </section>

    <footer>
        © 2026 Furkan'ın Berber Salonu
    </footer>

</body>
</html>
