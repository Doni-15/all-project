# Kumpulan Project C++ Dasar

Repository ini berisi empat latihan aplikasi command-line C++ yang dibuat untuk mempraktikkan algoritma, input/output, sorting, searching, dan pemodelan alur program sederhana.

## Isi Repository

1. **Tower of Hanoi ASCII Simulation** — simulasi rekursif Tower of Hanoi.
2. **CLI-Based E-Lottery Scratch Game** — permainan lotre sederhana di terminal.
3. **Graduation Result Viewer with Sorting & Searching** — pengelolaan hasil kelulusan dengan sorting dan searching.
4. **Simple Cashier System** — simulasi kasir berbasis CLI.

Setiap folder memiliki `main.cpp`, screenshot, dan README singkatnya sendiri.

## Kompilasi

Gunakan compiler yang mendukung C++17. Tiga program pertama mengimpor `windows.h`, sehingga perlu dikompilasi pada Windows atau menggunakan toolchain yang menyediakan Windows API. Contoh dengan MinGW pada Windows:

```bash
cd "1. Tower of Hanoi ASCII Simulation"
g++ -std=c++17 -Wall -Wextra main.cpp -o app
./app
```

Ulangi pola yang sama pada folder lain. `Simple Cashier System` tidak bergantung pada `windows.h` dan berhasil dikompilasi dengan GCC 16.1.1 pada Linux saat audit; tiga program lainnya belum portable ke Linux. Semua program bersifat interaktif, jadi output bergantung pada input pengguna.

## Konteks

Ini adalah kumpulan learning lab, bukan satu aplikasi production. Nilai utamanya berada pada jejak pembelajaran algoritma dan dasar pemrograman C++.
