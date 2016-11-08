<h3 align="center">NETWORK SECURITY</h3>
<h3 align="center">
“SNIFFING”
</h3>


<p align="center">
  <img src="https://github.com/nadiaaaAR/Keamanan-Jaringan/blob/master/img/images.png">
</p>


**1. Latar Belakang**

Sniffing adalah teknologi data intersepsi. Sniffer adalah program yang memonitor atau membaca semua lalu lintas jaringan yang lewat dan keluar melalui jaringan. Telnet, login kembali, FTP, NNTP, SMTP, HTTP, IMAP bahwa semua protokol rentan untuk mengendus karena mengirim data dan password dalam bentuk teks. Sniffing dapat menggunakan kedua cara legal atau ilegal seperti untuk lalu lintas jaringan memantau, keamanan jaringan dan untuk mencuri informasi seperti password, file dari jaringan. Sniffing dapat dilakukan baik dengan cara satu dari utilitas baris perintah dan lainnya adalah dari antarmuka GUI. Banyak insinyur jaringan; profesional keamanan dan bahkan kerupuk menggunakan teknik ini untuk mengendus jaringan. Teknik mengendus juga digunakan untuk hacking etis. Pada artikel ini, saya akan menjelaskan tentang sniffer dan bagaimana sniffer bekerja.
Komputer selalu berkomunikasi dengan mesin lainnya selama tugas normal seperti surfing web, file sharing, email dll komputer yang terhubung pada Local Area Network (LAN) berarti mereka berbagi koneksi dengan beberapa komputer lain. Ada dua jenis jaringan seperti jaringan bersama (menggunakan HUB) dan jaringan satu adalah Switched (menggunakan switch) sniffers kerja yang berbeda pada kedua jaringan. Dalam jenis jaringan bersama, semua host terhubung satu sama lain melalui hub dan mereka berbagi bandwidth yang sama. Dalam Bersama paket jaringan broadcast ke semua port. komputer Misalkan A ingin mengirim paket ke E Komputer maka komputer A mengirim paket pada jaringan dengan tujuan alamat MAC dari komputer E bersama dengan sumber alamat MAC tetapi dalam paket jaringan hub akan disiarkan ke setiap mesin port yang terhubung ke LAN. Jika hacker menjalankan alat sniffer pada salah satu mesin maka ia dapat dengan mudah mengambil data dan mengambil informasi berharga Anda tidak time.It umumnya wasit sebagai Man di tengah serangan metode sniffing ini benar-benar pasif dan sangat sulit untuk menemukan 
Dalam jenis ini jaringan semua host terhubung satu sama lain melalui switch. Beralih memelihara tabel setiap komputer MAC address.Switch beroperasi pada lapisan data link dari model OSI Layer. Switch tidak menyiarkan semua informasi pada jaringan. Switch memeriksa paket data untuk sumber dan tujuan alamat dan kemudian meneruskan paket data ke tujuan yang tepat. sehingga sulit untuk mengendus switch penyerang menggunakan teknik yang ia kirim palsu MAC Address untuk menipu switch. Penyerang menggunakan dua metode untuk mengendus switch jaringan ARP spoofing dan Mac Flooding





**2. Pembahasan**

**a.  Pengertian Sniffing**

Sniffing adalah teknologi data intersepsi. Sniffer adalah program yang memonitor atau membaca semua lalu lintas jaringan yang lewat dan keluar melalui jaringan. Telnet, login kembali, FTP, NNTP, SMTP, HTTP, IMAP bahwa semua protokol rentan untuk mengendus karena mengirim data dan password dalam bentuk teks.
Sniffing melibatkan menangkap, decoding, memeriksa dan menafsirkan informasi dalam sebuah paket jaringan pada jaringan TCP / IP. Tujuannya adalah untuk mencuri informasi, biasanya user ID, password, rincian jaringan, nomor kartu kredit, dll Sniffing umumnya disebut sebagai jenis "pasif" serangan, dimana penyerang bisa diam / terlihat pada jaringan. Hal ini membuat sulit untuk mendeteksi, dan karena itu adalah jenis yang berbahaya serangan.
Seperti yang sudah kita pelajari selama bulan-bulan sebelumnya, TCP / IP paket berisi informasi penting yang diperlukan untuk dua antarmuka jaringan untuk berkomunikasi satu sama lain. Ini berisi bidang-bidang seperti sumber dan tujuan alamat IP, port, nomor urut dan jenis protokol. Masing-masing bidang sangat penting untuk berbagai lapisan jaringan berfungsi, dan terutama untuk aplikasi Layer 7 yang menggunakan data yang diterima.
Sifatnya, protokol TCP / IP hanya dimaksudkan untuk memastikan bahwa paket dibangun, dipasang pada frame paket Ethernet, dan andal disampaikan dari pengirim ke penerima di jaringan. Namun, itu tidak secara default memiliki mekanisme untuk memastikan keamanan data. Dengan demikian, itu menjadi tanggung jawab dari lapisan jaringan atas untuk memastikan bahwa informasi dalam paket tersebut tidak dirusak.
Untuk memahami mengapa hacker mengendus, kita perlu tahu apa yang bisa mereka dapatkan dari jaringan. Gambar 1. menunjukkan lapisan OSI dan informasi hacker dapat mencuri di setiap lapisan dengan berhasil mengendus jaringan.
<p align="center">
  <img src="https://github.com/nadiaaaAR/Keamanan-Jaringan/blob/master/img/netsniffing1.jpg">
</p>
Proses sniffing digunakan oleh hacker baik untuk mendapatkan informasi secara langsung atau untuk memetakan rincian teknis dari jaringan dalam rangka untuk membuat serangan lebih lanjut. Hacker selalu mendukung mengendus, karena bisa dilakukan untuk waktu yang lama tanpa tertangkap.
penggunaan alat sniffer :<br>
**penggunaan etis**<br>
1. Packet menangkap<br>
2. Jaringan penggunaan lalu lintas dan analisis<br>
3. konversi Packet untuk analisis data<br>
4. tips Jaringan<br>
**penggunaan etis**<br>
1. Pengguna dan mencuri  Identitas dan password<br>
2. Email atau instant message data yang mencuri<br>
3. Packet spoofing dan data pencurian<br>
4. Moneter atau kerusakan reputasi<br>

Mengenai rincian teknis tentang bagaimana sniffing dilakukan, kita perlu ingat bahwa paket menangkap software selalu berjalan dalam mode promiscuous, dimana ia mampu mencegat dan menyimpan semua paket pada jaringan. Ini juga berarti bahwa, meskipun paket tersebut tidak dimaksudkan untuk antarmuka jaringan yang sniffer sedang berjalan, itu ditangkap, disimpan dan dianalisis.


**b.  Sniffing Active**

Ketika sniffing dilakukan pada jaringan diaktifkan, itu dikenal sebagai sniffing aktif. sniffing aktif bergantung pada suntikan paket ke dalam jaringan yang menyebabkan sniffing traffic.Active diperlukan untuk memotong segmentasi yang beralih provided.Switch mempertahankan Cache Arp jenis khusus mereka sendiri memori yang dikenal sebagai konten Memory adressable (CAM), mencatat yang host terhubung ke port.
Sniffer yang oprated di Data Link Layer dari model OSI. Ini berarti bahwa mereka tidak harus bermain dengan aturan yang sama seperti apllication dan jasa yang berada lebih jauh stack.Sniffer bisa ambil apa pun yang mereka lihat di kawat dan merekamnya untuk nanti review.They memungkinkan pengguna untuk melihat semua data yang ada di paket, bahkan informasi yang harus tetap tersembunyi.

**c.  Sniffing Pasive**

Hub melihat semua lalu lintas dalam domain.Sniffing tabrakan tertentu dilakukan pada hub dikenal sebagai passive sniffing.passive sniffing dilakukan ketika menggunakan adalah pada hub.Because pengguna pada hub, semua lalu lintas yang dikirim ke semua port. Semua Penyerang harus lakukan adalah mulai sniffer dan hanya menunggu kedepan seseorang di collision domain yang sama untuk mulai mengirim atau menerima domain data.Collision adalah area logis dari collision domain yang sama untuk mulai mengirim atau menerima domain data.Collision adalah logocal sebuah area jaringan di mana satu atau lebih paket data dapat saling bertabrakan.

**d.  Mendeteksi Sniffers**

Seperti disebutkan sebelumnya, karena sniffer bekerja diam-diam, sangat sulit untuk mendeteksi mereka pada jaringan. Namun demikian, beberapa trik yang dapat memberikan petunjuk untuk kehadiran sniffer mungkin. Ada dua cara untuk mendeteksi sniffer - berbasis jaringan berbasis host dan.
Dalam deteksi berbasis host, Anda dapat menggunakan utilitas kecil untuk mendeteksi jika NIC berjalan dalam modus promiscuous pada semua host di jaringan. Karena kebutuhan dasar untuk sniffer untuk bekerja adalah untuk menempatkan antarmuka jaringan di "membaca semua" mode, nonaktifkan dapat sangat efektif membantu mematikan sniffer liar.
Dalam hal deteksi berbasis jaringan, perangkat lunak anti-sniffer dapat dijalankan untuk mendeteksi keberadaan paket tanda tangan khusus. Dalam pendekatan lain, script dapat dijalankan untuk memeriksa setiap host jaringan untuk kehadiran sniffer diketahui, proses, dll modern anti-virus atau perangkat lunak anti-spyware yang mampu mendeteksi perangkat lunak mengendus dan nonaktifkan.

**e.  Perlindungan Dari Sniffers**

Sementara langkah pertama harus merancang sistem pertahanan perimeter ketat sementara menciptakan arsitektur jaringan, ada beberapa metode yang bisa dikerahkan untuk membuat infrastruktur yang kurang sniffer rawan. Trik berikut membantu mencapai itu untuk sebagian besar.
Menonaktifkan modus promiscuous hasil antarmuka jaringan dalam menutup sebagian software sniffer. Hal ini dapat dilakukan dengan menjalankan skrip admin sebagai pekerjaan sehari-hari di jaringan, atau menyebarkan kebijakan jaringan di tingkat host untuk mengontrol akses ke jaringan pengaturan konfigurasi kartu.
Menggunakan jaringan switched dapat mengurangi kemungkinan sniffer yang berjalan pada jaringan. Tidak seperti di jaringan hub, yang aktif dalam jaringan paket dikirim ke tujuan dan tidak terlihat oleh semua node - sehingga mengurangi kemungkinan seseorang mengendus itu di jalan. Juga, untuk administrator jaringan menjadi mudah untuk mendeteksi sniffers dengan berfokus pada segmen jaringan diaktifkan, satu per satu. Anti-sniffing alat dapat digunakan untuk mendeteksi modus antarmuka jaringan, serta berbagai proses dan software hadir pada server atau host jaringan. sistem deteksi intrusi modern memiliki ini sebagai fitur terintegrasi. enkripsi IPSec dapat digunakan untuk berbasis token keamanan paket dalam infrastruktur jaringan, jika data yang bersifat rahasia. IPSec menyediakan enkapsulasi data dan enkripsi standar yang tinggi, dan tersedia pada router modern, firewall dan komponen jaringan lainnya. Hampir semua sistem operasi yang mendukung IPSec, dan secara luas digunakan dalam infrastruktur TI yang serius. Untuk perlindungan lapisan sesi, SSL dan TLS dapat digunakan untuk mengenkripsi lalu lintas.




**3. Penutup**

**a. Kesimpulan**

Sniffing adalah teknologi data intersepsi. Sniffer adalah program yang memonitor atau membaca semua lalu lintas jaringan yang lewat dan keluar melalui jaringan. Telnet, login kembali, FTP, NNTP, SMTP, HTTP, IMAP bahwa semua protokol rentan untuk mengendus karena mengirim data dan password dalam bentuk teks. Sniffing dapat menggunakan kedua cara legal atau ilegal seperti untuk lalu lintas jaringan memantau, keamanan jaringan dan untuk mencuri informasi seperti password, file dari jaringan.

*b. Saran**

Selanjutnya untuk mendalami materi Sniffing dengan membaca sumber-sumber yang tersedia di buku maupun internet , dan  melakukan praktikum mandiri dengan apliaksi sniper yang tersedia.

-------

**Link Github** 	            :  https://github.com/nadiaaaAR/Keamanan-Jaringan<br>

**Referensi**	                :	 http://www.valencynetworks.com/articles/cyber-security-attacks-network-sniffing.html<br>

**Scan Plagiarisme**          : <br>
   
a. searchenginereport      :   https://drive.google.com/open?id=0B831iVXSuoJcbGl4cTdPeXRpLUE <br>
        
b. smallseotools	       :   https://drive.google.com/open?id=0B831iVXSuoJcNHduSl9uZ1V6WVk <br>

  
-------

> - Fullname 				 : Nadia Ayu Lestari Arifin
> - Nickname 				 : Nadia
> - NPM		 			     : 1144002
> - Class	 			     : D4 TI 3C
> - Department  		     : Informatics Engineering
> - Collage					 : Politeknik Pos Indonesia


