# DWO

A. Menyiapkan Database (SQL)
1. Unduh file warehouse_aw.sql dari folder Database di GitHub.
2. Jalankan XAMPP, aktifkan Apache dan MySQL, lalu buka phpMyAdmin.
3. Buat database baru dengan nama warehouse_aw.
4. Gunakan fitur IMPORT di phpMyAdmin untuk mengunggah file warehouse_aw.sql ke database tersebut.
5. Tunggu proses hingga selesai.

B. Konfigurasi Mondrian / OLAP / Cube
1. Pastikan Mondrian sudah terinstal di perangkat Anda.
2. Unduh folder Mondrian dari repositori GitHub.
3. Pindahkan file index.html, index2.html, dan testpage.html ke folder:
4. D:\Apk\XAMPP\tomcat\webapps\mondrian (sesuaikan lokasi ini dengan instalasi XAMPP Anda).
5. Pindahkan file memet.xml dan mamat.jsp dari folder queries ke:
6. XAMPP\tomcat\webapps\mondrian\WEB-INF\queries.
7. Salin file mysql-connector-java-5.1.4-bin.jar dari folder lib ke: XAMPP\tomcat\webapps\mondrian\WEB-INF\lib.

C. Menjalankan Mondrian
1. Buka XAMPP, lalu nyalakan Apache, MySQL, dan Tomcat.
2. Klik tombol Admin di bagian Tomcat.
3. Di peramban web, buka URL: http://localhost:8080/mondrian/index.html. (Pastikan port 8080 sesuai dengan konfigurasi XAMPP Anda.)
4. Pada halaman tersebut, Anda akan menemukan tautan menuju OLAP Cube hasil proses ETL.

D. Instalasi Dashboard
1. Unduh file ZIP berisi data DWO dari GitHub.
2. Ekstrak file ZIP tersebut.
3. Salin folder hasil ekstraksi ke direktori XAMPP\htdocs pada lokasi instalasi XAMPP Anda.

E. Mengakses Dashboard
1. Jalankan XAMPP dan aktifkan Apache, MySQL, serta Tomcat.
2. Buka peramban web dan masukkan URL: http://localhost/NamaFolderDashboard.
