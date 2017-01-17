<h3 align="center">NETWORK SECURITY</h3>
<h3 align="center">
”REMOTE AUTHENTICATION DIAL-IN PENGGUNA SERVICE (RADIUS)”
</h3>


<p align="center">
  <img src="https://github.com/nadiaaaAR/Keamanan-Jaringan/blob/master/img/radius.JPG">
</p>


**1. Latar Belakang**

Remote Authentication Dial-In Pengguna Service (RADIUS) adalah klien server protokol / dan software yang memungkinkan server akses remote untuk berkomunikasi dengan server pusat untuk mengotentikasi dial-in pengguna dan mengotorisasi akses mereka ke sistem atau layanan yang diminta. RADIUS memungkinkan perusahaan untuk mempertahankan profil pengguna di database pusat bahwa semua server remote dapat berbagi. Ini memberikan keamanan yang lebih baik, memungkinkan perusahaan untuk mengatur kebijakan yang dapat diterapkan pada titik jaringan tunggal diberikan. Memiliki layanan pusat juga berarti bahwa lebih mudah untuk melacak penggunaan untuk penagihan dan untuk menjaga statistik jaringan. Dibuat oleh Livingston (sekarang dimiliki oleh Lucent), RADIUS adalah de facto standar industri yang digunakan oleh sejumlah perusahaan produk jaringan dan merupakan standar IETF diusulkan.



**2. Pembahasan**
**A.	Remote Authentication Dial-In User Service (RADIUS)**

RADIUS adalah layanan keamanan untuk otentikasi dan otorisasi pengguna dial-up. Sebuah jaringan perusahaan yang khas mungkin memiliki server akses melekat kolam modem, bersama dengan server RADIUS untuk menyediakan layanan otentikasi. pengguna remote dial ke server akses, dan server akses mengirimkan permintaan otentikasi ke server RADIUS. RADIUS Server mengotentikasi pengguna dan wewenang akses ke sumber daya jaringan internal. pengguna jarak jauh adalah klien ke server akses dan server akses klien ke server RADIUS. RADIUS pada awalnya dikembangkan oleh Livingston Enterprises untuk seri portmaster mereka server akses jaringan. Lucent Technologies membeli Livingston pada Oktober 1997, dan kini mengklaim software itu "diciptakan oleh Access Bisnis Unit Remote dari Lucent Technologies pada tahun 1992." Sisa dari topik ini mengacu pada deskripsi RADIUS disediakan oleh Lucent. Perhatikan bahwa RADIUS merupakan protokol terbuka dan didistribusikan sebagai kode sumber. Hal ini didefinisikan dalam RFC Internet berikut. Lihat "NAS (Network Access Server)" untuk RFC terkait. RFC 2139 (RADIUS Akuntansi, April 1997) RFC 2865 (Remote Authentication Dial Dalam Pengguna Jasa (RADIUS), Juni 2000) Karena RADIUS terbuka, dapat disesuaikan untuk bekerja dengan produk keamanan pihak ketiga atau sistem keamanan proprietary. Server akses yang mendukung protokol client RADIUS dapat berkomunikasi dengan server RADIUS. RADIUS sering disebut sebagai RADIUS AAA, mengacu pada fungsi otentikasi, otorisasi, dan akuntansi. "Akuntansi" mengacu pada kemampuan RADIUS untuk mengumpulkan informasi tentang sesi pengguna yang dapat diolah untuk penagihan dan analisis jaringan. Sistem otentikasi RADIUS dasar menggunakan database pengguna sendiri, tetapi sumber-sumber informasi pengguna termasuk UNIX file password, Sun NIS (Network Information Service), dan direktori yang dapat diakses melalui LDAP (Lightweight Directory Access Protocol). Fitur yang paling penting dari RADIUS adalah model keamanan yang didistribusikan. Pada dasarnya, server komunikasi (akses server atau NAS) terpisah dari server otentikasi. Pendekatan ini lebih terukur dan aman. Informasi akun pengguna disimpan pada server RADIUS pusat yang dapat diakses oleh sejumlah server akses. Pendekatan didistribusikan Hal ini penting untuk ISP besar yang menangani ratusan atau ribuan account dial-up dari beberapa server akses. Contoh digambarkan pada Gambar R-1


**B.	Cara Kerja Remote Authentication Dial-In User Service (RADIUS)**

RADIUS menggunakan konsep AAA (Authentication, Authorization, Accounting) yaitu :<br>

•	Authentication<br>
<p>Authentication digunakan untuk membatasi pengguna yang tidak memiliki hak akses agar tidak masuk ke dalam jaringan. Jika pengguna ingin masuk ke jaringan tersebut maka harus diidentifikasi terlebih dahulu agar administrator mengetahui apakah pengguna tersebut memiliki hak akses atau tidak untuk masuk. Metode yang paling umum digunakan untuk mengetahui pengguna yang mengakses jaringan adalah dengan login menggunakan password.</p>
•	Authorization<br>
<p>Authorization adalah proses lanjutan dari authentication, yaitu memberikan batasan-batasan hak untuk mengakses jaringan, agar pengguna hanya mengakses sesuai hak akses yang dimilikinya. Metode yang paling sering digunakan untuk memberikan pembatasan ini adalah dengan menggunakan atribut yang dirangkai untuk menghasilkan kebijakan tentang hak akses pengguna yang telah disesuaikan dengan informasi yang ada di database.</p>
•	Accounting<br>
<p>Accounting digunakan untuk mengetahui informasi berapa lama pengguna terkoneksi dengan jaringan, dan informasi berapa besar data transaksi komunikasi yang melalui jaringan tersebut. Informasi ini sangat berguna untuk pengguna dan administrator untuk membuat laporan pemakaian, menganalisis karakteristik jaringan, melakukan proses auditing, dan lain-lain. </p>



**3. Penutup**

**a. Kesimpulan**

Remote Authentication Dial-In Pengguna Service (RADIUS) adalah klien server protokol / dan software yang memungkinkan server akses remote untuk berkomunikasi dengan server pusat untuk mengotentikasi dial-in pengguna dan mengotorisasi akses mereka ke sistem atau layanan yang diminta. RADIUS menggunakan konsep AAA (Authentication, Authorization, Accounting).

*b. Saran**

Selanjutnya untuk mendalami materi Remote Authentication Dial-In Pengguna Service (RADIUS)  dengan membaca sumber-sumber yang tersedia di buku maupun internet , dan  melakukan praktikum mandiri.

-------

**Link Github** 	            :  https://github.com/nadiaaaAR/Keamanan-Jaringan<br>

**Referensi**	                :  http://www.cisco.com/c/en/us/support/docs/security-vpn/remote-authentication-dial-user-service-radius/12433-32.html  <br>

**Scan Plagiarisme**          : <br>
   
a. searchenginereport     :   https://drive.google.com/open?id=0B831iVXSuoJcRThlUWUtbG84X0E  <br>
        
                       
b. smallseotools	      :   https://drive.google.com/open?id=0B831iVXSuoJccHhjQ0lKR3dyM1k<br>

                   
  
-------

> - Fullname 				 : Nadia Ayu Lestari Arifin
> - Nickname 				 : Nadia
> - NPM		 				 : 1144002
> - Class	 				 : D4 TI 3C
> - Department  		     : Informatics Engineering
> - Collage					 : Politeknik Pos Indonesia


