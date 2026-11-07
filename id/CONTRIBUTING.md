🌐 [English](../CONTRIBUTING.md) · Bahasa Indonesia

> ⚠️ Terjemahan ini dibuat dengan bantuan AI dan belum ditinjau oleh penutur asli. Mungkin masih ada kesalahan. Teks resminya adalah [versi bahasa Inggris](../CONTRIBUTING.md). Bantu kami: tinjau atau terjemahkan ulang.

# Berkontribusi

Manifesto ini bukan milik siapa pun: ia hanya titik awal. Koreksi, terjemahkan, perbaiki.

Semuanya berlangsung terbuka, di repositori ini. Tidak ada milis, tidak ada kanal pribadi. Issue dan pull request adalah catatannya.

## Cara berkontribusi

| Saya ingin… | Lakukan ini |
|---|---|
| Menandatangani manifesto | Ikuti [SIGNATURES.md](SIGNATURES.md) |
| Memperbaiki salah ketik atau tautan rusak | Langsung buka pull request |
| Mengusulkan perubahan kata-kata atau gagasan | Buka issue dengan templat **Text suggestion** |
| Menerjemahkan, atau meninjau terjemahan | Buka issue dengan templat **Translation or review**, lalu pull request |
| Bertanya atau menyampaikan keberatan | Cek dulu [FAQ.md](FAQ.md); kalau belum ada di sana, buka issue dengan templat **Text suggestion** dan beri label `question` |

## Teks resmi

- Teks resminya adalah versi bahasa Inggris di [README.md](../README.md).
- Teks bahasa Portugis di [pt/README.md](../pt/README.md) adalah naskah asli penulis dan acuan makna untuk semua terjemahan.
- Perubahan substansial pada teks resmi (apa pun selain salah ketik, tata bahasa, atau tautan) harus dimulai sebagai issue, agar alasannya terbuka sebelum ada yang diubah. Penulis dan para maintainer yang memutuskan; diskusinya tetap tercatat.
- Setiap perubahan lewat pull request yang ditinjau minimal satu maintainer. Branch `main` dilindungi; tidak ada yang di-push langsung ke sana, termasuk oleh maintainer.

## Terjemahan

1. Cek [TRANSLATIONS.md](../TRANSLATIONS.md) untuk melihat status bahasamu. Kalau sudah ada yang mengerjakannya, gabunglah di issue mereka, jangan buka yang baru.
2. Buka issue dengan templat **Translation or review**. Sebutkan bahasanya, apakah kamu penutur asli, dan apakah kamu menerjemahkan atau meninjau.
3. Terjemahkan dari teks bahasa Inggris. Kalau ada kalimat yang ambigu, gunakan naskah asli bahasa Portugis untuk menentukan maknanya. Pertahankan judul yang sama dan jumlah paragraf yang sama; jangan menambah, menghapus, atau mengubah urutan bagian.
4. Letakkan berkasnya di `<code>/README.md`, dalam folder yang dinamai dengan kode ISO 639-1 dua huruf (`es`, `fr`, `zh`, …); dokumen pendampingnya masuk ke folder yang sama: `PRINCIPLES.md`, `FAQ.md`, `NEUTRALITY.md`, `CONTRIBUTING.md`, `SIGNATURES.md`, dan `LICENSE` (terjemahan resmi Creative Commons, jika ada). Kalau suatu bahasa butuh varian regional, pakai tanda hubung dan kode wilayah (`pt-PT`, `zh-TW`).
5. Bahasa yang ditulis dari kanan ke kiri (Arab, Urdu, Persia, Ibrani): bungkus seluruh teks dengan `<div dir="rtl">` … `</div>`, dengan satu baris kosong setelah tag pembuka dan sebelum tag penutup. Lihat [ar/README.md](../ar/README.md).
6. Buka pull request. Terjemahan ditandai **Reviewed** setelah minimal satu penutur asli lain menyetujuinya di pull request.

Terjemahan ke bahasa di luar sepuluh yang terdaftar sangat disambut. Sepuluh itu titik awal, bukan batas.

## Gaya

- Kalimat pendek. Kata sederhana. Manifesto ini dibuat untuk dibacakan dengan lantang dan diulang-ulang.
- Jaga nadanya: mengajak, bukan menuduh. Kita menyalahkan jarak, bukan orang.
- Tidak ada partai, kandidat, pemerintah, atau negara yang didukung atau diserang, dalam bahasa apa pun.

## Sikap

Berdebat bukan berkelahi. Argumen punya sisi, dan sisi punya argumen. Tidak setuju dengan gagasan, bukan dengan orangnya. Maintainer akan menutup diskusi yang berubah menjadi serangan pribadi, dan dapat memblokir akun yang terus melakukannya.

## Lisensi

Dengan berkontribusi, kamu setuju kontribusimu diterbitkan di bawah lisensi yang sama dengan manifesto, [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). Penerjemah dicantumkan di berkas terjemahan dan di riwayat git.
