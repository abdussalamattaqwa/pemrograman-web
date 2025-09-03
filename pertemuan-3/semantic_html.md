# 📘 Modul 3: Semantic HTML

## 🎯 Tujuan Pembelajaran
Setelah mempelajari topik ini, mahasiswa mampu:
1. Memahami konsep **Semantic HTML** dan perbedaannya dengan non-semantic HTML.
2. Menggunakan elemen-elemen semantic HTML untuk membuat struktur halaman yang lebih bermakna.
3. Menerapkan semantic HTML untuk meningkatkan aksesibilitas dan SEO.

---

## 1. 🔎 Apa itu Semantic HTML?
**Semantic HTML** adalah penggunaan elemen HTML yang memiliki **makna khusus** (semantic) sesuai dengan konten yang dibungkusnya.  
Dengan semantic HTML:
- Struktur halaman menjadi lebih **jelas dan bermakna**.  
- Mesin pencari (SEO) lebih mudah memahami isi konten.  
- Membantu **aksesibilitas** (screen reader, alat bantu navigasi).  

Contoh:  
```html
<!-- Non-Semantic -->
<div id="header"></div>
<div id="footer"></div>

<!-- Semantic -->
<header></header>
<footer></footer>
```

---

## 2. 📑 Elemen-elemen Semantic HTML

### 2.1 `<header>`
Mendefinisikan bagian atas dari halaman atau section, biasanya berisi **judul, logo, navigasi**.  
```html
<header>
  <h1>Website Belajar HTML</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="artikel.html">Artikel</a>
    <a href="kontak.html">Kontak</a>
  </nav>
</header>
```

### 2.2 `<nav>`
Menandai **navigasi utama** dalam halaman.  
```html
<nav>
  <ul>
    <li><a href="home.html">Home</a></li>
    <li><a href="profil.html">Profil</a></li>
    <li><a href="kontak.html">Kontak</a></li>
  </ul>
</nav>
```

### 2.3 `<main>`
Mendefinisikan konten utama yang unik dalam halaman (hanya satu `<main>` per halaman).  
```html
<main>
  <h2>Artikel Terbaru</h2>
  <p>Ini adalah isi utama dari halaman web.</p>
</main>
```

### 2.4 `<section>`
Mendefinisikan **bagian (section)** dalam halaman, biasanya digunakan untuk mengelompokkan konten berdasarkan topik.  
```html
<section>
  <h2>Tentang Kami</h2>
  <p>Kami adalah komunitas belajar web programming.</p>
</section>
```

### 2.5 `<article>`
Digunakan untuk konten yang berdiri sendiri seperti **artikel, blog post, atau berita**.  
```html
<article>
  <h2>Belajar HTML Dasar</h2>
  <p>HTML adalah bahasa markup standar untuk membuat halaman web.</p>
</article>
```

### 2.6 `<aside>`
Konten sampingan, biasanya berupa sidebar, iklan, atau informasi tambahan.  
```html
<aside>
  <h3>Artikel Populer</h3>
  <ul>
    <li><a href="#">Belajar CSS</a></li>
    <li><a href="#">Belajar JavaScript</a></li>
  </ul>
</aside>
```

### 2.7 `<footer>`
Bagian bawah halaman atau section, biasanya berisi copyright, kontak, atau link tambahan.  
```html
<footer>
  <p>&copy; 2025 Belajar HTML. All Rights Reserved.</p>
</footer>
```

---

## 3. 🧩 Contoh Struktur Halaman dengan Semantic HTML
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Website Belajar HTML</title>
</head>
<body>
  <header>
    <h1>Belajar Semantic HTML</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="artikel.html">Artikel</a>
      <a href="kontak.html">Kontak</a>
    </nav>
  </header>

  <main>
    <article>
      <h2>Apa itu Semantic HTML?</h2>
      <p>Semantic HTML adalah elemen HTML yang memberikan makna terhadap konten yang dibungkusnya.</p>
    </article>

    <section>
      <h2>Manfaat Semantic HTML</h2>
      <ul>
        <li>Struktur halaman lebih jelas</li>
        <li>SEO lebih baik</li>
        <li>Meningkatkan aksesibilitas</li>
      </ul>
    </section>
  </main>

  <aside>
    <h3>Artikel Lainnya</h3>
    <ul>
      <li><a href="#">Belajar CSS Dasar</a></li>
      <li><a href="#">Belajar JavaScript</a></li>
    </ul>
  </aside>

  <footer>
    <p>&copy; 2025 Website Belajar HTML</p>
  </footer>
</body>
</html>
```

---

## 4. 💡 Latihan Eksplorasi
1. Buat sebuah halaman **profil pribadi** dengan struktur semantic HTML (header, main, section, aside, footer).  
2. Buat halaman **artikel/blog** dengan minimal satu `<article>` dan satu `<aside>`.  
3. Bangun mini website dengan navigasi `<nav>` yang menghubungkan minimal 3 halaman berbeda.  


---

## 📚 Referensi
- [W3Schools Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)  
- [MDN Web Docs - Semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html)
