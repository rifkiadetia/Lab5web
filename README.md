# Lab5Web — Praktikum 5 JavaScript Dasar

## 1. Deskripsi
Praktikum 5 membahas dasar-dasar JavaScript dan manipulasi HTML dalam mata kuliah Pemrograman Web. Praktikum ini bertujuan untuk memahami penggunaan JavaScript dalam membuat halaman web yang interaktif, mengolah data, memvalidasi input, dan memanipulasi elemen HTML.

## 2. Tujuan Praktikum
1. Memahami sintaks dasar JavaScript dan cara menghubungkannya dengan HTML.
2. Menggunakan variabel, tipe data, operator, percabangan, perulangan, dan function.
3. Menampilkan output menggunakan Console, alert, prompt, dan elemen HTML.
4. Memanipulasi konten dan gaya elemen HTML menggunakan DOM.
5. Membuat form interaktif dan melakukan validasi input.
6. Mendokumentasikan hasil praktikum beserta screenshot.

## 3. Alat dan Bahan
- Laptop atau komputer.
- Browser seperti Google Chrome, Mozilla Firefox, atau Microsoft Edge.
- Visual Studio Code atau editor kode lainnya.
- HTML dan JavaScript.

## 4. Langkah Kerja
1. Membuat folder kerja bernama `lab5_javascript`.
2. Membuat file `index.html` dan `script.js`.
3. Menghubungkan file JavaScript dengan HTML.
4. Mengerjakan delapan latihan sesuai urutan pada modul.
5. Membuat mini project kalkulator nilai mahasiswa.
6. Menjalankan program melalui browser.
7. Memeriksa output pada halaman web dan Console.
8. Menguji program menggunakan berbagai input.
9. Mengambil screenshot hasil setiap latihan.
10. Menyimpan seluruh pekerjaan ke repository GitHub bernama `Lab5Web`.

## 5. Cara Menjalankan Program
1. Buka folder proyek menggunakan Visual Studio Code.
2. Pastikan file `index.html` dan `script.js` tersedia.
3. Pastikan file JavaScript sudah terhubung pada HTML menggunakan tag berikut:

   ```html
   <script src="script.js"></script>
   ```

4. Buka file `index.html` menggunakan browser.
5. Ikuti instruksi pada halaman, seperti memasukkan nama, nilai, atau bilangan.
6. Untuk melihat output Console, buka Developer Tools dengan klik kanan pada halaman, pilih Inspect, kemudian pilih tab Console.
7. Uji setiap fitur untuk memastikan program berjalan sesuai tujuan.

## 6. Hasil Praktikum

### Latihan 1 — Menampilkan Output
**Tujuan:** Menampilkan teks pada halaman HTML dan Console.

**Langkah kerja:** Mengubah teks elemen HTML menggunakan `textContent` dan menampilkan pesan menggunakan `console.log()`.

**Hasil:** Teks "Hello World" ditampilkan pada halaman web dan Console.

### Latihan 2 — Alert dan Prompt
**Tujuan:** Menerima input nama pengguna dan menampilkan pesan.

**Langkah kerja:** Menggunakan `prompt()` untuk meminta nama, `alert()` untuk menampilkan sapaan, dan DOM untuk mengubah teks halaman.

**Hasil:** Program menampilkan sapaan sesuai nama yang dimasukkan. Jika nama kosong atau pengguna membatalkan input, program menampilkan pesan bahwa nama belum diisi.

### Latihan 3 — Function dan Operasi Aritmetika
**Tujuan:** Memahami penggunaan function untuk operasi matematika.

**Langkah kerja:** Membuat function yang menjalankan operasi penjumlahan, pengurangan, perkalian, pembagian, dan modulus.

**Hasil:** Hasil operasi aritmetika ditampilkan pada Console.

### Latihan 4 — Percabangan if–else
**Tujuan:** Menentukan status kelulusan berdasarkan nilai mahasiswa.

**Langkah kerja:** Meminta nilai melalui `prompt()`, mengonversi input menjadi angka, memvalidasi nilai, dan menentukan status kelulusan.

**Hasil:** Nilai minimal 60 menghasilkan status "Lulus", sedangkan nilai di bawah 60 menghasilkan status "Belum lulus". Input yang tidak valid ditolak.

### Latihan 5 — Percabangan switch
**Tujuan:** Memahami seleksi kondisi menggunakan `switch`.

**Langkah kerja:** Meminta pengguna memasukkan angka 1–5 dan menentukan nama bilangan berdasarkan pilihan.

**Hasil:** Program menampilkan nama bilangan yang sesuai. Pilihan di luar rentang menampilkan pesan "Pilihan tidak tersedia".

### Latihan 6 — Form Bilangan Genap atau Ganjil
**Tujuan:** Memvalidasi input dan menentukan jenis bilangan.

**Langkah kerja:** Membuat form input bilangan, tombol pemeriksaan, dan function untuk memeriksa apakah input merupakan bilangan bulat serta menentukan genap atau ganjil.

**Hasil:** Program menampilkan "Bilangan genap" atau "Bilangan ganjil". Input kosong atau desimal menghasilkan pesan validasi.

### Latihan 7 — Mengubah Warna Halaman
**Tujuan:** Memanipulasi gaya halaman menggunakan JavaScript.

**Langkah kerja:** Membuat function dengan parameter warna dan tombol untuk mengubah warna latar halaman.

**Hasil:** Warna latar halaman berubah sesuai tombol yang dipilih.

### Latihan 8 — DOM dan Checkbox Menu Makanan
**Tujuan:** Menghitung total harga berdasarkan menu yang dipilih.

**Langkah kerja:** Membuat checkbox menu makanan dan menggunakan event listener untuk menghitung total harga setiap kali pilihan berubah.

**Hasil:** Total harga diperbarui secara otomatis sesuai menu yang dicentang. Jika tidak ada menu yang dipilih, total harga adalah Rp0.

## 7. Mini Project — Kalkulator Nilai Mahasiswa

**Tujuan:** Menghitung nilai akhir, menentukan predikat, dan menampilkan status kelulusan mahasiswa.

**Langkah kerja:**
1. Membuat input nilai tugas, UTS, dan UAS.
2. Memvalidasi setiap nilai agar berada pada rentang 0–100.
3. Menghitung nilai akhir berdasarkan bobot yang ditentukan.
4. Menentukan predikat berdasarkan nilai akhir.
5. Menampilkan nilai akhir, predikat, dan status kelulusan pada halaman HTML.
6. Menguji program dengan minimal tiga skenario nilai.

**Rumus nilai akhir:**

Nilai Akhir = (Tugas × 30%) + (UTS × 30%) + (UAS × 40%)

**Aturan predikat:**
- Nilai ≥ 85: A
- Nilai ≥ 75: B
- Nilai ≥ 60: C
- Nilai ≥ 50: D
- Nilai < 50: E

**Hasil:** Program menghitung nilai akhir mahasiswa, menentukan predikat, dan menampilkan status "Lulus" jika nilai akhir minimal 60 atau "Belum lulus" jika kurang dari 60.

Contoh dari modul: nilai tugas 85, UTS 78, dan UAS 88 menghasilkan nilai akhir 83,50, predikat B, dan status Lulus.

## 8. Kesimpulan
Melalui praktikum ini, mahasiswa mempelajari dasar-dasar JavaScript, mulai dari penggunaan variabel, operator, function, percabangan, dan manipulasi DOM hingga validasi form. Praktikum juga memberikan pemahaman tentang cara membuat halaman web yang interaktif, menghitung data, serta menampilkan hasil berdasarkan input pengguna.
