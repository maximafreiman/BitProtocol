# BitProtocol

> Memahami Bitcoin dari dalam — bukan dari hype.

BitProtocol adalah kurikulum interaktif yang membangun pemahaman Bitcoin dari bawah ke atas. Setiap konsep dijelaskan dengan bahasa yang jujur, disertai simulasi langsung yang bisa dicoba di browser — tanpa instalasi, tanpa framework, tanpa jargon berlebihan.

---

## Kenapa BitProtocol Ada

Banyak orang "punya Bitcoin" tapi tidak paham cara kerjanya. Mereka mengirim satoshi ke alamat yang salah, menyimpan di custodial wallet tanpa sadar risikonya, atau bingung kenapa fee bisa lebih besar dari nilai yang dikirim.

BitProtocol dibuat untuk mengisi gap itu — bukan tutorial "cara beli Bitcoin", tapi fondasi teknis yang membuat seseorang benar-benar mengerti apa yang mereka pegang.

---

## Kurikulum

| Bab | Judul | Topik Utama |
|-----|-------|-------------|
| 01 | Permasalahan Sistem Terpusat | Single point of failure, kepercayaan, kontrol |
| 02 | Sejarah Perbankan & Internet | Konteks historis sebelum Bitcoin lahir |
| 03 | Apa Itu Bitcoin | Protokol vs aset, desentralisasi nyata |
| 04 | Sejarah Kriptografi & Bitcoin | Caesar cipher → Cypherpunk → Genesis Block |
| 05 | Kriptografi Dasar Bitcoin | CSPRNG, ECC, keypair, tanda tangan digital, hash |
| 06 | Transaksi Bitcoin | UTXO, input/output, fee implisit, RBF |
| 07 | Block & Blockchain | Anatomi block, Merkle Tree, chain, immutability |
| 08 | Mining & Proof of Work | Hash puzzle, difficulty, halving, block reward |
| 09 | Konsensus & Jaringan | Node, longest chain, fork, 51% attack |
| 10 | Wallet & Self-Custody | Seed phrase, BIP39, custodial vs non-custodial, Lightning |

---

## Fitur

- **10 bab lengkap** — berurutan, membangun satu di atas yang lain
- **Simulasi interaktif** di setiap bab — bukan sekadar teks
- **Progress indicator** — dot tracker di setiap bab, tersimpan otomatis
- **Resume otomatis** — kembali ke bab terakhir setelah menutup browser
- **PWA-ready** — bisa di-install ke home screen Android & iOS
- **Offline support** — setelah dibuka pertama kali, bisa dibaca tanpa internet
- **Single file** — seluruh kurikulum ada dalam satu `index.html`, tidak ada dependency

---

## Simulasi yang Tersedia

- CSPRNG keypair generator
- ECC clock visualization
- Digital signature simulator
- Hash function simulator
- UTXO wallet interaktif
- Transaction builder (pilih UTXO, hitung kembalian & fee)
- RBF (Replace-By-Fee) simulator
- Blockchain tampering simulator
- Merkle Tree interaktif
- Hash puzzle & Auto-Mine
- Mining race antar miner
- Difficulty adjustment simulator
- Halving chart (2024 → ~2140)
- Node network broadcast animation
- Fork simulator
- 51% attack calculator
- Seed phrase & HD wallet generator
- On-chain vs Lightning comparison

---

## Teknologi

Tidak ada framework. Tidak ada build step. Tidak ada dependency.

```
HTML + CSS + Vanilla JavaScript
```

Buka `index.html` di browser, langsung jalan.

---

## Deploy

BitProtocol di-host di Netlify:

🌐 **[bitprotocol.netlify.app](https://bitprotocol.netlify.app)**

---

## Penggunaan Lokal

```bash
git clone https://github.com/maximafreiman/BitProtocol.git
cd bitprotocol
# Buka index.html di browser — tidak perlu server
open index.html
```

---

## Lisensi

**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**

Kamu bebas untuk:
- ✅ Membagikan — menyalin dan mendistribusikan materi ini
- ✅ Mengadaptasi — mengubah, mentransformasi, dan membangun di atas materi ini

Dengan syarat:
- **Atribusi** — Sebutkan nama pembuat asli dan cantumkan link ke lisensi ini
- **NonKomersial** — Tidak boleh digunakan untuk kepentingan komersial
- **BerbagiSerupa** — Jika kamu mengadaptasi, distribusikan dengan lisensi yang sama

[Lihat teks lengkap lisensi →](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## Kontribusi

Menemukan kesalahan konten? Ada konsep yang kurang tepat?

Buka [Issue](https://github.com/maximafreiman/BitProtocol/issues) dan jelaskan temuanmu. Pull request untuk perbaikan konten sangat diterima.

Untuk penambahan fitur besar, buka diskusi dulu sebelum membuat PR.

---

*"Don't trust, verify."*
