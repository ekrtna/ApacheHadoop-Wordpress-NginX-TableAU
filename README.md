# Apache, Wordpress, NginX, and TableAU Installation

## 1. Apache 
1. Login sebagai user di ubuntu server.
2. Gunakan perintah “sudo apt update” untuk memperbarui daftar paket yang tersedia.
3. Menginstall apache dengan perintah “sudo apt install apache2”.
4. Mengecek apk yang diinstal dengan perintah “sudo ufw app list”.
5. Gunakan perintah “sudo systemctl status apache2”.
6. Gunakan perintah “hostname -I” untuk melihat ip address.
7. Mengecek apache2 pada ip address.
8. Masuk ke direktori "/var/www/html"
9. Mengedit
10. Tampilan di website


![image](https://github.com/ekrtna/ApacheHadoop-Wordpress-NginX-TableAU/assets/150004277/ea2ddd63-c83e-4cc2-ae53-103890a52a68)

## 2. Wordpress
1. Login sebagai pengguna root ke sistem dan perbarui sistem untuk memperbarui repositori.
2.	Install Apache.
3.	Untuk mengonfirmasi bahwa Apache telah terinstal di sistem, jalankan perintah "sudo systemctl status apache2".
4.	Buka browser dan buka alamat IP server.
5.	Install Maria-db
6.	Amankan mesin basis data MariaDB.
7.	Install PHP.
8.	Untuk mengonfirmasi bahwa PHP telah diinstal, buat file info.php di jalur /var/www/html/.
9.	Ketik line berikut.
10.	Simpan dan keluar. Buka browser Anda dan tambahkan /info.php ke URL server.
11.	Masuk ke database MariaDB sebagai root dan buat database untuk menampung data WordPress.
12.	Buat database untuk WordPress.
13.	Buat pengguna database untuk pengaturan WordPress.
14.	Berikan hak istimewa kepada pengguna Selanjutnya, berikan izin kepada pengguna untuk mengakses database.
15.	Sekarang Anda dapat keluar dari database.
16.	Buka direktori sementara dan unduh File WordPress terbaru.
17.	Buka kompresi tarball yang akan menghasilkan folder bernama "wordpress".
18.	Salin folder wordpress ke /var/www/html/.
19.	Mengubah kepemilikan direktori 'wordpress'.
20.	Ubah izin file folder WordPress.
21.	Buat direktori 'unggahan'. 
22.	Buka browser Anda dan buka URL server. Akan muncul halaman wordpress.


![image](https://github.com/ekrtna/ApacheHadoop-Wordpress-NginX-TableAU/assets/150004277/547486b2-fb6d-4f9d-8f1e-fd5860b85c38)


23. Login dengan username dan password yang telah kita buat tadi. Lalu, akan muncul homepage wordpress-admin setelah setelah melakukan login.


![image](https://github.com/ekrtna/ApacheHadoop-Wordpress-NginX-TableAU/assets/150004277/7f26e8fd-e830-4b3e-baab-b9e38d6aebf5)

24. Berikut hasil postingan yang sudah saya buat.
![image](https://github.com/ekrtna/ApacheHadoop-Wordpress-NginX-TableAU/assets/150004277/d9cfffcb-e918-4a7a-8de3-396efd0d4e48)
![image](https://github.com/ekrtna/ApacheHadoop-Wordpress-NginX-TableAU/assets/150004277/4f7c439f-c9f3-4b36-b566-36734a586d51)

## 3. NginX
1. Login sebagai user di ubuntu server.
2.	Gunakan perintah “sudo apt update” untuk memperbarui daftar paket yang tersedia.
3.	Install NginX dengan “sudo apt install nginx”.
4.	Melihat aplikasi apa saja yang sudah diinstal dengan “sudo ufw app list”.
5.	Disarankan agar mengaktifkan profil yang masih mengizinkan traffic yang dikonfigurasikan. Saat ini, hanya perlu mengizinkan traffic di port 80. 
6.	Memastikan layanan berjalan dengan command "sudo systemctl status nginx".
7.	Akses halaman arahan default Nginx untuk mengonfirmasi bahwa perangkat lunak berjalan dengan baik dengan menavigasi ke alamat IP server Anda. Jika tidak mengetahui alamat IP server Anda, Anda dapat menemukannya dengan menggunakan alat icanhazip.com.
8.	Setelah itu ketik IP tersebut di searchbar dan akan muncul tampilan sebagai berikut.

 ![image](https://github.com/ekrtna/ApacheHadoop-Wordpress-NginX-TableAU/assets/150004277/95ab2f8c-8050-453b-8185-52fdf3b17ba9)

 ## 4. TableAU
1. Download Tableau dengan mengetik “Download Tableau For Students’ di Google. Disini saya menggunakan Tableau For Students. Setelah selesai download bisa langsung kita run aplikasi Tableau.
2.	Setelah kita buka aplikasi Tableau, berikut adalah tampilan awalnya.
3.	Lalu kita bisa memasukkan data yang kita miliki, disini saya memilih memasukkan data dari Microsoft Excel karena file saya berbentuk .xls.
4.	Disini saya memakai data penjualan sebagai bahan dari visualisasi data saya.
5.	Lalu saya memasukkan data yang sama dalam bentuk .csv untuk menciptakan hubungan dari setiap variable di data tersebut.
6.	Disini saya menggunakan data dari Order ID untuk menghubungkan dua file tersebut.
7.	Lalu kita berpindah ke sheet 1 untuk melakukan visualisasi data. Berikut adalah visualisasi data penjualan setiap tahunnya.

![image](https://github.com/ekrtna/ApacheHadoop-Wordpress-NginX-TableAU/assets/150004277/4bd67f5a-4166-4815-9c38-da1fd8ba0b48)


9. Dan ini adalah visualisasi data berdasarkan negara dan juga jumlah kuantitasnya.


![image](https://github.com/ekrtna/ApacheHadoop-Wordpress-NginX-TableAU/assets/150004277/e3c4eb4a-c2fa-4a92-82ce-da78c559a104)









 


