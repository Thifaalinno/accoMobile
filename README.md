Nama   : Thifaalinno Fawwaz Abdi
NPM    : 2206082253
Kelas  : PBP - B

Tugas 7

1. Apa perbedaan utama antara stateless dan stateful widget dalam konteks pengembangan aplikasi Flutter?
StatelessWidget digunakan untuk widget yang tidak perlu berubah atau memiliki state internal, sedangkan StatefulWidget digunakan untuk widget yang memerlukan pembaruan tampilan berdasarkan perubahan state.

2. Sebutkan seluruh widget yang kamu gunakan untuk menyelesaikan tugas ini dan jelaskan fungsinya masing-masing.

1.MyHomePage (StatelessWidget): Ini adalah widget utama yang mewakili halaman beranda aplikasi.
2.Scaffold: Ini adalah widget yang digunakan untuk membuat tata letak dasar aplikasi, termasuk AppBar dan konten tubuh (body).
3.AppBar: Ini adalah widget yang mewakili bilah atas (app bar) aplikasi dengan judul "Backpacknya Bayu".
4.SingleChildScrollView: Ini adalah widget yang mengelilingi konten tubuh untuk mengaktifkan guliran jika kontennya lebih besar dari layar.
5.Padding: Ini adalah widget yang digunakan untuk memberikan padding ke dalam kontennya.
6.Column: Ini adalah widget yang digunakan untuk mengatur anak-anaknya secara vertikal.
7.Text: Ini adalah widget yang digunakan untuk menampilkan teks "Backpacknya Bayu" dengan gaya teks tertentu.
8.GridView.count: Ini adalah widget yang digunakan untuk membuat tampilan grid dengan jumlah kolom yang diberikan (3 kolom dalam hal ini).
9.ShopCard (StatelessWidget): Ini adalah widget yang digunakan untuk mewakili setiap item toko (kartu) dalam grid. Ini mengambil properti dari objek ShopItem dan menggambarkannya.
10.Material: Ini adalah widget yang digunakan untuk memberikan latar belakang warna untuk setiap ShopCard.
11.InkWell: Ini adalah widget yang digunakan untuk membuat area yang responsif terhadap sentuhan dan menampilkan SnackBar ketika card diklik.
12.Icon: Ini adalah widget yang digunakan untuk menampilkan ikon dengan warna putih.
13.Text: Ini adalah widget yang digunakan untuk menampilkan nama item dalam card dengan teks putih.

3. Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step (bukan hanya sekadar mengikuti tutorial)

1.Membuat aplikasi
2.Membuat file baru menu.dart
3.Mengubah file main.dart
4.Mengubah file menu.dart

Tugas 8

1. Jelaskan perbedaan antara Navigator.push() dan Navigator.pushReplacement(), disertai dengan contoh mengenai penggunaan kedua metode tersebut yang tepat!
1.Navigator.push:
-Metode ini digunakan untuk menambahkan layar baru ke tumpukan (stack) navigasi.
-Ketika menggunakan Navigator.push(), layar baru ditambahkan di atas layar yang ada di tumpukan, dan pengguna dapat kembali ke layar sebelumnya dengan menekan tombol kembali.
-Cocok digunakan ketika ingin menambahkan layar baru dan memungkinkan pengguna untuk kembali ke layar sebelumnya.
2.Navigator.pushReplacement():
-Metode ini digunakan untuk menambahkan layar baru ke tumpukan dan menggantikan layar yang ada di tumpukan dengan layar baru.
-Ketika menggunakan Navigator.pushReplacement(), layar yang ada di bawah layar baru dihapus dari tumpukan, sehingga ketika pengguna menekan tombol kembali, mereka langsung kembali ke layar sebelumnya sebelum layar yang baru ditambahkan.
-Cocok digunakan ketika ingin menggantikan layar saat ini dengan layar baru dan tidak ingin pengguna kembali ke layar sebelumnya.

2. Jelaskan masing-masing layout widget pada Flutter dan konteks penggunaannya masing-masing!
-Container : Digunakan untuk mengelompokkan widget lain dan mengatur terhadap layout attribute seperti margin dan padding.
-Column : Digunakan untuk menampilkan widget dalam susunan vertikal.
-Row : Digunakan untuk menampilkan widget dalam susunan horizontal.
-ListView : Digunakan untuk menampilkan daftar elemen scrollable.
-Stack : Digunakan untuk "menumpuk" widget satu di atas yang lain.

3. Sebutkan apa saja elemen input pada form yang kamu pakai pada tugas kali ini dan jelaskan mengapa kamu menggunakan elemen input tersebut!
Pada tugas kali ini saya hanya menggunakan TextFormField() karena pada tugas kali ini hanya membutuhkan input berupa String dan integer.

4. Bagaimana penerapan clean architecture pada aplikasi Flutter?
Penerapannya dibagi menjadi 3 lapisan utama:

1.Domain Layer:
-Berisi aturan bisnis atau logika inti aplikasi.
-Tidak bergantung pada detail implementasi atau teknologi tertentu.
-Termasuk use case, entitas, dan repositori yang menentukan kontrak untuk mengakses data.
2.Data Layer:
-Menangani pengambilan dan penyimpanan data.
-Implementasi dari repositori dan sumber data (API, database, dll.)
-Merupakan jembatan antara Domain Layer dan Presentation Layer.
3.Presentation Layer:
-Menangani tampilan dan antarmuka pengguna.
-Bergantung pada Domain Layer, tetapi tidak mengetahui detail implementasi Data Layer.
-State management, UI, dan navigasi berada di dalamnya.

5. Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step! (bukan hanya sekadar mengikuti tutorial)

1.membuat file BackPackForm.dart didalam folder lib/screens 
2.Menambahkan routing pada item_cards.dart dan left_drawer.dart

