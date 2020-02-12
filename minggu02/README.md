#LUSI PADMAWATI - 175610045
Praktikum Teknologi Cloud Computing - Minggu 2
===============================================
##LATIHAN 1 Perbedaan Saas, Iaas, Paas
-----------------------------------------------
SaaS: Perangkat Lunak sebagai Layanan
Ini berarti menjalankan aplikasi di cloud publik. Pengguna menggunakan aplikasi ini melalui Internet. Aplikasi ini dikelola oleh Penyedia Layanan. Beberapa mis., Penyedia Layanan, adalah SalesForce, Microsoft (Office 365), Oracle, Google (Google Apps), dll. Salesforce adalah perusahaan pertama yang mengubah dunia Saas, dan sejak saat itu, perusahaan lain telah melihat potensi di pasar ini dan meluncurkan aplikasi mereka.

Iaas: Infrastruktur sebagai Layanan
Ini memberikan lingkungan bagi pengembang untuk membangun aplikasi yang dapat digunakan pengguna. IaaS meliputi: -Pengguna membuat mesin virtual (VM) sesuai permintaan.Amazon (AWS) adalah vendor terkemuka dalam menyediakan IaaS.

PaaS: Platform sebagai Layanan
Ini agak mirip dengan IaaS tetapi perbedaannya adalah:Pengembang menyediakan aplikasi yang dijalankan platform.Mereka tidak secara langsung membuat VM. Anda akan berpikir bahwa PaaS sederhana dan itulah sebabnya banyak digunakan. Tetapi ini tidak benar. IaaS adalah 10 kali populer dari PaaS. Pengembang ingin memiliki kontrol lebih besar atas sumber daya.

###SAAS (Software As A service ) Platform Arsitekture
SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan pesan, perangkat lunak manajemen, virtualisasi dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS).

Penyedia SaaS menyimpan aplikasi dan data secara terpusat - tambalan penyebaran. Mereka meningkatkan ke aplikasi secara transparan, memberikan akses ke pengguna akhir melalui Internet. Banyak vendor menyediakan API yang digunakan pengembang untuk membuat aplikasi komposit. Ini berisi berbagai mekanisme keamanan untuk keamanan data selama transmisi dan penyimpanan.
Arsitektur AAS:

Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. Aplikasi ini diinstal pada banyak mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). Dalam beberapa kasus, versi kedua aplikasi diatur untuk menawarkan kelompok pelanggan tertentu dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian. Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode unik. Meskipun pengecualian, beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola secara efektif sejumlah besar pelanggan di tempat. Apakah multitenancy merupakan komponen yang diperlukan untuk perangkat lunak-sebagai-layanan adalah topik kontroversi.

Ada dua varietas utama SaaS:

SaaS Vertikal
Perangkat Lunak yang menjawab kebutuhan industri tertentu (mis., Perangkat lunak untuk kesehatan, pertanian, real estat, industri keuangan)
SaaS Horisontal
Produk-produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.
Manfaat SAAS:

Ini menawarkan peluang besar bagi organisasi dari semua ukuran untuk mengalihkan risiko akuisisi perangkat lunak, dan untuk memindahkan TI dari pusat biaya reaktif menjadi bagian perusahaan yang proaktif dan bernilai tambah. Secara tradisional, menyebarkan sistem perangkat lunak skala besar telah menjadi tugas utama. Menyebarkan sistem ini di perusahaan besar membutuhkan biaya lebih besar. Waktu, staf, dan persyaratan anggaran untuk penyebaran sebesar ini mewakili risiko yang signifikan bagi organisasi dalam ukuran berapa pun, dan sering kali menempatkan perangkat lunak seperti itu di luar jangkauan organisasi yang lebih kecil yang jika tidak dapat diturunkan darinya banyak utilitas. Model pengiriman berdasarkan permintaan mengubah beberapa hal ini. Aplikasi SaaS tidak memerlukan penyebaran infrastruktur besar di lokasi klien. Ini menghilangkan atau secara drastis mengurangi komitmen sumber daya dimuka.

####Arsitektur Platform SAAS (Perangkat Lunak sebagai Layanan)
Apa itu Platform SaaS?
SaaS juga merupakan salah satu pilar utama komputasi awan. Sebuah ledakan dalam komputasi Cloud, didorong oleh penyedia cloud seperti Microsoft dengan Azure atau Amazon dengan AWS, telah melihat pertumbuhan produk dan layanan lain yang disampaikan melalui internet seperti:
1. Infrastruktur sebagai Layanan
2. Platform sebagai Layanan
3. Pembelajaran Mesin sebagai Layanan

Setiap pembaruan atau tambalan untuk aplikasi SaaS semuanya ditangani oleh penyedia. Pelanggan tidak perlu mengunduh pemutakhiran atau menginstal ulang versi baru suatu produk saat perangkat lunak dikirimkan melalui internet.

1. Konsumen

Dari perspektif konsumen, produk SaaS adalah salah satu cara termudah untuk menggunakan layanan atau produk digital. Anda cukup mengaksesnya melalui web, membayar layanan dan menggunakannya! Dalam beberapa tahun terakhir kami telah melihat kemunculan ribuan produk SaaS yang ditargetkan untuk konsumen seperti:

-Netflix
-Microsoft Office 365
-Amazon Prime
-Indonesia
-Facebook
-Google Documents

2. Bisnis

Dari perspektif bisnis, produk perangkat lunak yang dikirimkan “sebagai layanan” memungkinkan perusahaan untuk menawarkan produk mereka dalam skala global, sementara juga memungkinkan mereka untuk mempertahankan kontrol keseluruhan atas produk mereka. Beberapa manfaat lain dari penerapan arsitektur SaaS dalam bisnis termasuk, tetapi tidak terbatas pada:

-Mengurangi waktu ke pasar
-Biaya perawatan lebih rendah
-Pembaruan yang lebih mudah

Beberapa teknologi B2B yang paling menarik saat ini sedang disampaikan menggunakan arsitektur SaaS. Sebagai contoh, Microsoft dan koleksi mereka Cognitive Services APIs telah secara efektif mendemokratisasikan apa yang sebelumnya merupakan algoritma pembelajaran mesin, ke dalam layanan web yang mudah dikonsumsi yang dikirim dengan teknologi cloud.

Bisnis dapat dengan mudah mengintegrasikan komponen SaaS ini ke dalam aplikasi mereka yang ada dan menambah fungsionalitas yang mereka tawarkan kepada pelanggan mereka. Bisnis tidak perlu khawatir tentang debugging atau pengujian komponen SaaS karena itu semua sudah ditangani oleh vendor.

#####Cara membangun aplikasi SaaS berbasis cloud
Bangun untuk cloud
Jadi, hal pertama yang pertama.

Bahasa pemrograman
 menggunakan Python. Python adalah bahasa pemrograman yang banyak digunakan, dirancang untuk menekankan keterbacaan kode-nya. Python dapat melakukan banyak hal. Apa pun aplikasi web yang ingin Anda bangun, kemungkinan ada kerangka kerja untuknya dengan Python.
mungkin dengan Python.

Basis data yang sempurna
Kami merekomendasikan penggunaan basis data berorientasi dokumen. Database dokumen sangat berbeda dengan konsep tradisional database relasional. Database dokumen mendapatkan informasi tipenya dari data itu sendiri. Dengan demikian setiap instance data dapat berbeda dari yang lain. Ini memungkinkan lebih banyak fleksibilitas, terutama ketika berhadapan dengan perubahan. Dan sering mengurangi ukuran basis data.

Singkatnya, konsep DOB menawarkan pengalaman yang lebih kaya dengan teknik pemrograman modern.

MongoDB - database untuk aplikasi web. MongoDB adalah database berorientasi dokumen yang memberikan kinerja tinggi, ketersediaan tinggi, dan skalabilitas mudah. Ya. Selain kinerja (yang menginginkan database yang lambat?), Skalabilitas adalah faktor terpenting bagi kami sebagai bisnis SaaS global.

Banyak pendiri SaaS bertujuan untuk meningkatkan skala bisnis mereka. Selain mengubah skala produk Anda dari perspektif bisnis, Anda tidak boleh melupakan masalah teknis. Menskalakan teknologi Anda dengan MongoDB cukup mudah (ok, setidaknya lebih mudah dibandingkan dengan database lain). Dengan sharding otomatis, Anda dapat mendistribusikan data di berbagai mesin. Sharding adalah metode untuk menyimpan data Anda di beberapa mesin. Dan MongoDB menggunakan sharding untuk mendukung penyebaran dengan dataset besar.
######  2 SOFTWARE SAAS
1. JIRA
JIRA adalah perangkat lunak manajemen proyek yang dikirimkan oleh Atlassian dan dapat dibeli secara berlangganan.

2. Dropbox
Dropbox adalah alat SaaS berbagi file yang memungkinkan banyak pengguna dalam grup atau organisasi untuk mengunggah dan mengunduh berbagai file.

#######