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
3.  Ikuti petunjuk instalasi *default* (pilih `1`).
4.  Aktifkan lingkungan Rust di sesi terminal saat ini:
    ```bash
    source $HOME/.cargo/env
    ```
5.  Verifikasi instalasi:
    ```bash
    rustc --version
    cargo --version
    ```

### 2. Menggunakan GitHub Codespaces (Lingkungan Otomatis)

Proyek ini telah dikonfigurasi untuk Codespaces, yang akan otomatis menyiapkan lingkungan Rust dan ekstensi VS Code yang diperlukan.

Cukup buka repositori ini di Codespaces, dan semua alat akan tersedia berkat konfigurasi di `.devcontainer/devcontainer.json`.

### 3. Cara Menjalankan Kode Contoh

#### A. Untuk File Tunggal (Misalnya `main.rs`)

1.  Kompilasi file kode:
    ```bash
    rustc <nama_file>.rs
    # Contoh: rustc hello_world/main.rs 
    ```
2.  Jalankan *executable binary* yang dihasilkan:
    ```bash
    ./<nama_file_tanpa_ekstensi>
    # Contoh: ./hello_world/main 
    ```
    (Hasil dari contoh `hello_world/main.rs` adalah: "Hello, world!")

#### B. Untuk Proyek dengan Cargo

Jika Anda menggunakan proyek yang dibuat dengan `cargo new`:

1.  Masuk ke direktori proyek.
2.  Jalankan dan kompilasi kode secara instan:
    ```bash
    cargo run
    ```
3.  Hanya untuk mengompilasi tanpa menjalankan:
    ```bash
    cargo build
    ```

---

## 📅 Log Pembelajaran Harian (History Belajar)

| Tanggal | Aktivitas Belajar | Hasil / Catatan |
| :--- | :--- | :--- |
| 2025-10-26 | **Setup Awal & Hello World** | Menginstal Rust dengan `rustup`. Membuat struktur folder awal. Menulis program pertama `hello_world/main.rs`. |
| 2025-10-26 | **Konfigurasi Codespaces** | Mengatur `.devcontainer/devcontainer.json` untuk integrasi otomatis Rust di Codespaces menggunakan *feature*. Menginstal ekstensi `rust-analyzer`. |
| **[YYYY-MM-DD]** | [Topik yang Dipelajari] | [Ringkasan singkat atau poin penting] |
| **[YYYY-MM-DD]** | [Topik yang Dipelajari] | [Ringkasan singkat atau poin penting] |
| **[YYYY-MM-DD]** | [Topik yang Dipelajari] | [Ringkasan singkat atau poin penting] |