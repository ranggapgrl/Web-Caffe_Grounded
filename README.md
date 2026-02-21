# ☕ Web-Caffe Grounded
**Sistem Informasi & Manajemen Cafe Berbasis Web**

Web-Caffe Grounded adalah aplikasi manajemen operasional kafe yang dirancang untuk memudahkan proses bisnis, mulai dari pengelolaan menu hingga integrasi database pelanggan. Proyek ini dibangun dengan arsitektur PHP modular untuk memastikan kemudahan dalam pengembangan dan kustomisasi.

## 📑 Struktur Proyek
Proyek ini diorganisir ke dalam beberapa direktori utama:
* **`CF_Hasaja/`**: Folder inti yang berisi logika aplikasi (PHP), komponen frontend (HTML/CSS/JS), serta aset gambar.
* **`database/`**: Berisi file skema SQL (`.sql`) untuk inisialisasi tabel sistem manajemen.

## 🚀 Fitur Utama
* **Dashboard Manajemen:** Ringkasan data operasional harian secara *real-time*.
* **Sistem Manajemen Menu:** Menambah, memperbarui, atau menghapus kategori dan item menu.
* **Manajemen Database Pelanggan:** Pencatatan profil dan riwayat transaksi.
* **Antarmuka Responsif:** Desain modern menggunakan CSS yang nyaman diakses melalui PC maupun smartphone.

## 🛠️ Teknologi yang Digunakan
* **Backend:** PHP 7.x/8.x (Server-side scripting).
* **Database:** MySQL (Sistem Manajemen Database Relasional).
* **Frontend:** HTML5, CSS3, dan JavaScript (Interaktivitas pengguna).
* **Web Server:** Direkomendasikan menggunakan Apache (XAMPP/WAMP/Laragon).

## ⚙️ Cara Instalasi & Penggunaan
1.  **Persiapan Lingkungan:** Pastikan server lokal seperti XAMPP atau WAMP sudah terinstal.
2.  **Clone / Download:** Salin repositori ini ke folder `htdocs` (XAMPP) atau `www` (WAMP).
    ```bash
    git clone [https://github.com/ranggapgrl/Web-Caffe_Grounded.git](https://github.com/ranggapgrl/Web-Caffe_Grounded.git)
    ```
3.  **Pengaturan Database:**
    * Buka `localhost/phpmyadmin`.
    * Buat database baru dengan nama (sesuaikan dengan isi file di folder database).
    * Impor file `.sql` yang ada di dalam folder `database/`.
4.  **Konfigurasi Koneksi:** Sesuaikan kredensial database (host, user, pass) pada file konfigurasi di dalam folder `CF_Hasaja/`.
5.  **Akses Aplikasi:** Buka browser dan ketik `http://localhost/Web-Caffe_Grounded`.

## 👨‍💻 Kontributor
**Rangga (ranggapgrl)**
*Software Developer & Coding Instructor*

---
*Proyek ini dikembangkan sebagai bagian dari portofolio pengembangan aplikasi web menggunakan PHP dan MySQL.*

