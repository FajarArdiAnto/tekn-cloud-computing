# Apa perbedaan antara IaaS, SaaS, dan Paas? 
* IaaS - Infrastructure-as-a-Service - Layanan cloud yang memungkinkan pengguna mendapatkan akses ke infrastruktur mereka sendiri - komputer, sumber daya jaringan, penyimpanan. Perlu dicatat bahwa ini biasanya sumber daya virtual, tetapi bisa jadi sumber daya nyata, fisik.

* PaaS - Platform-as-a-Service - Layanan cloud yang mengabstraksi infrastruktur (pengguna tidak bisa melihat komputer, loadbalancers, dll.) Melainkan menyediakan platform pengembangan perangkat lunak. Dimungkinkan untuk membuat kode dan menjalankan aplikasi pada PaaS dan sistem memastikan bahwa aplikasi memiliki infrastruktur yang diperlukan untuk membuatnya berjalan dan skala.

*SaaS - Software-as-a-Service - Layanan cloud yang memberikan pengguna akses ke perangkat lunak dengan layanan mandiri, sesuai permintaan. Ini bisa berupa aplikasi tunggal atau memberikan katalog perangkat lunak yang dapat dipilih pengguna.


# Arsitektur Platform SAAS (Perangkat Lunak sebagai Layanan)

Perangkat lunak sebagai layanan adalah model lisensi dan pengiriman perangkat lunak di mana perangkat lunak dilisensikan berdasarkan berlangganan dan di-host secara terpusat. Pengguna dapat mengaksesnya dengan bantuan browser web.

SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan pesan, perangkat lunak manajemen, virtualisasi dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS).

Penyedia SaaS menyimpan aplikasi dan data secara terpusat - tambalan penyebaran. Mereka meningkatkan ke aplikasi secara transparan, memberikan akses ke pengguna akhir melalui Internet. Banyak vendor menyediakan API yang digunakan pengembang untuk membuat aplikasi komposit. Ini berisi berbagai mekanisme keamanan untuk keamanan data selama transmisi dan penyimpanan.

Ada dua varietas utama SaaS:

* SaaS Vertikal
Perangkat Lunak yang menjawab kebutuhan industri tertentu (mis. Perangkat lunak untuk kesehatan, pertanian, real estat, industri keuangan)
* SaaS Horisontal
Produk-produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.


# SAAS (Software as a Service) Platform Architecture

Pada saat inilah kita melihat perubahan paradigma dalam cara di mana perangkat lunak sedang dibangun dan tersedia untuk konsumen akhir. Konsumen tidak lagi harus mengunduh dan menginstal aplikasi ke mesin mereka untuk menjalankannya. Didukung oleh cloud computing, konsumen dan bisnis dapat menggunakan layanan melalui web hanya dengan beberapa klik mouse. SaaS dilahirkan - Perangkat Lunak sebagai Layanan.

SaaS juga merupakan salah satu pilar utama komputasi awan. Sebuah ledakan dalam komputasi Cloud, didorong oleh penyedia cloud seperti Microsoft dengan Azure atau Amazon dengan AWS, telah melihat pertumbuhan produk dan layanan lain yang disampaikan melalui internet seperti:
* Infrastruktur sebagai Layanan
* Platform sebagai Layanan
* Pembelajaran Mesin sebagai Layanan dan banyak lagi!

Setiap pembaruan atau tambalan untuk aplikasi SaaS semuanya ditangani oleh penyedia. Pelanggan tidak perlu mengunduh pemutakhiran atau menginstal ulang versi baru suatu produk saat perangkat lunak dikirimkan melalui internet.

-Fitur dan Manfaat Utama dari Platform SaaS
Solusi SaaS memiliki fitur berbeda dengan aplikasi yang lebih tradisional yang diinstal pada desktop Anda misalnya, berikut adalah beberapa manfaat lain yang dapat diberikan oleh penggunaan produk berbasis SaaS.

* Kesederhanaan
Aplikasi perangkat lunak yang dirancang sebagai solusi SaaS biasanya diakses melalui web melalui berbagai jenis perangkat. Kemajuan dalam bahasa pemrograman sisi klien seperti JavaScript telah menghasilkan antarmuka web yang lebih intuitif dan dengan demikian, membuat penggunaan aplikasi yang dikirim melalui internet mudah digunakan seperti rekan-rekan desktop mereka.

*Ekonomis
Model pembayaran biaya subskrip bulanan atau tahunan memudahkan bisnis untuk menganggarkan dana, ditambah dengan biaya pemasangan infrastruktur nol, mudah untuk melihat bagaimana memilih menggunakan solusi SaaS dapat menghemat uang bisnis.

* Keamanan
Keamanan adalah aspek penting dari solusi pengembangan perangkat lunak dan platform SaaS tidak berbeda. Sebagai konsumen aplikasi yang dirancang menggunakan SaaS, Anda tidak perlu khawatir dengan bagaimana data Anda dikunci. Itu dipegang dengan aman di awan!

* Kesesuaian
Dengan penginstalan perangkat lunak tradisional, pembaruan dan tambalan terkadang membutuhkan banyak waktu dan uang. Ini terutama benar dalam perusahaan. Selain itu, perbedaan versi antara anggota tim dari tenaga kerja Anda dapat menyebabkan masalah kompatibilitas dan bahkan lebih banyak waktu terbuang. Namun, dengan SaaS, pelanggan dapat log-on ke layanan yang sudah ditingkatkan.

# How to build a cloud-based SaaS Application

* Bangun untuk cloud
Saat membangun aplikasi SaaS (global), kemungkinan besar Anda membangunnya di cloud. The awan memiliki banyak keuntungan - memikirkan skalabilitas - kontras dengan lingkungan server lokal.

Selain kemampuan dan keterampilan pribadi, pilihan bahasa pemrograman Anda akan dipengaruhi oleh kemungkinan masing-masing bahasa. Ada berbagai bahasa pemrograman (modern) di luar sana sehingga sulit untuk memilih yang benar.

* Basis data yang sempurna
Jadi, salah satu hal pertama dalam daftar Anda akan mencakup pemasangan basis data. Kami merekomendasikan penggunaan basis data berorientasi dokumen . Database dokumen sangat berbeda dengan konsep tradisional 

* database relasional.
Mengapa memilih basis data berorientasi dokumen?
Database dokumen mendapatkan informasi tipenya dari data itu sendiri. Dengan demikian setiap instance data dapat berbeda dari yang lain.

Mengapa kami memilih MongoDB? Karena MongoDB adalah database berorientasi dokumen yang memberikan kinerja tinggi, ketersediaan tinggi, dan skalabilitas mudah. Ya. Selain kinerja (yang menginginkan database yang lambat?), Skalabilitas adalah faktor terpenting bagi kami sebagai bisnis SaaS global .


