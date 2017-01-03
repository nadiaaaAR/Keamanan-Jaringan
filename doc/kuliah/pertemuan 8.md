<h3 align="center">NETWORK SECURITY</h3>
<h3 align="center">
“TUTORIAL ISNTALL SNORT Di centOS”
</h3>


<p align="center">
  <img src="https://github.com/nadiaaaAR/Keamanan-Jaringan/blob/master/img/snort.jpg">
</p>


**1. Latar Belakang**

Centos adalah distribusi Linux yang mencoba untuk memberikan gratis, kelas enterprise, komunitas yang didukung platform komputasi fungsional kompatibel dengan sumber hulu, Red Hat Enterprise Linux (RHEL).
Snort berdasarkan libpcap (untuk capture paket perpustakaan), alat yang banyak digunakan di sniffer lalu lintas TCP / IP dan analisis. Melalui analisis protokol dan pencarian konten dan pencocokan, Snort mendeteksi metode serangan, termasuk penolakan layanan, buffer overflow, serangan CGI, scan port siluman, dan probe SMB. Ketika perilaku yang mencurigakan terdeteksi, Snort mengirimkan real-time peringatan ke syslog, file 'alert' terpisah, atau jendela pop-up.
NSS Group, keamanan jaringan organisasi pengujian Eropa, diuji Snort bersama dengan sistem deteksi intrusi (IDS) produk dari 15 vendor besar termasuk Cisco, Computer Associates, dan Symantec. Menurut NSS, Snort, yang adalah satu-satunya open source freeware produk diuji, jelas keluar-dilakukan produk proprietary.



**2. Pembahasan**

**a.  Pengertian Firewall**

Jaringan IDS atau NIDS melakukan seperti namanya, memonitor data paket yang dikirim dan diterima melalui antarmuka jaringan tertentu itu dikonfigurasi untuk. Hal ini bertujuan untuk menangkap ancaman menargetkan kerentanan sistem anda menggunakan deteksi dan analisis protokol teknologi berbasis signature. software NIDS ketika diinstal dan dikonfigurasi dengan benar dapat mengidentifikasi serangan terbaru, infeksi malware, sistem dikompromikan, dan pelanggaran kebijakan jaringan.
Snort adalah salah satu yang paling umum digunakan untuk IDS berbasis jaringan. Ini adalah sistem open source yang tersedia untuk banyak platform, ringan, dan dapat nyaman diinstal bahkan di terkecil dari contoh server cloud. Meskipun Snort mampu lebih dari sekedar jaringan pemantauan, panduan ini menunjukkan bagaimana untuk mengkonfigurasi dan menjalankan Snort dalam mode NIDS dengan setup dasar yang nanti dapat memperluas. 
Mempersiapkan Server 
Menyiapkan konfigurasi Snort dasar cukup sederhana tetapi membutuhkan beberapa langkah untuk menyelesaikan. Anda harus terlebih dulu menginstal semua perangkat lunak prasyarat untuk siap cloud server Anda untuk menginstal Snort sendiri. Pasang membutuhkan perpustakaan dengan perintah berikut
sudo yum install gcc flex bison zlib libpcap pcre libdnet libdnet-devel tcpdump
Dengan prasyarat terpenuhi, berikutnya adalah menginstal Snort. Pada CentOS 7 Anda dapat menggunakan paket mengelola yum untuk menginstal versi terbaru langsung, yang menyederhanakan proses setup jauh, hanya memeriksa bagian bawah untuk menginstal Snort dengan yum. sistem yang lebih tua harus men-download dan menginstal program secara manual dari sumber.

**Instalasi dengan yum**

Snort memberikan paket rpm nyaman untuk CentOS 7, yang dapat diinstal hanya dengan perintah di bawah ini. Snort sendiri menggunakan sesuatu yang disebut Data Acquisition perpustakaan (DAQ) untuk melakukan panggilan abstrak untuk packet capture perpustakaan. Periksa nomor versi terbaru dari website Snort, jika versi yang lebih baru dari DAQ atau Snort tersedia cukup mengganti nomor versi di perintah berikut dengan opsi terbaru.

**Instalasi dari Source**

Menyiapkan Snort dari kode sumber terdiri dari beberapa langkah: download kode, mengkonfigurasi, kompilasi kode dan terakhir menginstal itu. Pertama membuat folder download sementara untuk direktori home Anda dan kemudian bergerak ke dalamnya dengan perintah ini

mkdir ~/snort_src
cd ~/snort_src

Download paket terbaru sumber DAQ dari website Snort dengan perintah wget bawah, ganti nomor versi jika ada sumber yang lebih baru yang tersedia

wget https://www.snort.org/downloads/snort/daq-2.0.6.tar.gz

Download hanya akan memakan waktu beberapa detik, ekstrak setelah selesai kode sumber dan melompat ke dalam direktori baru dengan perintah berikut

tar -xvzf daq-2.0.6.tar.gz
cd daq-2.0.6

Jalankan script konfigurasi dengan default, kemudian gunakan membuat untuk mengkompilasi program dan kemudian akhirnya memasang DAQ

./configure
make
sudo make install

Dengan DAQ yang diinstal Anda bisa memulai dengan Snort, mengubah kembali ke folder download

cd ~/snort_src

Kemudian download kode sumber Snort dengan wget, memeriksa nomor versi terbaru dari situs Snort dan menggantinya di perintah berikut jika diperlukan.

wget https://www.snort.org/downloads/snort/snort-2.9.8.0.tar.gz

Setelah download selesai, ekstrak sumber dan mengubah ke dalam direktori baru dengan perintah ini

tar -xvzf snort-2.9.8.0.tar.gz
cd snort-2.9.8.0

Kemudian mengkonfigurasi instalasi dengan modus Sourcefire diaktifkan, jalankan make dan make install.

./configure --enable-sourcefire
make
sudo make install




**3. Penutup**

**a. Kesimpulan**

Snort adalah salah satu yang paling umum digunakan untuk IDS berbasis jaringan. Ini adalah sistem open source yang tersedia untuk banyak platform, ringan, dan dapat nyaman diinstal bahkan di terkecil dari contoh server cloud. Meskipun Snort mampu lebih dari sekedar jaringan pemantauan, panduan ini menunjukkan bagaimana untuk mengkonfigurasi dan menjalankan Snort dalam mode NIDS dengan setup dasar yang nanti dapat memperluas.

*b. Saran**

Selanjutnya untuk mendalami materi Snort  dengan membaca sumber-sumber yang tersedia di buku maupun internet , dan  melakukan praktikum mandiri.

-------

**Link Github** 	            :  https://github.com/nadiaaaAR/Keamanan-Jaringan<br>

**Referensi**	                :  https://www.upcloud.com/support/installing-snort-on-centos/ <br>

**Scan Plagiarisme**          : <br>
   
a. searchenginereport     :   https://drive.google.com/open?id=0B831iVXSuoJccUhTSVRWanZaUzA<br>
        
                       
b. smallseotools	      :   https://drive.google.com/open?id=0B831iVXSuoJceV9yYlUyVGVHd3c<br>

  
-------

> - Fullname 				 : Nadia Ayu Lestari Arifin
> - Nickname 				 : Nadia
> - NPM		 				 : 1144002
> - Class	 				 : D4 TI 3C
> - Department  		     : Informatics Engineering
> - Collage					 : Politeknik Pos Indonesia


