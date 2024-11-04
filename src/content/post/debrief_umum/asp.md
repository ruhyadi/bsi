## Strategi

Unit kerja IT Application Support Group (ASP) adalah unit baru yang terbentuk dari pemekaran IT & Digital Development Group (IDG). Tugas utama ASP adalah memberikan dukungan operasional untuk aplikasi yang telah diimplementasikan oleh IDG, memastikan aplikasi tersebut berjalan dengan baik dan memenuhi kebutuhan pengguna.

Strategi ASP tercermin dalam tahapan SDLC (Software Development Life Cycle) yang meliputi Test Management Plan (TMP), Testing (SIT, UAT, Performance testing), Release Control Board (RCB), Product Trial Run (PTR), dan Post Implementation Review (PIR). Berikut adalah rincian strategi ASP:

1. Test Management Plan (TMP): Menyusun rencana pengujian yang menyeluruh untuk memastikan semua aspek pengujian tercakup.
2. System Integration Testing (SIT): Memastikan bahwa berbagai komponen atau sistem yang berbeda dapat bekerja bersama dengan baik.
3. User Acceptance Testing (UAT): Memastikan bahwa sistem atau aplikasi memenuhi kebutuhan dan persyaratan bisnis pengguna akhir.
4. Performance Testing: Mengukur kinerja sistem atau aplikasi di bawah beban kerja tertentu untuk memastikan kecepatan, skalabilitas, dan stabilitas.
5. Release Control Board (RCB): Mengelola dan mengontrol rilis perangkat lunak atau sistem untuk memastikan kualitas dan kesiapan sebelum diterapkan ke lingkungan produksi.
6. Product Trial Run (PTR): Mengidentifikasi dan memperbaiki masalah potensial dalam kondisi yang mendekati lingkungan produksi sebelum peluncuran penuh.
7. Post Implementation Review (PIR): Mengevaluasi keberhasilan dan efektivitas implementasi sistem atau proyek.

## Fungsi Peran

Unit kerja ASP terdiri dari 9 departemen yang dikelompokkan menjadi 4 bagian utama: Subject Matter Expert (SME), IT Testing & Quality Assurance, IT Information & Data Services, dan IT Release Management & Testing. Tanggung jawab utama ASP adalah sebagai Subject Matter Expert (SME) yang menangani perbaikan (troubleshoot) isu-isu yang terjadi di production. Berikut adalah gambaran fungsi peran dari masing-masing bagian:

1. Subject Matter Expert (SME): Departemen ini merupakan cerminan dari masing-masing departemen IDG, bertugas sebagai pemegang pengetahuan aplikasi dan memberikan dukungan operasional terhadap aplikasi yang telah diimplementasikan.
2. IT Testing & Quality Assurance: Bertugas melakukan pengujian dan quality assurance terhadap aplikasi, baik saat tahap pengembangan maupun sebelum produksi.
3. IT Information & Data Services: Bertanggung jawab memberikan dukungan terhadap isu-isu yang terkait dengan data (data warehouse, data migration, dll) di production.
4. IT Release Management & Testing: Bertugas melakukan manajemen rilis dan pemantauan terhadap aplikasi yang telah diimplementasikan.

### IT Core Banking System Services

Departemen IT Core Banking System Services memiliki tugas utama untuk menerima dan memperbaiki masalah yang muncul dalam sistem Core Banking yang digunakan oleh BSI, seperti transaksi dan setor tunai. Sistem Core Banking yang digunakan oleh BSI yakni Temenos 24 atau yang biasa disingkat T24. Departemen ini juga bertugas untuk mengimplementasikan sistem inti perbankan atau melakukan peningkatan pada sistem yang sudah ada, dan juga melakukan maintenance pada sistem untuk mencegah terjadinya gangguan. Memberikan dukungan teknis kepada pengguna sistem, baik internal maupun eksternal juga merupakan tanggung jawab dari departemen ini. Pengintegrasian sistem inti dengan sistem-sistem lain yang digunakan oleh bank, seperti sistem ATM, Net banking, dan Mobile banking juga merupakan tugas dari departemen ini. Departemen ini juga bertugas untuk menjaga konektivitas yang baik dengan sistem surrounding. Aplikasi yang baru dan hendak dihubungkan ke sistem Core Banking tidak disambungkan atau dimasukkan langsung ke dalam sistem T24, namun ia dimasuklkan ke dalam Temenos Web Service dimana ia baru akan dihubungkan dengan Core Banking.

### IT Digital Channel Services

Departemen IT Digital Channel Services bertugas untuk menerima dan memperbaiki masalah yang muncul dalam channel-channel digital yang ada di BSI. Tugas utama departemen ini yakni untuk membangun dan mengelola platform digital, mengintegrasikan sistem, seperti sistem Core Banking, dengan channel-channel digital baru, serta mengembangkan fitur-fitur baru dan layanan digital yang inovatif untuk memenuhi kebutuhan nasabah. Channel digital ini termasuk SuperApps BYOND yang baru rilis secara terbatas. Digital channel yang digunakan dalam SuperApps dilewatkan ke ESB terlebih dahulu sebelum menuju ke sistem Core Banking. Jika terjadi error dalam transaksi melewati channel digital, departemen akan memeriksa log yang muncul dari transaksi tersebut. Jika tidak ketemu maka harus dilakukan query yang detail hingga ke menit dan detik dimana transaksi tersebut dilakukan agar log dari permasalahan tersebut dapat terbaca. Saat inidepartemen sedang memastikan channel-channel digital yang dimiliki oleh SuperApps BYOND dapat berjalan dengan benar dalam environment production yang terbatas dan jika terjadi masalah maka root cause dapat diidentifikasi dengan tepat dan penanganan dapat cepat dilakukan.

### IT Testing & Quality Assurance

Departemen IT Testing & Quality Assurance memiliki tugas utama untuk melakukan proses pengujian dari aplikasi / software yang akan dirilis. Dalam prosesnya, departemen akan mengacu pada TMP yang telah disusun untuk proses pengujian. Departemen ini memiliki test script yang mengcover hampir seluruh kemungkinan yang terjadi saat software digunakan oleh user. Kesalahan atau bug yang muncul dapat disebut sebagai defect. Defect yang muncul akan diberi keterangan detailnya beserta bukti eksekusi dan hasil testing kemudian dikumpulkan dan dilaporkan kembali agar bisa diperbaiki oleh tim development. Tim development kemudian akan memvalidasi defect yang muncul apakah sesuai dengan pelaporan dan kemudian jika terkonfirmasi maka dilakukan proses perbaikan program. Setelah itu akan diserahkan kembali ke tester agar diperiksa kembali.

### IT Release Management & Testing

Departemen IT Release Management & Testing berperan sebagai representasi ASP dalam Release Control Board (RCB), yakni komite yang bertanggung jawab untuk mengesahkan atau membuat keputusan rilis software. RCB biasanya terdiri dari perwakilan dari berbagai departemen, dan bertugas untuk membuat rencana rinci tentang bagaimana proses rilis akan diterapkan, mengkoordinasikan berbagai tim yang terlibat dalam proses rilis, dan memantau proses rilis untuk mengidentifikasi dan mengatasi masalah yang mungkin terjadi. Selain itu, tanggung jawab dan kewenangan untuk melakukan performance testing dari aplikasi yang akan dideploy juga ada di departemen ini. Departemen ini juga bertugas untuk memantau dan memonitoring kelancaran jalannya aplikasi.

### IT Financing & Collection Services

Departemen IT Financing & Collection Services bertugas untuk menerima dan memperbaiki masalah yang muncul dalam sistem pembiayaan dan collection yang digunakan oleh BSI. Departmen ini juga memiliki decision engine, yakni sebuah tools yang dapat menentukan apakah kriteria dari permohonan pembiayaan yang diajukan nasabah sudah sesuai dan berapa nilai pembiayaan yang sesuai. Ketika departemen menerima tiket terkait permasalahan di aplikasi pengelola pembiayaan, departemen akan menganalisa dan mengidentifikasi root cause dari permasalahan tersebut. Jika dinilai tidak bisa ditangani di ASP maka akan dieskalasi untuk diperbaiki di IDG.

### IT Payment & Integration Services

Departemen IT Payment & Integration Services memiliki tugas utama untuk menerima dan memperbaiki masalah yang muncul dalam proses payment dan integrasi yang digunakan oleh BSI. Masalah-masalah yang dihadapi seringkali terkait dengan channel sistem pembayaran yang melalui SmartVista, Enterprise Service Bus (ESB), JSwitch, dan berbagai aplikasi middleware yang digunakan untuk menghubungkan channel pembayaran BSI ke channel pembayaran eksternal / Banklain. SmartVista sendiri adalah sebuah platform perbankan end-to-end untuk pembayaran elektronik seperti transfer dana dan pembayaran tagihan. Beberapa tools SmartVista yang digunakan diantaranya SmartVista FE, SmartVista BO, dan SmartVista Perso. Departemen akan memeriksa log yang masuk apabila terdapat laporan error yang masuk dan diidentifikasi root causenya.

### IT Classic Channel Services

Departemen IT Classic Channel Services bertugas untuk menerima dan memperbaiki masalah yang muncul dalam channel-channel klasik yang digunakan oleh BSI, seperti BSI Net Banking, Mobile Banking (BSI Mobile), dan BSI Smart Agent. Ketika departemen menerima laporan / tiket terkait permasalahan di channel klasik, departemen akan menganalisa dan mengidentifikasi root cause dari permasalahan tersebut. Jika dinilai tidak bisa ditangani di ASP maka akan dieskalasi untuk diperbaiki di IDG.

### IT Information & Data Services

Departemen IT Information & Data Services tugas utama untuk mengelola informasi dan data yang masuk melalui aplikasi yang berjalan serta mengatur penyimpanan data dan memenuhi permintaan data oleh departemen / unit bisnis yang memerlukannya. Dalam praktiknya, permintaan data dari departemen atau unit bisnis dapat dikategorikan menjadi 2, yakni data yang diupdate dalam kurun waktu tertentu seperti harian, dan permintaan data ad-hoc yakni ketika unit bisnis meminta data untuk kepentingan tertentu. Data yang masuk dari aplikasi yang dimaintain oleh ASP akan masuk ke Data Warehouse yang dimiliki oleh departemen ini. Departemen ini juga bertugas untuk melakukan data engineering dari data yang masuk agar data tertata dan mudah untuk digunakan. Salah satu kegiatan yang dilakukan departemen Information & Data Services saat ini adalah untuk memindahkan database dari DB2 yang sudah tidak disupport lagi ke database Oracle

### IT Wholesale & Office Automation Services

Departemen IT Wholesale & Office Automation Services memiliki tugas utama untuk mengelola, menerima dan memperbaiki masalah yang muncul dalam aplikasi yang digunakan oleh bagian wholesale. Departemen ini memiliki jumlah aplikasi terbanyak yang dikelola, yakni 44 aplikasi. Aplikasi-aplikasi tersebut dapat dibagi berdasarkan skala prioritasnya dalam perbaikan masalah. Pembagian tersebut yakniVery Critical Applications yang termasuk didalamnya aplikasi EXA dan New CMS, Critical Applications seperti Web BSI, Moderate Applications seperti WebForm, dan Non Critical Applications seperti E-Doc. Departemen ini juga bertugas untuk mengembangkan dan melaksanakan otomasi dari proses-proses yang ada di ASP.

## Bisnis Proses

## Ketentuan Operasional

## Kebijakan Operasional