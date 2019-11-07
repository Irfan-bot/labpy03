# TUGAS PRAKTIKUM 3

## Latihan 1
latihan 1 kita akan mencari angka terkecil yang kurang dari 0,5
1.Masukkan nilai input. Nilai input ini berfungsi untuk menampilkan banyak data. Anda bisa memasukkan nilai berapa saja.
2.Dengan menggunakan fungsi random. Yakni, fungsi yang akan menampilkan angka dibawah 0.5 secara acak. Fungsi random sudah otomatis ditampilkan.
3.Ketika anda sudah memberikan input nilai, maka akan langsung muncul data nilai random. Berikut hasilnya :

![1 1](https://user-images.githubusercontent.com/56944673/68371056-b0695480-00f2-11ea-8a52-89cd4fcd2e22.png)
## output
![1 2](https://user-images.githubusercontent.com/56944673/68371381-75b3ec00-00f3-11ea-9626-aa0ccd12870f.png)

## Latihan 2
Latihan 2 akan menampilkan bilangan terbesar dari n buah data yang diinputkan
1. Masukkan bilangan
2. Program akan terus mengulang untuk meminta anda memasukkan bilangan.
3. Pengulangan akan berhenti ketika anda memasukkan angka 0 (nol).
4. Lalu akan ditampilkan bilangan terbesar dari semua bilangan yang
![2 1](https://user-images.githubusercontent.com/56944673/68371483-a431c700-00f3-11ea-9f93-55deb3b4e511.png)
## output
![2 2](https://user-images.githubusercontent.com/56944673/68371583-de9b6400-00f3-11ea-9b9e-d3ac758880a1.png)

## Pemrograman 1
Pada program ini kita akan mencari keuntungan pada usaha yang telah berjalan selama 8 bulan dengan kondisi yang telah ditentukan
1. Nilai modal
- modal = 100000000
2. Nilai laba 0
- laba = 0
3. Nilai untung 0
- untung = 0
4. perulangan i dengan nilai awal 1, nilai akhir 9 dan step 1
- for i in range (1,9):
5. Kondisi apabila belum bulan ke 3 laba masih 0%
- if (i < 3):
- laba = c
- untung = untung + laba
6.  kondisi apabila belum memasukan bulan ke 5 mendapat laba sebesar 1%
- elif(1 < 5):
- laba = modal*1/100
- untung = untung + laba 
7. kondisi apabila belum memasukan bulan ke 8 mendapatkan laba sebesar 5%
- elif(1<8):
- laba = modal*1/100
- untung = untung + laba
8. Pada bulan ke 8 laba menurun 2% sehingga laba bulan ke 8 sebesar 3%
- else:
- laba = modal*2/100
- untung = untung + laba
9. Mencetak laba per bulan
- print("Laba bulan ke", i, "sebesar:", laba)
10. Menghitung total laba selama 8 bulan 
- print("Total laba adalah:", untung)

![3 1](https://user-images.githubusercontent.com/56944673/68371627-f246ca80-00f3-11ea-9e56-5f3a6bcf5021.png)
## output 
![3 2](https://user-images.githubusercontent.com/56944673/68371653-038fd700-00f4-11ea-8b67-28647d3d2142.png)