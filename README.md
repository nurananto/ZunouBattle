# Ore wa Gakuen Zunou Battle no Enshutsuka!

> Di Akademi Teio, segalanya ditentukan lewat duel permainan. Yang harus kulakukan sebagai perwujudan karakter figuran, Tanaka Kanata, bukanlah meraih kejayaan untuk diriku sendiri! Satu-satunya tugasku adalah “menyutradarai” dari balik layar agar Kiriya, murid pindahan terkuat dari bawah, hingga mencapai puncak sebagai 'protagonis terkuat'!  …Seharusnya begitu, tapi entah sejak kapan aku sendiri malah ikut jadi pusat perhatian—ini maksudnya apa sih!? Komedi pertarungan akademi terkuat sepanjang sejarah karya dari orang yang mengaku-ngaku sebagai seorang 'sutradara' resmi dimulai!

---

## Info

| | |
|---|---|
| Judul | Ore wa Gakuen Zunou Battle no Enshutsuka! |
| Judul Alternatif | 俺は学園頭脳バトルの演出家! |
| Author | Hotori Katanuma |
| Artist | Hattori Masaki |
| Tipe | Manga (Hitam Putih) |
| Genre | Shounen · Comedy · Action · School Life · Psychological · Video Games |

## Link

- [MangaDex](https://mangadex.org/title/00fccb9d-c43b-4083-b68d-693f5501ea78/ore-wa-gakuen-zunou-battle-no-ensyutsuka-jishou-mob-ga-kage-kara-egaku-saikyou-shujinkou-musou)
- [Raw](https://comic-gardo.com/episode/2551460909967440804)

---

## Struktur

```
ZunouBattle/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)