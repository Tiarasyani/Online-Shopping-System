# Online-Shopping-System


## 📌 Alur Program


Berikut ini adalah alur kerja dari sistem **Online Shopping System**:

### 1. Inisialisasi Objek Produk
Program dimulai dari kelas `MainApp`.  
Di dalamnya, dua objek dibuat:
- Satu objek dari kelas `Electronics`
- Satu objek dari kelas `Clothing`

### 2. Penggunaan Constructor dan Encapsulation
- Setiap objek dibuat dengan memanggil konstruktor yang mengisi atribut seperti `name`, `price`, dan `productId`.
- Semua atribut bersifat `private` (enkapsulasi) dan hanya dapat diakses melalui method `get` dan `set`.

### 3. Pewarisan (Inheritance)
Kelas `Electronics` dan `Clothing` merupakan subclass dari `Product`.  
Mereka mewarisi atribut umum dari `Product` dan menambahkan atribut spesifik:
- 🖥️ **Electronics** → memiliki atribut tambahan `warrantyMonths`
- 👕 **Clothing** → memiliki atribut tambahan `size`

### 4. Overriding Method (`getInfo()`)
Method `getInfo()` yang ada di kelas `Product` dioverride di masing-masing subclass untuk menambahkan informasi khusus:
- `Electronics` menampilkan informasi garansi.
- `Clothing` menampilkan informasi ukuran.

### 5. Output ke Konsol
Setelah objek dibuat, method `getInfo()` dipanggil dari masing-masing objek.  
Hasilnya ditampilkan ke layar, misalnya:

### 6. Struktur Berkas
Proyek terdiri dari 4 berkas utama:
- `Product.java` → Kelas induk produk
- `Electronics.java` → Subclass untuk produk elektronik
- `Clothing.java` → Subclass untuk pakaian
- `MainApp.java` → Kelas utama untuk menjalankan program dan menampilkan informasi produk
