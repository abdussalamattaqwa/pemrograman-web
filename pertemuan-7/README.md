# 📘 Pertemuan 7: Penggunaan Elemen Aplikasi JavaScript

## 🎯 Tujuan Pembelajaran
Mahasiswa mampu memahami, menjelaskan, dan mengimplementasikan konsep dasar aplikasi JavaScript, meliputi:
1. Pengenalan JavaScript  
2. Menambahkan Script ke Halaman Web (Add a Script to Pages)  
3. Menulis JavaScript (Writing JavaScript)  

---

## 📝 Materi

### 1. Pengenalan JavaScript
- **JavaScript** adalah bahasa pemrograman yang berjalan di browser untuk membuat halaman web menjadi **interaktif**.  
- Berbeda dengan **HTML** (struktur) dan **CSS** (tampilan), JavaScript berfungsi untuk **logika dan interaksi pengguna**.  
- Contoh penggunaan JavaScript:
  - Validasi form.
  - Menampilkan pesan pop-up.
  - Mengubah isi elemen HTML secara dinamis.
  - Animasi sederhana.

---

### 2. Menambahkan Script ke Halaman Web
JavaScript bisa ditulis dengan 2 cara:

#### a. Internal JavaScript
Ditulis langsung dalam file HTML menggunakan tag `<script>`.
```html
<!DOCTYPE html>
<html>
<head>
  <title>Contoh Internal JavaScript</title>
</head>
<body>
  <h1>Hello JavaScript</h1>
  <script>
    alert("Halo, ini pesan dari JavaScript!");
  </script>
</body>
</html>
```

#### b. External JavaScript
Ditulis dalam file terpisah dengan ekstensi `.js`, lalu dipanggil menggunakan atribut `src`.
```html
<!DOCTYPE html>
<html>
<head>
  <title>Contoh External JavaScript</title>
  <script src="script.js"></script>
</head>
<body>
  <h1>Belajar JavaScript Eksternal</h1>
</body>
</html>
```

Isi file `script.js`:
```javascript
alert("Halo dari file eksternal!");
```

---

### 3. Menulis JavaScript (Writing JavaScript)

Beberapa contoh dasar:

#### a. Menulis ke Halaman
```html
<script>
  document.write("<p>Belajar JavaScript Menyenangkan!</p>");
</script>
```

#### b. Mengubah Isi Elemen HTML
```html
<p id="demo">Teks awal</p>
<button onclick="document.getElementById('demo').innerHTML = 'Teks sudah berubah!'">
  Klik Saya
</button>
```

#### c. Interaksi dengan Pengguna
```html
<script>
  let nama = prompt("Siapa nama Anda?");
  alert("Selamat datang, " + nama + "!");
</script>
```

#### d. Event Handling
```html
<button onclick="alert('Tombol diklik!')">Klik Saya</button>
```

---

## 🧩 Latihan

### Latihan Dasar
1. Buat halaman HTML yang menampilkan **alert** sederhana saat dibuka.  
2. Buat file JavaScript eksternal, lalu tampilkan pesan selamat datang ke dalam halaman dengan `document.write()`.  
3. Buat tombol yang jika diklik, akan mengubah teks dari sebuah paragraf.

### Latihan Menengah
4. Buat form dengan input nama. Jika tombol submit diklik, munculkan alert berisi "Halo, [nama]".  
5. Buat 2 tombol: satu untuk mengubah warna background menjadi biru, satu lagi untuk mengubahnya ke kuning.

### Latihan Eksplorasi
6. Buat halaman yang meminta pengguna memasukkan angka, lalu tampilkan hasil perkalian angka tersebut dengan 2.  
7. Buat halaman dengan sebuah gambar yang berubah ketika diklik.  

---

## ✅ Tugas Akhir Pertemuan
Buat sebuah halaman web dengan ketentuan:
- Menggunakan **JavaScript internal dan eksternal**.  
- Memiliki minimal 2 interaksi (contoh: klik tombol untuk ubah teks, prompt input, atau ganti warna background).  
- Kreatifitas tema bebas (profil, game kecil, kuis sederhana, dsb).  
