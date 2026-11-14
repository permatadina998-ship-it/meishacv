# meishacv
about me

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Creative CV</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
    scroll-behavior: smooth;
}

body {
    background: #080b18;
    color: white;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 8%;
    background: #10152b;
    position: sticky;
    top: 0;
    z-index: 10;
}

.logo {
    color: #00e5ff;
    font-size: 25px;
    font-weight: bold;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
}

nav a:hover {
    color: #00e5ff;
}

.hero {
    min-height: 90vh;
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding: 50px 8%;
    flex-wrap: wrap;
    gap: 30px;
}

.hero-text h3 {
    color: #00e5ff;
    font-size: 22px;
}

.hero-text h1 {
    font-size: 48px;
    margin: 15px 0;
}

.hero-text span {
    color: #00e5ff;
}

.hero-text p {
    color: #b9c1d9;
    line-height: 1.8;
    max-width: 500px;
}

.btn {
    display: inline-block;
    margin-top: 25px;
    padding: 12px 25px;
    background: #00e5ff;
    color: #080b18;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    transition: .3s;
}

.btn:hover {
    background: white;
    transform: translateY(-4px);
}

.profile {
    width: 260px;
    height: 260px;
    border-radius: 50%;
    border: 5px solid #00e5ff;
    box-shadow: 0 0 35px #00e5ff;
    object-fit: cover;
}

section {
    padding: 70px 8%;
}

.title {
    text-align: center;
    font-size: 32px;
    margin-bottom: 40px;
}

.title span {
    color: #00e5ff;
}

.about {
    background: #10152b;
    border-radius: 20px;
    padding: 30px;
    line-height: 1.9;
    color: #cbd5e1;
    max-width: 900px;
    margin: auto;
    text-align: center;
}

.skills {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(200px,1fr));
    gap: 20px;
}

.card {
    background: #151c36;
    padding: 25px;
    border-radius: 15px;
    text-align: center;
    border: 1px solid #26395b;
    transition: .3s;
}

.card:hover {
    transform: translateY(-8px);
    border-color: #00e5ff;
    box-shadow: 0 0 20px #00e5ff44;
}

.card h3 {
    color: #00e5ff;
    margin-bottom: 12px;
}

.card p {
    color: #cbd5e1;
    line-height: 1.7;
}

.contact {
    text-align: center;
    background: #10152b;
}

.contact p {
    margin: 12px;
    color: #cbd5e1;
}

footer {
    text-align: center;
    padding: 25px;
    color: #8993ae;
}

@media(max-width:600px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    nav a {
        margin: 5px;
        font-size: 13px;
    }

    .hero-text h1 {
        font-size: 35px;
    }

    .profile {
        width: 200px;
        height: 200px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">MY PORTFOLIO.</div>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skill</a>
        <a href="#education">Pendidikan</a>
        <a href="#contact">Kontak</a>
    </nav>
</header>

<section class="hero" id="home">
    <div class="hero-text">
        <h3>HALO, SELAMAT DATANG!</h3>
        <h1>Saya <span>MEISHA DALIMAH</span></h1>
        <h3>Pelajar Teknik Komputer dan Jaringan</h3>
        <p>
            Saya adalah seorang pelajar yang memiliki minat
            dalam teknologi, komputer, jaringan internet,
            dan pengembangan website.
        

<section id="about">
    <h2 class="title">Tentang <span>Saya</span>/h2>
    <div class="about">
        <p>
            Perkenalkan, nama saya Nama Kamu.
            Saya merupakan siswa jurusan Teknik Komputer
            dan Jaringan (TKJ). Saya senang mempelajari
            dunia teknologi, instalasi komputer, jaringan,
            troubleshooting, dan desain website.
            Saya ingin terus mengembangkan kemampuan
            dan mendapatkan pengalaman baru.
        </p>
    </div>
</section>


    <div class="skills">
        <div class="card">
            <h3>💻 Hardware</h3>
            <p>Merakit komputer dan mengenal komponen PC.</p>
        </div>

        <div class="card">
            <h3>🌐 Networking</h3>
            <p>Konfigurasi jaringan LAN dan dasar router.</p>
        </div>

        <div class="card">
            <h3>🔧 Troubleshooting</h3>
            <p>Menganalisis dan memperbaiki masalah komputer.</p>
        </div>

        <div class="card">
            <h3>⌨️ Web Design</h3>
            <p>Membuat website menggunakan HTML 

<section id="contact" class="contact">
    <h2 class="title">Hubungi <span>Saya</span></h2>
    <p>📧 Email: emailkamu@gmail.com</p>
    <p>📱 WhatsApp: 08xxxxxxxxxx</p>
    <p>📍 Alamat: Kota tempat tinggal</p>
    <a href="mailto:emailkamu@gmail.com" class="btn">
        Kirim Email
    </a>
</section>

<footer>
    <p>© 2026 My Creative CV | Dibuat dengan HTML & CSS</p>
</footer>

</body>
</html>
