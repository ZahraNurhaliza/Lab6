# Lab6

## Latihan
• Ubahlah kode dibawah ini menjadi fungsi menggunakan lambda.
import math

def a(x):
return x**2

def b(x, y):
return math.sqrt(x**2 + y**2)

def c(*args):
return sum(args)/len(args)

def d(s):
return "".join(set(s))

### Program
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Latihan1(Program).png)

### RUN
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Latihan1(RUN).png)

## Praktikum
Buat program sederhana dengan mengaplikasikan penggunaan fungsi
yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:
• Fungsi tambah() untuk menambah data
• Fungsi tapilkan() untuk menampilkan data
• Fungsi hapus(nama) untuk menghapus data berdasarkan nama
• Fungsi ubah(nama) untuk mengubah data berdasarkan nama
• Buat flowchart dan penjelasan programnya pada README.md. 

### Program
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.1(Program).png)
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.2(Program).png)
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.3(Program).png)
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.4(Program).png)

### RUN
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.1(RUN).png)
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.2(RUN).png)
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.3(RUN).png)
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.4(RUN).png)
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.5(RUN).png)
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.6(RUN).png)
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/Lab6.7(RUN).png)


### Penjelasan
1. Definisikan dictionary terlebih dahulu data = {}.
2. Membuat fungsi
   • Fungsi tampilkan(), untuk menambahkan data def tampilkan()
   • Fungsi tambah(), untuk menampilkan data def tambah()
   • Fungsi hapus(nama), untuk menghapus nama pada data def hapus(nama)
   • Fungsi ubah(nama), untuk mengubah nama pada data def ubah(nama)
3. Menggunakan Perulangan while True: dapat diartikan perulangan akan terus mengulang jika inputan benar dan masuk kedalam proses jika tidak maka perulangan berhenti atau lanjut ke proses selanjutnya. Gunakan statement if untuk memproses perintah yang di inginkan sesuai inputan.
4. Untuk menambahkan data pilih "[1] Tambah" gunakan fungsi if gunakan perintah "1", lalu masukan nama, nim, tugas, uts, uas, nilaiakhir, nilai akhir didapat dari = ((tugas)*30/100 + (uts)*35/100 + (uas)*35/100.
5. Lalu jika ingin memilih "[2] Lihat" gunakan fungsi 'elif' dan gunakan fungsi 'for x in data.items():' untuk melihat data pada tabel data yang kita inputkan, dengan perintah "2". Jika data tidak terdaftar maka akan tampil "TIDAK ADA DATA" atau = 0.
6. Lalu untuk menampilan pilihan "[3] Ubah" gunakan fungsi 'elif' kemudian gunakan fungsi 'if nama in data.keys():' kemudian input nama, nim, nilai tugas, nilai uts, nilai uas untuk mengubah data nama kemudian gunakan fungsi 'else' untuk menampilkan data nama yang kita ingin ubah tidak ada.
7. Untuk menghapus data pilih "[4] Hapus" gunakan fungsi 'elif' kemudian gunakan fungsi 'if nama in data.keys():' kemudian fungsi 'del.data[nama] jika nama yang kita hapus tidak ada dalam tabel maka gunakan fungsi 'else' untuk menampilkan "TIDAK ADA DATA".
8. Untuk keluar maka gunakan fungsi else dan exit() atau gunakan perintah [5] Keluar.
9. Selesai.

### Flowchart
![image](https://github.com/ZahraNurhaliza/Lab6/blob/main/screenshot/fw.png)


## Commit dan push repository ke github.
