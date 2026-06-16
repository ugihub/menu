# Panduan Menu Food Court Universitas Widyatama (Hosting Netlify)

Panduan ini dibuat khusus untuk membantu kamu mengelola dan menampilkan menu makanan kampus dengan cara yang sangat mudah, bahkan jika kamu belum pernah membuat website sebelumnya.

## Apa itu Aplikasi Ini?
Ini adalah website sederhana yang menampilkan daftar menu makanan dari berbagai kedai di Food Court Universitas Widyatama. Pengunjung bisa memilih kedai (seperti "Kedai Poci" atau "Bakmie Kampus") dan melihat foto menu yang tersedia.

---

## 📋 Cara Menyiapkan File (Persiapan)

Aplikasi ini terdiri dari beberapa bagian utama:
1. **index.html**: Halaman depan (daftar nama kedai).
2. **menu.html**: Halaman detail (untuk menampilkan foto-foto menu).
3. **Folder assets**: Tempat menyimpan semua foto makanan.

### Cara Menambah atau Mengganti Foto:
1. Siapkan foto menu kamu (format `.jpg`, `.png`, atau `.webp`).
2. Masukkan foto tersebut ke dalam folder `assets`.
3. Jika kedai tersebut punya banyak foto (seperti Kedai Poci), buatkan folder sendiri di dalam `assets` (contoh: `assets/poci/`).
4. Pastikan nama file foto di dalam kode `menu.html` (di bagian paling bawah dalam teks `<script>`) sama persis dengan nama file fotonya.

---

## 🚀 Cara Memasang (Hosting) ke Netlify
Netlify adalah tempat "menitipkan" file website agar bisa dibuka oleh orang lain lewat internet secara gratis.

### Langkah-langkah untuk Orang Awam:

1. **Siapkan Akun:**
   - Buka [netlify.com](https://www.netlify.com/).
   - Daftar (Sign Up) menggunakan email.

2. **Siapkan Folder:**
   - Pastikan semua file (`index.html`, `menu.html`, dan folder `assets`) berada dalam satu folder utama di komputer kamu (misal nama foldernya: `menu-kampus`).

3. **Unggah (Upload):**
   - Setelah masuk ke Netlify, cari menu **"Add new site"** lalu pilih **"Deploy manually"**.
   - Kamu akan melihat kotak besar bertuliskan *"Drag and drop your site folder here"*.
   - Tarik (drag) folder `menu-kampus` dari komputer kamu dan lepaskan (drop) ke kotak tersebut.

4. **Selesai!**
   - Tunggu beberapa detik hingga proses unggah selesai.
   - Netlify akan memberikan link otomatis (contoh: `https://nama-acak.netlify.app`).
   - Kamu bisa mengganti nama link tersebut di menu **"Site configuration"** > **"Change site name"**.

---

## 📱 Cara Menggunakan (Untuk Pengunjung)

1. Buka link website yang diberikan oleh Netlify di HP atau Laptop.
2. Klik salah satu tombol nama kedai (misal: **KEDAI POCI**).
3. Website akan menampilkan foto menu kedai tersebut.
4. Jika kedai punya lebih dari satu foto, klik kotak foto kecil (gambar mini) di bawah foto utama untuk mengganti tampilan.
5. Klik tombol **"KEMBALI KE MENU UTAMA"** untuk memilih kedai lain.

---

## 💡 Tips Tambahan
* **Ukuran Foto:** Usahakan ukuran foto tidak terlalu besar (di bawah 1MB) agar website terbuka dengan cepat saat dibuka lewat HP mahasiswa.
* **Update Menu:** Jika ada menu baru, cukup ganti file fotonya di komputer, lalu upload ulang foldernya ke Netlify (dengan cara tarik-lepas seperti langkah di atas).

---
*Dibuat untuk mempermudah akses informasi kuliner di Universitas Widyatama.*
