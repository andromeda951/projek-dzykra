# 🎮 Challenge — Upgrade Rock Paper Scissors

Kamu sudah berhasil membuat game **Rock Paper Scissors (Batu, Gunting, Kertas)**.

Sekarang saatnya mengembangkan game tersebut dengan beberapa fitur tambahan.

Gunakan program Rock Paper Scissors yang sudah kamu buat sebelumnya sebagai dasar.

---

## 🎯 Challenge 1 — Input Harus Valid

Saat ini program masih bisa menerima input yang tidak sesuai.

Contoh:

```text
=== RONDE 1 ===
Pilihan kamu: apel
Pilihan komputer: batu

Kamu menang!
```

Perbaiki program agar pemain **harus memasukkan pilihan yang valid**.

Pilihan yang diperbolehkan:

```text
batu
gunting
kertas
```

Jika pemain memasukkan pilihan yang salah:

```text
Pilihan kamu: apel

Pilihan tidak valid!
```

Program harus meminta pemain memasukkan pilihan lagi sampai benar.

---

## 🎯 Challenge 2 — Tampilkan Skor Setiap Ronde

Saat ini skor hanya ditampilkan di akhir permainan.

Ubahlah program agar skor ditampilkan setelah setiap ronde.

Contoh:

```text
=== RONDE 3 ===

Pilihan kamu: batu
Pilihan komputer: gunting

Kamu menang!

Skor sementara:
Kamu     : 2
Komputer : 1
```

---

## 🎯 Challenge 3 — Statistik Permainan

Tambahkan statistik permainan.

Setelah permainan selesai, tampilkan:

```text
====================
STATISTIK GAME
====================

Menang : 3
Seri   : 1
Kalah  : 1
```

Program harus menghitung:

* Berapa kali pemain menang
* Berapa kali seri
* Berapa kali pemain kalah

---

## 🎯 Challenge 4 — Main Lagi

Setelah permainan selesai, tanyakan kepada pemain:

```text
Main lagi? (y/n):
```

Jika pemain memilih `y`, maka permainan dimulai kembali.

Jika pemain memilih `n`, maka program berhenti dan menampilkan:

```text
Terima kasih sudah bermain!
```

Contoh:

```text
====================
KAMU MENANG!
====================

Main lagi? (y/n): y


=== ROCK PAPER SCISSORS ===

=== RONDE 1 ===
...
```

---

## 🎯 Challenge 5 — Pilihan Menggunakan Angka

Ubah cara pemain memilih.

Sebelumnya:

```text
Pilihan kamu: batu
```

Sekarang gunakan menu:

```text
=== ROCK PAPER SCISSORS ===

1. Batu
2. Gunting
3. Kertas

Pilihan kamu: 1
```

Jika pemain memilih:

* `1` → Batu
* `2` → Gunting
* `3` → Kertas

Pilihan yang tidak tersedia harus ditolak.

Contoh:

```text
Pilihan kamu: 5

Pilihan tidak valid!

Pilihan kamu: 2
```

---

## 🔥 Challenge 6 — Best of 3 / Best of 5

Tambahkan pilihan mode permainan.

Di awal permainan tampilkan:

```text
=== ROCK PAPER SCISSORS ===

1. Best of 3
2. Best of 5

Pilih mode:
```

### Best of 3

Pemain yang mendapatkan **2 kemenangan** terlebih dahulu menjadi pemenang.

Contoh:

```text
Skor:
Kamu     : 2
Komputer : 0

====================
KAMU MENANG!
====================
```

Permainan tidak perlu menunggu sampai 3 ronde jika salah satu pemain sudah mendapatkan 2 kemenangan.

### Best of 5

Pemain yang mendapatkan **3 kemenangan** terlebih dahulu menjadi pemenang.

Contoh:

```text
Skor:
Kamu     : 1
Komputer : 3

====================
KOMPUTER MENANG!
====================
```

Permainan berhenti ketika salah satu pemain sudah mendapatkan 3 kemenangan.

---

## ⭐ Bonus Challenge 1 — Nama Pemain

Tambahkan nama pemain di awal permainan.

Contoh:

```text
Masukkan nama kamu: Andi
```

Kemudian gunakan nama tersebut pada hasil permainan.

Contoh:

```text
Andi menang!

Skor akhir:
Andi      : 3
Komputer  : 1
```

---

## ⭐ Bonus Challenge 2 — Riwayat Permainan

Simpan hasil setiap ronde.

Di akhir permainan, tampilkan riwayat permainan.

Contoh:

```text
====================
RIWAYAT PERMAINAN
====================

Ronde 1
Kamu     : batu
Komputer : gunting
Hasil    : Menang

Ronde 2
Kamu     : kertas
Komputer : kertas
Hasil    : Seri

Ronde 3
Kamu     : gunting
Komputer : batu
Hasil    : Kalah
```

---

## ⭐ Bonus Challenge 3 — Statistik Lengkap

Gabungkan seluruh informasi permainan menjadi hasil akhir.

Contoh:

```text
========================
HASIL AKHIR
========================

Nama          : Andi
Total ronde   : 5

Menang        : 3
Seri          : 1
Kalah         : 1

Skor kamu     : 3
Skor komputer : 1

========================
ANDI MENANG!
========================
```

---

## 🏆 Target Akhir

Jika semua challenge berhasil dikerjakan, game kamu memiliki fitur:

* Input yang tervalidasi
* Skor setiap ronde
* Statistik permainan
* Fitur bermain kembali
* Pilihan menggunakan angka
* Mode Best of 3
* Mode Best of 5
* Nama pemain
* Riwayat permainan
* Statistik lengkap

Tidak harus mengerjakan semuanya sekaligus.

Kerjakan **Challenge 1 → 2 → 3 → 4 → 5 → 6** secara berurutan.

Setelah semua selesai, lanjutkan ke **Bonus Challenge**.

---

## 📌 Aturan

1. Gunakan program Rock Paper Scissors yang sudah dibuat sebelumnya.
2. Jangan menghapus fitur utama permainan.
3. Program harus tetap bisa dimainkan dengan normal.
4. Kerjakan challenge secara bertahap.
5. Coba pecahkan masalah sendiri sebelum mencari solusi.
6. Jika menemukan error, baca pesan error dan cari tahu penyebabnya.
7. Setelah satu challenge selesai, pastikan program masih berjalan dengan benar sebelum lanjut ke challenge berikutnya.
8. **Jangan langsung menyalin solusi dari internet.**
9. Jika mengalami kesulitan, coba jelaskan terlebih dahulu bagian mana yang belum kamu pahami.

```
```

