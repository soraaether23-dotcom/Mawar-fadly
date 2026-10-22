# Maken Invited — Fadli & Mawar

## Struktur wajib
Pastikan folder yang diunggah ke GitHub memiliki struktur ini:

    index.html
    assets/
      asset-....png / .webp / .mp3
    README.md

`index.html` dan folder `assets` harus berada pada tingkat folder yang sama.

## Menguji sebelum publikasi
1. Ekstrak ZIP ini.
2. Buka folder `Maken_Invited_Paket_GitHub`.
3. Klik dua kali `index.html` untuk pemeriksaan awal lokal.
4. Untuk hosting, unggah seluruh isi folder ke akar repositori GitHub.
5. Di GitHub: Settings > Pages > Deploy from a branch > main > /(root) > Save.

## Jika tampilan rusak setelah diunggah
- Jangan mengunggah `index.html` saja.
- Jangan mengganti nama folder `assets`.
- Jangan meletakkan `index.html` di dalam folder lain, misalnya `Maken_Invited_Paket_GitHub/Maken_Invited_Paket_GitHub/index.html`.
- Jika menggunakan GitHub Desktop, salin `index.html`, `assets/`, dan `README.md` ke folder repositori lokal, kemudian Commit dan Push.
- Setelah pembaruan, lakukan hard refresh di browser: Ctrl+F5.

## Catatan ukuran
HTML ini merujuk pada aset eksternal di folder `assets`. Ini sengaja dibuat agar file HTML utama kecil dan tidak melewati batas unggahan per-file GitHub. Jangan menggabungkan semua gambar dan audio kembali ke dalam HTML.
