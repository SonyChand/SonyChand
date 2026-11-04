<div align="center">

# Sony Chandra Maulana, S.Kom.

### Backend Developer · Software Engineer

**Building practical software for real-world workflows.**

Saya mengembangkan aplikasi web, API, dan sistem backend yang membantu tim bekerja lebih rapi, cepat, dan terukur.

[![GitHub](https://img.shields.io/badge/GitHub-SonyChand-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/SonyChand)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lorddaud)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sonychandmaulana@gmail.com)

</div>

---

## Tentang saya

Halo! Saya Sony, seorang **Backend Developer di PT Hexagon Karyatama Indonesia**. Sehari-hari saya banyak berkutat dengan API, database, business logic, integrasi antarsistem, dan memastikan aplikasi bisa berjalan dengan baik di lingkungan yang benar-benar digunakan orang.

Saya juga terbiasa bekerja secara **full-stack** ketika proyek membutuhkannya: mulai dari merancang alur pengguna, membuat antarmuka, menghubungkannya ke backend, sampai deployment dan QA.

Perjalanan saya melibatkan pengembangan produk untuk perusahaan, institusi pendidikan, layanan profesional, serta **proyek transformasi digital di sektor publik dan pemerintahan**. Dalam pekerjaan yang melibatkan banyak pihak, saya berkontribusi **sebagai salah satu developer di dalam tim**. Saya percaya hasil yang baik datang dari kerja sama, komunikasi, dan perhatian pada detail—bukan dari klaim bahwa satu orang mengerjakan semuanya.

Hal yang paling saya nikmati adalah mengurai kebutuhan yang awalnya rumit menjadi sistem yang masuk akal: alurnya jelas, datanya konsisten, aksesnya terkontrol, dan mudah dikembangkan setelah rilis.

- **Fokus utama:** backend engineering, REST API, database design, business workflow, authentication & authorization.
- **Juga mengerjakan:** frontend, integrasi pihak ketiga, background jobs, dokumentasi, testing, dan deployment.
- **Saat ini banyak menggunakan:** Go, PHP/Laravel, Vue 3, TypeScript, PostgreSQL/MySQL, Redis, dan Docker.
- **Di luar pengembangan produk:** berbagi pengetahuan dan mendampingi praktik pengembangan aplikasi bagi siswa PKL/SMK.

## Selected projects

Berikut beberapa aplikasi dan kelompok solusi yang pernah atau sedang saya kerjakan. **Daftar fitur menggambarkan cakupan pengembangan yang relevan, bukan janji bahwa seluruh modul tersedia di setiap instalasi atau sudah dirilis ke publik.** Sebagian source code merupakan milik organisasi/klien sehingga tidak tersedia sebagai repository publik.

### 01 — SIMKARYA | Human Capital Management System

Sistem HRIS/HCM untuk membantu perusahaan mengelola siklus kerja karyawan secara terintegrasi, dari administrasi SDM sampai proses evaluasi dan penggajian.

**Fitur dan modul:**
- **Core HR & organisasi:** data karyawan, jabatan, departemen, struktur pelaporan, dan pengaturan akses.
- **Presensi & cuti:** shift kerja, clock-in/out, pengajuan izin/cuti, koreksi kehadiran, dan proses persetujuan.
- **Payroll:** komponen kompensasi, periode penggajian, alur persetujuan berjenjang, dan slip gaji PDF.
- **Rekrutmen:** lowongan, kandidat, tahapan seleksi, dan penjadwalan wawancara.
- **Performance management:** KPI, penilaian kinerja, PIP, rencana pengembangan individu, dan 360° feedback.
- **Learning & Development:** katalog pelatihan, pendaftaran, evaluasi, dan pengelolaan sertifikat.
- **Dokumen & layanan mandiri:** pengelolaan dokumen berversi, template PDF, akses dokumen, serta permintaan keuangan karyawan.
- **Notifikasi & administrasi:** notifikasi berbasis peristiwa, role/permission management, konfigurasi perusahaan, dan integrasi layanan.

**Tech stack:** Go · Gin · GORM · Vue 3 · TypeScript · Vite · Tailwind CSS · MySQL/MariaDB · Redis · Docker · Nginx

**Kontribusi:** pengembangan backend, business logic, API, integrasi modul, penguatan akses dan keamanan, serta pengujian alur aplikasi bersama tim.

### 02 — EduMutu | School & Foundation Management Platform

Platform terintegrasi untuk operasional sekolah dan yayasan, dengan pendekatan multi-tenant dan akses berdasarkan organisasi, sekolah, serta peran pengguna. Proyek ini sebelumnya menggunakan identitas **Heksara** dan sedang melalui penyesuaian branding.

**Fitur dan modul:**
- **Manajemen yayasan & sekolah:** tenant, satuan pendidikan, pengguna, role, permission, dan audit aktivitas.
- **Akademik:** tahun ajaran, kelas, jadwal, kurikulum, guru, siswa, serta data orang tua/wali.
- **PPDB:** periode penerimaan, pendaftaran, dokumen, seleksi, dan proses menjadi siswa aktif.
- **Pembelajaran:** materi, tugas, pengumpulan, ujian, penilaian, rapor, dan presensi.
- **Keuangan & SDM:** tagihan sekolah, pembayaran, akuntansi, data pegawai, dan penggajian.
- **Layanan sekolah:** perpustakaan, inventaris, konseling, UKS, layanan SMK/PKL, serta fasilitas sekolah.
- **Komunikasi & portal wali:** pengumuman, pesan, notifikasi, dan akses informasi anak sesuai hak pengguna.
- **Operasional platform:** pengelolaan paket/modul, pelaporan, analitik, serta integrasi layanan tambahan.

**Tech stack:** Go · Gin · Vue 3 · TypeScript · Vite · Pinia · PostgreSQL · Redis · NATS JetStream · Docker · Nginx

**Kontribusi:** pengembangan layanan backend dan frontend, alur akses lintas peran, integrasi antarmodul, dan kesiapan deployment.

### 03 — Jatidiri | Psychological Assessment Platform

Ekosistem layanan asesmen psikologis dengan pemisahan beberapa domain layanan agar proses autentikasi, persiapan asesmen, pengerjaan tes, dan penyusunan hasil dapat dikelola lebih terstruktur.

**Fitur dan modul:**
- **Account & authentication:** pengelolaan akses dan sesi pengguna.
- **Assessment services:** pengelolaan instrumen, bank soal, sesi asesmen, dan pemrosesan jawaban.
- **Scoring & reporting:** pengolahan hasil tes dan penyusunan laporan/psikogram.
- **Supporting services:** layanan persiapan, bimbingan konseling, pemeriksaan, komunitas, dan konsultasi.
- **API routing:** pemisahan layanan melalui gateway untuk kebutuhan integrasi.
- **Infrastructure:** caching, pengelolaan koneksi database, observability, dan containerized deployment.

**Tech stack:** Go · Gin · PostgreSQL · GORM · Redis · PgBouncer · Traefik · Docker Compose · OpenTelemetry

**Kontribusi:** pengembangan dan integrasi backend service, pemrosesan data asesmen, serta penataan infrastruktur layanan.

### 04 — CBTQu | Learning & Computer-Based Testing

Platform pembelajaran dan ujian daring yang menyatukan materi belajar, pengelolaan paket, pelaksanaan tes, serta analisis hasil belajar.

**Fitur dan modul:**
- **Learning content:** katalog paket, modul, materi, dan ruang belajar peserta.
- **Question bank:** kategori soal, impor soal, penyusunan ujian, dan pengelolaan komposisi tes.
- **CBT sessions:** instruksi ujian, pelaksanaan tes dengan timer, penyimpanan jawaban, dan riwayat pengerjaan.
- **Results & analytics:** hasil ujian, laporan PDF, analisis butir soal, dan statistik peserta.
- **Transactions:** katalog paket berbayar, checkout, riwayat transaksi, dan invoice.
- **Administration:** pengelolaan pengguna, konten, artikel, pengaturan, dan hak akses.

**Tech stack:** PHP · Laravel 12 · Livewire 3 · Volt · Tailwind CSS · Vite · Laravel Sanctum · Midtrans

**Kontribusi:** pengembangan alur ujian dan pembelajaran, modul administrasi, pelaporan, dan integrasi pembayaran.

### 05 — University Admission System | PMB Universitas BTH

Aplikasi penerimaan mahasiswa baru untuk membantu kampus mengelola pendaftaran, seleksi, administrasi berkas, dan pembayaran dalam satu alur.

**Fitur dan modul:**
- **Pendaftaran:** akun pendaftar, verifikasi email, pengisian biodata, dan riwayat pendidikan.
- **Jalur & program studi:** pengaturan pilihan program dan persyaratan pendaftaran.
- **Seleksi:** pengelolaan ujian/CBT, hasil seleksi, serta proses penerimaan.
- **Administrasi dokumen:** unggah dan pemeriksaan berkas pendaftar.
- **Keuangan PMB:** biaya pendaftaran, metode pembayaran, cicilan, dan pencatatan transaksi.
- **Back office:** pengelolaan data calon mahasiswa, dashboard, dan laporan.

**Tech stack:** PHP · Laravel 11 · Blade · Tailwind CSS · Vite · MySQL · Laravel Fortify · Dompdf · PhpSpreadsheet

**Kontribusi:** pengembangan fitur PMB, backend, alur seleksi, transaksi, dan administrasi data.

### 06 — STIKES Budi Luhur Cimahi | Admission & Enrollment System

Sistem penerimaan mahasiswa baru dengan kebutuhan administrasi yang lebih spesifik, termasuk dukungan jalur pendaftaran dan alur pascapenerimaan.

**Fitur dan modul:**
- **Pendaftaran online:** biodata, pendidikan, keluarga, pilihan program, dan unggah persyaratan.
- **Seleksi masuk:** pengaturan ujian berbasis komputer sesuai jalur/program studi serta hasil seleksi.
- **Pembayaran:** metode pembayaran, skema cicilan, dan pencatatan pembayaran pendaftar.
- **Referral sekolah:** pengelolaan rujukan dari guru BK/sekolah.
- **Administrasi akademik awal:** pengelolaan data mahasiswa dan penomoran NIM.
- **Akses pengelola:** area administrasi dan pengelolaan data per program studi.
- **Pelaporan:** rekap pendaftaran, pembayaran, dan progres penerimaan.

**Tech stack:** PHP · Laravel 11 · Blade · Tailwind CSS · Vite · MySQL/MariaDB · Dompdf · PhpSpreadsheet

**Kontribusi:** pengembangan dan penyempurnaan proses PMB, QA, integrasi modul, serta persiapan deployment.

### 07 — Finance & Bookkeeping System

Aplikasi pengelolaan keuangan operasional yang berfokus pada pencatatan pemasukan dan pengeluaran serta penyediaan laporan untuk pengelola.

**Fitur dan modul:**
- **Pemasukan:** pencatatan sumber dana, nominal, tanggal, dan keterangan.
- **Pengeluaran:** pengelompokan biaya operasional, personalia, pemeliharaan, dan kategori lain.
- **Pembukuan:** pengorganisasian transaksi keuangan untuk kebutuhan administrasi.
- **Pelaporan:** rekap dan penyajian data pemasukan/pengeluaran.
- **Manajemen pengguna:** akses administrasi dan dashboard pengelola.

**Tech stack:** PHP · CodeIgniter · MySQL · JavaScript

**Kontribusi:** pengembangan modul transaksi, formulir, pengolahan data, dan tampilan laporan.

### 08 — SIDENTING | Early Stunting Detection & Growth Prediction

Proyek penelitian dan pengembangan aplikasi untuk membantu pemantauan pertumbuhan anak melalui pengolahan data antropometri dan prediksi tren pertumbuhan. Proyek ini merupakan bagian dari perjalanan akademik dan inovasi teknologi saya.

**Fitur dan modul:**
- **Data anak & pengukuran:** pencatatan profil dan riwayat pertumbuhan.
- **Indikator pertumbuhan:** pengolahan pengukuran berat/tinggi sesuai kelompok umur.
- **Deteksi dini:** perhitungan indikator antropometri untuk membantu identifikasi risiko pertumbuhan.
- **Growth prediction:** pendekatan regresi Least Squares untuk memproyeksikan perkembangan berdasarkan data yang tersedia.
- **Dashboard & laporan:** ringkasan data, visualisasi perkembangan, dan laporan hasil pengukuran.
- **Role-based workflow:** pemisahan akses sesuai kebutuhan pencatatan dan pemantauan.

**Tech stack:** PHP · Laravel 11 · MySQL · PHP-ML · Laravel Sanctum · Spatie Permission · Charting · PDF/Excel Export

**Kontribusi:** perancangan dan pengembangan sistem penelitian, pengolahan data, serta implementasi metode prediksi. **Hasil sistem merupakan alat bantu, bukan pengganti penilaian tenaga kesehatan.**

### 09 — Multi-Step Invoice Generator | Fleetify Technical Test

Proyek technical assessment yang berfokus pada pembuatan invoice berbasis formulir bertahap, dengan validasi perhitungan di server dan pemisahan frontend/backend.

**Fitur dan modul:**
- **Multi-step form:** pengisian invoice dengan pengelolaan state antar-langkah.
- **Master item:** pilihan item dan data referensi dari backend.
- **Server-side validation:** harga dan total dihitung ulang di backend.
- **Transactional writes:** penyimpanan data dalam transaksi database.
- **Print-ready invoice:** tampilan khusus untuk mencetak invoice.
- **Async webhook:** contoh pemrosesan webhook asinkron.
- **Containerized setup:** frontend, backend, dan database dijalankan melalui Docker Compose.

**Tech stack:** Next.js 14 · React · TypeScript · Go · Fiber · PostgreSQL · GORM · Zustand · TanStack Query · Docker

**Source code:** [SonyChand/fleetify-technical-test](https://github.com/SonyChand/fleetify-technical-test)

---

## Pengalaman pengembangan sistem untuk institusi

Selain produk-produk di atas, saya juga pernah terlibat **sebagai salah satu anggota tim developer** dalam pekerjaan pengembangan dan penyempurnaan sistem untuk organisasi serta lingkungan **sektor publik/pemerintahan**.

Ruang kontribusi teknisnya antara lain:
- Perancangan dan pengembangan **REST API, data model, dan business process**.
- Implementasi **role-based access control**, autentikasi, validasi, dan jejak audit.
- Integrasi proses administrasi, pengelolaan dokumen, impor data, dan pelaporan.
- Pemeriksaan kualitas data, investigasi bug, serta pengujian fungsional lintas peran.
- Penataan deployment, container, monitoring dasar, dan pemeliharaan aplikasi bersama tim.

**Nama aplikasi, instansi, detail arsitektur internal, serta informasi operasional proyek tertentu sengaja tidak dicantumkan pada profil publik ini.** Deskripsi di sini membahas bidang kontribusi, bukan rincian proyek yang bersifat terbatas.

## Technology & tools

| Area | Technologies |
| --- | --- |
| **Backend** | Go, PHP, Laravel, Gin, Fiber, CodeIgniter, REST API, GORM |
| **Frontend** | Vue 3, TypeScript, JavaScript, React, Next.js, Livewire, Blade, Tailwind CSS, Vite |
| **Data** | PostgreSQL, MySQL, MariaDB, Redis, SQL, data migration |
| **Infrastructure** | Docker, Docker Compose, Nginx, Traefik, Linux, Git, GitHub Actions |
| **Architecture** | Modular monolith, microservices, RBAC, API integration, background processing, event-driven workflows |
| **Integrations & reporting** | Payment gateways, email/SMTP, webhooks, PDF/Excel generation, Google Workspace integrations |
| **Quality & delivery** | API testing, functional QA, debugging, logging, documentation, CI/CD workflows |

Saya tidak terpaku pada satu framework. Pemilihan teknologi mengikuti kebutuhan sistem, kapasitas tim, biaya operasional, dan kemudahan pemeliharaan jangka panjang.

## How I approach software development

1. **Understand the workflow.** Memastikan masalah dan kebutuhan pengguna dipahami sebelum menentukan struktur aplikasi.
2. **Model the data carefully.** Menentukan relasi, validasi, batas akses, dan perubahan data sejak awal.
3. **Keep business logic explicit.** Membuat alur proses jelas agar mudah diuji, diperiksa, dan diperbaiki.
4. **Think beyond local development.** Memperhatikan konfigurasi, keamanan, logging, migrasi, deployment, dan rollback.
5. **Test real user flows.** Tidak menganggap build berhasil sama dengan fitur sudah siap dipakai.
6. **Document decisions.** Menyimpan konteks keputusan teknis agar pengembangan bisa diteruskan oleh tim.

## Education, achievements & mentoring

- **S.Kom. — Teknik Informatika, STMIK Mardira Indonesia** (2025).
- **Juara 1 Pemuda Pelopor Kabupaten Ciamis, Bidang Inovasi Teknologi (2024)** melalui pengembangan SIDENTING.
- **Top 6 Nasional Baparekraf Digital Talent Challenge (2024)** — kategori inovasi transformasi pelayanan publik.
- Terlibat dalam **bimbingan teknis dan pendampingan pengembangan aplikasi** bagi siswa PKL/SMK, termasuk materi Laravel dan dasar pengembangan backend.

## Let's connect

Saya terbuka untuk diskusi tentang backend development, arsitektur aplikasi, kolaborasi teknis, atau berbagi pengalaman membangun produk digital.

- **Email:** [sonychandmaulana@gmail.com](mailto:sonychandmaulana@gmail.com)
- **LinkedIn:** [linkedin.com/in/lorddaud](https://www.linkedin.com/in/lorddaud)
- **GitHub:** [github.com/SonyChand](https://github.com/SonyChand)

<div align="center">

---

<sub>Good software is not just code that runs. It should make someone's work easier.</sub>

</div>
