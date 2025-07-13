----------------------------------------------------------PRAKTIKUM 6-------------------------------------------------------------------
Pada Praktikum 6, Anda mempelajari cara mengimplementasikan fitur upload gambar pada artikel menggunakan Framework CodeIgniter 4.
Membuat validasi data pada controller artikel untuk memastikan data yang diinputkan valid.
Menggunakan metode getFile() untuk menangani file gambar yang diupload, dan memindahkan file tersebut ke folder publik.
Menyimpan data artikel (judul, isi, slug, dan nama gambar) ke dalam database.
Menambahkan input file pada form di tampilan untuk memungkinkan pengguna meng-upload gambar saat menambah artikel.
![image](https://github.com/user-attachments/assets/bc8a59a3-506c-41f0-a61a-df01f4085104)
![image](https://github.com/user-attachments/assets/cc19dd32-6de9-4ec0-bd52-caeb0140f37f)

----------------------------------------------------------PRAKTIKUM 7-------------------------------------------------------------------
Membuat Tabel Kategori: Tabel baru kategori dibuat untuk menyimpan data kategori artikel.

Mengubah Tabel Artikel: Menambahkan kolom id_kategori pada tabel artikel untuk membentuk relasi dengan tabel kategori.

Membuat Model Kategori: Model KategoriModel dibuat untuk berinteraksi dengan tabel kategori.

Memodifikasi Model Artikel: Model ArtikelModel dimodifikasi dengan menambahkan metode getArtikelDenganKategori() untuk mengambil data artikel beserta nama kategorinya menggunakan join.

Modifikasi Controller Artikel: Controller Artikel.php diubah untuk menggunakan model baru dan menampilkan artikel yang telah bergabung dengan kategori.

Memodifikasi View: View diubah agar data kategori ditampilkan bersama artikel, baik di halaman depan maupun di halaman admin.
<img width="1365" height="729" alt="image" src="https://github.com/user-attachments/assets/929b54ee-546b-4421-8b12-9e4b8ad028cb" />
<img width="1365" height="728" alt="image" src="https://github.com/user-attachments/assets/380377f0-e4ca-4269-8aa4-60059c0b3c64" />
<img width="1365" height="727" alt="image" src="https://github.com/user-attachments/assets/1d2453b9-6287-447b-ac08-25fa3d6f5734" />




