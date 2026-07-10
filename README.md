# 👨‍💻 Sony Chandra Maulana, S.Kom.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lorddaud)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sonychandmaulana@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/6281312157307)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/SonyChand)

---

## 🧑‍💼 Tentang Saya

Full-Stack Software Engineer & Systems Architect dengan jam terbang tinggi dalam mendesain, membangun, dan mengorkestrasi sistem produksi skala *Enterprise*, Pemerintahan, Edukasi, dan Militer. 

Fokus keahlian saya berada pada arsitektur **Distributed Microservices (Go)**, **Ekosistem Monolitik Terpadu (Laravel/Livewire/Inertia)**, serta **Modern Frontend Interfaces (Vue/Nuxt/React)**. Saya terbiasa menangani siklus hidup pengembangan perangkat lunak hulu ke hilir: dari rekayasa sistem akuntansi kompleks, *payment gateway* terpusat, analitik data masif, hingga infrastruktur server berbasis *container* (Docker/Traefik).

> _"Teknologi téh lain ukur nyieun kode wungkul, tapi kumaha cara nyieun solusi nu ngabantuan rahayat, méré mangpaat, jeung ngahirupkeun harepan pikeun masa depan." – Sony Chandra Maulana_

---

## 🛠️ Tech Stack Matrix

- **Backend & Microservices:** Go (Standard Library, Gin, Fiber), PHP (Laravel 11/12, CodeIgniter), Node.js, Python
- **Frontend & SSR Ecosystem:** Vue.js (Vue 3, Nuxt.js, Vite), React, Inertia.js, Laravel Livewire, Astro, Tailwind CSS, Bootstrap
- **Database & Data Structure:** PostgreSQL, MySQL/MariaDB, SQLite, Redis
- **Architecture & Infrastructure:** Docker & Docker Compose, Traefik API Gateway, Nginx Reverse Proxy, Cloudflare, AWS Core Services, GCP, CI/CD Pipeline
- **Integration & APIs:** Payment Gateways (Duitku, Midtrans), WhatsApp API, Email SMTP Pipelines, RESTful API Design

---

## 💼 High-Level System Architecture & Ecosystems

Sebagai Lead Developer, saya memimpin pengembangan berbagai *massive ecosystems* yang terdiri dari banyak aplikasi yang saling terhubung:

### 🎓 1. University Admission & Management Ecosystem (Universitas BTH & UNPAS)
Membangun ekosistem penerimaan mahasiswa baru dan portal informasi perguruan tinggi hulu ke hilir yang menangani ribuan transaksi dan pendaftar secara bersamaan.
- **Pendaftaran & Seleksi Portal (`pendaftaran.universitas-bth.ac.id`):** Engine pendaftaran terintegrasi dengan sistem Computer Based Test (CBT) adaptif. Mendukung validasi dokumen, *Email OTP validation*, penjadwalan ujian otomatis, hingga manajemen kelulusan berbasis skor (IRT Scoring Modules).
- **Omnichannel Payment & Installment Core:** Sistem penagihan yang menangani pembayaran via **Duitku Gateway** lengkap dengan *Asynchronous Installment Schema* (skema cicilan otomatis), webhook callback, pelacakan riwayat pembayaran, hingga pembuatan invoice/kuitansi digital.
- **SSG Information Portal (`info.admisi.bth`):** Front-end terpisah berbasis **Nuxt.js/Vue** untuk performa SEO maksimal dan *load-time* instan, menampilkan informasi biaya kuliah, jalur pendaftaran, hingga prodi.
- **Headless CMS Engine (`cms.pmb.universitas-bth.ac.id` / `cms-unpas`):** Backend pengelolaan konten terpusat (Fakultas, Agenda, Jurnal, Beasiswa) berbasis API yang mendistribusikan data ke seluruh *landing page* dan portal informasi kampus.

### 🧠 2. Jatidiri Psychological Microservices Ecosystem (`jatidiri.app`)
Infrastruktur asesmen psikologis tingkat lanjut untuk skala korporasi yang dipecah ke dalam berbagai layanan mikro (Microservices) yang independen.
- **Distributed Microservices Mesh:** Pemisahan *concern* ke dalam puluhan modul independen: *Auth Service*, *Assessment Service*, *BK Service*, *Preparation Service*, *Komunitas Service*, hingga *Halopsy Service* (Telekonseling) yang di-routing melalui **Traefik API Gateway Core**.
- **Massive Diagnostic Engines:** Mesin kalkulasi tes psikologi lengkap (CFIT, DISC, EPPS, FRT, IAA, IST, LBC, MAP, Pauli, PM, RMIB) yang diproses secara *real-time* dan konkruen menggunakan performa tinggi dari **Golang**.
- **Automated Psychogram & AI Reporting:** Generator laporan komprehensif (Psikogram) yang terintegrasi dengan analitik dan AI (*Gemini Service*) untuk menghasilkan deskripsi karakter, bakat, karier, dan rekomendasi klinis dalam hitungan detik.

### 💰 3. Enterprise Finance & Accounting System (`keuangan`)
Platform ERP *(Enterprise Resource Planning)* untuk manajemen finansial dan akuntansi tingkat lanjut.
- **Automated General Ledger (Jurnal Umum):** Pencatatan otomatis untuk setiap transaksi (KasBank, Mutasi Rekening, Pembayaran Dimuka, Penjualan, Pembelian, Produksi) lengkap dengan *chart of accounts* (CoA) yang dapat dikustomisasi.
- **Asset Depreciation & HPP Engine:** Kalkulator otomatis untuk Harga Pokok Penjualan (HPP) produksi dan penyusutan aset tetap *(Asset Depreciation)* secara periodik.
- **Financial Reporting Suite:** Pembuatan laporan Neraca, Laba/Rugi, Arus Kas, dan Perubahan Ekuitas yang digenerate dalam format tabel dan PDF presisi tinggi.

### 📝 4. EdTech & Advanced CBT Platform (`cbtqu`)
Sistem Computer-Based Test (CBT) dan Learning Management System dengan fitur analitik cerdas.
- **Student Analytics & Item Analysis:** Modul analitik dalam Laravel Livewire/Volt yang membedah pola pengerjaan siswa dan menganalisis tingkat kesulitan butir soal secara statistik.
- **AI-Powered Testimonial Generator:** Arsitektur generator testimoni berbasis *Blueprints* dan *Persona Factory* untuk merangkum sentimen pengguna secara otomatis.
- **Scalable Exam Sessions:** Infrastruktur pengerjaan ujian serentak (Tryout Nasional, USM Ukrida, Persiapan PTN) dengan sistem *auto-save* jawaban dan manajemen transaksi via **Midtrans**.

### 🗳️ 5. Smartpol — Election & Campaign Management System
Sistem intelijen politik dan pemantauan kampanye relawan hulu ke hilir.
- **Real-time Vote & Fraud Tracking:** Modul pemantauan perolehan suara dan pelaporan pelanggaran secara *real-time* dari saksi di tingkat TPS (Village/District level).
- **Hierarchical Campaign Network:** Manajemen anggota tim sukses bertingkat (Saksi, Timses, Dewan) dengan analitik geografis interaktif (*Larapex Charts*) berdasarkan agregasi wilayah.

### 🪖 6. MABES Military Payroll & HRIS (`mabes_tukin_gaji`)
Platform manajemen kompensasi finansial dan administrasi personel institusi strategis.
- **Heavy Data Import/Export Engine:** Pemrosesan kalkulasi Tunjangan Kinerja (Tukin) dan Gaji massal berbasis antrean (Jobs/Queues) untuk mencegah *server timeout*.
- **Automated Payroll Pipelines:** Pembuatan PDF SPM, verifikasi dokumen KU-1, hingga pengiriman Slip Gaji (*Payslip*) personal via Email dan WhatsApp otomatis.

### 🌐 7. Corporate Portals & Headless Architecture (`hexagon.co.id`)
Pengembangan profil korporat dan manajemen konten berbasis **Inertia.js & Vue**.
- **Decentralized CMS:** Sistem pengelolaan layanan, portofolio, harga, dan manajemen karir yang diakses secara fleksibel menggunakan integrasi Scribe API Documentation.

---

## 🏆 Penghargaan & Prestasi Nasional

- 🥇 **Juara 1 Pemuda Pelopor Kabupaten Ciamis (2024)** — Kategori Inovasi Teknologi (Sistem Deteksi Dini Stunting / SIDENTING).
- 🏅 **Top 6 Nasional Baparekraf Digital Talent Challenge (2024)** — Inovasi Transformasi Pelayanan Publik.

---

## 📜 Sertifikasi & Kompetensi

- ☁️ **Amazon Web Services (AWS):** Cloud Practitioner Essentials, Technical Architecting, Foundations of Prompt Engineering, Machine Learning Terminology.
- 💻 **Software Engineering (Dicoding):** Architectural Principles of SOLID Programming, Advanced Web Application with React, Professional Foundation of Python.

---

## 🤝 Mari Berkolaborasi!

Saya terbuka untuk peluang kolaborasi teknis, arsitektur sistem skala besar, migrasi *cloud*, pengembangan *enterprise web app*, atau konsultasi infrastruktur digital.

📧 **sonychandmaulana@gmail.com** | 📱 **[+62 813-1215-7307](https://wa.me/6281312157307)** | 🔗 **[LinkedIn Profile](https://www.linkedin.com/in/lorddaud)**
