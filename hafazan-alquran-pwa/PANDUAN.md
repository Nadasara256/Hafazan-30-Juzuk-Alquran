# Panduan: pasang Hafazan Al-Quran sebagai aplikasi

Pakej ini ialah versi yang boleh dipasang pada skrin utama telefon atau tablet (PWA). Selepas dipasang, ia dibuka skrin penuh dan berfungsi tanpa internet.

Aplikasi perlu diletakkan di satu pautan https supaya pelayar membenarkan pemasangan. Fail `.html` yang dibuka terus daripada telefon tidak boleh dipasang begini, tetapi masih berfungsi seperti biasa.

## 1. Letak di GitHub Pages (percuma)

1. Daftar akaun percuma di github.com, kemudian pilih **New repository**.
2. Namakan repositori (contohnya `hafazan`), pilih **Public**, dan cipta.
3. Pilih pautan **uploading an existing file**. Seret SEMUA fail dalam folder `hafazan-alquran-pwa` (index.html, sw.js, manifest.webmanifest dan semua fail .png), kemudian tekan **Commit changes**.
4. Buka **Settings > Pages**. Di bawah **Source** pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, kemudian **Save**.
5. Tunggu 1 hingga 2 minit. Pautannya: `https://NAMA-GITHUB-ANDA.github.io/hafazan/`

## 2. Pasang pada telefon (Chrome Android)

1. Buka pautan itu semasa ada internet dan biarkan halaman dimuat sepenuhnya sekali.
2. Tekan menu (tiga titik) > **Install app** atau **Add to Home screen**.
3. Buka daripada ikon baharu di skrin utama. Tekan lama ikon untuk pintasan Jadual, Uji dan Tracker.

Ulang langkah yang sama pada tablet jika mahu.

## 3. Pindahkan kemajuan sedia ada

Data tidak berpindah sendiri antara fail `.html` lama dan aplikasi baharu, kerana ia disimpan berasingan untuk setiap alamat.

1. Dalam versi lama: **Tetapan > Eksport kemajuan**.
2. Dalam aplikasi yang dipasang: **Tetapan > Import kemajuan** dan pilih fail tadi.

Telefon dan tablet juga tidak berkongsi data. Guna Eksport dan Import untuk memindahkannya.

## 4. Kemas kini kemudian

Gantikan SEMUA fail dalam repositori dengan versi baharu (sw.js turut berubah setiap kali). Kemudian buka aplikasi semasa ada internet, dua kali. Versi baharu dimuat di latar dan dipaparkan pada pembukaan seterusnya.

## Nota

- Pautan GitHub Pages bersifat awam. Sesiapa yang ada pautan boleh membuka aplikasi, tetapi kemajuan awak tidak dihantar ke mana-mana kerana ia hanya disimpan dalam pelayar peranti awak. Pautan juga mengandungi nama pengguna GitHub awak.
- Jika data pelayar dipadam, kemajuan hilang. Eksport secara berkala sebagai sandaran.
