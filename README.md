# Nitro-Itera-Racing

## Tugas-Besar-PBO

Tugas Besar PBO kelompok 9 Kelas PBO-RD Yang berisikan:
1. Zulfa Puri Anjani             (122140023)
2. Marchel Karuna Kwee           (122140065)
3. Michael Caren Sihombing       (122140066) 
4. Muhammad Fauzan As Shabierin  (122140074)
5. Edwin Darren Hasannudin       (122140111)

## Nama Game

Nama game yang dibuat oleh kelompok 9 yaitu NITRO ITERA RACING. Kata NITRO dan RACING diambil karena memiliki arti kecepatan dan keterampilan pemain dalam mengemudikan mobil sembari menghindari lalu lintas padat di jalan raya, sedangkan unsur ITERA diambil karena yang membuat game ini yaitu kami selaku Mahasiswa ITERA dan mobil yang kami buat ada unsur logo ITERA nya. 

## Deskripsi Game

Nitro Itera Racing adalah permainan yang memacu adrenalin, menguji kecepatan, refleks, dan keterampilan pengendaraan Anda dalam menghadapi lalu lintas padat di jalan raya. Dalam petualangan ini, Anda akan memasuki jalur yang sibuk, mengendalikan mobil Anda dengan kecepatan tinggi sambil berusaha menghindari tabrakan dengan kendaraan lain dan berbagai rintangan-rintangan yang menghalangi jalan Anda. Semakin lama dan jauh Anda bertahan untuk tidak tertabrak dengan kendaraan lain dan rintangannya, maka semakin banyak poin yang terkumpul, itulah kunci dalam meningkatkan skor Anda. Aturan Permainan :
1. Anda harus menghindari tabrakan dengan kendaraan lain dan rintangan-rintangan yang ada
2. Semakin lama Anda bertahan, semakin banyak score yang terkumpul
3. Jika player dapat bertahan lebih lama dan mendapat score yang tinggi maka score yang didapat akan dicatat sebagi HighScor
4. Saat player tidak dapat menghindari tabrakan player dapat memulai permainan dari awal dengan menekan tombol Y pada keyboard.

##  Dependensi paket (library) yang dibutuhkan untuk menjalankan aplikasi

1. pygame:
- pygame adalah library untuk membuat game 2D di Python. Library ini menyediakan berbagai fungsi untuk menangani grafik, suara, dan input pengguna.
- Dalam program ini, pygame digunakan untuk menginisialisasi layar permainan, menggambar objek (seperti mobil, jalan, pohon), menangani input pengguna (keyboard dan mouse), dan memperbarui tampilan permainan.
2. https://github.com/chaelren/Nitro-Itera-Racing/releases
- https://github.com/chaelren/Nitro-Itera-Racing/releases adalah modul yang menyediakan konstan-konstan yang sering digunakan dalam pygame, seperti jenis-jenis event dan tombol keyboard.
- Dalam program ini, digunakan untuk mengimport konstan-konstan seperti QUIT, KEYDOWN, K_LEFT, K_RIGHT, K_UP, K_DOWN, K_p, MOUSEBUTTONDOWN, yang digunakan untuk menangani event di permainan.
3. random:
- random adalah modul standar Python untuk menghasilkan angka acak dan melakukan operasi acak lainnya.
- Dalam program ini, random digunakan untuk menentukan posisi acak dan kecepatan pohon serta untuk memilih jalur dan gambar kendaraan rintangan secara acak.
4. https://github.com/chaelren/Nitro-Itera-Racing/releases
- https://github.com/chaelren/Nitro-Itera-Racing/releases adalah modul dalam pygame yang menangani semua operasi terkait suara, seperti memutar efek suara dan musik latar.
- Dalam program ini, https://github.com/chaelren/Nitro-Itera-Racing/releases digunakan untuk memuat dan memutar efek suara, termasuk suara tampilan awal, suara mobil, dan suara crash.
5. pickle:
- pickle adalah modul standar Python untuk serialisasi dan deserialisasi objek Python. Dengan pickle, Anda dapat menyimpan objek Python ke dalam file dan memuatnya kembali nanti.
- Dalam program ini, pickle digunakan untuk menyimpan dan memuat high score permainan ke dan dari file https://github.com/chaelren/Nitro-Itera-Racing/releases
5. abc dan abstractmethod:
- abc adalah modul standar Python yang menyediakan alat untuk menggunakan kelas abstrak dan metode abstrak.
- abstractmethod adalah decorator yang digunakan untuk menandai metode dalam kelas abstrak sebagai metode abstrak yang harus diimplementasikan oleh kelas turunan.
- Dalam program ini, abc dan abstractmethod digunakan untuk mendefinisikan kelas AbstractColor, yang merupakan kelas abstrak untuk warna-warna yang digunakan dalam permainan. Kelas-kelas warna seperti Hitam, Abu, Hijau, Merah, Putih, Kuning, Biru mengimplementasikan metode generate_color dari kelas abstrak ini.

## DIAGRAM UNIFIED MODELING LANGUAGE

1. Spesifikasi Game - Use Case Diagram_ Pengguna
![1](https://github.com/chaelren/Nitro-Itera-Racing/releases)
2. Spesifikasi Game - Use Case Diagram_ Pengembang
![2](https://github.com/chaelren/Nitro-Itera-Racing/releases)
3. Spesifikasi Game - CLASS DIAGRAM
![3](https://github.com/chaelren/Nitro-Itera-Racing/releases)
![4](https://github.com/chaelren/Nitro-Itera-Racing/releases)
![5](https://github.com/chaelren/Nitro-Itera-Racing/releases)




