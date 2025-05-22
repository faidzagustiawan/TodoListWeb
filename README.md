# ✅ To-Do List Dashboard

Aplikasi dashboard to-do list berbasis HTML, JavaScript, dan Tailwind CSS. Dirancang dengan tampilan modern dan interaktif, aplikasi ini membantu pengguna mengelola tugas harian mereka dengan visualisasi status dan prioritas.

## ✨ Fitur Utama

* 🎨 **Desain modern** menggunakan Tailwind CSS
* 📝 Tambah tugas dengan:

  * Judul
  * Deskripsi
  * Tanggal
  * Prioritas (Low, Moderate, High)
* 📊 Visualisasi status tugas:

  * Not Started
  * In Progress
  * Completed
* 🔍 Kolom pencarian (dummy UI)
* 📅 Tampilan waktu dan ikon interaktif
* 👤 Tampilan profil pengguna sidebar

## 🧱 Teknologi yang Digunakan

* **HTML5** – Struktur halaman
* **Tailwind CSS** – Desain UI yang cepat dan fleksibel
* **JavaScript** – Fungsi interaktif (popup, tambah tugas, validasi)
* **Font Awesome** – Ikon-ikon pada UI

## 📦 Struktur Folder

```bash
├── index.html           # File utama aplikasi
├── src/
│   └── output.css       # Output Tailwind CSS
│   └── input.css        # Input Tailwind CSS
├── README.md
```

## 🚀 Cara Menjalankan

1. **Pastikan sudah generate file CSS dari Tailwind:**
   Jika menggunakan Tailwind CLI atau PostCSS, jalankan:

   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```

2. **Buka file `index.html` di browser**:

   * Klik dua kali
   * Atau buka dengan Live Server (VS Code Extension)

3. **Gunakan tombol "add task"** untuk menambahkan tugas baru.

## 🧠 Cara Kerja

* Form tambah tugas akan muncul dalam modal popup.
* Tugas disimpan secara **sementara di DOM**, tidak ada penyimpanan ke database atau localStorage.
* Setelah tugas ditambahkan:

  * Ditampilkan di bawah bagian "My Tasks"
  * Status awal: "Not Started"
  * Prioritas diberi warna sesuai level
* Diagram lingkaran pada "Task Status" menunjukkan persentase (dummy).

## 📝 Catatan

* Aplikasi ini **belum menyimpan data secara permanen**.
* Tidak menggunakan framework JS seperti React/Vue.
* Cocok sebagai template awal untuk project dashboard tugas.

## 📸 Cuplikan Tampilan

> *(Tambahkan screenshot aplikasi di sini jika ada)*

```markdown
![Preview Aplikasi](path/to/screenshot.png)
```

## 📄 Lisensi

Proyek ini bersifat open-source dan bebas digunakan untuk pembelajaran atau pengembangan lebih lanjut.
