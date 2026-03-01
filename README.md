# Minpro_1_PBW
### GHIFARI AL AZHAR
### 2409116059

# Website Portofolio

## Deskripsi Project
Website portofolio sederhana berbasis HTML dan CSS dengan bantuan Bootstrap 5. Website ini terdiri dari tiga section utama yaitu Home, About Me, dan Certificates. Website bersifat statis dan responsif.

---

## Tampilan Setiap Section

### 1. Home Section
<img width="1235" height="869" alt="image" src="https://github.com/user-attachments/assets/1bc1c75f-c882-41d2-a05e-1316f3d86d3f" />

Berisi:
- Nama
- Perkenalan singkat
- Foto profil
- Navbar

Home menggunakan Bootstrap untuk layout dan CSS custom untuk styling gradient serta tampilan visual.

---

### 2. About Me Section
<img width="1234" height="865" alt="image" src="https://github.com/user-attachments/assets/d946edc8-1c20-4cba-b51e-7a01820c51ba" />

Berisi:
- Deskripsi diri
- Pengalaman
- Skills menggunakan progress bar

Progress bar dibuat menggunakan komponen Bootstrap dan dimodifikasi dengan CSS untuk memberikan tampilan yang lebih menarik.

---

### 3. Certificates Section
<img width="1233" height="846" alt="image" src="https://github.com/user-attachments/assets/96f7b5b4-e7c6-4a5e-8a54-26325e7c97aa" />

Berisi:
- Daftar sertifikat dalam bentuk card
- Layout grid menggunakan Bootstrap (row & col)
- Gambar sertifikat 

Card dibuat menggunakan komponen Bootstrap dan disusun responsif menggunakan Grid System.

---

# Penjelasan Code Setiap Section / Fitur

### 1. Navbar

Navbar dibuat menggunakan komponen bawaan Bootstrap 5 untuk mendukung tampilan responsif.

```bash
<nav class="navbar navbar-expand-lg navbar-dark fixed-top">
    <div class="container">
        <a class="navbar-brand" href="#">MyPortfolio</a>

        <button class="navbar-toggler" type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#home">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#about">About Me</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#certificates">Certificates</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
```
Penjelasan:
navbar-expand-lg → Navbar akan berubah menjadi hamburger menu pada layar kecil.
fixed-top → Navbar tetap berada di bagian atas saat halaman di-scroll.
data-bs-toggle="collapse" → Mengaktifkan fitur collapse Bootstrap.
data-bs-target="#navbarNav" → Menghubungkan tombol toggle dengan menu navigasi.


### 2. Home Section (Hero Section)

Home section digunakan sebagai tampilan awal website dan berisi perkenalan singkat.
```bash
<section id="home" class="vh-100 d-flex align-items-center">
    <div class="container text-center">
        <img src="" alt="Foto Profil" class="profile-img">
        <h1>Ghifari Al Azhar</h1>
        <p>Mahasiswa Sistem Informasi yang memiliki minat dalam dunia film dan game.</p>
    </div>
</section>
```
Penjelasan:
vh-100 → Tinggi section mengikuti 100% tinggi layar.
d-flex align-items-center → Menggunakan Flexbox untuk menengahkan konten secara vertikal.
profile-img → Class CSS untuk mengatur ukuran, border, dan shadow foto profil.

### 3. About Me Section
Section ini menggunakan Grid System Bootstrap untuk membagi konten menjadi dua kolom.
```bash
<section id="about">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <h5>Deskripsi</h5>
                <p>Penjelasan tentang diri.</p>

                <h5>Pengalaman</h5>
                <ul>
                    <li>Project Website</li>
                    <li>Project Database</li>
                </ul>
            </div>

            <div class="col-md-6">
                <h5>Skills</h5>
                <div class="progress">
                    <div class="progress-bar" style="width: 85%"></div>
                </div>
            </div>
        </div>
    </div>
</section>
```
row → Baris grid Bootstrap.
col-md-6 → Membagi menjadi dua kolom pada layar medium ke atas.
progress → Komponen progress bar Bootstrap.
style="width: 85%" → Menentukan persentase skill.

### 4. Certificates Section
Bagian ini menggunakan komponen Card dan Grid System Bootstrap
```bash
<section id="certificates">
    <div class="container">
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="" alt="Sertifikat" class="certificate-img">
                    <div class="card-body">
                        <h5 class="card-title">Certificate 1</h5>
                        <p class="card-text">Deskripsi singkat sertifikat.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
```
col-md-4 → Menampilkan 3 card dalam satu baris pada layar medium ke atas.
card → Komponen Bootstrap untuk menampilkan konten dalam bentuk kotak.

---

## Teknologi yang Digunakan
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="30" height="30" />
- HTML5
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="30" height="30" />
- CSS3
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-original-wordmark.svg" alt="Bootstrap" width="30" height="30" />
- Bootstrap 5.3.8

