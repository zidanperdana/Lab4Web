# Lab4Web

Pertanyaan dan Tugas
1. Tambahkan Layout untuk menu About
=> buat single layout yang berisi deskripsi, portfolio, dll
2. Tambahkan layout untuk menu Contact
=> yang berisi form isian: nama, email, message, dll
Laporan Praktikum
1. Buatlah repository baru dengan nama Lab4Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Saya</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 2em 0;
        }

        h1 {
            font-size: 2.5em;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
        }

        .portfolio-item {
            margin-bottom: 20px;
        }

        .portfolio-item img {
            max-width: 100%;
            height: auto;
        }

        form {
            margin-top: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #555;
        }
        .img img {
            width: 100px;
            height: 100px;
            margin: 20px;
        }
        .img {
            display: flex;
            align-items: left;
            justify-content:left;

        }
    </style>
</head>
<body>
    <header>
        <h1>Portofolio Saya</h1>
    </header>

    <div class="container">
        <section>
            <h2>Deskripsi</h2>
            <p>Ini adalah deskripsi singkat tentang diri saya.</p>
            <h3>Maulana Zidan Perdana</h3>
            <p>Seorang manusia biasa</p>
        </section>
        <section class="portfolio-item"></section
        <section>
            <h2>Hubungi Saya</h2>
            <a href="https://www.facebook.com/maulana.z.perdana?mibextid=ZbWKwL" target="_blank">
                <i class="fab fa-facebook"></i>
              </a>
              
              <a href="https://www.instagram.com/mz_per?igshid=NTc4MTIwNjQ2YQ==" target="_blank">
                <i class="fab fa-instagram"></i>
              </a>
              
              <a href="https://www.tiktok.com/@ina_danzz" target="_blank">
                <i class="fab fa-tiktok"></i>
    
            <div class="img">
            </a>
            <a href="https://www.facebook.com/maulana.z.perdana?mibextid=ZbWKwL" target="_blank">
              <img src="FB.png" alt="Facebook">
            </a>
            
            <a href="https://www.instagram.com/mz_per?igshid=NTc4MTIwNjQ2YQ==" target="_blank">
              <img src="IG.png" alt="Instagram">
            </a>
            
            <a href="https://www.tiktok.com/@ina_danzz" target="_blank">
              <img src="TT.png" alt="TikTok">
            </a>
            <form>
                <label for="nama">Nama:</label>
                <input type="text" id="nama" name="nama" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="pesan">Pesan:</label>
                <textarea id="pesan" name="pesan" rows="4" required></textarea>

                <button type="submit">Kirim Pesan</button>
            </form>
        </section>
    </div>
</body>
</html>


seperti ini lah tampilan nya

![image](https://github.com/zidanperdana/Lab4Web/assets/116040175/c38c5580-37e4-44eb-a57b-50aa0ea8999a)
