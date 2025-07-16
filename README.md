
# KalkulatorJS

Sebuah **kalkulator sederhana berbasis web** menggunakan **HTML**, **CSS**, dan **JavaScript**. Dirancang untuk melakukan operasi dasar serta beberapa fungsi ekstra jika diperlukan.

---

## 🎯 Fitur

- Operasi aritmatika dasar:
  - Penjumlahan (`+`)
  - Pengurangan (`−`)
  - Perkalian (`×`)
  - Pembagian (`÷`)
- Mendukung input angka desimal (float)
- **Opsional** (tergantung implementasi):
  - Clear (`C`)
  - Plus/Minus toggle (`±`)
  - Angka terakhir (`Ans`)
  - Persen (`%`)

---

## 📁 Struktur Direktori

```
KalkulatorJS/
├─ index.html           # Tampilan halaman kalkulator
├─ style.css            # Styling untuk UI
└─ app.js               # Logika kalkulasi (event handling & evaluasi)
```

---

## 🚀 Cara Menjalankan

1. Clone repo:
   ```bash
   git clone https://github.com/BintangSry/KalkulatorJS.git
   ```
2. Masuk ke direktori:
   ```bash
   cd KalkulatorJS
   ```
3. Buka `index.html` di browser (cukup klik dua kali atau gunakan live server).

---

## 🛠️ Cara Kerja

- Tombol tombol (`0-9`, operator, `=`, `C`, dll.) terhubung dengan event listener di `app.js`.
- Input POP secara dinamis ditampilkan di layar kalkulator.
- Ekspresi dihitung saat `=` ditekan.
- Fitur tambahan:
  - `C` = Clear layar.
  - `±` = Toggle positif/negatif.
  - `Ans` = Menyimpan hasil terakhir.

---

## 🧪 Contoh Penggunaan

| Input         | Output |
|---------------|--------|
| `12 + 7` `=`  | `19`   |
| `5.3 × 2` `=` | `10.6` |
| `10 ÷ 4` `=`  | `2.5`  |
| `C`           | Layar reset |

---

## 🧩 Kontribusi

Kontribusi sangat welcome! Silakan:

1. Fork repositori ini.
2. Buat branch baru: `git checkout -b fitur-baru`.
3. Commit perubahan kamu: `git commit -m "Menambah fitur X"`.
4. Push ke branch: `git push origin fitur-baru`.
5. Buat pull request.

---

## ✨ Ide Pengembangan

- Menambahkan **kalkulator ilmiah** (fungsi `sin`, `cos`, `tan`, `sqrt`, `exp`, `ln`, `π`, `e`, dsb.)
- Support keyboard input penuh.
- Mode tema (gelap/terang).
- Riwayat perhitungan (`history`).

---

## 📄 Lisensi

MIT © 2025 — dibuat oleh BintangSry

---

## 📌 Kontak

Jika ada pertanyaan atau ide:
- Instagram/Twitter: `@BintangSry`  
- Email: misal `bintangsry@example.com` (jika mau ditambahkan)

---

Selamat coding 🧑‍💻, semoga bermanfaat dan makin berkembang! 🚀
