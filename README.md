# Pono Music

**Pemutar musik web gratis** bergaya Spotify dengan katalog [YouTube Music](https://music.youtube.com). Tanpa akun.

- **Website:** [pono-music.vercel.app](https://pono-music.vercel.app)
- **Repo asli:** [github.com/ramax100/YT-Music-Mod](https://github.com/ramax100/YT-Music-Mod)

> **Proyek ini adalah fork.** Seluruh kode dan fitur berasal dari [YT-Music-Mod (Rich Music)](https://github.com/ramax100/YT-Music-Mod) buatan **ramax100**. Terima kasih kepada pembuat aslinya.

---

## Apa yang berbeda dari repo asli

Perubahannya sedikit. Semua fitur dan cara kerja aplikasi tetap sama dengan aslinya.

| Yang diubah | Keterangan |
| --- | --- |
| **Nama** | Dari *Rich Music* menjadi **Pono Music** |
| **Domain** | Menggunakan `pono-music.vercel.app` |
| **Logo** | Logo baru (headphone dengan nota musik, latar transparan) |
| **iPhone** | Musik bisa tetap berjalan di latar belakang di iPhone |

Selain empat hal di atas, tidak ada perubahan lain.

---

## Tentang

Pono Music adalah pemutar musik di browser. Cari lagu, buka album dan artis, buat playlist, lihat lirik, atur antrian, semuanya tanpa daftar akun.

Library (favorit, playlist, riwayat, statistik) tersimpan di perangkatmu. Audio diputar lewat pemutar resmi YouTube.

Tidak berafiliasi dengan YouTube, Google, atau Spotify.

---

## Cara memakai

1. Buka **[pono-music.vercel.app](https://pono-music.vercel.app)**
2. Cari lagu, atau pilih dari Home / Charts / Browse all
3. Ikon hati = favorit. **Playlist** = simpan ke folder
4. Pindah HP? Library → **Backup**, di perangkat baru **Restore**

---

## Fitur

- Pencarian dengan saran otomatis, filter lagu/video/album/artis/playlist
- Home, Charts, dan rekomendasi dari favorit & riwayat
- Library lokal: playlist, favorit, riwayat, statistik, Backup / Restore
- Import dari link YouTube Music
- Antrian, shuffle, repeat, kecepatan putar 0.5×–2×
- Lirik sinkron
- Download MP3 dan SponsorBlock
- Sleep timer, widget mengambang, Picture-in-Picture
- Mode gelap / terang

Daftar fitur lengkap ada di [repo asli](https://github.com/ramax100/YT-Music-Mod).

---

## Menjalankan di komputer sendiri

Perlu [Node.js](https://nodejs.org) 18+ (disarankan 20).

```bash
git clone https://github.com/zeanadira69-dotcom/Music.git
cd Music
npm install
npm start
```

Buka **http://localhost:3000**

---

## Deploy ke Vercel

Di dashboard Vercel: **Add New → Project → Import Git Repository** → pilih repo ini → **Deploy**.

Setiap commit baru ke branch `main` akan otomatis dideploy ulang.

---

## Isi repo

```
Music/
├── public/           # website (HTML, CSS, JS, logo)
├── server.js         # API: YouTube Music, lirik, download
├── api/index.js      # entry Vercel
├── vercel.json
├── package.json
└── README.md
```

---

## Lisensi dan kredit

Proyek asli dinyatakan **gratis dan bebas dipakai**: dijalankan, dibagikan, diubah, dan dideploy ulang. Fork ini mengikuti ketentuan yang sama.

Kode asli oleh **ramax100** — [YT-Music-Mod](https://github.com/ramax100/YT-Music-Mod).
