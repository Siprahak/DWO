# DWO

A. Menyiapkan Database (SQL)
Unduh file warehouse_aw.sql dari folder Database di GitHub.
Jalankan XAMPP, aktifkan Apache dan MySQL, lalu buka phpMyAdmin.
Buat database baru dengan nama warehouse_aw.
Gunakan fitur IMPORT di phpMyAdmin untuk mengunggah file warehouse_aw.sql ke database tersebut.
Tunggu proses hingga selesai.

B. Konfigurasi Mondrian / OLAP / Cube
Pastikan Mondrian sudah terinstal di perangkat Anda.
Unduh folder Mondrian dari repositori GitHub.
Pindahkan file index.html, index2.html, dan testpage.html ke folder:
D:\Apk\XAMPP\tomcat\webapps\mondrian (sesuaikan lokasi ini dengan instalasi XAMPP Anda).
Pindahkan file memet.xml dan mamat.jsp dari folder queries ke:
XAMPP\tomcat\webapps\mondrian\WEB-INF\queries.
Salin file mysql-connector-java-5.1.4-bin.jar dari folder lib ke:
XAMPP\tomcat\webapps\mondrian\WEB-INF\lib.

C. Menjalankan Mondrian
Buka XAMPP, lalu nyalakan Apache, MySQL, dan Tomcat.
Klik tombol Admin di bagian Tomcat.
Di peramban web, buka URL: http://localhost:8080/mondrian/index.html.
(Pastikan port 8080 sesuai dengan konfigurasi XAMPP Anda.)
Pada halaman tersebut, Anda akan menemukan tautan menuju OLAP Cube hasil proses ETL.

D. Instalasi Dashboard
Unduh file ZIP berisi data DWO dari GitHub.
Ekstrak file ZIP tersebut.
Salin folder hasil ekstraksi ke direktori XAMPP\htdocs pada lokasi instalasi XAMPP Anda.

E. Mengakses Dashboard
Jalankan XAMPP dan aktifkan Apache, MySQL, serta Tomcat.
Buka peramban web dan masukkan URL: http://localhost/NamaFolderDashboard.
