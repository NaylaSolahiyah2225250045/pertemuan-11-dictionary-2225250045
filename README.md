# Pertemuan 11 - Dictionary/Map
Nama: Nayla Solahiyah
NIM: 2225250045
Kelas: 3A

## Tujuan
Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value.

## Struktur Data
Program menggunakan NIM sebagai key utama untuk membedakan setiap mahasiswa. Value berupa dictionary yang berisi nama, kelas, dan nilai mahasiswa.

## Cara Menjalankan
```bash
python praktik/data_mahasiswa.py
```

## Test Case
| Input/Aksi | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|
| Pencarian A003 | Data Citra ditampilkan | A003: {'nama': 'Citra', 'kelas': 'B', 'nilai': 92} | Berhasil |
| Pencarian A999 | Data tidak ditemukan | Belum diuji | Belum diuji |
| A002 menjadi 82 | Nilai A002 berubah menjadi 82 | Nilai berubah menjadi 82 | Berhasil |
| Menambahkan A006 | Key A006 tersedia | A006 berhasil ditambahkan | Berhasil |
| Rekap menggunakan items() | Semua NIM dan data tampil | Semua data mahasiswa ditampilkan | Berhasil |

## Refleksi
Dari praktik ini, saya belajar menggunakan dictionary untuk menyimpan dan mengelola data. Saya juga memahami bahwa penggunaan key yang tidak tersedia dapat menyebabkan `KeyError`, sehingga method `get()` bisa digunakan untuk menghindari kesalahan tersebut