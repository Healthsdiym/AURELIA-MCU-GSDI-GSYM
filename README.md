# AURELIA MCU — GSDI & GSYM

**AURELIA — Astra Agro Health Intelligence & Analytics**

Dashboard monitoring Medical Check Up (MCU) untuk PT GSDI dan PT GSYM.

## Struktur

- `index.html` — aplikasi web utama.
- `AURELIA-logo-mark.png` — logo AURELIA.
- `AURELIA-branding.png` — master visual branding.

## Fitur utama

- Dashboard monitoring MCU.
- Filter perusahaan GSDI / GSYM.
- Input transaksi kehadiran peserta.
- Status: BELUM HADIR, HADIR / PROSES, MCU SELESAI, TIDAK HADIR.
- Form Hasil MCU.
- Monitoring pencapaian per AFD/Bagian.
- Export data ke Excel.
- Responsive untuk desktop dan mobile.
- Penyimpanan transaksi browser melalui IndexedDB dengan fallback localStorage pada versi standalone.

## Data master

Master peserta dapat dimuat melalui fitur Import Excel pada aplikasi. Format sumber mengikuti workbook MCU yang digunakan untuk GSDI dan GSYM.

## Deployment GitHub Pages

1. Buat repository GitHub, misalnya `AURELIA-MCU-GSDI-GSYM`.
2. Upload seluruh isi folder ini ke root repository.
3. Pastikan `index.html` berada di root.
4. Buka **Settings → Pages**.
5. Pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/ (root)`.
7. Save.

URL GitHub Pages akan mengikuti format:

`https://USERNAME.github.io/AURELIA-MCU-GSDI-GSYM/`

## Catatan

Versi ini mempertahankan logic aplikasi yang ada. Firebase/realtime multi-device dapat diaktifkan sebagai tahap berikutnya tanpa mengubah workflow transaksi yang sudah berjalan.
