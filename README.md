# Sony Chandra Maulana, S.Kom.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lorddaud)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sonychandmaulana@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/SonyChand)

---

## Tentang Saya

Full-Stack Software Engineer dengan 5+ tahun pengalaman membangun sistem produksi di domain **enterprise, pemerintahan, dan kesehatan**.

Core expertise: **Go microservices**, **Laravel/PHP**, **PostgreSQL**, dan **containerised infrastructure (Docker)**.

Terbiasa menangani application security (IDOR, BAC, race conditions), database forensics, automated testing (Pest), CI/CD pipelines, dan AI/LLM integration ke sistem web produksi.

> *"Teknologi téh lain ukur nyieun kode wungkul, tapi kumaha cara nyieun solusi nu ngabantuan rahayat, méré mangpaat, jeung ngahirupkeun harepan pikeun masa depan."*

---

## Tech Stack

**Backend**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-F55247?style=flat&logo=laravel&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

**Frontend**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat&logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-4E56A6?style=flat&logo=laravel&logoColor=white)

**Database & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

---

## Proyek Unggulan

### 🧠 Jatidiri — Psychological Assessment Platform
> `Go` `Gin` `PostgreSQL` `Docker` `Traefik` `Redis` `Gemini AI` `wkhtmltopdf`

Platform asesmen psikologis enterprise dengan arsitektur **7 Go microservices** yang berjalan di balik Traefik API Gateway.

**Fitur teknis utama:**
- Multi-format PDF psikogram (IST, Pauli, DISC, EPPS, BRI, MAP, Leadership, Religius) — render via wkhtmltopdf dengan template HTML
- **AI Psikogram Generator** menggunakan Gemini Flash Lite: async goroutine queue, Redis progress tracking, 9-key rotation untuk rate limit management
- Bulk AI generation dengan antrean background yang dapat dipantau real-time oleh psikolog
- Sistem scoring kompleks: IST (9 subtest + IQ norma), Pauli (9 dimensi: PK/AC/SM/FK/KT/PCK/KK/AA/RK), DISC profiling, EPPS combine scoring
- **Forensic database recovery** — restore 635+ user records setelah corruption event dengan zero data loss
- Automated backup pipeline: rclone → Google Drive, cron setiap 3 jam, retensi 7 hari
- Patched IDOR/Broken Access Control, confirmed oleh tim Cyber Security internal
- Excel batch reporting tool (Python/openpyxl) untuk 56-participant assessment exports
- CFIT (4 subtest visual), FRT (45 soal gambar), BK/Komunitas/Halopsy/Pemeriksaan service terpisah

---

### 🎓 PMB Universitas Bakti Tunas Husada
> `Laravel 11` `PHP 8.3` `MySQL 8.0` `Pest` `Duitku` `Nginx` `Cloudflare`

Platform enrollment mahasiswa baru dengan 2.400+ registran aktif.

**Fitur teknis utama:**
- Integrasi **Duitku payment gateway**: Virtual Account, QRIS, retail outlet — dengan callback handling, signature validation, dan auto-expiry logic
- 5 critical security vulnerability patch: IDOR pada dokumen registrasi, business-logic payment bypass, hardcoded credentials, race condition pada slot pembayaran, mass assignment
- **Pest automated test suite**: 44 passed / 0 failed — payment flow, IDOR protection, callback validation, duplicate registration guard
- Soft delete + statistik pendaftar ganda untuk audit data
- Zero-downtime server migration: DigitalOcean → VPS baru dengan SSL Cloudflare Origin Certs + DNS cutover
- 6 subdomain Nginx virtual host dengan SSL + Cloudflare proxy
- Hourly DB backup via rclone → Google Drive dengan restore point saat insiden `RefreshDatabase` production
- Multi-role system: Admin, Operator BK, Customer (calon mahasiswa)
- OTP email verification, activity log, laporan rekap pendaftar per jalur/prodi

---

### 🪖 SISFOKUAD / PAKU — Military Payroll System
> `Laravel 12` `Livewire 3` `MySQL` `Pest` `Maatwebsite Excel` `GitHub Actions`

Sistem penggajian dan tunjangan kinerja personel militer TNI AD.

**Fitur teknis utama:**
- Import Excel format flat (Tukin, Gaji, Personel, Anak) dengan validasi multi-layer dan preview sebelum commit ke database
- Kalkulasi komponen gaji: gaji pokok, tunjangan kinerja (tukin), potongan, bersih per satker — dengan rekap per golongan/pangkat
- **Personnel Detail Dashboard** 5 tab: data personel, riwayat mutasi, riwayat pangkat/golongan, komponen gaji, data anak
- Per-satker recap table dengan drill-down ke detail individu
- Mutation history tracking: grade change, unit transfer, masa aktif
- Export multi-sheet Excel (Bank, Detail, Komponen, Kwitansi, Rekap Golongan) + PDF (Format 1–4, Slip Gaji, KU-1 Verification, SPM)
- Pest test suite: 44 passed / 0 failed — TukinImport, PersonnelImport, SalaryImport, RBAC
- CI/CD via **GitHub Actions** → deploy otomatis ke `/var/www/mabes_tukin_gaji`
- Job Queue untuk generate SPM PDF batch + WhatsApp payslip delivery
- Activity log setiap perubahan data sensitif

---

### 🌉 Sijembat — Bridge Asset Management
> `Go` `Gin` `Vue.js` `PostgreSQL` `Docker Compose`

Sistem manajemen aset jembatan untuk TNI AD.

**Fitur teknis utama:**
- Server migration antar environment produksi: Docker Compose reconfigure, PostgreSQL dump/restore, zero downtime
- Financial dashboard UI dengan **ApexCharts** — visualisasi RAB, realisasi, dan sisa anggaran per bridge asset
- Decimal precision input bug fix pada Vue.js form (floating point rounding issue)
- Arsitektur Go/Gin REST API + Vue.js SPA dengan Docker Compose v1 syntax

---

### 📚 CodingQu LMS
> `Astro 5` `React` `Golang Fiber v2` `Strapi v5` `Vercel` `Render` `FPDF`

LMS dengan headless architecture untuk lembaga pelatihan.

**Fitur teknis utama:**
- Headless CMS: Strapi v5 sebagai content backend, Astro 5 + React sebagai frontend (SSG/SSR hybrid)
- PDF certificate generator menggunakan **Golang FPDF** — otomatis setelah course completion
- CI/CD pipeline: GitHub → Vercel (frontend) + Render (backend) — deploy on push
- Course progress tracking, quiz system, user dashboard

---

### 🌿 SIDENTING — Intelligent Stunting Detection
> `Laravel` `MySQL` `Chart.js` `Google OAuth` `WHO Z-Score` `Least-Squares Regression`

Sistem deteksi dini stunting berbasis ML — Juara 1 Pemuda Pelopor Kabupaten Ciamis 2024.

**Fitur teknis utama:**
- Kalkulasi **WHO Z-Score** (BB/U, TB/U, BB/TB) sesuai Permenkes No. 2/2020
- **Least-Squares Regression** untuk prediksi tren pertumbuhan anak
- 6-level RBAC: Dinkes, Puskesmas, Posyandu, Bidan, Kader, Orang Tua
- Chart.js analytics dashboard: grafik pertumbuhan individual + populasi
- Google OAuth untuk login wali/orang tua

---

### 🏦 GovSpend Radar
> `Laravel 12` `MySQL` `Node.js` `Python` `Risk Scoring Engine`

Sistem Smart Belanja Daerah berbasis Analitik Risiko — Kompetisi DIGDAYA x Hackathon Bank Indonesia & OJK 2026.

**Fitur teknis utama:**
- **Multi-engine scraper**: concurrent Node.js + Python scraper untuk data belanja publik
- Dynamic Weighted Keyword risk scoring engine — deteksi anomali pengeluaran daerah
- MySQL CRUD API high-availability untuk pipeline data
- Dashboard monitoring real-time risiko belanja per SKPD

---

### 🏥 SIPENTING / SAYANGIBU — Health Service Ecosystem
> `Laravel` `MySQL` `Kemenkes Standards`

Ekosistem aplikasi layanan kesehatan untuk Dinas Kesehatan dan Puskesmas.

**Fitur teknis utama:**
- Multi-app ecosystem: SIPENTING (stunting), SIPEKAMANJUR (KIA), SAYANGIBU (maternal health)
- Standar data sesuai regulasi Kemenkes RI
- Integrasi antar unit layanan: Dinkes → Puskesmas → Posyandu → Bidan

---

### 🗳️ Platform Pengawasan Data Pemilih
> `Laravel` `MySQL` `Real-time Dashboard`

**Fitur teknis utama:**
- Dashboard monitoring real-time data pemilih berbasis wilayah
- Sistem pelaporan masyarakat dengan validasi multi-level
- Role-based access: KPU, Pengawas, Publik

---

### 📍 Platform Absensi Geolocation & HRIS
> `Laravel` `MySQL` `QR Code` `Geolocation API`

**Fitur teknis utama:**
- **Geolocation Radius Fencing** — validasi koordinat GPS saat absensi
- Dynamic QR Code per sesi dengan expiry token
- Multi-shift scheduling, izin/cuti/lembur approval workflow
- Real-time productivity dashboard per departemen

---

### 🎓 Enterprise CBT & AI Platform
> `Laravel 12` `IRT Scoring` `AI Analytics`

**Fitur teknis utama:**
- **IRT (Item Response Theory) scoring** untuk ujian masuk PTN
- Anti-cheat system: tab monitoring, fullscreen enforcement, browser lock
- AI learning analytics: rekomendasi materi berdasarkan pola jawaban

---

## Prestasi

| | Penghargaan | Tahun |
|---|---|---|
| 🥇 | **Juara 1 Pemuda Pelopor Kabupaten Ciamis** — Inovasi Sistem Deteksi Dini Stunting (SIDENTING) | 2024 |
| 🏅 | **Pemenang Baparekraf Digital Talent Challenge** — Transformasi Pelayanan Publik (Top 6 Nasional) | 2024 |

---

## Pengalaman

**Full-Stack Developer — PT Hexagon Karyatama Indonesia** *(2024 – Sekarang)*

Mengelola 4+ proyek produksi enterprise dan pemerintahan secara concurrent.

**Full-Stack Developer — CV Quantum** *(2021 – 2026)*

Membangun 10+ sistem digital untuk instansi pemerintah, lembaga pendidikan, dan UMKM.

**Instructor — Lembaga Pengembangan Pelatihan Quantum** *(2021 – 2026)*

Mengajar 30+ peserta: Modern Web Dev, Laravel, Go microservices, AWS & GCP.

---

## Pendidikan & Sertifikasi

**S1 Teknik Informatika** — STMIK Mardira Indonesia *(2021–2025, IPK 3.56/4.00)*

- ☁️ AWS Cloud Practitioner Essentials (2024)
- ☁️ Architecting on AWS (2024)
- 🤖 AWS Foundations of Prompt Engineering (2024)
- ⚙️ Dicoding: SOLID Principles (2024)
- ⚛️ Dicoding: React Fundamentals (2024)

---

## Fokus & Minat

- 🔐 Application security — OWASP Top 10, IDOR, BAC, race conditions, automated pen-test
- 🧠 AI/LLM integration ke sistem web produksi (Gemini, Redis queue, async goroutines)
- 🏗️ Microservices architecture — Go/Gin, Traefik, Docker, PostgreSQL
- 📊 Data pipeline & analytics — scraping, risk scoring, real-time dashboard
- 🌐 Cloud infrastructure — AWS, GCP, Cloudflare, CI/CD

---

📧 **sonychandmaulana@gmail.com** | 📱 **+62 813-1215-7307** | 🔗 [linkedin.com/in/lorddaud](https://www.linkedin.com/in/lorddaud)
