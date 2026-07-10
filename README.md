# 👨‍💻 Sony Chandra Maulana, S.Kom.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lorddaud)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sonychandmaulana@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/SonyChand)

---

## 🧑‍💼 Tentang Saya

Full-Stack Software Engineer & Systems Architect dengan pengalaman lebih dari 5 tahun dalam merancang, membangun, dan mengamankan sistem produksi skala besar di domain **Enterprise, Pemerintahan, dan Militer**. 

Berfokus pada pengembangan arsitektur yang tangguh menggunakan **Go Microservices**, **Laravel Enterprise**, pipeline otomatisasi data, serta manajemen infrastruktur berbasis kontainer (**Docker/Traefik/Nginx**). Berpengalaman mentransformasi proses bisnis manual menjadi ekosistem digital berbasis fitur automasi tingkat tinggi, pengawasan keamanan ketat, serta pemrosesan data analitik yang konkruen.

> _"Teknologi téh lain ukur nyieun kode wungkul, tapi kumaha cara nyieun solusi nu ngabantuan rahayat, méré mangpaat, jeung ngahirupkeun harepan pikeun masa depan." – Sony Chandra Maulana_

---

## 🛠️ Tech Stack Matrix

- **Backend Development:** Go (Standard Library, Gin, Fiber v2), PHP (Laravel 11/12, CodeIgniter), Java Enterprise (J2EE), Node.js (Express/Fastify), Python
- **Frontend Architecture:** Vue.js (Vue 3, Vite), React, Astro 5, Tailwind CSS, Bootstrap, Livewire Engine
- **Database & Caching:** PostgreSQL, MySQL/MariaDB, SQLite, Redis Data Structures
- **Infrastructure & DevSecOps:** Docker & Docker Compose, Traefik API Gateway, Nginx Reverse Proxy, Cloudflare Shield Proxy, AWS Core Services, Google Cloud Platform (GCP), GitHub Actions CI/CD Pipeline

---

## 💼 Portofolio & Arsitektur Fitur Sistem Production

### 🏢 Proyek Enterprise & Pemerintahan (PT Hexagon Karyatama Indonesia)

#### 🧠 Jatidiri — Psychological Assessment Platform (`jatidiri.app`)
Platform mikroservis mutakhir untuk kebutuhan asesmen psikologis massal korporasi dan instansi.
- **Distributed Microservices Mesh:** Pemisahan fungsional independen antara *Auth Service*, *Assessment Service*, *BK Service*, *Preparation Service*, dan *Halopsy Service* yang dikonsolidasikan melalui **Traefik API Gateway Core** dengan enkripsi SSL dinamis.
- **Multi-Engine Psychogram Compiler:** Fitur kalkulasi otomatis hasil tes psikologi berbasis standarisasi baku instrumen psikotes internasional (IST, Pauli, DISC, EPPS, BRI, MAP, Leadership, dan Religius) yang dikompilasi secara real-time menjadi dokumen pelaporan multi-format terenkripsi.
- **Hourly Cloud Backup Pipeline:** Fitur otomatisasi pencadangan data basis data dan media aset (*snapshot mirroring*) secara berkala setiap 1 jam menggunakan sinkronisasi terenkripsi via **Rclone Engine** ke Google Drive Cloud Storage dengan sistem manajemen pembersihan siklus retensi 7 hari otomatis.
- **Defensive Gateway Middleware Infrastructure:** Implementasi proteksi keamanan terpusat di layer middleware, meliputi *Global Rate Limiter*, *Request ID Tracking Engine*, *Strict JWT State Verification*, serta pengetatan otorisasi akses data multidimensi untuk mencegah celah manipulasi parameter bisnis.

#### 🎓 PMB Universitas Bakti Tunas Husada (`admisi.universitas-bth.ac.id`)
Sistem Informasi Manajemen Penerimaan Mahasiswa Baru berskala institusi tinggi dengan ribuan pengguna aktif secara concurrent.
- **Asynchronous Installment Schema Architecture:** Fitur fleksibilitas skema cicilan pembayaran dana perkuliahan otomatis terintegrasi dengan profil data finansial mahasiswa, lengkap dengan pelacakan *history tracking* dan manajemen jatuh tempo tagihan.
- **Omnichannel Payment Gateway Core:** Sistem transaksi keuangan terintegrasi dengan **Duitku Gateway API** (Virtual Account, QRIS, Retail Outlets) yang dilengkapi fitur *Instant Webhook Callback Processing*, proteksi manipulasi parameter logika nominal pembayaran, serta *Auto-Expiry Invoice Logic*.
- **Multi-Channel Transaction Alert System:** Fitur notifikasi otomatis berbasis antrean (*Queue Workers Processing*) yang memicu pengiriman OTP, bukti transaksi, dan kredensial akun mahasiswa baru melalui integrasi **Email SMTP** dan **WhatsApp Gateway Gateway API Engine**.
- **High-Availability VPS & Proxy Server Architecture:** Orkestrasi infrastruktur web server menggunakan **Nginx Virtual Hosts Subdomain Clustering** berbasis Cloudflare Proxy SSL Origin Certificates untuk menjamin zero-downtime saat migrasi server dan propagasi DNS massal.

#### 🪖 SISFOKUAD / PAKU — Military Payroll System (TNI AD)
Sistem informasi terpusat untuk pengelolaan manajemen penggajian dan kompensasi finansial internal personel militer.
- **Advanced Batch Calculation Matrix Engine:** Fitur pemrosesan massal (*bulk data import-export handling*) komponen gaji pokok, tunjangan kinerja (Tukin), tunjangan anak istri, dan potongan kas kasual melalui parsing file spreadsheet besar ke dalam arsitektur database relasional tanpa membebani memori utama (*low-memory footprint parsing*).
- **Asynchronous Document Generator & Archiver Engine:** Fitur otomatisasi pembuatan slip gaji (*payslip generator*) personal, kwitansi dinamis, rekapitulasi anggaran golongan, dan dokumen verifikasi KU-1 berbasis *Background Job Workers Pipeline*.

#### 🌉 Sijembat — Military Bridge Asset Management (TNI AD)
Sistem Pengawasan dan Pemantauan Aset Strategis Infrastruktur Militer.
- **RAB Budget Optimization Engine:** Fitur kalkulasi estimasi anggaran perbaikan dan pemeliharaan jembatan yang disesuaikan secara dinamis dengan standarisasi regulasi nasional terbaru (INKINDO Standards).
- **Real-Time Financial Visualizer Dashboard:** Fitur interaktif visualisasi alokasi dan penyerapan pagu anggaran keuangan markas besar menggunakan komponen grafik dinamis **ApexCharts**.

---

### 💻 Proyek Inovasi Digital & Sistem Informasi Publik (CV Quantum & Freelance)

#### 🔬 SIDENTING (`sidenting.my.id`) — Intelligent Early Stunting Detection
Sistem kecerdasan buatan untuk deteksi dini risiko stunting balita yang meraih **Juara 1 Pemuda Pelopor Kabupaten Ciamis 2024**.
- **WHO Z-Score Machine Learning Prediction Engine:** Fitur analisis antropometri balita real-time berbasis standar formula **Permenkes No. 2/2020** dan algoritma pemodelan prediksi tren pertumbuhan anak menggunakan metodologi *Least-Squares Regression Machine Learning*.
- **Multi-Tier Role-Based Access Control (RBAC):** Sistem manajemen otorisasi berjenjang 6 tingkat akses (Dinas Kesehatan, Puskesmas, Posyandu, Orang Tua, dll) yang menjamin kerahasiaan rekam medis data kesehatan masyarakat.

#### 📊 GovSpend Radar — Smart Regional Spending Monitoring System
Platform pemantauan kepatuhan anggaran daerah berbasis analitik risiko untuk kompetisi **DIGDAYA x Hackathon Bank Indonesia & OJK 2026**.
- **Concurrent Risk Scoring Scraper:** Fitur *Web Scraper Engine* berbasis Node.js dan Python yang berjalan secara konkuren untuk mengekstraksi data belanja daerah, kemudian diolah melalui *Dynamic Weighted Keyword Risk Engine* untuk mendeteksi anomali transaksi keuangan secara otomatis.

#### 🎯 Enterprise CBT Platform & AI Analytics 
Platform ujian terpusat terkomputerisasi untuk simulasi seleksi masuk Perguruan Tinggi Negeri.
- **IRT (Item Response Theory) Scoring Module:** Fitur penilaian adaptif menggunakan parameter bobot tingkat kesulitan soal ujian secara otomatis berdasarkan probabilitas jawaban benar dari total seluruh peserta ujian.
- **Anti-Cheat Radius System:** Fitur pengawasan integritas ujian yang membatasi ruang gerak browser peserta secara ketat untuk mencegah kebocoran soal dan kecurangan pengerjaan.

#### 📍 Geolocation Radius Fencing Presence & HRIS
Sistem manajemen kehadiran pegawai korporasi berskala enterprise.
- **Radius-Fencing Location Tracking Engine:** Fitur validasi presensi menggunakan koordinat GPS realtime pegawai yang dicocokkan dengan koordinat *fencing zone* radius kantor, diamankan dengan verifikasi *Dynamic QR Code Validation Architecture* untuk menangkal spoofing lokasi.

#### ♻️ ELFIS — LMS & Waste Bank Integration (`sobatqu.com`)
Aplikasi pengelolaan lingkungan berdampak sosial yang diakui sebagai **Pemenang Baparekraf Digital Talent Challenge 2024 (Top 6 Nasional)**.
- **Waste-to-Points Conversion Algorithm:** Fitur konversi data berat penjemputan sampah rumah tangga secara otomatis menjadi poin pembelajaran (*learning points*) untuk ditukarkan dengan akses premium materi kursus di dalam platform.

---

## 🏆 Penghargaan & Prestasi Nasional

- 🥇 **Juara 1 Pemuda Pelopor Kabupaten Ciamis (2024)** — Kategori Inovasi Teknologi melalui Sistem Deteksi Dini Stunting (SIDENTING).
- 🏅 **Top 6 Nasional Pemenang Baparekraf Digital Talent Challenge (2024)** — Inovasi Transformasi Pelayanan Publik melalui Digitalisasi Platform ELFIS.

---

## 📜 Sertifikasi Profesional

- ☁️ AWS Cloud Practitioner Essentials Certification — Amazon Web Services
- 🏗️ AWS Technical Architecting on AWS Certification — Amazon Web Services
- 🤖 AWS Foundations of Prompt Engineering Certified — Amazon Web Services
- 📊 AWS Machine Learning Terminology & Process — Amazon Web Services
- ⚙️ Dicoding: Architectural Principles of SOLID Programming
- ⚛️ Dicoding: Advanced Web Application Development with React
- 🐍 Dicoding: Professional Foundation of Python Programming

---

📧 **sonychandmaulana@gmail.com** | 📱 **+62 813-1215-7307** | 🔗 [LinkedIn](https://www.linkedin.com/in/lorddaud)
