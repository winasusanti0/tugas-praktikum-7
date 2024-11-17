# WINA SUSANTI R - NIM : 352310473 (TUGAS PRAKTIKUM 7)
# Penjelasan Program Daftar Nilai Mahasiswa Menggunakan Dictionary
Perintah program menggunakan phyton dengan tampilan perintah sebagai berikut : 

![perintah program 1](https://github.com/user-attachments/assets/ebdee0c6-0153-465a-b353-9e2058eea30f)
![perintah program 2](https://github.com/user-attachments/assets/cf9eb4da-dc16-42e6-808b-7aab1b2085ce)
![perintah program 3](https://github.com/user-attachments/assets/2d2ada26-5ba8-41be-8359-bb68eecafb2c)
![perintah program 4](https://github.com/user-attachments/assets/45d988df-aaba-4e5c-9c4b-8305e9763fec)

## Fungsi Utama

### `Hitung_nilai_akhir(nilai_tugas, nilai_uts, nilai_uas)`
- **Deskripsi**: Menghitung nilai akhir mahasiswa berdasarkan komponen nilai.
- **Parameter**:
  - `nilai_tugas`: Nilai tugas mahasiswa.
  - `nilai_uts`: Nilai UTS mahasiswa.
  - `nilai_uas`: Nilai UAS mahasiswa.
- **Rumus**:
  
 ![rumus tugas akhir](https://github.com/user-attachments/assets/21ff5d05-c762-4684-abff-8379a6247b5a)

 
- **Return**: Mengembalikan nilai akhir yang telah dihitung.

## Struktur Data

### Dictionary `data_mahasiswa`
- **Kunci**: NIM mahasiswa.
- **Nilai**: Dictionary yang berisi:
  - `nama`: Nama mahasiswa.
  - `nilai_tugas`: Nilai tugas.
  - `nilai_uts`: Nilai UTS.
  - `nilai_uas`: Nilai UAS.
  - `nilai_akhir`: Nilai akhir yang dihitung.

## Menu Interaksi

Pengguna diberikan pilihan untuk melakukan operasi berikut:

1. **L. Lihat Data**
   - Menampilkan seluruh data mahasiswa dalam format tabel.

2. **T. Tambah Data**
   - Meminta input dari pengguna untuk menambahkan data mahasiswa baru, termasuk nama, NIM, nilai tugas, nilai UTS, dan nilai UAS. Data yang dimasukkan akan dihitung nilai akhirnya dan disimpan.

3. **U. Ubah Data**
   - Meminta NIM mahasiswa yang ingin diubah. Jika data ditemukan, pengguna dapat memperbarui nilai tugas, UTS, dan UAS. Nilai akhir akan diperbarui sesuai dengan perubahan.

4. **H. Hapus Data**
   - Meminta NIM mahasiswa yang ingin dihapus. Jika data ditemukan, maka data mahasiswa tersebut akan dihapus dari daftar.

5. **C. Cari Data**
   - Meminta NIM mahasiswa yang ingin dicari. Jika data ditemukan, program akan menampilkan informasi mahasiswa tersebut.

6. **K. Keluar**
   - Mengakhiri program.

## Contoh Tampilan Interaksi

![TAMPILAN PROGRAM](https://github.com/user-attachments/assets/82fa0f9c-1de7-4892-82a1-2e832e83f8fd)


Berikut adalah contoh interaksi pengguna dengan program:
1. Start: Titik awal program.
2. Inisialisasi Dictionary data_mahasiswa: Membuat dictionary kosong untuk menyimpan data mahasiswa.
3. Tampilkan Menu: Menampilkan pilihan menu kepada pengguna (Lihat, Tambah, Ubah, Hapus, Cari, Keluar).
4. Input Pilihan Menu: Pengguna memasukkan pilihan menu.
5. Pilihan Menu:
Jika pengguna memilih T (Tambah):
Input data mahasiswa (Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS).
Hitung nilai akhir menggunakan fungsi hitung_nilai_akhir.
Simpan data ke dalam dictionary.
Tampilkan pesan bahwa data berhasil ditambahkan.
Jika pengguna memilih U (Ubah):
Input NIM mahasiswa yang ingin diubah.
Jika NIM ditemukan, input nilai baru (Tugas, UTS, UAS).
Hitung nilai akhir baru dan perbarui data.
Tampilkan pesan bahwa data berhasil diubah.
Jika pengguna memilih H (Hapus):
Input NIM mahasiswa yang ingin dihapus.
Jika NIM ditemukan, hapus data dari dictionary.
Tampilkan pesan bahwa data berhasil dihapus.
Jika pengguna memilih L (Lihat):
Tampilkan semua data mahasiswa dalam format tabel.
Jika pengguna memilih C (Cari):
Input NIM mahasiswa yang ingin dicari.
Jika NIM ditemukan, tampilkan informasi mahasiswa.
Jika pengguna memilih K (Keluar):
6. Tampilkan pesan bahwa program selesai dan keluar dari loop.
7. End: Titik akhir program.

## FLOWCHART PERINTAH 

![flow chart](https://github.com/user-attachments/assets/3fd8bc07-4af3-47ad-afb9-cd0cf761637e)
