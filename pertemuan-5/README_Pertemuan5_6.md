# 📘 Pertemuan 5 & 6: Elemen-Elemen CSS dalam HTML

## 🎯 Tujuan Pembelajaran
Mahasiswa mampu memahami, menjelaskan, dan mengimplementasikan elemen-elemen CSS dalam HTML, meliputi:
1. Links
2. Backgrounds
3. Lists
4. Tables
5. Outlines
6. Pseudo-Classes `:focus` & `:active`
7. Generated Content
8. Miscellaneous Properties
9. Additional Rules
10. Positioning with CSS

---

## 📝 Materi

### 1. Links
CSS dapat mengatur tampilan hyperlink (`<a>`).
```css
a {
  color: blue;
  text-decoration: none;
}
a:hover {
  color: red;
}
a:visited {
  color: purple;
}
a:active {
  color: orange;
}
```

---

### 2. Backgrounds
Mengatur latar belakang elemen.
```css
body {
  background-color: lightgray;
  background-image: url("bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
```

---

### 3. Lists
Mengatur tampilan daftar.
```css
ul {
  list-style-type: square;
}
ol {
  list-style-type: upper-roman;
}
```

---

### 4. Tables
Menambahkan style pada tabel.
```css
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
th {
  background-color: lightblue;
}
```

---

### 5. Outlines
Outline berbeda dengan border (tidak memengaruhi layout).
```css
p {
  border: 1px solid black;
  outline: 2px dashed red;
}
```

---

### 6. Pseudo-Classes `:focus` & `:active`
- `:focus` → ketika elemen form aktif.
- `:active` → ketika elemen sedang ditekan.
```css
input:focus {
  border: 2px solid green;
}
button:active {
  background-color: yellow;
}
```

---

### 7. Generated Content
Menambahkan konten dengan `::before` dan `::after`.
```css
h1::before {
  content: "★ ";
  color: gold;
}
h1::after {
  content: " ★";
  color: gold;
}
```

---

### 8. Miscellaneous Properties
Beberapa properti tambahan.
```css
p {
  text-transform: uppercase;
  letter-spacing: 2px;
  word-spacing: 5px;
}
```

---

### 9. Additional Rules
Contoh aturan tambahan: mengatur opacity dan visibility.
```css
img {
  opacity: 0.7;
}
```

---

### 10. Positioning with CSS
Mengatur posisi elemen: `static`, `relative`, `absolute`, `fixed`, `sticky`.
```css
div.relative {
  position: relative;
  left: 30px;
}
div.absolute {
  position: absolute;
  top: 50px;
  left: 50px;
}
```

---

## 🧩 Latihan

### Latihan Dasar
1. Buat halaman dengan 3 link. Atur warnanya dengan CSS untuk kondisi normal, hover, visited, dan active.
2. Buat halaman dengan background:
   - Warna solid.
   - Gambar background (repeat dan cover).
3. Buat daftar (ul dan ol) dengan style berbeda (square, roman, none).
4. Buat tabel sederhana dengan border, warna header, dan hover effect pada baris.

---

### Latihan Menengah
5. Buat paragraf dengan border dan outline berbeda.
6. Buat form dengan input teks dan tombol. Beri style khusus pada saat `:focus` dan `:active`.
7. Gunakan `::before` dan `::after` untuk menambahkan ikon atau teks tambahan pada heading.
8. Coba properti tambahan seperti `text-transform`, `letter-spacing`, `word-spacing` pada paragraf.

---

### Latihan Eksplorasi
9. Buat halaman dengan satu gambar yang memiliki opacity 70%, lalu tambahkan efek hover agar opacity kembali 100%.
10. Buat 3 kotak dengan posisi:
    - Kotak pertama `relative`.
    - Kotak kedua `absolute` di pojok kanan atas.
    - Kotak ketiga `fixed` di pojok bawah kanan.
11. Kembangkan mini layout halaman dengan positioning CSS sederhana.

---

## ✅ Tugas Akhir Pertemuan
Buat sebuah halaman **bebas tema** dengan ketentuan:
- Menggunakan minimal 5 elemen CSS dari daftar materi (links, background, lists, tables, outlines, pseudo-class, generated content, dll).
- Menyertakan positioning (`relative`, `absolute`, atau `fixed`) pada salah satu elemen.
- Kreatifitas tema bebas (profil, artikel, portofolio, hobi, dsb).
