<h3 align="center">NETWORK SECURITY</h3>
<h3 align="center">
“SPOOFING”
</h3>


<p align="center">
  <img src="https://github.com/nadiaaaAR/Keamanan-Jaringan/blob/master/img/sp.png">
</p>


**1. Latar Belakang**

Hari ini, Anda dapat menemukan orang-orang dari semua lapisan masyarakat menggunakan internet secara teratur. Di sisi lain masalah dan bahaya dalam penggunaan internet juga telah meningkat. Ada banyak jenis ancaman internet seperti pencurian ID, serangan virus dan spoofing. Spoofing adalah tindakan asumsi identitas beberapa komputer atau program lainnya. Spoofing mengambil bentuk IP spoofing, email spoofing dan spoofing jaringan.
Sementara sebagian besar tindakan spoofing adalah berbahaya dan berbahaya, spoofing jaringan dapat berfungsi sebagai teknik membantu. Ketika Anda mendapatkan akses ke sumber-sumber dan informasi dari setiap jaringan yang tidak sah, itu dikenal sebagai spoofing jaringan.


**2. Pembahasan**

**a.  Pengertian Spoofing**

Spoofing, secara umum, adalah praktik penipuan atau berbahaya di mana komunikasi dikirim dari sumber yang tidak diketahui menyamar sebagai sumber diketahui penerima. Spoofing adalah yang paling lazim dalam mekanisme komunikasi yang tidak memiliki tingkat keamanan yang tinggi
**Techopedia menjelaskan Spoofing**
Email spoofing adalah salah satu parodi terkenal. Sejak inti SMTP gagal untuk menawarkan otentikasi, itu adalah sederhana untuk menempa dan meniru email. email palsu dapat meminta informasi pribadi dan mungkin tampak dari pengirim yang dikenal. email tersebut meminta penerima untuk membalas dengan nomor rekening untuk verifikasi. The spoofer email kemudian menggunakan nomor rekening ini untuk tujuan pencurian identitas, seperti mengakses rekening bank korban, mengubah rincian kontak dan sebagainya.
Penyerang (atau spoofer) tahu bahwa jika penerima menerima email palsu yang tampaknya dari sumber yang dikenal, kemungkinan untuk dibuka dan ditindaklanjuti. Jadi email palsu juga berisi ancaman tambahan seperti Trojan atau virus lainnya. Program-program ini dapat menyebabkan kerusakan komputer yang signifikan dengan memicu aktivitas tak terduga, akses remote, penghapusan file dan banyak lagi.


**b.  Spoofing Attacks**

Sebuah serangan spoofing adalah ketika pihak jahat meniru perangkat lain atau pengguna pada jaringan untuk memulai serangan terhadap host jaringan, mencuri data, menyebarkan malware atau akses pintas kontrol. Ada beberapa jenis serangan spoofing yang pihak berbahaya dapat menggunakan untuk mencapai hal ini. Beberapa metode yang paling umum termasuk IP serangan alamat spoofing, serangan spoofing ARP dan serangan spoofing DNS server.

**c.  Spoofing IP Address**

IP spoofing alamat adalah salah satu metode serangan spoofing yang paling sering digunakan. Dalam sebuah serangan spoofing alamat IP, penyerang mengirimkan paket IP dari palsu (atau "palsu") alamat sumber untuk menyamarkan diri. Denial-of-service serangan sering menggunakan IP spoofing membebani jaringan dan perangkat dengan paket yang tampak dari alamat IP sumber yang sah. Ada dua cara bahwa serangan spoofing IP dapat digunakan untuk membebani target dengan lalu lintas. Salah satu metode adalah dengan hanya membanjiri target yang dipilih dengan paket-paket dari beberapa alamat palsu. Metode ini bekerja dengan langsung mengirim korban lebih banyak data daripada yang dapat menangani. Metode lainnya adalah untuk menipu alamat IP target dan mengirim paket dari alamat yang ke banyak penerima yang berbeda pada jaringan. Ketika mesin lain menerima sebuah paket, maka secara otomatis akan mengirimkan paket ke pengirim respon. Karena paket palsu tampaknya dikirim dari alamat IP target, semua tanggapan terhadap paket palsu akan dikirim ke (dan banjir) alamat IP target. serangan spoofing IP juga dapat digunakan untuk memotong otentikasi berbasis alamat IP. Proses ini bisa sangat sulit dan terutama digunakan ketika hubungan kepercayaan berada di tempat antara mesin pada jaringan dan sistem internal. hubungan kepercayaan menggunakan alamat IP (bukan login pengguna) untuk memverifikasi identitas mesin 'ketika mencoba untuk mengakses sistem. Hal ini memungkinkan pihak jahat untuk menggunakan serangan spoofing untuk meniru mesin dengan izin akses dan langkah-langkah keamanan jaringan berbasis kepercayaan memotong.

**d.  Spoofing ARP

ARP adalah singkatan Address Resolution Protocol, protokol yang digunakan untuk menyelesaikan alamat IP ke MAC (Media Access Control) alamat untuk transmisi data. Dalam sebuah serangan spoofing ARP, pihak jahat mengirimkan pesan ARP palsu di jaringan area lokal untuk menghubungkan alamat MAC penyerang dengan alamat IP dari anggota yang sah dari jaringan. Jenis hasil serangan spoofing data yang dimaksudkan untuk alamat IP host mendapatkan dikirim ke penyerang gantinya. pihak berbahaya umumnya menggunakan ARP spoofing untuk mencuri informasi, memodifikasi data dalam transit atau menghentikan lalu lintas di LAN. serangan spoofing ARP juga dapat digunakan untuk memfasilitasi jenis-jenis serangan, termasuk denial-of-service, pembajakan sesi dan serangan man-in-the-middle. ARP spoofing hanya bekerja pada jaringan area lokal yang menggunakan Address Resolution Protocol.

**e.  Spoofing DNS Server**

Domain Name System (DNS) adalah suatu sistem yang mengaitkan nama domain dengan alamat IP. Perangkat yang terhubung ke internet atau jaringan swasta lainnya bergantung pada DNS untuk menyelesaikan URL, alamat email dan nama domain terbaca-manusia lain ke alamat IP yang sesuai mereka. Dalam serangan spoofing DNS server, pihak jahat memodifikasi server DNS untuk mengubah rute nama domain khusus untuk alamat IP yang berbeda. Dalam banyak kasus, alamat IP baru akan untuk server yang sebenarnya dikendalikan oleh penyerang dan berisi file yang terinfeksi dengan malware. serangan spoofing DNS server yang sering digunakan untuk menyebarkan worm komputer dan virus.

**f.  Pencegahan dan Mitigasi Serangan Spoofing**


Ada banyak alat-alat dan praktik yang organisasi dapat mempekerjakan untuk mengurangi ancaman serangan spoofing. langkah-langkah umum bahwa organisasi dapat mengambil untuk spoofing pencegahan serangan meliputi:

•	Packet filtering: Packet filter menginspeksi paket seperti yang ditransmisikan melalui jaringan. Packet filter yang berguna dalam alamat IP pencegahan serangan spoofing karena mereka mampu menyaring dan memblokir paket dengan informasi alamat sumber yang saling bertentangan (paket dari luar jaringan yang menunjukkan alamat sumber dari dalam jaringan dan sebaliknya).
•	Hindari hubungan kepercayaan: Organisasi harus mengembangkan protokol yang mengandalkan hubungan kepercayaan sesedikit mungkin. Hal ini secara signifikan lebih mudah bagi penyerang untuk menjalankan serangan spoofing ketika hubungan kepercayaan berada di tempat karena hubungan kepercayaan hanya menggunakan alamat IP untuk otentikasi.
•	Gunakan perangkat lunak pendeteksi spoofing: Ada banyak program yang tersedia yang membantu organisasi mendeteksi serangan spoofing, terutama ARP spoofing. Program ini bekerja dengan memeriksa dan mensertifikasi data sebelum ditransmisikan dan memblokir data yang tampaknya palsu.
•	Menggunakan protokol jaringan kriptografi: Transport Layer Security (TLS), Secure Shell (SSH), Secure HTTP (HTTPS) dan komunikasi aman lainnya protokol mendukung upaya pencegahan serangan spoofing dengan mengenkripsi data sebelum dikirim dan otentikasi data seperti yang diterima.


**3. Penutup**

**a. Kesimpulan**

Spoofing, secara umum, adalah praktik penipuan atau berbahaya di mana komunikasi dikirim dari sumber yang tidak diketahui menyamar sebagai sumber diketahui penerima. Spoofing adalah yang paling lazim dalam mekanisme komunikasi yang tidak memiliki tingkat keamanan yang tinggi

*b. Saran**

Selanjutnya untuk mendalami materi Spoofing dengan membaca sumber-sumber yang tersedia di buku maupun internet , dan  melakukan praktikum mandiri.

-------

**Link Github** 	            :  https://github.com/nadiaaaAR/Keamanan-Jaringan<br>

**Referensi**	                :	 https://www.veracode.com/security/spoofing-attack<br>

**Scan Plagiarisme**          : <br>
   
a. searchenginereport     :   https://drive.google.com/open?id=0B831iVXSuoJcanZWcnktalZWVnc <br>
        
b. smallseotools	      :   https://drive.google.com/open?id=0B831iVXSuoJceG1KYTB0bWItelk<br>

  
-------

> - Fullname 				 : Nadia Ayu Lestari Arifin
> - Nickname 				 : Nadia
> - NPM		 				 : 1144002
> - Class	 				 : D4 TI 3C
> - Department  		     : Informatics Engineering
> - Collage					 : Politeknik Pos Indonesia


