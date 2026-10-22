# Echoes of Veyra — v5.5 (versi tampil di kiri atas: "THE EXILED SOULS · v5.5")

**v5.5:** tampilan responsif.
- Ukuran kotak dan teks HUD menyesuaikan layar otomatis: mengecil di HP kecil, membesar di tablet/browser (index dan battle).
- Di browser (lebar ≥ 900 px) seluruh peta otomatis di-zoom agar muat dan memenuhi layar; tepi di luar peta diisi pepohonan. Di HP kamera selalu berpusat pada pemain, tanpa tertahan di tepi peta.
- Tekan **Z** (atau menu → Kamera) untuk berpindah antara "Pas layar" dan "Ikuti pemain". Pilihan tersimpan.
- Interior dan tap/klik pada peta ikut menyesuaikan zoom.

**v5.4:** musuh baru **Pipit Hitam** (menggantikan Moss Slime di Hutan Berbisik) dengan sprite besar di arena: idle mengepak, menyerang dengan menyambar ke arah Kael, bereaksi saat kena hit, dan jatuh saat kalah. Arena battle memakai latar bersih (`assets/battle_bg_clean.jpg`) agar sprite asli tidak bertumpuk dengan gambar karakter/UI bawaan latar lama. Kelemahan Pipit: Lightning (x1.5), Ice (x1.25); resist Wind.

**Perbaikan v5.1:** ketuk di bagian mana pun pada bangunan kini bisa masuk (sebelumnya hanya dekat pintu); tidak macet lagi bila ada NPC di jalan; keluar lebih mudah (area pintu lebih lebar, tombol A dekat pintu, ketuk pintu); penanda ▲ MASUK dan ▼ KELUAR.

**v5.3:** UI HP dirapikan (HUD tidak saling menimpa; dialog, hint, dan toast di atas kontrol; level/EXP pindah ke kiri atas; footer disembunyikan di layar kecil). Kael sedikit diperkecil agar proporsional dengan bangunan.

## v5: masuk bangunan
Tekan INTERAKSI (atau Enter/Spasi, atau sentuh bangunan) di dekat pintu untuk masuk. Keluar lewat pintu di bagian bawah ruangan.
- **Penginapan:** Bu Sera. Menginap 20 Gil memulihkan HP dan MP penuh (tidak dipungut bila sudah penuh).
- **Toko Desa:** pedagang membuka toko yang sama dengan sebelumnya.
- **Rumah Tetua:** Tetua Aldren, dialog berubah mengikuti status quest.
- **Rumah Lyria:** Lyria memberi petunjuk.
- **Gudang:** peti sekali ambil (40 Gil + 2 Ramuan HP), status peti ikut tersimpan.
- Menyimpan saat di dalam bangunan akan menaruh Kael di depan pintu bangunan itu.

## v4
- Battle memakai artwork Kael, quest ikut tersimpan, autosave, tombol Game Baru.

## v3
- Walk 8 frame, idle 6 frame.

## Catatan
- Interior memakai gambar Canvas sederhana (belum ada artwork khusus).
- Kael digambar sedikit lebih kecil di dalam ruangan agar proporsional.

## Upload ke Netlify
Ekstrak zip ini, lalu drag-and-drop **isi folder** (yang ada `index.html` di dalamnya) ke Netlify Drop. Zip ini sudah disusun dengan `index.html` di root. File `_headers` mencegah browser memakai versi lama. Setelah deploy, pastikan tulisan "v5.5" muncul di kiri atas game; kalau tidak, itu masih versi lama (coba hard refresh atau buka di tab privat).
