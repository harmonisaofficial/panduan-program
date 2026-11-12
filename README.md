# Panduan Program Harmoni

Laman panduan surat dan dokumen program Persatuan Mahasiswa Harmoni UiTM Shah Alam.

## Isi folder

- `index.html`: laman utama (Semak keperluan, Program, Templat)
- `templates/`: templat Word, contoh kertas kerja HEMA (PDF) dan contoh poster
- `preview/`: gambar setiap halaman templat, untuk pratonton sebelum muat turun

## Cara terbitkan di GitHub Pages

1. Log masuk ke github.com, kemudian tekan **New repository**.
2. Namakan repo, contohnya `panduan-harmoni`. Pilih **Public**, kemudian tekan **Create repository**.
3. Pada halaman repo, tekan **uploading an existing file**.
4. Seret **semua isi** folder ini (`index.html`, `README.md`, folder `templates` dan folder `preview`) ke dalam kotak muat naik. Jangan seret folder induknya.
5. Tekan **Commit changes**.
6. Pergi ke **Settings → Pages**. Di bawah *Build and deployment*, pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, kemudian tekan **Save**.
7. Tunggu 1–2 minit. Pautan laman akan dipaparkan di bahagian atas halaman Pages:
   `https://<nama-pengguna>.github.io/panduan-harmoni/`

## Kemas kini templat

Untuk menggantikan templat, muat naik fail baharu ke folder `templates/` dengan **nama fail yang sama**, kemudian commit. Gambar pratonton dalam `preview/` tidak dikemas kini secara automatik, jadi gantikan juga gambar halaman (`<nama>-1.jpg`, `<nama>-2.jpg`, …) atau minta bantuan untuk menjananya semula.

Untuk menambah templat baharu, nama fail perlu ditambah dalam bahagian `FILES` di `index.html`.

## Senarai semak

Senarai semak program disimpan dalam pelayar setiap pengguna (localStorage). Ia tidak dikongsi dan tidak dihantar ke mana-mana pelayan.
