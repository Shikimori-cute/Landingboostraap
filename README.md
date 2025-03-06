# <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Landing Page Bootstrap</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .hero {
            background: url('https://source.unsplash.com/1600x900/?business,technology') no-repeat center center;
            background-size: cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .feature-icon {
            font-size: 3rem;
            color: #0d6efd;
        }
    </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light shadow">
    <div class="container">
        <a class="navbar-brand fw-bold" href="#">MyBrand</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#features">Fitur</a></li>
                <li class="nav-item"><a class="nav-link" href="#testimonials">Testimoni</a></li>
                <li class="nav-item"><a class="nav-link" href="#contact">Kontak</a></li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<header class="hero">
    <div class="container">
        <h1 class="fw-bold">Solusi Digital Terbaik Untuk Bisnis Anda</h1>
        <p class="lead">Tingkatkan produktivitas dan efisiensi dengan teknologi terkini.</p>
        <a href="#contact" class="btn btn-primary btn-lg">Hubungi Kami</a>
    </div>
</header>

<!-- Features Section -->
<section id="features" class="py-5">
    <div class="container">
        <div class="text-center">
            <h2 class="fw-bold">Mengapa Memilih Kami?</h2>
            <p class="text-muted">Kami menawarkan layanan terbaik dengan fitur unggulan.</p>
        </div>
        <div class="row text-center mt-4">
            <div class="col-md-4">
                <i class="feature-icon bi bi-speedometer2"></i>
                <h4>Kecepatan</h4>
                <p>Layanan cepat dan efisien untuk kebutuhan bisnis Anda.</p>
            </div>
            <div class="col-md-4">
                <i class="feature-icon bi bi-shield-lock"></i>
                <h4>Keamanan</h4>
                <p>Data Anda aman dengan teknologi enkripsi tingkat tinggi.</p>
            </div>
            <div class="col-md-4">
                <i class="feature-icon bi bi-people"></i>
                <h4>Dukungan 24/7</h4>
                <p>Tim kami siap membantu kapan saja Anda butuhkan.</p>
            </div>
        </div>
    </div>
</section>

<!-- Testimonials -->
<section id="testimonials" class="bg-light py-5">
    <div class="container">
        <div class="text-center">
            <h2 class="fw-bold">Apa Kata Mereka?</h2>
            <p class="text-muted">Pendapat klien kami tentang layanan yang kami berikan.</p>
        </div>
        <div class="row mt-4">
            <div class="col-md-4">
                <div class="card p-3 shadow">
                    <p>"Layanan terbaik yang pernah saya gunakan. Sangat direkomendasikan!"</p>
                    <h5 class="fw-bold">- John Doe</h5>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card p-3 shadow">
                    <p>"Kecepatan dan keamanan yang luar biasa. Bisnis saya berkembang pesat."</p>
                    <h5 class="fw-bold">- Jane Smith</h5>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card p-3 shadow">
                    <p>"Dukungan pelanggan yang sangat responsif dan profesional."</p>
                    <h5 class="fw-bold">- Michael Brown</h5>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-5">
    <div class="container">
        <div class="text-center">
            <h2 class="fw-bold">Hubungi Kami</h2>
            <p class="text-muted">Konsultasikan kebutuhan bisnis Anda dengan kami.</p>
        </div>
        <div class="row mt-4">
            <div class="col-md-6">
                <form>
                    <div class="mb-3">
                        <label class="form-label">Nama</label>
                        <input type="text" class="form-control" placeholder="Masukkan nama Anda">
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Email</label>
                        <input type="email" class="form-control" placeholder="Masukkan email Anda">
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Pesan</label>
                        <textarea class="form-control" rows="4" placeholder="Tulis pesan Anda"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Kirim</button>
                </form>
            </div>
            <div class="col-md-6">
                <h5>Alamat Kami</h5>
                <p>Jl. Contoh No. 123, Jakarta</p>
                <h5>Email</h5>
                <p>info@example.com</p>
                <h5>Telepon</h5>
                <p>+62 812 3456 7890</p>
            </div>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="bg-dark text-white text-center py-3">
    <p class="mb-0">&copy; 2025 MyBrand. All Rights Reserved.</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
