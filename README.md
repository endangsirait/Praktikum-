
# Latihan -1
1. Apa yang harus didefinisikan sebeum membuat objek?
2. Buatlah gambar diagram class dan dua buah objek dari class Person
bernama Antor dan Riko
3. Buatlah gambar diagram objek AkunBank dengan instance method
simpanUang, ambilUang dan cekSaldo

# * Hal-hal penting yang perlu didefenisikan sebelum membuat objek:
1. Class: Class adalah cetak biru atau template untuk menciptakan objek. Class mendefinisikan atribut (properties) dan metode (fungsi atau prosedur yang dapat dipanggil oleh objek dari class tersebut).
2. Atribut: Atribut adalah variabel yang dideklarasikan di dalam class untuk menyimpan data. Setiap objek dari class tersebut akan memiliki nilai untuk atribut ini.
3. Metode: Metode adalah fungsi yang didefinisikan dalam class dan dapat dipanggil oleh objek. Metode ini biasanya berfungsi untuk memanipulasi data dalam atribut atau melakukan tugas tertentu.
4. Konstruktor: Konstruktor adalah metode khusus yang digunakan untuk menginisialisasi objek ketika objek tersebut dibuat. Di Python, konstruktor didefinisikan dengan metode __init__.

# * Buatlah gambar diagram class dan dua buah objek dari class person bernama Antor dan Riko

![Screenshot 2024-10-09 092846](https://github.com/user-attachments/assets/2062e0ea-5586-40be-a129-a155d8b4fc84)

dari diagram di atas objek antor dan riko belum ditambahkan

# Diagram class yang telah dimasukan dua objek
* Diagram objek untuk anton
  
![Screenshot 2024-10-09 102837](https://github.com/user-attachments/assets/a83846d3-3292-41f6-9b9d-a80c95011d93)

Objek anton adalah instance dari class person, yang dimana atribut spertibnama, jenis kelamin, dan umur di isi biodata anton

* Diagram objek untuk Riko

![image](https://github.com/user-attachments/assets/d4ea6543-b392-4d66-8bd6-5bb2ce7f52d6)

Objek Riko adalah instance dari class person, yang dimana atribut seperti nama, jenis kelamin, dan umur di isi biodata Riko

# * Buatlah gambar diagram objek AkunBank dengan instane method simpanUang, ambilUang dan cekSaldo

![image](https://github.com/user-attachments/assets/9131e05c-4d59-4dcd-ad2c-2ee818496662)

Diagram diatas adalah diagram class AkunBank, tetapi di dalam diagram tersebut belum terdapat objek yang dimasukkan

* Berikut adalah diagram objek dari AkunBank

![image](https://github.com/user-attachments/assets/f875200b-1922-40a0-9cb3-db21cb011e45)

# Latihan -2
# Buatlah kode program java untuk:
* Mendeklarasikan class Person, dengan atribut Nama,
JenisKelamin, Umur
* Buatlah dua buah objek dari class Person bernama Anton
dan Riko
# * INPUT
![Screenshot 2024-10-09 091509](https://github.com/user-attachments/assets/89f7664d-c7db-4ad0-8cf5-01cc3dbfb118)
![Screenshot 2024-10-09 092423](https://github.com/user-attachments/assets/4465ff50-82b6-418c-a346-9d6f5c3b5405)

# * OUTPUT
![Screenshot 2024-10-09 092526](https://github.com/user-attachments/assets/e0540fd8-3fbd-4f7a-acb5-5491fc1036f7)

# Penjelasan
* Kelas person mendeklarasikan atribut nama, jeniskelamin, dan umur.
* Constructor digunakan untuk menginsialisasi atribut saat objek dibuat.
* Dua objek (anton dan riko) dibuat dengan menggunakan constructor dan datanya diisi.
* Method tampilkaninfo digunakan untuk menampilkan informasi dan objek tersebut.

# Latihan -3
# * Buatlah kode java untuk:
1. Mendeklarasikan class AkunBank dengan instance method
simpanUang, ambilUang dan cekSaldo
2. Buat objek AkunBank dan tetapkan nilai saldo awal Rp. 100000,
kemudian panggil 3 method tersebut dan tampilkan proses berikut:
![image](https://github.com/user-attachments/assets/e95c44bc-6f8b-4f88-be87-05544d62c26c)

* INPUT
![Screenshot 2024-10-09 110909](https://github.com/user-attachments/assets/dd0b1491-9478-487d-a425-76a5b7f7b5c0)
![image](https://github.com/user-attachments/assets/77c26a07-1296-4cbf-9df3-5ca0e730e417)

# * OUTPUT
![image](https://github.com/user-attachments/assets/b46581f1-41c0-4fbc-b774-a36fc8e383ad)

# Penjelasan
* Atribut saldo: Menyimpan saldo yang diinisialisasi melalui constructor.
* Method simpanUang(int jumlah): Menambahkan jumlah uang yang disimpan ke dalam saldo.
* Method ambilUang(int jumlah): Mengurangi saldo sesuai jumlah uang yang diambil jika saldo mencukupi.
* Method cekSaldo(): Menampilkan saldo saat ini.
* Main Method: Membuat objek AkunBank, menampilkan pesan awal, dan memanggil metode simpanUang dan ambilUang sesuai skenario pada gambar.
* Ketika program dijalankan, hasil yang ditampilkan sesuai dengan yang diminta di gambar.








