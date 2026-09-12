# 📚 Books - Aplikasi Manajemen Buku (Proyek Praktikum)

[![.NET Framework](https://img.shields.io/badge/.NET%20Framework-4.7.2-blue.svg)](https://dotnet.microsoft.com/)
[![Language](https://img.shields.io/badge/Language-C%23-green.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![IDE](https://img.shields.io/badge/IDE-Visual%20Studio-purple.svg)](https://visualstudio.microsoft.com/)
[![Category](https://img.shields.io/badge/Category-Praktek%20%2F%20Practice-orange.svg)](#)

Aplikasi desktop **Books** berbasis Windows Forms (C#) yang dibangun sebagai **tugas praktikum** untuk mempelajari konsep dasar pembuatan GUI, pengolahan data, manajemen pengguna (User Management), serta interaksi basis data menggunakan **LINQ to SQL**.

---

## 📌 Fitur Utama

- 📖 **Manajemen Data Buku**: Menampilkan, menambah, memperbarui, dan menghapus data koleksi buku.
- 👤 **Manajemen Pengguna (Add User)**: Form khusus untuk menambahkan dan mengelola data pengguna/petugas.
- 🔗 **LINQ to SQL Integration**: Menggunakan `DataClasses1.dbml` untuk pemetaan Objek-Relasional (ORM) ke basis data SQL.
- 🖥️ **Antarmuka Grafis (GUI)**: Tampilan simpel dan interaktif berbasis Windows Forms.

---

## 🛠️ Teknologi & Stack

* **Bahasa Pemrograman**: C# (.NET Framework 4.7.2)
* **Tipe Aplikasi**: Windows Forms Application (WinForms)
* **ORM / Access Layer**: LINQ to SQL (`DataClasses1.dbml`)
* **Database**: Microsoft SQL Server / LocalDB
* **IDE**: Microsoft Visual Studio

---

## 📂 Struktur Proyek

```text
Books/
├── Books.sln                   # Solution File Visual Studio
└── Books/
    ├── Add User.cs             # Logic Form Tambah Pengguna
    ├── Add User.Designer.cs    # Layout UI Form Tambah Pengguna
    ├── Form1.cs                # Form Utama (Manajemen Buku)
    ├── DataClasses1.dbml       # Pemetaan LINQ to SQL
    ├── Program.cs              # Entry point aplikasi
    └── App.config              # Konfigurasi aplikasi & Connection String
```

---

## 🚀 Cara Menjalankan Proyek

1. **Clone Repository**:
   ```bash
   git clone https://github.com/username/Books.git
   ```
2. **Buka Proyek**:
   - Buka file `Books.sln` menggunakan Visual Studio 2019 / 2022.
3. **Konfigurasi Database**:
   - Sesuaikan *Connection String* pada file `App.config` atau melalui designer `DataClasses1.dbml` sesuai dengan instance SQL Server lokal Anda.
4. **Build & Run**:
   - Tekan `F5` atau klik tombol **Start** di Visual Studio untuk menjalankan aplikasi.

---

## 📝 Catatan Praktikum

Aplikasi ini merupakan bagian dari modul latihan/praktikum materi pemrograman berorientasi objek (OOP) dan pemrosesan basis data pada platform .NET C#.
