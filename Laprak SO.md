<h2>Pendahuluan</h2>
<h3>Latar belakang</h3>
<p>VirtualBox adalah perangkat lunak virtualisasi open-source yang memungkinkan pengguna menjalankan sistem operasi tambahan di dalam sistem operasi utama tanpa memodifikasi sistem fisik. Dengan fitur seperti snapshot dan manajemen disk dinamis, VirtualBox memungkinkan Anda untuk bereksperimen dengan berbagai sistem operasi, seperti Linux, tanpa risiko.</p>
  
<p>Ubuntu adalah salah satu distribusi Linux yang populer, terkenal karena kemudahan penggunaan, keamanan yang kuat, dan dukungan komunitas yang luas. Untuk menggunakan Ubuntu di VirtualBox, Anda cukup mengunduh dan menginstal VirtualBox, lalu membuat mesin virtual baru. Setelah itu, unduh file ISO Ubuntu, dan jalankan instalasi di dalam mesin virtual tersebut. Ini memungkinkan Anda untuk mencoba Ubuntu tanpa mengubah konfigurasi atau instalasi sistem utama di komputer Anda.</p>

<h3>Perangkat yang dibutuhkan</h3>
<h4>1.	Komputer atau laptop</h4>
<h4>2.	Siapkan file iso ubuntu 24.04</h4>
<h4>3.	Aplikasi Virtualbox</h4>

<h3>Tujuan Praktikum</h3>
1.	Memahami prosedur instalasi sistem operasi linux <br/>
2.	Mampu melakukan instalasi menggunakan antarmuka grafis (GUI) maupun baris perintah (command line) Linux <br/>
3.	Mampu memnganalisis dan mengevaluasi proses instalasi <br/>

<h3>Dasar Teori</h3>
Virtualisasi adalah teknologi yang memungkinkan menjalankan beberapa sistem operasi di atas satu mesin fisik. VirtualBox, perangkat lunak virtualisasi open-source, memungkinkan pengguna membuat mesin virtual yang berfungsi seperti komputer fisik. Dalam praktikum ini, VirtualBox digunakan untuk menginstal Linux Ubuntu, sebuah distribusi Linux yang terkenal dengan kemudahan dan keamanan.
Praktikum ini melibatkan pembuatan mesin virtual, konfigurasi perangkat keras virtual, dan instalasi Ubuntu di dalamnya. Tujuannya adalah memahami cara kerja virtualisasi dan proses instalasi sistem operasi tanpa mengganggu sistem utama. Ini memberikan dasar penting untuk administrasi sistem dan teknologi virtualisasi.

<h2>Pembahasan</h2>
<h3>Langkah-langkah Instalasi Linux Ubuntu</h3>
1. Download file iso ubuntu https://ubuntu.com/download/desktop/thank-you?version=24.04.1&architecture=amd64&lts=true  <br/>
  
2. Download juga aplikasi virtualbox software untuk menjalankan sistem operasi linux ubuntu https://download.virtualbox.org/virtualbox/7.0.20/VirtualBox-7.0.20-163906-Win.exe  <br/>

3. Setelah itu buka aplikasi virtualbox dan klik bagian "new"  <br/>
<img src = https://github.com/user-attachments/assets/11677ee1-2a33-4668-90e7-0d6d99dff744 width=500/>  <br/>

4. Kemudian isi nama dan klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/49981124-8b37-4aec-811e-5d4276db1bc2 width=500/>  <br/>

5. Setelah itu base memory nya pilih di angka 4096 MB dan dan prosesornya di angka 6 dan klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/ac4121e0-f378-43d1-a9ba-154382dfb1d0 width=500/>  <br/>

6. Ukuran disknya pilih di angka 8 GB dan klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/7b620447-2661-4436-b011-de47a8f2a4fd width=500/>  <br/>

7. Setelah jadi, klik bagian setting dan pilih "stroge". Pada bagian controller IDE klik bagian "Empty" dan klik ikon lingkaran berwarna biru di samping optical drive dan pilih file iso ubuntu  <br/>
<img src = https://github.com/user-attachments/assets/084deaa3-f132-46c5-96aa-a4408d133cce width=500/>  <br/>

8. Setelah itu klik start dan tampilan akan menjadi seperti ini  <br/>
<img src = https://github.com/user-attachments/assets/3451fde9-cdf4-4b43-81b2-f5117c7dcc04 width=500/>  <br/>

9. Setelah itu pilih bahasa sesuai dengan keinginan dan klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/5be6fa7f-7fdd-4881-8ea9-57f8ccb303d4 width=500/>  <br/>

10. Kemudian klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/109591b8-baeb-4554-84eb-e39a03fefac5 width=500/>  <br/>

11. "Next" lagi  <br/>
<img src = https://github.com/user-attachments/assets/7f570743-e365-4b56-9ecb-28ebe8f5f258 width=500/>  <br/>

12. Lalu klik "use wired connection" dan klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/843635e3-285c-4953-8a49-ab7352323567 width=500/>  <br/>

13. Kemudian klik install ubuntu dan klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/9e387cc4-d4d6-4479-8897-75701d7a85d5 width=500/>  <br/>

14. Klik interactive installation dan "next"  <br/>
<img src = https://github.com/user-attachments/assets/93ab3217-e94c-4bd3-9f8b-710dad9732e1 width=500/>  <br/>

15. Pilih default selection kemudian klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/7f6f69f5-1fcc-4886-9aee-3ae3b598d446 width=500/>  <br/>

16. Lalu centang keduanya dan klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/4524df78-06c2-4bbc-8d6f-0c9a9a49c034 width=500/>  <br/>

17. kemudian pilih erase disk and install ubuntu dan klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/f5ee3928-385a-49c5-8aee-82f3c83cefb0 width=500/>  <br/>

18. Lalu membuat akun, isi sesuai keinginan dan klik "next"  <br/>
<img src = https://github.com/user-attachments/assets/7fb7de30-4ec6-4cb1-bff3-fbc647d64047 width=500/>  <br/>

19. Kemudian pilih lokasi di Jakarta  <br/>
<img src = https://github.com/user-attachments/assets/dd186464-0f79-4a7d-8a92-2c3dc021bfd4 width=500/>  <br/>

20. Lalu klik "install"  <br/>
<img src = https://github.com/user-attachments/assets/79300d8f-734f-4df3-af89-87409eee4f96 width=500/>  <br/>

21. Tunggu sampai proses penginstalan selesai  <br/>
<img src = https://github.com/user-attachments/assets/9b432b89-e92b-4b92-bdc0-e21a51af7982 width=500/>  <br/>

22. Setelah selesai, klik "restart"  <br/>
<img src = https://github.com/user-attachments/assets/63160042-c775-4d12-a932-502e92987ed0 width=500/>  <br/>

23. Kemudian tekan "enter"  <br/>
<img src = https://github.com/user-attachments/assets/f6c9c9b5-c841-4812-96e9-0f974689b5c1 width=500/>  <br/>

24. Setelah di restart, buka virtualbox dan start kembali dan tampilan akan seperti ini  <br/>
<img src = https://github.com/user-attachments/assets/88d7bfe8-da95-4b6b-81c9-a882be864c4c width=500/>  <br/>

25. Masukkan username dan password yang telah dibuat sebelumnya  <br/>
<img src = https://github.com/user-attachments/assets/5ac7b2d9-274b-465b-8bcd-53698db2b98e width=500/>  <br/>

26. Tampilan sistem operasi ubuntu 24.04 yang telah terinstall<br/>
<img src = https://github.com/user-attachments/assets/05d632dd-64ae-44da-8d20-d575752c692a width=500/>  <br/>

<h2>ANALISIS SAAT INSTALASI PERLU MEMILIH "/" PADA OPSI MOUNT POINT</h2>
Tanda "/" dalam sistem Linux berfungsi sebagai direktori root, yaitu direktori utama di mana semua file dan folder sistem diatur. Partisi root, yang ditandai dengan "/", adalah titik awal dari seluruh struktur sistem file Linux, mirip dengan drive C: di Windows yang menjadi pusat sistem operasi. Saat Anda memilih "/" sebagai mount point, Anda menentukan bahwa partisi tersebut akan digunakan sebagai lokasi untuk menyimpan file dan folder sistem operasi utama, serta semua komponen penting lainnya yang mendukung kinerja sistem Linux.<br/>

<h2>PENJELASAN EXT4, EXT3, SWAP, NTFS, FAT32, BTRFS</h2>
<b>Ext4</b>adalah sistem file default untuk banyak distribusi Linux modern. Ini adalah versi lanjutan dari EXT3 dan menawarkan beberapa fitur tambahan seperti manajemen ruang yang lebih efisien, dukungan untuk partisi besar, dan peningkatan kinerja dalam penanganan file besar. EXT4 juga memiliki fitur journaling, yang membantu menjaga integritas data dengan mencatat perubahan sebelum benar-benar diterapkan ke disk.<br/>

<b>EXT3</b> adalah pendahulu dari EXT4 dan juga mendukung journaling, yang membantu memulihkan data setelah kegagalan sistem. Meskipun EXT3 cukup stabil dan andal, kinerjanya lebih rendah dibandingkan EXT4, terutama dalam menangani file besar dan jumlah file yang sangat banyak. Namun, EXT3 masih banyak digunakan di sistem yang lebih lama.<br/>

<b>Swap</b> bukan sistem file melainkan partisi khusus dalam sistem Linux yang berfungsi sebagai ruang memori virtual. Ketika RAM fisik habis, sistem operasi menggunakan SWAP sebagai perpanjangan memori, membantu menjalankan aplikasi yang membutuhkan lebih banyak memori. Meskipun lebih lambat dari RAM, SWAP sangat berguna dalam situasi di mana memori terbatas.<br/>

<b>NTFS</b> atau New Technology File System adalah sistem file milik Microsoft yang digunakan di sistem operasi Windows. NTFS mendukung fitur-fitur canggih seperti enkripsi, kompresi, dan manajemen kuota. NTFS juga sangat efisien dalam menangani file besar dan partisi besar, serta mendukung journaling untuk menjaga integritas data. <br/>

<b>FAT32</b> atau File Allocation Table 32 adalah sistem file yang lebih tua dan digunakan secara luas untuk perangkat penyimpanan eksternal seperti USB drive dan kartu SD. Meskipun sangat kompatibel dengan banyak sistem operasi, FAT32 memiliki keterbatasan, seperti tidak bisa menyimpan file yang lebih besar dari 4GB dan ukuran partisi maksimum 2TB.<br/>

<b>Btrfs</b> atau B-Tree File System adalah sistem file Linux yang dikembangkan untuk menawarkan fitur-fitur canggih seperti snapshotting, checksums, dan manajemen volume terintegrasi. BTRFS dirancang untuk menjadi lebih skalabel dan fleksibel dibandingkan EXT4, dengan kemampuan untuk menangani partisi besar dan fitur RAID built-in. BTRFS juga mendukung penyimpanan data yang lebih efisien dan pemulihan data otomatis, menjadikannya pilihan yang kuat untuk server dan lingkungan penyimpanan besar.<br/>

<h2>PENUTUP</h2>
<h3>KESIMPULAN</h3>
Sistem operasi adalah perangkat lunak inti yang bertugas mengelola dan mengoordinasikan semua perangkat yang terhubung ke komputer, sehingga memungkinkan komunikasi di antara perangkat tersebut. Sistem operasi memuat pertama kali ke dalam memori saat komputer dinyalakan, sebelum menjalankan perangkat lunak lainnya. Linux, sebagai sistem operasi open-source, menyediakan berbagai distribusi dengan fitur dan layanan yang bervariasi. Salah satu distribusi yang populer adalah Ubuntu, yang dirancang untuk memenuhi kebutuhan bisnis maupun pengguna umum. Dengan antarmuka yang mudah digunakan dan banyak fasilitas yang mendukung produktivitas, Ubuntu menjadi pilihan favorit bagi banyak pengguna di berbagai bidang.<br/>
