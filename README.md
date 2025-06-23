<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Warung Mie - UMKM</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f8f8f8; }
        header { background: #d7263d; color: #fff; padding: 20px 0; text-align: center; }
        nav { background: #1a1a1a; text-align: center; }
        nav a { color: #fff; padding: 14px 20px; display: inline-block; text-decoration: none; }
        nav a:hover { background: #d7263d; }
        .container { max-width: 900px; margin: 30px auto; background: #fff; padding: 30px; box-shadow: 0 0 10px #ddd; }
        h1, h2, h3 { color: #d7263d; }
        .menu-list { display: flex; flex-wrap: wrap; gap: 20px; }
        .menu-item { flex: 1 1 200px; background: #f1f1f1; padding: 15px; border-radius: 8px; box-shadow: 0 0 5px #ccc; }
        .menu-item img { width: 100%; border-radius: 8px; }
        .contact { margin-top: 30px; }
        footer { text-align: center; padding: 15px 0; background: #1a1a1a; color: #fff; position: relative; bottom: 0; width: 100%; }
    </style>
</head>
<body>
    <header>
        <h1>Warung Mie</h1>
        <p>Mie lezat, harga bersahabat!</p>
    </header>
    <nav>
        <a href="#tentang">Tentang</a>
        <a href="#menu">Menu</a>
        <a href="#kontak">Kontak</a>
    </nav>
    <div class="container">
        <section id="tentang">
            <h2>Tentang Kami</h2>
            <p>
                Warung Mie adalah usaha UMKM yang menyediakan berbagai macam mie dengan cita rasa khas dan harga terjangkau. Kami berkomitmen memberikan layanan terbaik dan bahan-bahan berkualitas untuk pelanggan kami.
            </p>
        </section>
        <section id="menu">
            <h2>Menu Andalan</h2>
            <div class="menu-list">
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=400&q=80" alt="Mie Goreng">
                    <h3>Mie Goreng</h3>
                    <p>Mie goreng spesial dengan topping ayam dan sayuran segar.</p>
                    <strong>Rp 12.000</strong>
                </div>
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1502741338009-cac2772e18bc?auto=format&fit=crop&w=400&q=80" alt="Mie Kuah">
                    <h3>Mie Kuah</h3>
                    <p>Mie kuah gurih dengan kaldu ayam dan bawang goreng.</p>
                    <strong>Rp 13.000</strong>
                </div>
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1467003909585-2f8a72700288?auto=format&fit=crop&w=400&q=80" alt="Mie Ayam">
                    <h3>Mie Ayam</h3>
                    <p>Mie ayam lezat dengan potongan ayam melimpah dan pangsit.</p>
                    <strong>Rp 15.000</strong>
                </div>
            </div>
        </section>
        <section id="kontak" class="contact">
            <h2>Kontak</h2>
            <p>Alamat: Jl. Contoh No. 123, Kota UMKM</p>
            <p>Telepon: 0812-3456-7890</p>
            <p>Email: warungmie@email.com</p>
        </section>
    </div>
    <footer>
        &copy; 2025 Warung Mie. All Rights Reserved.
    </footer>
</body>
</html>
