# Pemrograman Berbasis Framework<br>
Nama : Isna Dewi Malika Arum<br>
Kelas : TI - 2D<br>
NIM : 220102087<br>

**Codeigniter4**<br>
=> Kerangka Pengembangan Aplikasi - sebuah toolkit - untuk orang-orang yang membangun situs web menggunakan PHP. <br>
**Basis Data yang Didukung**<br>
=> MySQL melalui MySQLidriver (hanya versi 5.1 ke atas)<br>
=> PostgreSQL melalui Postgredriver (hanya versi 7.4 dan lebih tinggi)<br>
=> SQLite3 melalui SQLite3driver<br>
=> Microsoft SQL Server melalui SQLSRVdriver (hanya versi 2005 dan lebih tinggi)<br>
=> Oracle Database melalui OCI8driver (hanya versi 12.1 dan lebih tinggi)<br>

**1. Installation**<br>
    **a. Composer Installation**
      Teknik pertama buka cmder pada web server, lalu ketikan seperti dibawah<br>
      ```composer create-project codeigniter4/appstarter project-root```<br>
      project-root dapat diganti sesuai nama projek anda<br>
      contohnya <br>
      ![Screenshot 2024-03-18 101407](https://github.com/IsnaDewi/IsnaDewiMalikaArum/assets/134571793/6c42ca1c-a2a5-4daf-81ea-b0ed2399adfb)<br>
      Kemudian untuk menjalankan server ketikan<br>
      ```cd (isikan nama root anda)``` <br>
      lalu ketikan <br>
      ```php spark serve``` <br>
      contohnya<br>
      ![image](https://github.com/IsnaDewi/IsnaDewiMalikaArum/assets/134571793/c3c86f39-5131-4d1b-b00e-7bfe7ff64c5b)<br>

   **2. Build Your First Application** <br>
   Anda akan melewati halaman-halaman berikut:<br>
Pendahuluan, halaman ini, yang memberi Anda gambaran umum tentang apa yang diharapkan dan membuat aplikasi default Anda diunduh dan dijalankan.<br>
 Tutorial ini dimaksudkan untuk memperkenalkan Anda pada framework CodeIgniter4 dan prinsip dasar arsitektur MVC. Ini akan menunjukkan kepada Anda bagaimana aplikasi dasar CodeIgniter dibangun secara langkah demi langkah.<br>
   Tutorial ini terutama akan fokus pada:<br>
      =>Dasar-dasar Model-View-Controller<br>
      =>Dasar-dasar peroutean<br>
      =>Validasi formulir<br>
      =>Melakukan query database dasar menggunakan Model CodeIgniter<br>
**Halaman statis**, yang akan mengajarkan Anda dasar-dasar pengontrol, tampilan, dan peroutean.
      1. Buka file rute yang terletak di app/Config/Routes.php
      ```<?php<br>
         use CodeIgniter\Router\RouteCollection;<br>
         /**<br>
         * @var RouteCollection $routes<br>
         */<br>
         $routes->get('/', 'Home::index');``` <br>
         
**Bagian Berita** , tempat Anda akan mulai menggunakan model dan melakukan beberapa operasi basis data dasar.
**Buat item berita** , yang akan memperkenalkan operasi database lebih lanjut dan validasi formulir.
**Kesimpulan** , yang akan memberi Anda beberapa petunjuk tentang bacaan lebih lanjut dan sumber daya lainnya.
      
      
