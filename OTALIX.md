# Otalix
Fork Metrolist dengan nama, warna biru, dan bottom bar liquid glass. Developer: Oscar Mandala.

## Build APK lewat GitHub Actions
1. Upload isi folder ini ke repo GitHub (branch `main`).
2. Tab Actions → **Build Otalix APK** → Run workflow (atau otomatis tiap push).
3. Selesai, unduh APK dari bagian Artifacts (`Otalix-debug-apk`).

## Yang diubah dari Metrolist
- Nama aplikasi jadi Otalix, applicationId `com.oscarmandala.otalix`.
- Warna tema default biru `#2F7BFF`, ikon launcher berlatar biru.
- Bottom bar melayang dengan tampilan kaca (aktif secara default).
- Login YouTube tetap opsional, aplikasi bisa dipakai tanpa login.
- Workflow lama Metrolist dipindah ke `.github/_metrolist-workflows`.

Lisensi tetap GPL-3.0 (lihat LICENSE) karena ini turunan Metrolist.
