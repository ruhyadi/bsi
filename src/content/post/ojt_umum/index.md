---
title: "OJT Umum"
publishDate: "09 September 2024"
description: "OJT Umum"
tags: ["ojt"]
---

## IDG (IT Development Group)

User IDG untuk superapp adalah DPG (Digital Product Group).

### Core Banking

- Mau belajar
- Analitcal skill yang kuat
- Menggunakan bahasa tersendiri
- Core banking upgrade dari R10 ke R23
- Menggunakan Temenos
- Dept Head: Dedy Wahyudi (Dewa)
- Pembicara: Nabila
- Main application: T24, EXA (Express Account)
  - Kenapa ada dua akun? User experience T24 bisa diganti oleh EXA
- Semua channel akan disimpan datanya di core banking
- Temenos Web Service (TWS)
  - TC merupakan protocol yang digunakan ATM untuk hubungan ke core banking  
- Day to day: develop user requirement dari tim bisnis, penambahan flagging, penambahan field, penambahan fitur
- Tech stack: Temenos (R10, Infobasic) akan upgrade ke (R23, Java)
- Jumlah orang: 18 orang

### WHA (IT Wholesale & Office Otomation)

- Pengembangan aplikasi internal di BSI
- Robotics Otomasi (RPA)
- Dept Head: Ricky Mahendra
- Pembicara: Zakia
- Aplikasi: SIP (Absen), Inventory Mangement, NPS (Dokumen petunjuk tekniks dan prosedur), LMS (Learning Management System)
- Techstack: mobile, web, frontend, backend (lebih variatif)
- Office otomation
- Aplikasi: Visualisasi Rekonsilasi data otomatis (data BSI vs pihak ke tiga)
- Tech stack: PHP Laravel, Java Spring Boot, React Typescript
- Jumlah: 10 organic + 21 MSA

### PIN (IT Payment & Integration)

- Dept Head: Teddy Wallad
- Pengembangan aplikasi dan integrasi internal dan external BSI
- Pengelola ESB Web Method
- BSI Smart Agent
- API third party
- Penengah semua channel, BSI Mobile, Internet Banking
- Contoh aplikasi: switching ATM, switching umroh dan haji, BSI SMART (EDC, HP, Website) (full stack, backend dan frontend), asuransi
- Tech stack: Java Spring (Java dan Kotlin)
- Tidak ada user spesific, semua orang bisa jadi user.
- Organik 9 orang + 10 outsource

### MIS (Information and Platform Management)

- Dept Head: Rusman Hadi
- Pembicara: Ali
- Tentang supply data dan ETL
- Pengembangan aplikasi pelaporan
- Memastikan data di basis data BSI terkini dan terupdate
- Basis data menjadi informasi yang diakses oleh user (bisnis, legal, compliance)
- Diutamakan yang bisa query SQL
- Machine learning
- Aplikasi: dashboard pelaporan, extraksi data core banking, regulatory report, MIS (Management Information System), SIAP (Aplikasi lebih baru)
- Tech stack: IBM data state, Oracle data integrator, Pentaho, SIAP (Code Igniter), MIS (**PHP**)
- Rekonsilasi data untuk WHA (Wholessale & Office Automation) baik data BSI dan pihak ke tiga
- Jumlah orang: 5 

### Classic E-Channel

- Dept Head: Mukhlis Yani
- Pembicara: Farhan Dani
- Melakukan pengembangan aplikasi/produk digital yang digunakan oleh nasabah (end-user)
- Aplikasi: BSI mobile, BSI Net, CMS, LPC (Landing Page Consumer), Physical Channel (ATM, EDC)
- Techstack: android, ios, backend (spring)
- BSI Mobile (semi agile, daily meeting, backend java native, ios objective-c)
- BSI Net (backend java spring, front-end larevel, SDLC waterfall)
- CMS (full-stack laravel, oleh vendor)
- CRM (untuk sales, oleh vendor)
- Jumlah orang: 39 (10-15 organic)

### Financing & Collection

- Dept Head: Arry Pratama
- Pembicara: Rifky Ramadhan
- Melakukan pengembangan aplikasi pembiayaan dan penagihan
- Aplikasi: APPLE, WISE, E-QURMA, NOS (mitraguna online), Robotic IDEB, J-FAST, Magic, Salam Digital
- Tech stack: APPLE (C#), WISE (Java Spring), E-Qurma (Java Spring), J-FAST (vendor), Magic (PHP), NOS (Low code platform)
- Jumlah orang: 37
- Superproject: Medina (menggantikan WISE untuk project pembiayaan KPR (Griya))
- MAGIC (Mass Application Govermance Institute and Corporate): payroll dan program-program dari pemerintah (bansos). User governmance dan ACG. Kebanyakan digunakan di daerah aceh.

### Customer Banking

- Dept Head: Muhammad Akbar
- Melakukan pengembangan superapp
- Methodology: Agile

### IT Service Banking (SBP)

- Dept Head: Agus Mukti
- Dibawah langsung deputy IT (karena mau fokus ke service banking)
- Pembicara: Kiki Wahyudi, Adi Nur Rahman
- Jobdesc: bikin API, middleware, pembuatan service
- Integrasi BSI dengan Channel (atau channel antar channel)
- Integrasi untuk core banking
- Middleware & API integration
- Bertanggung jawab untuk pengembangan digital core dan BaaS
- Aplikasi: ESB (Enterprise Service Bus)
- API: kebutuhan dari setiap channel
- Semuanya harus lewat ESB
- EBS: ESB internal, ESB openapi, UBP (Unified Bill Payment)
  - ESB Internal: aplikasi internal to internal
  - ESB Openapi: aplikasi eksternal to internal, menggunakan standar SNAP BI
  - UBP: internal/eksternal to biller
  - Gateway: software AGI
- Jumlah: 14 orang. Organik: agus, firman, nugi, alham, ade, kiki, hendra
- Tidak boleh memanage satu product karena dipake rame-rame
- Fungsi trothling: pembatasan, gateway, logging, security, monitoring
- UBP: untuk bayar-bayar taginah, akan migrasi ke SNAP BI
- Lagi dikerjain: integrasi ke snap dan pembayaran topoup emoney
- SOP: semua masuk lewat PM, akan manage ke developer terkait
- Tech stack: software AG (webmethods/IBM) API Gateway, integration server (bawaan gateway)
- Surronding juga punya otorisasi

### IT Digital Resource & Delivery Enabelment

- Langsung dibawah Deputy
- Mengatur resource dan sumber daya manusia di IDG untuk non-organic
- Erat dengan ISG vendor management

### SDLC

Berikut adalah tabel perbedaan antara **Agile** dan **Waterfall** dalam SDLC:

| Aspek                   | Agile                                     | Waterfall                                    |
| ----------------------- | ----------------------------------------- | -------------------------------------------- |
| **Pendekatan**          | Iteratif dan inkremental                  | Linear dan berurutan                         |
| **Proses Pengembangan** | Dibagi menjadi sprint atau iterasi pendek | Dilakukan dalam satu siklus panjang          |
| **Kebutuhan/Kriteria**  | Fleksibel, bisa berubah selama proses     | Tetap dan harus ditentukan sejak awal        |
| **Keterlibatan Klien**  | Tinggi, feedback diberikan secara berkala | Biasanya hanya di awal dan akhir proyek      |
| **Pengujian**           | Dilakukan bersamaan dengan pengembangan   | Dilakukan setelah tahap pengembangan selesai |
| **Tim**                 | Tim cross-functional bekerja bersamaan    | Tim bekerja dalam fase yang berbeda-beda     |
| **Risiko**              | Mudah diadaptasi untuk perubahan          | Sulit beradaptasi jika ada perubahan         |
| **Waktu dan Biaya**     | Bisa bervariasi tergantung pada perubahan | Biasanya lebih mudah diperkirakan sejak awal |
| **Cocok untuk**         | Proyek kompleks dan yang mungkin berubah  | Proyek dengan kebutuhan tetap dan jelas      |

## CISO (Chief Information Security Officer)

- Pembicara: Deni Saputra (Hardening), Firdaus (Security Code Review Engineer), Alfan Azizi (Directory service)
- Orang pertama yang tau akan ancaman dan orang terakhir yang melindungi
- Buat PPT
- Tanggung jawab:
  - Monitoring ancaman
  - Management resiko
  - Kepatuhan regulasi
  - Perimeter security (endpoint, cloud, internet)
    - PAM (Privilage Access Management): cyberark
    - User ID: cloud pakai microsoft 365
    - DLP (Data Loss Prevention): terlibat untuk penyedia tools
      - Data masking untuk comply pada UU PDP

### IT Security Project & QA

- Dept Head: Aditya
- Project management di CISO
- Mengelola project dari project security digital di BSI
- Pengadaan software dan alat yang berkaitan dengan security
- IT QA: memastikan bahwa security sesuai dengan SOP CISO
- Trendmicro: antivirus
- Global Protect: VPN
- Forescout: monitoring device, compliance
- 20+ project yang berjalan
- Total orang: 4 orang + DH

#### Security QA

- Memastikan seluruh proses kerja dan bisnis memenuhi PTO & SPO dan juga memenhi ketentuan dari regulator (OJK, BI, Bank Mandiri, dll)
- Tahapan:
  - Pengumpulan data yang diakan diaudit
  - Data dikirim ke pihak yang memninta
  - Pihak terkait akan melakukan audit (wawanacara, pengecekan dokumen)
  - Pra-exit, QA akan dikasih CAT (Catatan Atas Temuan)
  - Jika tidak bisa memenuhi, maka harus membuat memo sampai ke direksi
- Dari sisi audit:
  - Audit internal: bisa dari QA
  - Audit eksternal: bisa dari konsultan (PWC)
- Collect semua data terkait security
- Sebagai yang menjawab jika terdapat pertanyaan dari regulator atau pihak luar
- Validasi terkait permintaan open acess:
  - Firewall
  - VPN
  - Network
- Inti dari QA:
  - Audit
  - Validasi
  - Sebagai jempatan untuk group lain di direktorat atau pihak luar
- Harus mengerti semua proses bisnis di CISO
- Project:
  - Maturitas security: untuk mengevaluasi dept di CISO apakah sudah best-practice dengan praktek diluar sana. Tujuan: minta dibuatkan blue-print oleh vendor untuk pengembangan CISO kedepannya. Ingin mengikuti framework NIST cyberscurity.
  - Perpanjang ISO 27001 terkait sertifikasi CISO
- Support data untuk permintaan data dari auditor
- Berkolaborasi dengan seluruh departemen CISO untuk melengkapi dokumen terkait audit
- Review berkas open koneksi untuk selanjutnya diserahkan ke bagian Security Operation (SecOps)
- Standar open koneksi:
  - Akses lewat PAM
  - Harus terinstall antivirus
- PAM adalah pintu pertama untuk akses ke server. PAM menggunakan CybserArk

#### IT Security Project

- User internal: semua departemen yang ada di CISO
- User external: semua departemen yang ada di BSI
- Dokumen pengadaan:
  - Nota izin prinsip (pengajuan ke direksi yang telah di review oleh SOR) (terdapat kajian teknis)
  - Memo pengadaan (info untuk procurement)
  - PFA
- Satu kali pengadaan bisa sampai 2-3 bulan
- Fase: pengadaan, project, maintenance

### Application Identity Management

- Dept Head: Agus Setiawan
- Integrasi aplikasi dan user management
- Pembuatan akun untuk karyawan baru
- Identity management: LDAP, Active Directory
- Privilege access management: mengatur hak akses user
- Cyberark: untuk akses server development dan production
- CISO menjadi admin dari setiap aplikasi BSI. Total aplikasi ada 140
- Total: 14 orang
- Total daily tiket rerata 500
- Menangani BAST aplikasi baru untuk dihandle tim user id
- Project:
  - Reset email by mandiri

#### Identity Management

- CRUD user
- Metric kewenangan (CS diaplikasi T24 dapat apa saja)
- Dapat data HC (Human Capital) setiap hari terkait user database
- Review userid per tahun
- Portal user id untuk aktivasi kembali dengan form request (harus melampirkan kontrak yang terbaru)

#### Privilege Access Management

- Setiap user mempunyai user metrics
- Dilakukan review user per tahun 1 kali
- Tidak login 30 hari akan non-aktif

#### Directory Services & Email Management


### Network Access & Data Protection

- Pembicara: Abdul Ghofur
- Mangement keamanan transfer data dan akses jaringan
- Email keluar masuk di pantau oleh departemen ini
- XDR (Extended Detection and Response): untuk mendeteksi ancaman
- Hanya sebagai gate didepan, tidak untuk monitoring semuanya
- Mempunyai policy dan aturan (9 Policy)
  - Antivirus: 14 hari harus update
  - Forescout: harus terinstall disemua endpoint
    - Termasuk IoT, server, CCTV, SmartTV
    - Definisi aplikasi yang tidak boleh diakses (blacklist)
  - Joint domain
  - LAPS: mengontrol endpoint non-admin
  - Harus login user LDAP
  - VPN global protect
  - OS ditentukan classificationnya, diatas windows 10 (diatas 22H2)
  - DLP (Data Loss Protection)
- Jika ditemukan temuan
  - Blok by switch (dikarantina)
    - SNMP
  - Blok by firewall
    - whitebox: memenuhi standarisasi
    - graybox: masih belum terpenuhi terdeteksi oleh forescout
    - blackbox: di blacklist

#### Customer Identity Management

- SSO unutk nasabah
- Sangat costly untuk 20 juta nasabah BSI
- CIAM: Customer Identity Access Management -> untuk customer behavior

#### Data Encryption & Key Management

- Bertugas untuk mengelola public key, private key, serta perlindungan jalur server
- Menggunakan HSM (Hardware Security Module) untuk menyimpan key
- Handle sertifikat SSL untuk domain yang ada di BSI

#### Data Protection Management

- Data masking: untuk melindungi data sensitif

### IT Security Services

- Dept Head: Nanang Setiawan
- Mengecek keamanan dari setiap device di BSI
- Hardening dan pengamanan aplikasi
- Menjaga dari sisi development (Code review) (SASTI DASTI)
- Security code review dikasih langsung ke IDG
- Hardening and patching (CIS Level 1)
- Assessment VAPT, Red Teaming
- Penetration testing dengan pihak ketiga
- Pentest sendiri tidak bisa dilakukan untuk laporan (Rapid7, Nessus)
- BSI sebagai blue team
- Bounty hunter harus ke corporate secretary terlebih dahulu
- Pentest biasanya dilakukan per tahun
  - Aplikasi critical: core banking, switching
- Red teaming
- Melakukan uji penyerangan pada sistem BSI
- Security assessment
- Core banking dengan CISO
  - Hardening dan patching
  - Penyediaan server yang aman
  - Aplikasi T24 akan masuk ke source code review
- Sertifikasi: CEH & CHFI

### IT Security Operation

- Dept Head: Haerul Umar
- Mengamankan jaringan dari BSI
- Menghandle firewall
- Ketika ditempatkan:
  - Terus belajar
  - Cari hal positvenya
  - Jangan suka mengeluh
- Bekerja 24/7 (2/3 shift)
- Total: 8 orang
- Seperti satpam perumahan yang melakukan keliling patroli
- Daily activity: monitoring, patching, availability
- Hectic:
  - adanya production issue, cek dari sisi firewall
  - monitoring dengan vendor
- Keterkaitan
  - monitoring disemua perangkat
  - user yang menginginkan open access (yang dibuka adalah port nya)

#### Infrastructure & System Security

- Endpoint security (antivirus, EDR (Endpoint Detection and Response), XDR (Extended Detection and Response))
- Monitoring keamanan infrastruktur, jika ditemukan keamanan akan dilaporkan ke IT service untuk di-patch
- Server: 2000 server fisik & virtual
- Endpoint: 21,000 endpoint (laptop, desktop)

#### Cloud Security

- IaaS (Infrastructure as a Service): kita sewa cloud kemudian kita bangun infrastruktur kita sendiri
- PaaS (Platform as a Service): kita sewa cloud kemudian kita bangun platform (database, server) kita sendiri
- SaaS (Software as a Service): kita sewa cloud kemudian kita bangun aplikasi kita sendiri
- AWS dan GCP digunakan untuk BYOND menggunakan konsep IaaS
- Security: firewall, CSPM (Cloud Security Posture Management), anti-DDoS (disisi cloud, aplikasi: Imperva)

#### Network Security

- Firewall, IPS (Intrusion Prevention System) (sampai melakukan blocking), WAF (Web Application Firewall), IDS (Intrusion Detection System)

### Security Operations Center

- Dept Head: Deni Wahyudi (Bank BTPN, Bank Jago) (Security dan Infra)
- Pembicara: Lukman (0817 0519 760)
- Monitoring semua aktivitas di BSI
- Bertugas:
  - untuk menemukan celah keamanan di endpoint, server, cloud dan jaringan
  - memperbaiki celah keamanan
  - WAF (Web Application Firewall)
  - membuat blacklist web atau service yang tidak aman
- Monitoring 24 jam
- Pembentukan baru setelah tahun 2023
- ARCSIGHT: SIEM (Security Information and Event Management)
- Microsfot Sentinel: digunakan untuk monitoring cloud (masih menggunakan vendor Entity)
- SIEM: platform untuk monitoring security log (antivirus, DNS, firewall)
  - Punya kemampuan backtrack (history)
- Antivirus: Trendmicro diinstall diseluruh endpoint
  - Preventif dan pengecekan untuk mencari celah keamanan
  - Antivirus akan melapor ke SIEM

#### Incident Response

- Melakukan validasi saat user (endpoint) mengakses situs yang tidak aman (terlarang)

### Presentasi Review

- CIA (Confidentiality, Integrity, Availability)