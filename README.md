# Dibuat oleh Salsabila Chairunnisa  
# Penggunaan Fungsi Def/Sub Rutin

Program ini dirancang untuk mengelola data mahasiswa dengan beberapa fungsi utama: menambah, menampilkan, menghapus, dan mengubah data mahasiswa. Data mahasiswa disimpan dalam bentuk daftar (list) yang berisi dictionary, di mana setiap dictionary menyimpan nama dan nilai mahasiswa.

## 1. Struktur Program

Program ini memiliki beberapa fungsi utama untuk mengelola data mahasiswa:

- **Menambah data**
- **Menampilkan data**
- **Menghapus data**
- **Mengubah data**

## 2. Fungsi-Fungsi dalam Program

### Fungsi `tambah(nama, nilai)`

- **Deskripsi**: Menambahkan data mahasiswa ke dalam daftar.
- **Parameter**:
  - `nama`: Nama mahasiswa.
  - `nilai`: Nilai yang diperoleh mahasiswa.
- **Proses**: 
  - Fungsi ini akan menambahkan dictionary baru ke dalam daftar `mahasiswa` dan mencetak pesan konfirmasi.

### Fungsi `tampilkan()`

- **Deskripsi**: Menampilkan semua data mahasiswa dalam daftar.
- **Proses**:
  - Mengecek apakah daftar kosong. Jika kosong, akan mencetak pesan "Daftar mahasiswa kosong".
  - Jika tidak kosong, mencetak semua nama dan nilai mahasiswa yang ada dalam daftar.

### Fungsi `hapus(nama)`

- **Deskripsi**: Menghapus data mahasiswa berdasarkan nama.
- **Parameter**:
  - `nama`: Nama mahasiswa yang ingin dihapus.
- **Proses**:
  - Menggunakan list comprehension untuk membuat daftar baru yang tidak termasuk mahasiswa dengan nama yang diberikan.
  - Mencetak pesan konfirmasi setelah penghapusan.

### Fungsi `ubah(nama, nilai_baru)`

- **Deskripsi**: Mengubah nilai mahasiswa berdasarkan nama.
- **Parameter**:
  - `nama`: Nama mahasiswa yang nilainya ingin diubah.
  - `nilai_baru`: Nilai baru yang akan diberikan.
- **Proses**:
  - Mencari mahasiswa dalam daftar. Jika ditemukan, nilai mahasiswa akan diubah dan mencetak pesan konfirmasi.
  - Jika nama tidak ditemukan, mencetak pesan bahwa data tidak ditemukan.

## 3. Contoh Penggunaan

Di bagian akhir program, terdapat contoh penggunaan fungsi-fungsi yang telah didefinisikan:

1. Menambahkan beberapa mahasiswa: Mulyono, Sarjono, Ajiwoto, Prabowo, dan Gibran dengan nilai masing-masing.
2. Menampilkan daftar mahasiswa setelah penambahan.
3. Mengubah nilai Mulyono dari 80 menjadi 95.
4. Menghapus data Sarjono dari daftar.
5. Menampilkan daftar mahasiswa terakhir setelah perubahan dan penghapusan.

## berikut ini tampilan perintah program dalam phyton :

![perintah program 1](https://github.com/user-attachments/assets/e30a3608-f8c4-4f0d-8365-f805129ae91f)
![perintah program 2](https://github.com/user-attachments/assets/226c4a3d-11e1-4cbc-8715-a37f26b89c5b)

## Output (RUN) dari perintah program tersebut tampilannya sebagai berikut :

![run](https://github.com/user-attachments/assets/bc58c1d8-e101-4f75-88b6-ed07d981e988)

