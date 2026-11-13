# To-Do List Kelompok 1

Aplikasi web To-Do List sederhana yang dibuat oleh satu kelompok (6 orang) dalam satu sprint Scrum selama 45 menit. Proyek ini adalah praktikum mata pelajaran **Rekayasa Perangkat Lunak (RPL)** dengan materi metode Agile/Scrum dan kolaborasi kode menggunakan Git & GitHub.

## Deskripsi

Pengguna mengetik tugas di kotak isian, menekan tombol **Tambah**, lalu tugas muncul di daftar. Aplikasi dibangun dengan **HTML, CSS, dan JavaScript tanpa framework**, agar fokus praktikum tetap pada proses Scrum dan Git.

## Fitur

- Menambahkan tugas baru ke daftar (tugas kosong diabaikan)
- Menandai tugas selesai dengan **klik satu kali** (tugas menjadi tercoret)
- Menghapus tugas dengan **klik dua kali**
- Menampilkan **jumlah tugas** secara otomatis
- Tampilan rapi dan mudah dibaca

## Cara Menjalankan

Tidak perlu instalasi apa pun.

1. Clone repository ini:
   ```bash
   git clone https://github.com/adamming26>/todo-kelompok-1.git
   cd todo-kelompok-1
   ```
2. Buka file `index.html` di browser (klik dua kali pada file, atau klik kanan lalu *Open with* browser).
3. Ketik tugas di kotak isian, lalu klik **Tambah**.

## Cara Menggunakan

| Aksi | Cara |
|---|---|
| Menambah tugas | Tulis tugas di kotak isian, klik tombol **Tambah** |
| Menandai selesai | Klik tugas di daftar |
| Membatalkan tanda selesai | Klik tugas yang sudah tercoret |
| Menghapus tugas | Klik dua kali pada tugas |

## Struktur Proyek

```
todo-kelompok-1/
├── index.html   # Halaman utama (US-1)
├── script.js    # Fitur tambah tugas dan tandai selesai (US-2)
├── style.css    # Tampilan (US-3)
├── README.md    # Dokumentasi proyek (US-4)
├── hapus.js     # Fitur hapus tugas (US-5)
└── hitung.js    # Fitur jumlah tugas (US-6)
```

### ID elemen HTML yang dipakai bersama

| ID | Fungsi |
|---|---|
| `inputTugas` | Kotak isian tugas |
| `btnTambah` | Tombol Tambah |
| `daftarTugas` | Daftar tugas |
| `jumlahTugas` | Teks jumlah tugas |

## Anggota Kelompok dan Peran Scrum

| No | Nama | Peran | User Story | File | Branch |
|---|---|---|---|---|---|
| 1 | Adam | Scrum Master (SM) | US-1 | `index.html` | `fitur/us-1-halaman` |
| 2 | Cinta | Developer 1 | US-2 | `script.js` | `fitur/us-2-tambah-tugas` |
| 3 | Ridha | Developer 2 | US-3 | `style.css` | `fitur/us-3-tampilan` |
| 4 | Marcelo | Product Owner (PO) | US-4 | `README.md` | `fitur/us-4-readme` |
| 5 | Amal | Developer 3 | US-5 | `hapus.js` | `fitur/us-5-hapus-tugas` |
| 6 | Ihwal | Developer 4 | US-6 | `hitung.js` | `fitur/us-6-jumlah-tugas` |

**Tanggung jawab peran:**

- **Product Owner**: menentukan prioritas backlog, menerima atau menolak hasil saat sprint review.
- **Scrum Master**: membuat repository, menjaga waktu (timebox), memimpin daily scrum, dan melakukan merge pull request.
- **Developer**: mengerjakan user story, membuat pull request, dan me-review pull request teman.

## Product Backlog

| ID | User Story |
|---|---|
| US-1 | Sebagai pengguna, saya ingin melihat halaman berisi judul, kotak isian, dan tombol Tambah, agar bisa menulis tugas. |
| US-2 | Sebagai pengguna, saya ingin menambahkan tugas ke daftar dan menandainya selesai, agar bisa mencatat pekerjaan. |
| US-3 | Sebagai pengguna, saya ingin tampilan yang rapi dan tugas selesai tercoret, agar nyaman dibaca. |
| US-4 | Sebagai pengembang, saya ingin README yang menjelaskan aplikasi dan anggota tim, agar proyek mudah dipahami orang lain. |
| US-5 | Sebagai pengguna, saya ingin menghapus tugas dengan klik dua kali, agar daftar tidak penuh tugas lama. |
| US-6 | Sebagai pengguna, saya ingin melihat jumlah tugas di daftar, agar tahu berapa banyak pekerjaan saya. |

## Definition of Done (DoD)

- [x] Aplikasi bisa dibuka di browser
- [x] Tugas bisa ditambahkan
- [x] Tugas yang diklik tercoret
- [x] Tugas bisa dihapus dengan klik dua kali
- [x] Jumlah tugas tampil
- [x] Tampilan rapi
- [x] README menjelaskan aplikasi

## Alur Kerja Sprint (45 Menit)

| Menit | Tahap |
|---|---|
| 0–5 | Sprint Planning |
| 5–10 | Persiapan repository |
| 10–30 | Sprint (coding, commit, push, pull request) |
| 20 | Daily Scrum |
| 30–38 | Integrasi (review dan merge pull request) |
| 38–42 | Sprint Review |
| 42–45 | Retrospektif |

## Alur Kolaborasi Git & GitHub

- Setiap anggota bekerja di **branch sendiri** dan tidak langsung push ke `main`.
- Setiap anggota membuat **pull request**, lalu di-review oleh pasangan reviewer: SM ↔ PO, Developer 1 ↔ Developer 3, Developer 2 ↔ Developer 4.
- Scrum Master melakukan merge dengan urutan: US-1, US-3, US-2, US-5, US-6, US-4.
- Pesan commit diawali ID user story, contoh: `US-2: menambahkan fitur tambah tugas`.

## Teknologi

- HTML
- CSS
- JavaScript (tanpa framework)
- Git & GitHub

---

Dibuat oleh Kelompok 1, Kelas A, dalam praktikum Rekayasa Perangkat Lunak (RPL).