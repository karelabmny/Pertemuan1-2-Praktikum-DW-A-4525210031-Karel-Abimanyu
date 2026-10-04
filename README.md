# Penulis

Dibuat oleh Karel Abimanyu Ahpandi, mahasiswa Teknik Informatika, Universitas Pancasila.
NIM : 4525210031 | Kelas : A

# Profil UKM Basket Universitas Pancasila

Halaman web statis sederhana yang saya buat menggunakan HTML untuk memperkenalkan UKM Basket Universitas Pancasila (UKM BASKET KMUP). Halaman ini berisi profil UKM, program latihan, alur pendaftaran anggota baru, serta kontak dan media sosial.

## Deskripsi Singkat

Proyek ini saya buat untuk menerapkan dasar-dasar HTML, seperti struktur dokumen, heading, paragraf, gambar, list , link, dan navigasi antarbagian dalam satu halaman.

## Struktur Halaman

- **Header**: judul "UKM Basket Universitas Pancasila" (`<h1>`).
- **Navigasi**: tautan anchor (`<nav>` dan `<a href="#...">`) yang membawa pengguna ke bagian Profil, Program Latihan, Pendaftaran Anggota, dan Kontak.
- **Profil UKM**: logo (`<img>` dengan atribut `alt` dan `width`) serta paragraf yang menjelaskan UKM Basket KMUP, tahun resmi menjadi UKM (2016), julukan para pebasket (*Hope*), dan prestasi tim. Teks ditebalkan dengan `<strong>` dan dimiringkan dengan `<em>`.
- **Program Latihan**: daftar tidak berurutan (`<ul>`) dengan sub-daftar bersarang, yaitu Latihan Fisik (lari dan daya tahan, kekuatan otot), Latihan Teknik (shooting, dribbling, passing), dan Latihan Taktik Tim.
- **Pendaftaran Anggota Baru**: tahapan pendaftaran dalam bentuk ordered list (`<ol>`): mengisi formulir, mengikuti sesi tryout, dan mengikuti latihan perdana.
- **Kontak & Media Sosial**: tautan website kampus, Instagram, dan YouTube (`target="_blank"` agar terbuka di tab baru) serta email (`mailto:`).
- **Footer**: pernyataan hak cipta dengan simbol `&copy;`.

## Tag HTML yang Digunakan

| Tag | Fungsi |
| --- | --- |
| `<!DOCTYPE html>` | Menentukan bahwa dokumen menggunakan HTML5 |
| `<html lang="id">` | Elemen root dengan bahasa Indonesia |
| `<head>`, `<meta>`, `<title>` | Informasi dokumen, encoding (UTF-8), dan judul tab |
| `<h1>` - `<h2>` | Judul dan subjudul |
| `<p>` | Paragraf |
| `<nav>`, `<a>` | Navigasi dan tautan (anchor internal, tautan eksternal, dan `mailto:`) |
| `<img>` | Menampilkan logo UKM |
| `<ul>`, `<ol>`, `<li>` | Daftar tidak berurutan (termasuk bersarang) dan berurutan |
| `<strong>`, `<em>` | Teks tebal dan teks miring |
| `<br>` | Pindah baris pada bagian kontak |
| `&ndash;`, `&amp;`, `&copy;` | Entitas HTML untuk tanda hubung, simbol &, dan simbol hak cipta |

## Cara Menjalankan

1. Simpan kode sebagai `Tugas 2.html`.
2. Pastikan file logo tersedia sesuai path pada atribut `src` di tag `<img>`. Jika folder proyek dipindahkan ke komputer lain, ubah path tersebut menjadi path relatif, misalnya `img/nama-file-logo.jpg`, dan letakkan file logo di folder `img` pada direktori yang sama.
3. Buka `Tugas 2.html` di browser (Chrome, Firefox, dll.).

## Hasil Run

<img width="1920" height="1045" alt="output tugas 2 src" src="https://github.com/user-attachments/assets/306f3524-b90f-44e1-918a-96d65e2d1751" />
