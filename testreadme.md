<!DOCTYPE html>  
<html lang="id">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Proyek Website - Tema Elektronik Gelap</title>  
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">  
    <style>  
        body {  
            font-family: 'Roboto', sans-serif;  
            margin: 0;  
            padding: 0;  
            background-color: #111111;  
            color: #FFFFFF;  
            display: flex;  
            flex-direction: column;  
            align-items: center;  
            justify-content: center;  
            height: 100vh;   
            text-align: center;  
        }  

        h1 {  
            font-weight: 700;  
            margin-bottom: 20px;  
        }  

        h2 {  
            color: #FFFFFF;  
        }  
        
        p {  
            font-weight: 400;  
            color: #CCCCCC;  
            margin: 10px 0;  
        }  

        .button-container {  
            display: flex;  
            flex-direction: column;  
            gap: 20px;  
            margin-top: 20px;  
        }  

        .button {  
            background-color: rgba(98, 88, 99, 0.7);  
            color: #ffffff;  
            padding: 15px 30px;  
            border: none;  
            border-radius: 5px;  
            cursor: pointer;  
            font-size: 18px;  
            transition: background-color 0.3s, transform 0.3s;  
        }  

        .button:hover {  
            background-color: rgba(98, 88, 99, 0.9);  
        }  

        .button:active {  
            transform: scale(0.95);  
        }  

        .content {  
            background-color: rgba(0, 0, 0, 0.6);  
            padding: 20px;  
            border-radius: 10px;  
            margin-top: 20px;  
            width: 80%;  
        }  

        .contact-info {  
            background-color: rgba(98, 88, 99, 0.8);  
            border-radius: 8px;  
            padding: 20px;  
            margin-top: 20px;  
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);  
        }  

        a {  
            color: #1e88e5;  
            text-decoration: none;  
        }  
        
        a:hover {  
            text-decoration: underline;  
        }  
    </style>  
</head>  
<body>  
    <h1>Selamat Datang di Website Kami</h1>  
    <p>Ini adalah Proyek Lain dari Saya, Silahkan Dikunjungi.</p>  

    <div class="button-container">  
        <button class="button" onclick="window.location.href='https://github.com/aryamusthofa/belajargithub/'">GITHUB SIMPANAN PROJECT WEBSITE INI</button>  
        <button class="button" onclick="window.location.href='https://aryamusthofa.github.io/belajargithub'">PERGI KE WEBSITE INI ALIAS REFRESH</button>  
        <button class="button" onclick="window.location.href='https://aryamusthofa.github.io/belajargithub/newfileproj.html'">PROJECT AWAL SAYA HANYA UNTUK PERCOBAAN</button>  
        <button class="button" onclick="window.location.href='https://aryamusthofa.github.io/belajargithub/projectone.html'">PROJECT KEDUA SAYA DALAM PERKEMBANGAN</button>  
    </div>  

    <div class="content">  
        <h2>Informasi Kontak</h2>  
        <p>Email: <a href="mailto:alamat@email.com">alamat@email.com</a></p>  
        <p>Website: <a href="https://linkwebsite.com" target="_blank">linkwebsite.com</a></p>  
    </div>  

    <div class="content">  
        <h2>Cara Penggunaan</h2>  
        <p>Jelaskan langkah-langkah untuk menggunakan aplikasi atau proyek Anda di sini.</p>  

        <h2>Teknologi</h2>  
        <ul>  
            <li>Teknologi 1</li>  
            <li>Teknologi 2</li>  
            <li>Teknologi 3</li>  
        </ul>  

        <h2>Kontribusi</h2>  
        <p>Kontribusi Anda sangat dihargai! Silahkan buka issue atau buat pull request.</p>  

        <h2>Lisensi</h2>  
        <p>Tentukan lisensi proyek Anda di sini. Misalnya, MIT.</p>  
        
        <h2>Tema Elektronik Gelap</h2>  
        <p>Untuk tampilan web yang menarik dan bertema elektronik gelap, kami sarankan menggunakan kombinasi warna gelap dan terang, font yang tajam, dan efek animasi yang sederhana.</p>  
        
        <h2>Warna:</h2>  
        <ul>  
            <li>Warna Utama: #111111 (hitam pekat)</li>  
            <li>Warna Sekunder: #222222 (abu-abu gelap)</li>  
            <li>Warna Aktif: #00FF00 (hijau terang)</li>  
            <li>Warna Teks: #FFFFFF (putih)</li>  
        </ul>  

        <h2>Font:</h2>  
        <ul>  
            <li>Judul: Roboto Black</li>  
            <li>Teks: Roboto Regular</li>  
        </ul>  

        <h2>Animasi:</h2>  
        <ul>  
            <li>Efek transisi halus (misalnya, fade-in)</li>  
            <li>Gerakan kecil (misalnya, hover yang sedikit bergerak)</li>  
        </ul>  

        <h2>Catatan</h2>  
        <p>Gambar pada README ini hanyalah contoh. Anda dapat mengganti dengan gambar Anda sendiri.</p>  
        <p>Anda dapat menyesuaikan desain dan gaya sesuai dengan kebutuhan proyek Anda.</p>  
        <p>Jangan lupa untuk mengganti placeholder dengan informasi yang relevan.</p>  
        <p>Semoga README ini bermanfaat!</p>  

        <h2>Panduan Membuat README</h2>  
        <ol>  
            <li><strong>Header:</strong> Gunakan header dengan judul yang menarik dan gambar proyek.</li>  
            <li><strong>Deskripsi:</strong> Tulis deskripsi singkat yang jelas tentang proyek Anda.</li>  
            <li><strong>Fitur:</strong> Daftar fitur utama dengan bullet point.</li>  
            <li><strong>Screenshot:</strong> Tampilkan screenshot yang menarik dari aplikasi Anda.</li>  
            <li><strong>Instalasi dan Penggunaan:</strong> Berikan petunjuk instalasi dan penggunaan yang jelas.</li>  
            <li><strong>Teknologi:</strong> Cantumkan teknologi utama yang digunakan dalam proyek.</li>  
            <li><strong>Kontribusi:</strong> Dorong kontribusi dengan informasi tentang cara berkontribusi.</li>  
            <li><strong>Lisensi:</strong> Jelaskan lisensi proyek Anda.</li>  
            <li><strong>Informasi Kontak:</strong> Berikan informasi kontak yang mudah diakses.</li>  
            <li><strong>Tema Elektronik Gelap:</strong> Jelaskan tema elektronik gelap dan berikan contoh desain.</li>  
            <li><strong>Catatan:</strong> Berikan catatan tambahan untuk membantu pembaca memahami README.</li>  
        </ol>  
        
        <h2>Tips tambahan:</h2>  
        <ul>  
            <li>Gunakan gambar dengan kualitas tinggi dan ukuran yang optimal.</li>  
            <li>Buat desain yang mudah dibaca dan diakses.</li>  
            <li>Gunakan markdown secara efektif untuk mengatur format dan struktur konten.</li>  
            <li>Pastikan README Anda informatif dan menarik bagi pembaca.</li>  
        </ul>  

        <p>Semoga ini membantu Anda membuat <code>README.md</code> yang menarik dan bermanfaat! 😉</p>  
    </div>  
</body>  
</html>