# 📘 Modul 4: Konsep Dasar CSS

## 🎯 Tujuan Pembelajaran
Setelah mempelajari modul ini, mahasiswa mampu:
1. Memahami dasar-dasar CSS (Cascading Style Sheet).
2. Menggunakan aturan dasar CSS untuk mempercantik tampilan web.
3. Menerapkan berbagai properti CSS untuk mengontrol teks, font, ukuran, dan layout.
4. Memahami konsep **inheritance**, **selectors**, dan **box model**.
5. Membuat halaman web dengan gaya berbeda sesuai kebutuhan.

---

## 1. 🔗 Links
CSS dapat dihubungkan ke HTML dengan tiga cara:
1. **Inline CSS**
   ```html
   <p style="color:blue;">Teks ini berwarna biru</p>
   ```
2. **Internal CSS**
   ```html
   <style>
     p { color: green; }
   </style>
   ```
3. **External CSS**
   ```html
   <link rel="stylesheet" href="style.css">
   ```

---

## 2. 📚 Pengenalan Cascading Style Sheet: Basic Example & Inheritance
- **Cascading** → aturan CSS mengikuti prioritas: inline > internal > external.
- **Inheritance** → beberapa properti diwariskan ke elemen turunan, misalnya `color` dan `font-family`.

Contoh:
```html
<body style="color: blue;">
  <p>Teks ini biru karena mewarisi dari body</p>
</body>
```

---

## 3. ⚖️ CSS Rules
Struktur dasar aturan CSS:
```css
selector {
  property: value;
}
```

Contoh:
```css
h1 {
  color: red;
  font-size: 24px;
}
```

---

## 4. 🛠️ CSS Properties
Beberapa properti umum:
- **color**, **background-color**
- **font-family**, **font-size**
- **margin**, **padding**, **border**
- **width**, **height**

---

## 5. ✍️ Controlling Fonts
Mengatur font dengan CSS:
```css
p {
  font-family: "Arial", sans-serif;
  font-size: 16px;
  font-weight: bold;
}
```

---

## 6. 🔤 Text Formatting
Beberapa properti:
```css
p {
  text-align: justify;
  text-decoration: underline;
  text-transform: capitalize;
}
```

---

## 7. 🎭 Text Pseudo-Classes
Pseudo-class digunakan untuk keadaan tertentu.
```css
a:link { color: blue; }
a:hover { color: red; }
a:visited { color: purple; }
```

---

## 8. 🎯 Selectors
Jenis-jenis selector:
```css
/* Elemen */
p { color: black; }

/* ID */
#judul { font-size: 24px; }

/* Class */
.highlight { background-color: yellow; }

/* Group */
h1, h2, p { margin: 10px; }

/* Descendant */
div p { color: gray; }
```

---

## 9. 📏 Length
Satuan panjang:
- Absolut: `px`, `pt`, `cm`
- Relatif: `%`, `em`, `rem`, `vw`, `vh`

Contoh:
```css
p {
  font-size: 1.5em;  
  margin: 10px;
}
```

---

## 10. 📦 Percentages & Box Model
CSS Box Model terdiri dari:
- **Content**
- **Padding**
- **Border**
- **Margin**

Contoh:
```css
div {
  width: 50%;       
  padding: 20px;
  border: 2px solid black;
  margin: 10px;
}
```

---

# 🧩 Latihan Eksplorasi: Semantic HTML + CSS Dasar

## 1. Profil Pribadi dengan Semantic + CSS
- Buat halaman profil pribadi menggunakan struktur semantic (`<header>`, `<main>`, `<section>`, `<footer>`).  
- Tambahkan CSS:
  - Atur warna teks (`color`) dan latar belakang (`background-color`) berbeda untuk tiap bagian.
  - Gunakan **font-family** berbeda untuk judul dan isi.  

---

## 2. Artikel Sederhana
- Buat halaman artikel dengan `<article>` dan `<aside>`.  
- Tambahkan CSS:
  - Atur ukuran teks judul artikel (`font-size`).
  - Gunakan **text-align** (misalnya center, justify).
  - Tambahkan warna link dan efek hover pada link artikel terkait.  


---

## 3. Navigasi Dasar
- Buat navigasi sederhana dengan `<nav>` yang berisi beberapa link.  
- Tambahkan CSS:
  - Ubah warna link default (`a { color: ... }`).
  - Gunakan pseudo-class `:hover` untuk memberi efek saat diarahkan mouse.
  - Gunakan pseudo-class `:visited` untuk link yang sudah dikunjungi.  

---

## 4. Eksperimen Panjang & Persentase
- Buat 2 kotak di dalam `<section>`.  
- Kotak pertama: gunakan `width` dalam **px** (misalnya 200px).  
- Kotak kedua: gunakan `width` dalam **%** (misalnya 50%).  
- Tambahkan **padding** dan **margin** untuk membedakan ruang.  
➡️ Variasi mahasiswa: ukuran, warna, margin, padding berbeda.

---

## 5. Tugas Akhir Modul (Mini Page)
- Buat satu halaman dengan struktur semantic lengkap: `<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>`.  
- Tambahkan CSS dasar:
  - Atur warna teks dan latar.
  - Gunakan font berbeda untuk header dan isi.
  - Format teks (tebal, miring, underline) pada beberapa bagian.
  - Gunakan minimal satu pseudo-class pada link.  
➡️ Hasil tiap mahasiswa akan berbeda karena bebas memilih tema, warna, dan isi halaman.


---

📚 **Referensi:**
- [W3Schools CSS](https://www.w3schools.com/css/)
- [MDN CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
