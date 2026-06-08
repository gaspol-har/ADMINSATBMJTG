# Checklist Satuan Brimob Polda Jawa Tengah

Halaman web statis untuk mengunduh **Checklist Perlengkapan Perorangan** dan
**Checklist Berkas Administrasi** dalam format PDF berkop resmi satuan.

## Fitur
- Kop satuan (logo + alamat) di **pojok kiri atas** tiap PDF.
- Judul **CHECKLIST PERLENGKAPAN PERORANGAN** / **CHECKLIST BERKAS ADMINISTRASI**
  rata tengah dengan garis bawah.
- Tabel checklist + kolom kotak centang, kolom tanda tangan (yang bersangkutan & pemeriksa).
- Form data personel opsional (Nama, Pangkat/NRP, Kesatuan, Keperluan) yang ikut tercetak.
- 100% berjalan di peramban (client-side), tanpa server. Logo sudah tertanam di dalam file.

## Cara deploy ke GitHub Pages
1. Buat repository baru di GitHub, mis. `checklist-brimob`.
2. Unggah file **`index.html`** (dan `README.md`) ke repository.
3. Buka **Settings ▸ Pages**.
4. Bagian *Build and deployment* ▸ *Source*: pilih **Deploy from a branch**.
5. *Branch*: pilih **main** dan folder **/ (root)**, lalu **Save**.
6. Tunggu ±1 menit, situs aktif di `https://<username>.github.io/checklist-brimob/`.

> Tidak perlu file lain — cukup `index.html`.
