# 🦀 Belajar Rust: Repository Pembelajaran Dasar

Repositori ini berisi catatan, kode contoh, dan proyek mini untuk mempelajari bahasa pemrograman Rust.

## 🚀 Memulai

### 1. Prasyarat: Instalasi Rust

Cara paling disarankan untuk menginstal Rust adalah menggunakan `rustup`.

1.  Buka Terminal Anda.
2.  Jalankan skrip instalasi:
    ```bash
    curl --proto '=https' --tlsv1.2 -sSf [https://sh.rustup.rs](https://sh.rustup.rs) | sh
    ```
3.  Ikuti petunjuk instalasi *default*.
4.  Aktifkan lingkungan Rust di sesi terminal saat ini:
    ```bash
    source $HOME/.cargo/env
    ```

### 2. Menggunakan GitHub Codespaces

Proyek ini telah dikonfigurasi untuk Codespaces, yang akan otomatis menyiapkan lingkungan Rust dan ekstensi VS Code yang diperlukan.

### 3. Cara Menjalankan Kode Contoh

#### A. Kompilasi Manual (Menggunakan `rustc`)

Digunakan untuk file Rust tunggal.

1.  Kompilasi file kode:
    ```bash
    rustc hello_world/main.rs 
    ```
2.  Jalankan *executable binary* yang dihasilkan:
    ```bash
    ./hello_world/main 
    ```
    (Contoh ada di `hello_world/main.rs`)

#### B. Menggunakan Cargo (Disarankan)

Digunakan untuk semua proyek Rust yang lebih kompleks.

1.  Masuk ke direktori proyek Cargo (misalnya `hello_cargo`).
2.  Jalankan dan kompilasi kode secara instan:
    ```bash
    cargo run
    ```
3.  Hanya untuk mengompilasi tanpa menjalankan:
    ```bash
    cargo build
    ```
    (Contoh proyek Cargo ada di `hello_cargo`)

---

## 📅 Log Pembelajaran Harian (History Belajar Berdasarkan Commit)

| Tanggal | Aktivitas Belajar | Folder Terkait | Hasil / Catatan |
| :--- | :--- | :--- | :--- |
| **2025-10-26** | **Setup Awal & Hello World Manual** | `hello_world` | Menginstal Rust dengan `rustup` dan mengkonfigurasi Codespaces. Membuat program pertama dan mengkompilasi secara manual menggunakan `rustc`. |
| **2025-10-26** | **Mempelajari Cargo** | `hello_cargo` | Memahami peran **Cargo** sebagai *build system* dan *package manager* Rust. Membuat proyek baru dengan `cargo new`. Menjalankan kode menggunakan `cargo run`. |
| **[YYYY-MM-DD]** | [Topik Belajar Selanjutnya, misal: Ownership & Borrowing] | [Nama folder/file] | [Catatan singkat atau hasil belajar] |