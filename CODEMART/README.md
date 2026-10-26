# CODEMART — Misi Toko Online

Media pembelajaran interaktif Informatika Kelas X Fase E tentang ekspresi dalam pemrograman, sesuai dengan `LKPD_Revisi_Misi_Toko_Online.docx` yang menjadi acuan.

## Cara menjalankan
1. Ekstrak ZIP ini ke folder di komputer.
2. Buka `index.html` dengan browser modern (Chrome, Edge, Firefox).
3. Tidak perlu instalasi, akun, backend, API key, atau server lokal untuk fungsi inti.

> Catatan: Google Fonts hanya digunakan sebagai peningkatan tipografi jika internet tersedia. Aplikasi dan logika inti berjalan lokal; jika offline, browser menggunakan font sistem.

## Isi proyek
- `index.html` — struktur aplikasi.
- `style.css` — desain responsif.
- `app.js` — navigasi, simulator, parser ekspresi terbatas, umpan balik, latihan, dan progres lokal.
- `README.md` — panduan ini.

## Fitur
- Dashboard dan progres berbasis aktivitas.
- Petunjuk belajar dan alur lima fase PBL.
- Misi Kasus (LKPD A), pengaturan saldo kelompok dan peran.
- Modul 1: penugasan variabel berurutan (LKPD B).
- Modul 2: lima ekspresi wajib aritmatika (LKPD C).
- Modul 3: enam operator relasional dan nilai true/false (LKPD D).
- Modul 4: transaksi Dina, pajak, ongkir, voucher, dan kecukupan saldo (LKPD E).
- Ringkasan materi untuk kesimpulan kelompok (LKPD F).
- 13 latihan bertingkat dengan umpan balik.
- Hasil belajar dan refleksi tersimpan lokal.
- Mode guru, mode presentasi, dan Exit Ticket lima soal.
- Ekspresi diproses menggunakan parser terbatas; tidak memakai `eval()`.

## Data utama dari LKPD
- Subtotal Dina: `(85000 * 2) + (45000 * 1) = 215000`
- Pajak: `subtotal * 10 / 100 = 21500`
- Total: `subtotal + pajak + 10000 - 20000 = 226500`
- Cek saldo: `cukup = saldo >= total`

Saldo kelompok pada prompt: Kelompok 1 Rp250.000; Kelompok 2 Rp226.500; Kelompok 3 Rp226.000; Kelompok 4 Rp215.000. Saldo awal mengikuti Kelompok 1 dan dapat diganti melalui Misi Kasus atau Mode Guru.

## Catatan penggunaan pedagogis
Website adalah media eksplorasi dan pemeriksaan hasil, bukan pengganti LKPD. Peserta didik tetap menulis prediksi, hasil web, alasan, kesimpulan, dan jawaban Exit Ticket pada LKPD sesuai instruksi guru.
