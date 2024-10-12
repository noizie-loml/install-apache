Server HTTP Apache adalah webserver yang paling banyak digunakan di dunia. Webserver ini menyediakan banyak fitur canggih termasuk modul yang dapat dimuat secara dinamis, dukungan media yang kuat, dan integrasi luas dengan perangkat lunak populer lainnya.

Langkah 1, Menambahkan Repository Software Apache
Pertama-tama yang harus kamu lakukan adalah login ke server ubuntu kamu. Untuk login kamu bisa menggunakan ssh atau putty. Login ke root, jalankan perintah dibawah ini untuk mengupdate OS atau Operation Sistem Debian 10 Milikmu.

$ sudo apt update
Langkah 2, Menginstall Apache
Setelah menambahkan repository dan packet-packet untuk server milikmu, Kamu hanya tinggal menginstall packet-packet tersebut, jalankan perintah berikut untuk menginstall Apache Kamu 

$ sudo apt install apache2
Langkah 3, Mengaktifkan Apache
Selesai menginstall Apache kamu perlu mengaktifkan Apache agar dapat dijalankan dengan mengetik command

$ sudo systemctl start apache2
Lalu jalankan command

$ sudo systemctl status apache2
Langkah 4, Melihat Hostname Default Apache
Jika kita ingin menguji apakah Apache server di debianmu sudah terinstall adalah di membuka hostname di browser. Untuk mengetahui hostname Kamu bisa ketik command dibawah.

$ hostname -I
Setelah kamu menjalankan command diatas maka akan keluar daftar hostname yang dapat kamu gunakan.
Catat ip publicnya, di contoh ini ip publicnya adalah 101.50.3.220

Langkah 5, Menguji Apache
Buka browser lalu ketik hostname server dalam contoh ini alamat ipnya adalah 101.50.3.220
