# To-Do List App

## 1. Tujuan Aplikasi  
Aplikasi ini dibuat untuk membantu pengguna dalam mengelola daftar tugas (to-do list) sehari-hari dengan mudah dan efisien. Pengguna dapat menambahkan, mengedit, dan menghapus tugas serta mengelompokkan tugas berdasarkan kategori dan batas waktu.

## 2. Tech Stack  
Aplikasi ini dibangun menggunakan:  
- Python 3  
- Flask (Web Framework)  
- SQLite (Database)  
- HTML, CSS (Bootstrap untuk styling)

## 3. Fitur-Fitur

### Functional Requirements (Fitur Fungsional)  
- Menampilkan daftar tugas yang tersimpan dengan informasi judul, kategori, dan batas waktu.  
- Menambah tugas baru dengan input judul, kategori, dan tanggal jatuh tempo.  
- Mengedit tugas yang sudah ada.  
- Menghapus tugas.  
- Mengelompokkan kategori tugas (misal: Pribadi, Umum).  
- Validasi input form saat menambahkan atau mengedit tugas.

### Non-Functional Requirements (Fitur Non-Fungsional)  
- Antarmuka yang responsif dan user-friendly menggunakan Bootstrap.  
- Penyimpanan data yang sederhana dan ringan menggunakan SQLite.  
- Aplikasi berjalan secara lokal pada port default Flask (http://127.0.0.1:5000).  
- Kode sumber mudah dipahami dan dikembangkan.

## 4. Cara Instalasi  

### Persiapan Lingkungan  
1. Pastikan Python 3 sudah terinstall.  
2. (Opsional) Buat virtual environment untuk project:  
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/macOS  
   venv\Scripts\activate     # Windows
