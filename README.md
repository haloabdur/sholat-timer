# Timer Sholat

Hitung mundur sederhana menuju waktu sholat berikutnya (5 waktu). Satu file `index.html` (HTML + CSS + JS), tanpa build, cocok untuk HP, monitor, atau TV masjid.

## Fitur

- Hitung mundur besar menuju sholat berikutnya (contoh: jam 07:00 → menuju Dzuhur).
- Saat waktu sholat tiba, layar menampilkan "Waktu … telah tiba" dengan jeda (default **5 menit**), lalu otomatis pindah ke sholat berikutnya.
- Pilih lokasi saat pertama dibuka: deteksi otomatis (GPS) atau cari kota (±100 kota Indonesia bawaan, plus pencarian online via OpenStreetMap).
- Mode terang / gelap / otomatis (mengikuti sistem).
- Pengaturan: durasi jeda (1–30 menit), metode perhitungan (default Kemenag RI: Subuh 20°, Isya 18°), koreksi waktu/ihtiyat (default +2 menit), layar tetap menyala.
- Tombol layar penuh untuk TV/monitor.
- Zona waktu WIB/WITA/WIT mengikuti provinsi lokasi.
- Semua pengaturan tersimpan di browser (localStorage).

## Cara pakai

Buka `index.html` di browser. Untuk TV masjid: buka di browser TV/Android box/PC, tekan tombol layar penuh.

Catatan:
- Perhitungan waktu sholat berjalan offline. Internet hanya dipakai untuk font Inter, pencarian kota online, dan nama lokasi dari GPS.
- Deteksi lokasi (GPS) dan "layar tetap menyala" butuh halaman dibuka lewat `https://` (misalnya GitHub Pages) atau `localhost`.
- Jadwal dihitung secara astronomis dan bisa berbeda 1–2 menit dari jadwal resmi Kemenag; sesuaikan lewat "Koreksi waktu (ihtiyat)" bila perlu.
