# Mohef Home-Lab: Pusat Infrastruktur & DIY NAS 🖥️

## 📝 Ringkasan Proyek
Proyek ini mendokumentasikan pembangunan dan pengelolaan **Home-Lab** mandiri yang berfungsi ganda sebagai unit komputasi server dan solusi penyimpanan data jaringan (**DIY NAS**). Infrastruktur ini merupakan tulang punggung operasional untuk pengembangan aplikasi di **Mohef Tech** serta pengelolaan aset digital pada bisnis **LAH PhotoBooth**.

---

### ⚙️ Spesifikasi Perangkat Keras (Hardware)
Ekosistem ini dibangun dengan mengoptimalkan perangkat keras yang ada untuk mencapai efisiensi maksimal:
* **Server Utama & NAS:** Laptop Dell Latitude.
* **Sistem Operasi:** Ubuntu Server (LTS).
* **Stasiun Kerja (Workstation):** Asus A409F (Intel i5 Gen 8, RAM 20GB, SSD 512GB).

---

### 💾 Solusi DIY NAS & Manajemen Data
Bagian ini difungsikan sebagai pusat penyimpanan data terpusat yang aman dan dapat diakses secara privat:
* **Penyimpanan Aset:** Digunakan untuk menyimpan ribuan file foto dan template desain dari proyek **LAH PhotoBooth**.
* **Protokol Jaringan:** Menggunakan **Samba/NFS** untuk membagikan file secara cepat antar perangkat di jaringan lokal.
* **Pusat Backup:** Tempat penyimpanan otomatis (*automated backup*) untuk kode sumber proyek Laravel dan Flutter sebelum dilakukan *push* ke GitHub.

---

### 🌐 Layanan & Arsitektur Jaringan
Server ini menjalankan berbagai layanan untuk mendukung produktivitas dan pemantauan sistem secara *real-time*:
* **Reverse Proxy:** Menggunakan **Nginx** untuk mengarahkan lalu lintas web ke berbagai aplikasi yang dihosting secara internal.
* **Akses Jarak Jauh:** Menggunakan **Tailscale (VPN)** untuk memastikan akses ke server dan NAS tetap aman dari mana saja.
* **Monitoring:** Menjalankan layanan pemantauan berbasis **Golang** untuk memastikan status server selalu aktif (*uptime monitoring*).
* **Hosting Aplikasi:** Menampung database dan backend untuk proyek organisasi, seperti sistem website **PMII Sidoarjo**.

---

### 🤖 Alur Kerja AI-Augmented
Seluruh manajemen konfigurasi, optimasi skrip Linux, hingga penyusunan dokumentasi ini dilakukan melalui pendekatan **AI-Augmented workflow**. Hal ini memungkinkan pemeliharaan infrastruktur yang kompleks secara mandiri dengan standar efisiensi industri.

---

### 📸 Dokumentasi Fisik
![Setup Home-Lab](fisik Dell Server.jpg)
*Visualisasi infrastruktur Mohef Home-Lab yang dikelola secara mandiri.*

---
*Dokumentasi ini dikelola secara berkala oleh Mohef Tech untuk memastikan skalabilitas infrastruktur.*
