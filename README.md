flowchat
![image](https://user-images.githubusercontent.com/115876367/202967152-db585107-0312-44fc-9e10-a575bd95c7f9.png)
Tamilan program
![Screenshot (16)](https://user-images.githubusercontent.com/115876367/202967527-23ad4fc9-4d99-4693-ac63-cc71e40b6dbc.png)
from prettytable import PrettyTable Membuat header table menggunakan prettytable. Variabel import berfungsi untuk memanggil file lain di dalam satu module yang berbeda.

print("Program Input Data Mahasiswa") print() untuk menampilkan kalimat yang di input.

tabelNama = PrettyTable(["No" ,"Nama" ,"NIM" ,"Nilai Tugas" ,"Nilai UTS" ,"Nilai UAS" ,"Nilai Akhir" ])
a = 0
(Deklarasi list)untuk menginput data yang dimasukkan kedalam list. input tabelNama untuk memanggil. sedangkan PrettyTable berfungsi untuk membungkus semua list. Deklarasi *a = 0* untuk membuat nomor pada isi table.

Membuat program perulangan menggunakan py while True:

 a += 1
 b = input("Masukkan Nama : ")
 c = input("Masukkan NIM : ")
 d = int(input("Masukkan Nilai Tugas : "))
 e = int(input("Masukkan Nilai UTS : "))
 f = int(input("Masukkan Nilai UAS :" ))
 g = "{:.2f}".format((d*.30) + (e*.35) + (f*.35))
a += 1 untuk menginput nomer pada awal table. deklarasi list dan Memasukkan Input Dengan Fungsi input() untuk menulis nama yang akan kita simpan dalam variabel. int(input()) untuk menginput tipe data interger (bilangan bulat) dalam variabel.

{:.2f}".format((d*.30) + (e*.35) + (f*.35)) untuk menginput Nilai Akhir yang di ambil dari perhitungan 3 komponen nilai.

 tabelNama.add_ro ([a,b,c,d,e,f,g])
 tabelNama.horizontal_char = "="
 tabelNama.junction_char = "="
 variabel di atas adalah untuk membentuk sebuah table.
Program input tanya [y/t], apabila jawaban t atau T, maka program inputan dihentikan statement break dan akan menampilkan data yang sudah diinput.
hasil output![Screenshot (17)](https://user-images.githubusercontent.com/115876367/202967726-80c45679-7fd2-42f3-ba4d-6d01918363d7.png)

