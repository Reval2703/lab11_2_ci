| Nama                    | NIM        | Kelas   | Matkul            |
|-------------------------|------------|---------|-------------------|
| Muhammad Reval Prasetya | 312310437  | TI.23.A4| Pemrograman Web 2 |

Praktikum 1-6

1. Membuat Tabel Kategori
Kita akan membuat tabel baru bernama `kategori` untuk mengkategorikan artikel.
Struktur Tabel `kategori`:

Jalankan query berikut:
![Screenshot 2025-06-17 101611](https://github.com/user-attachments/assets/48a387d5-78ec-4e41-ba23-c73eced93484)

2. Mengubah Tabel Artikel
Tambahkan foreign key `id_kategori` pada tabel `artikel` untuk membuat relasi dengan tabel 
`kategori`. 
Query untuk menambahkan foreign key:

![image](https://github.com/user-attachments/assets/07770285-6aa2-4d06-82c7-d3f9731abad7)

3. Membuat Model Kategori
Buat file model baru di `app/Models` dengan nama `KategoriModel.php`:

![image](https://github.com/user-attachments/assets/935c14d4-f941-4fa2-9458-5bdf16f55df0)

4. Memodifikasi Model Artikel
Modifikasi `ArtikelModel.php` untuk mendefinisikan relasi dengan `KategoriModel`:

![image](https://github.com/user-attachments/assets/ce339452-0656-4daf-a88c-8f4acd645344)

Menambahkan method `getArtikelDenganKategori()` untuk mengambil data artikel beserta 
nama kategorinya menggunakan join

5. Memodifikasi Controller Artikel
Modifikasi `Artikel.php` untuk menggunakan model baru dan menampilkan data relasi:

![image](https://github.com/user-attachments/assets/1f0c0376-460f-4641-8f99-5d7a9a69b769)

![image](https://github.com/user-attachments/assets/1ccca0a1-56be-46ba-894e-5f81db6628df)

![image](https://github.com/user-attachments/assets/4aaa30dd-035d-482d-9242-a6da1d344378)

![image](https://github.com/user-attachments/assets/a8ab05c9-975a-4e71-a707-0c777a0c7052)

![image](https://github.com/user-attachments/assets/ec7b5a4b-d17e-4da1-8cd4-1e17aa1bbb7b)

![image](https://github.com/user-attachments/assets/02cff5c1-8d92-440f-bbde-c5cf9356b543)

![image](https://github.com/user-attachments/assets/66040985-7704-465c-be37-45c0ec89ed7a)

6. Memodifikasi View
Buka folder view/artikel sesuaikan masing-masing view.
**index.php**

![image](https://github.com/user-attachments/assets/fff913f3-aa5d-4d7b-9890-2f46abb4e30a)

**admin_index.php**

![image](https://github.com/user-attachments/assets/6c98713c-fb44-4f70-be84-b70195c41fb6)

![image](https://github.com/user-attachments/assets/83cad4ec-7c8c-4465-b16c-e80783edfb7b)

![image](https://github.com/user-attachments/assets/9f909071-72e0-4070-be52-025f1fd75166)

![image](https://github.com/user-attachments/assets/d5ad6833-466f-4b36-a528-ab02056c54de)

![image](https://github.com/user-attachments/assets/77f11021-378e-46bd-b490-4fe9a482c0f5)

**form_add.php**

![image](https://github.com/user-attachments/assets/007e1d63-f75b-4720-991e-245eab7d6645)

![image](https://github.com/user-attachments/assets/4c3c2a5f-16ce-4068-b506-f2dc7321fb48)

![image](https://github.com/user-attachments/assets/f08f0878-867d-4bb1-b7e3-9e4d5d7ec436)

