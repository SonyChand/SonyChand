# 👨‍💻 Sony Chandra Maulana, S.Kom.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lorddaud)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sonychandmaulana@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/SonyChand)

---

## 🧑‍💼 Tentang Saya

Full-Stack Software Engineer dengan 5+ tahun pengalaman membangun sistem produksi di domain **enterprise, pemerintahan, dan militer**.  
Core expertise: **Go microservices**, **Laravel/PHP**, **PostgreSQL**, dan **containerised infrastructure (Docker)**.  
Terbiasa menangani security remediation (IDOR, BAC, race conditions), database forensics, automated testing (Pest), dan CI/CD pipelines.

> _"Teknologi téh lain ukur nyieun kode wungkul, tapi kumaha cara nyieun solusi nu ngabantuan rahayat, méré mangpaat, jeung ngahirupkeun harepan pikeun masa depan." – Sony Chandra Maulana_

---

## 🛠️ Tech Stack

**Backend**  
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-F55247?style=flat&logo=laravel&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-E44D26?style=flat&logo=codeigniter&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Frontend**  
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat&logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)

**Database & Infrastructure**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

---

## 🏆 Prestasi & Penghargaan

| # | Penghargaan | Tahun |
|---|-------------|-------|
| 🥇 | **Juara 1 Pemuda Pelopor Kabupaten Ciamis** — Inovasi Sistem Deteksi Dini Stunting (SIDENTING) | 2024 |
| 🏅 | **Pemenang Baparekraf Digital Talent Challenge** — Transformasi Pelayanan Publik (Top 6 Nasional) | 2024 |

> 📄 Sumber: [bdd.kemenparekraf.go.id](https://bdd.kemenparekraf.go.id/news/581/selamat-kepada-pemenang-baparekraf-digital-talent-challenge-2024)

---

## 💼 Pengalaman Kerja

### 🏢 Full-Stack Developer — PT Hexagon Karyatama Indonesia *(2024 – Sekarang)*

Mengelola proyek-proyek produksi berskala enterprise secara concurrent:

**🧠 Jatidiri — Psychological Assessment Platform** ([jatidiri.app](https://jatidiri.app))
- Architected Go microservices backend (PostgreSQL, Docker, Traefik API Gateway) untuk layanan asesmen psikologis enterprise
- Engineered multi-format PDF psikogram (IST, Pauli, DISC, EPPS, BRI, MAP, Leadership, Religious) untuk batch assessment
- Forensic database recovery setelah corruption event (Juni 2026) — restore 635+ user records, zero data loss
- Automated backup pipeline: rclone → Google Drive (cron, hourly, 7-day retention)
- Patched IDOR/Broken Access Control vulnerability, confirmed valid oleh tim Cyber Security internal
- Built Excel assessment reporting tools (Python/openpyxl) untuk 56-participant batch exports

**🎓 PMB Universitas Bakti Tunas Husada** ([admisi.universitas-bth.ac.id](https://admisi.universitas-bth.ac.id))
- Laravel 11 / PHP 8.3 enrollment platform — 2.400+ registran aktif, MySQL 8.0, Nginx, Ubuntu 22.04
- Integrasi Duitku payment gateway (VA, QRIS, retail) dengan callback handling & auto-expiry logic
- Remediasi 5 critical security vulnerabilities: IDOR, business-logic payment manipulation, hardcoded secrets, race conditions
- Server migration dari DigitalOcean → backup VPS: SSL Cloudflare Origin Certs, DNS propagation, zero-downtime cutover
- Configured 6 subdomain Nginx virtual hosts dengan SSL + Cloudflare proxy
- Pest automated test suite: **44 passed / 0 failed** (payment flow, IDOR protection, callback validation)

**🪖 SISFOKUAD / PAKU — Military Payroll System (TNI AD)**
- Comprehensive codebase review sistem penggajian personel militer (Laravel/Livewire)
- Patched 5 production bugs dalam Excel import logic; Pest test suite: **44 passed / 0 failed**
- Produced full S2 thesis document untuk Unhan RI (Defense University), formatted per pedoman resmi

**🌉 Sijembat — Military Bridge Asset Management (TNI AD)**
- Server migration Golang/Gin + Vue.js + Docker/PostgreSQL antar environment produksi — zero downtime
- Developed DENMABESAD financial UI dengan ApexCharts; RAB budget estimation docs (INKINDO 2026 standards)

---

### 💻 Full-Stack Developer — CV Quantum *(2021 – 2026)*

- **CodingQu LMS** ([lms-enterprise-project.vercel.app](https://lms-enterprise-project.vercel.app)) — Headless architecture: Astro 5 + React, Golang Fiber v2, Strapi v5 CMS; CI/CD via GitHub → Vercel + Render; PDF certificates via Golang FPDF
- **ELFIS** ([sobatqu.com](https://www.sobatqu.com)) — LMS terintegrasi dengan sistem Bank Sampah Digital; konversi data penjemputan sampah → learning points; Midtrans payment gateway
- **SIDENTING** ([sidenting.my.id](https://sidenting.my.id)) — Intelligent Stunting Detection: WHO Z-Score + Permenkes No. 2/2020 + Least-Squares Regression ML; 6-level RBAC; Chart.js analytics; Google OAuth
- **GovSpend Radar (2026)** — Sistem Smart Belanja Daerah berbasis Analitik Risiko (Kompetisi DIGDAYA x Hackathon Bank Indonesia & OJK)
- **Enterprise CBT & AI Platform (2026)** — Platform ujian masuk PTN dengan IRT Scoring, anti-cheat system, dan AI learning analytics (Laravel 12)
- **Multi-Engine Scraper & Risk Scoring (2025)** — Concurrent Node.js + Python scraper; Dynamic Weighted Keyword risk engine; MySQL CRUD API high-availability
- **Platform Absensi Geolocation & HRIS (2025)** — Geolocation Radius Fencing + QR Code; multi-shift scheduling; leave/overtime approval; real-time productivity dashboard
- **Platform Pengawasan Data Pemilih (2025)** — Dashboard monitoring real-time + pelaporan masyarakat
- **E-IMES (2025)** — Enterprise Internship Monitoring: Presensi QR dinamis + Logbook digital otomatis
- **SIPENTING / SIPEKAMANJUR / SAYANGIBU (2022)** — Ekosistem aplikasi layanan kesehatan (Dinas Kesehatan, Puskesmas) sesuai standar Kemenkes

---

### 👨‍🏫 Instructor — Lembaga Pengembangan Pelatihan Quantum *(2021 – 2026)*

Mengajar 30+ peserta: Modern Web Development (HTML/CSS/JS, React.js), Laravel 11/12, Java Enterprise (J2EE), Go microservices, AWS & GCP deployment.

---

### 🤝 Freelance Full-Stack Developer *(2022 – Sekarang)*

MIS berskala menengah-besar untuk instansi pemerintah (Dinas Kesehatan, Puskesmas) — fokus skalabilitas, keamanan, dan kepatuhan regulasi.

---

## 🎓 Pendidikan

| Jenjang | Institusi | Tahun | Keterangan |
|---------|-----------|-------|------------|
| S1 Teknik Informatika | STMIK Mardira Indonesia | 2021–2025 | IPK 3.56 / 4.00 |
| Teknik Komputer & Jaringan | SMKN 1 Kawali | 2018–2021 | — |

---

## 📜 Sertifikasi

- ☁️ AWS Cloud Practitioner Essentials (2024)
- ☁️ Architecting on AWS (2024)
- 🤖 AWS Foundations of Prompt Engineering (2024)
- 📊 AWS Machine Learning Terminology & Process (2024)
- 🏗️ Dicoding: Cloud Practitioner Essentials — Belajar Dasar AWS Cloud (2023)
- ⚙️ Dicoding: Belajar Prinsip Pemrograman SOLID (2024)
- ⚛️ Dicoding: Belajar Fundamental Aplikasi Web dengan React (2024)
- 🐍 Dicoding: Memulai Pemrograman dengan Python (2024)

---

## 🎯 Fokus & Minat Profesional

- 🚀 Inovasi teknologi di bidang kesehatan dan pendidikan
- 🔐 Application security (OWASP, IDOR, BAC, automated testing)
- 📊 Sistem enterprise high-performance & microservices architecture
- 🧠 Integrasi AI/ML & Data Analytics ke sistem web
- 🌐 Cloud (AWS/GCP), CI/CD, dan headless architecture
- 💡 Solusi digital berdampak sosial (e-government, layanan publik)

---

## 🌱 Terbuka Untuk

- Kolaborasi pengembangan sistem informasi publik & e-government
- Freelance web app full-stack skala menengah–besar
- Konsultasi arsitektur sistem digital desa / puskesmas / instansi
- Pemateri workshop, bootcamp digital, atau IT instructor

---

📧 **sonychandmaulana@gmail.com** | 📱 **+62 813-1215-7307** | 🔗 [LinkedIn](https://www.linkedin.com/in/lorddaud)
