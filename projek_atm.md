# 💳 Mini Project — ATM Sederhana

Buat sebuah program **ATM Sederhana** menggunakan Python.

Dalam program ini, pemain berperan sebagai pengguna ATM yang dapat melihat saldo, menarik uang, dan melakukan beberapa transaksi.

Saldo awal pengguna adalah **Rp500.000**.

Menu ATM:

* `cek saldo`
* `tarik uang`
* `keluar`

---

## 🎯 Target 1 — Tampilkan Menu ATM

Tampilkan menu ATM kepada pengguna.

Contoh:

```text
=== ATM SEDERHANA ===

1. Cek Saldo
2. Tarik Uang
3. Keluar

Pilihan kamu: 1
```

---

## 🎯 Target 2 — Cek Saldo

Jika pengguna memilih menu **Cek Saldo**, tampilkan saldo yang dimiliki.

Contoh:

```text
=== ATM SEDERHANA ===

1. Cek Saldo
2. Tarik Uang
3. Keluar

Pilihan kamu: 1

Saldo kamu: Rp500000
```

---

## 🎯 Target 3 — Tarik Uang

Jika pengguna memilih menu **Tarik Uang**, minta pengguna memasukkan jumlah uang yang ingin ditarik.

Contoh:

```text
=== ATM SEDERHANA ===

1. Cek Saldo
2. Tarik Uang
3. Keluar

Pilihan kamu: 2

Jumlah uang yang ingin ditarik: 100000

Penarikan berhasil!
Saldo kamu sekarang: Rp400000
```

---

## 🎯 Target 4 — Cek Saldo Sebelum Menarik

Sebelum melakukan penarikan, periksa apakah saldo pengguna cukup.

Jika saldo cukup:

```text
Jumlah uang yang ingin ditarik: 200000

Penarikan berhasil!
Saldo kamu sekarang: Rp300000
```

Jika saldo tidak cukup:

```text
Jumlah uang yang ingin ditarik: 600000

Saldo tidak cukup!
Saldo kamu: Rp500000
```

---

## 🎯 Target 5 — Beberapa Transaksi

Sekarang buat agar pengguna dapat melakukan transaksi beberapa kali.

Contoh:

```text
=== ATM SEDERHANA ===

1. Cek Saldo
2. Tarik Uang
3. Keluar

Pilihan kamu: 1

Saldo kamu: Rp500000

=== ATM SEDERHANA ===

1. Cek Saldo
2. Tarik Uang
3. Keluar

Pilihan kamu: 2

Jumlah uang yang ingin ditarik: 100000

Penarikan berhasil!
Saldo kamu sekarang: Rp400000

=== ATM SEDERHANA ===

1. Cek Saldo
2. Tarik Uang
3. Keluar

Pilihan kamu: 2

Jumlah uang yang ingin ditarik: 50000

Penarikan berhasil!
Saldo kamu sekarang: Rp350000
```

Buat agar menu ATM dapat digunakan sebanyak **5 kali**.

---

## 🎯 Target 6 — Tentukan Aksi Berdasarkan Menu

Buat program menjalankan aksi yang berbeda berdasarkan pilihan pengguna.

Jika memilih `1`:

```text
Saldo kamu: Rp500000
```

Jika memilih `2`:

```text
Jumlah uang yang ingin ditarik: 100000

Penarikan berhasil!
Saldo kamu sekarang: Rp400000
```

Jika memilih `3`:

```text
Terima kasih telah menggunakan ATM!
```

Jika memasukkan pilihan lain:

```text
Pilihan tidak tersedia!
```

---

## 🎯 Target 7 — Hitung Jumlah Transaksi

Tambahkan penghitung untuk mengetahui berapa kali pengguna melakukan penarikan uang.

Contoh:

```text
Penarikan berhasil!
Saldo kamu sekarang: Rp400000

Penarikan berhasil!
Saldo kamu sekarang: Rp300000

Penarikan berhasil!
Saldo kamu sekarang: Rp250000

====================

Jumlah penarikan: 3 kali
Saldo akhir: Rp250000

====================
```

Setiap pengguna berhasil melakukan penarikan, jumlah transaksi bertambah.

---

## 🎯 Target 8 — Kondisi Saldo Akhir

Setelah seluruh transaksi selesai, tampilkan kondisi saldo pengguna.

Jika saldo masih lebih dari `0`:

```text
====================

Saldo akhir: Rp250000

Saldo kamu masih tersedia.

====================
```

Jika saldo menjadi `0`:

```text
====================

Saldo akhir: Rp0

Saldo kamu sudah habis.

====================
```

---

# 🧠 Konsep yang Dipelajari

> **Buka bagian ini setelah mencoba menyelesaikan semua target.**

```text
Target 1

input + variable

   ↓

Target 2

variable

   ↓

Target 3

input + variable + operasi matematika

   ↓

Target 4

if / else

   ↓

Target 5

for loop

   ↓

Target 6

if / elif / else

   ↓

Target 7

counter + loop + if

   ↓

Target 8

if / else
```

## 🎯 Tujuan Project

Setelah menyelesaikan project ini, kamu diharapkan memahami:

* penggunaan `input`
* penggunaan variable
* penggunaan operasi matematika
* penggunaan `if / elif / else`
* penggunaan `for` loop
* penggunaan counter
* penggunaan kondisi
* mengubah nilai variable
* menggabungkan beberapa konsep Python dalam satu program

---

# 💡 Petunjuk

> **Coba kerjakan sendiri terlebih dahulu. Gunakan petunjuk ini jika mengalami kesulitan.**

### Target 1

Simpan pilihan pengguna ke dalam sebuah variable menggunakan `input`.

### Target 2

Simpan saldo awal ke dalam sebuah variable.

### Target 3

Gunakan `input` untuk meminta jumlah uang yang ingin ditarik. Jangan lupa mengubah input menjadi angka.

### Target 4

Bandingkan jumlah uang yang ingin ditarik dengan saldo menggunakan kondisi.

### Target 5

Gunakan `for` untuk mengulang proses transaksi sebanyak 5 kali.

### Target 6

Gunakan `if`, `elif`, dan `else` untuk menentukan tindakan berdasarkan pilihan menu.

### Target 7

Buat sebuah variable counter dengan nilai awal `0`. Tambahkan `1` setiap kali penarikan berhasil.

### Target 8

Gunakan kondisi untuk memeriksa apakah saldo akhir masih lebih dari `0` atau sudah habis.

---

# ⭐ Bonus Challenge

Jika semua target sudah selesai, tambahkan fitur **batas penarikan**.

Pengguna hanya boleh menarik uang maksimal **Rp200.000 dalam satu transaksi**.

Contoh:

```text
Jumlah uang yang ingin ditarik: 300000

Maksimal penarikan adalah Rp200000!
```

Jika pengguna menarik Rp150.000:

```text
Jumlah uang yang ingin ditarik: 150000

Penarikan berhasil!
Saldo kamu sekarang: Rp350000
```

Coba buat fitur ini tanpa melihat petunjuk terlebih dahulu.

### Hint

Gunakan kondisi untuk memeriksa jumlah uang yang ingin ditarik.
