# Online-Shopping-System

**📌 ALUR PROGRAM**
Berikut ini adalah alur kerja dari sistem Online Shopping System:

1. Inisialisasi Objek Produk
    Program dimulai dari kelas MainApp.
    Di dalamnya, dua objek dibuat:
      Satu objek dari kelas Electronics
      Satu objek dari kelas Clothing

2. Penggunaan Constructor dan Encapsulation
    Setiap objek dibuat dengan memanggil konstruktor yang mengisi atribut seperti name, price, dan productId.
    Semua atribut bersifat private (enkapsulasi) dan diakses melalui method get dan set.

3. Pewarisan (Inheritance)
    Kelas Electronics dan Clothing merupakan subclass dari Product.
    Mereka mewarisi atribut umum dari Product dan menambahkan atribut spesifik:
      _Electronics_: memiliki atribut tambahan warrantyMonths.
      _Clothing_: memiliki atribut tambahan size.

4. Overriding Method (getInfo())
    Method getInfo() yang ada di kelas Product dioverride di masing-masing subclass untuk menambahkan informasi khusus:
      Electronics menampilkan informasi garansi.
      Clothing menampilkan informasi ukuran.

5. Output ke Konsol
    Setelah objek dibuat, method _getInfo()_ dipanggil dari masing-masing objek.
    Hasilnya ditampilkan ke layar.

6. Struktur Berkas
    Proyek terdiri dari 4 berkas utama:
      _Product.java_ → Kelas induk produk
      _Electronics.java_ → Subclass untuk produk elektronik
      _Clothing.java_ → Subclass untuk pakaian
      _MainApp.java_ → Kelas utama untuk menjalankan program
