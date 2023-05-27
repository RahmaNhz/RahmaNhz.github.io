Nama : Rahma Nurhaliza

NIM : 210411100176

Kelas : PENDATA B

- Mengumpulkan data dari beberapa sumber dan format database

  Melalui Cloud ElephantSQL

  1. Buat server baru pada postgresql dengan nama pendatab
  2.  pada database pilih schemas lalu public dan klik table
  3. pada pilihan table klik kanan untuk untuk menampilkan query tool
  4. masukan query untuk membuat table data iris
  5. klik run dan table telah berhasil dibuat
  6. lalu coba untuk import data iris dengan cara klik kanan pada table dan pilih export/import berikan tempat penyimpanan untuk data yang akan di export klik oke dan data iris pada cloud berhasil untuk di export

  Melalui Local Postgresql

  1. Register server pada server local dengan nama localpendatab
  2. Buat database baru dengan nama databaseiris lalu pilih schemas
  3. pada pilihan table klik kanan untuk untuk menampilkan query tool
  4. masukan query untuk membuat table data iris 
  5. klik run dan table telah berhasil dibuat
  6. lalu coba untuk import data iris dengan cara klik kanan pada table dan pilih export/import berikan tempat penyimpanan untuk data yang akan di export klik oke dan data iris pada lokal berhasil untuk di export

  Melalui Mysql

  1. buka php myadmin pilih tekan new untuk membuat database  dan berikan nama untuk database
  2. pada database yang dibuat pilih import lalu masukkan file data iris yang telah di export dari postgresql
  3. Tekan Import dan dalam database yang dibuat berhasil memuat table yang berisi data iris

  Mengimport data dari Local PostgreSQL ke Power BI

  1. Pada Power BI pilih Get data pilih database postgreSQL
  2.  masukkan nama Server local yaitu localhost
  3. masukkan nama database yang berisi data yang akan di import
  4. masukkan username yaitu postgres
  5. masukkan password postgresql
  6. lalu tunggu proses selesai pilih  pilih trasfrom kemudian pilih close and apply
  7. maka data dari local postgreSQL akan berhasil di import ke power BI untuk di analisis

  Mengimport data dari Cloud 

  1. Pada Power BI pilih Get data pilih database postgreSQL
  2. masukkan nama Server cloud dan port
  3. masukkan nama database yang berisi data yang akan di import
  4. masukkan username akun cloud
  5. masukkan password akun cloud
  6. lalu tunggu proses selesai pilih trasfrom kemudian pilih close and apply
  7. maka data dari cloud postgreSQL akan berhasil di import ke power BI untuk dianalisis

  Mengimport data dari Mysql Ke Power BI

  1. Download terlebih dahulu mysql connector
  2. Pada Power BI pilih Get data pilih MySQL database
  3. masukkan Nama Server yaitu Localhost:3306
  4. masukkan nama database yang berisi data iris
  5. Setelah itu pada pilihan database masukkan username dari mysql yaitu root
  6. kemudian pada password kosongkan saja
  7. lalu tunggu proses selesai ilih trasfrom kemudian pilih close and apply
  8. maka data dari cloud postgreSQL akan berhasil di import ke power BI untuk dianalisis

  Mengimport data text/csv

  1. Pada Power BI pilih Get data pilih text/csv
  2. masukkan file csv
  3. pilih trasfrom kemudian pilih close and apply tunggu proses selesai
  4. maka data iris csv berhasil di load pada power BI 

  

  

  

