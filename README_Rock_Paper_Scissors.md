# 🎮 Mini Project — Rock Paper Scissors

Buat sebuah program **Rock Paper Scissors (Batu, Gunting, Kertas)** menggunakan Python.

Dalam game ini, pemain bermain melawan komputer.

Komputer akan memilih salah satu dari:
- `batu`
- `gunting`
- `kertas`

Pemain juga memilih salah satu pilihan tersebut.

Aturan permainan:

- Batu menang melawan Gunting
- Gunting menang melawan Kertas
- Kertas menang melawan Batu
- Jika pilihan sama, hasilnya Seri

---

## 🎯 Target 1 — Pilihan Pemain

Minta pemain memasukkan pilihannya.

Contoh:

```text
=== ROCK PAPER SCISSORS ===

Pilih:
1. batu
2. gunting
3. kertas

Pilihan kamu: batu
```

**Konsep:** `input`, variable.

---

## 🎯 Target 2 — Pilihan Komputer

Gunakan module `random` agar komputer memilih secara acak.

Contoh:

```text
=== ROCK PAPER SCISSORS ===

Pilihan kamu: batu
Pilihan komputer: kertas
```

**Konsep:** `random`, list.

> 💡 Petunjuk: Kamu bisa menyimpan pilihan `batu`, `gunting`, dan `kertas` ke dalam sebuah list.

---

## 🎯 Target 3 — Tentukan Pemenang

Bandingkan pilihan pemain dan komputer.

Jika sama:

```text
Pilihan kamu: batu
Pilihan komputer: batu

Seri!
```

Jika pemain menang:

```text
Pilihan kamu: batu
Pilihan komputer: gunting

Kamu menang!
```

Jika komputer menang:

```text
Pilihan kamu: batu
Pilihan komputer: kertas

Komputer menang!
```

**Konsep:** `if / elif / else`.

---

## 🎯 Target 4 — Main 5 Kali

Sekarang buat game dimainkan sebanyak **5 ronde**.

Contoh:

```text
=== ROUND 1 ===
Pilihan kamu: batu
Pilihan komputer: gunting
Kamu menang!

=== ROUND 2 ===
Pilihan kamu: kertas
Pilihan komputer: kertas
Seri!

=== ROUND 3 ===
Pilihan kamu: gunting
Pilihan komputer: batu
Komputer menang!
```

Lanjutkan sampai ronde ke-5.

**Konsep:** `for` loop.

> 💡 Gunakan `for` untuk mengulang permainan sebanyak 5 kali.

---

## 🎯 Target 5 — Hitung Skor

Tambahkan skor untuk pemain dan komputer.

Setiap ronde:

- Pemain menang → skor pemain +1
- Komputer menang → skor komputer +1
- Seri → tidak ada yang mendapat poin

Contoh:

```text
=== ROUND 1 ===
Kamu menang!

=== ROUND 2 ===
Seri!

=== ROUND 3 ===
Komputer menang!

=== ROUND 4 ===
Kamu menang!

=== ROUND 5 ===
Kamu menang!

====================
Skor kamu: 3
Skor komputer: 1
====================
```

**Konsep:** counter + `for` loop + `if`.

---

## 🎯 Target 6 — Tentukan Pemenang Akhir

Setelah 5 ronde selesai, tentukan siapa yang memenangkan pertandingan.

Jika skor pemain lebih tinggi:

```text
====================
Skor kamu: 3
Skor komputer: 1

KAMU MENANG!
====================
```

Jika skor komputer lebih tinggi:

```text
====================
Skor kamu: 1
Skor komputer: 4

KOMPUTER MENANG!
====================
```

Jika skornya sama:

```text
====================
Skor kamu: 2
Skor komputer: 2

HASIL AKHIR: SERI!
====================
```

**Konsep:** `if / elif / else`.

---

## 🧠 Konsep yang Dipelajari

```text
Target 1
input + variable
   ↓
Target 2
random + list
   ↓
Target 3
if / elif / else
   ↓
Target 4
for loop
   ↓
Target 5
counter + loop + if
   ↓
Target 6
if / elif / else
```

## 🎯 Tujuan Project

Setelah menyelesaikan project ini, kamu diharapkan memahami:

- penggunaan `input`
- penggunaan variable
- penggunaan list
- penggunaan `random`
- penggunaan `if / elif / else`
- penggunaan `for` loop
- penggunaan counter
- menggabungkan beberapa konsep Python dalam satu program

## ⭐ Bonus Challenge

Jika semua target sudah selesai, tambahkan fitur:

> Setelah pertandingan selesai, tanyakan apakah pemain ingin bermain lagi.

Contoh:

```text
Main lagi? (y/n): y

Game dimulai lagi!

Main lagi? (y/n): n

Terima kasih sudah bermain!
```

**Hint:** Gunakan `while`.
