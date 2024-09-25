---
title: "IOG (IT Operation Group)"
publishDate: "23 September 2024"
description: "OJT Umum"
tags: ["ojt"]
---

## Introduction

- PTO: prosedur teknik operational

## IT Service Desk

- Depth head: Ibu Enza
- ITKU (Jira)
- Costumer management
- Service delivery: SLA yang diberikan IT kepada cabang (user)
- Scheduler ticker notification: pada saat user create ticker, akan diberikan notifikasi terkait issue (tiket) tersebut, jika ada jawaban maka notifikasi akan terkirim juga
  - Jika terdapat SLA yang akan habis, sistem akan mengirim notifikasi ke tim service desk
- IT escalation management
  - IOG tidak bisa memastikan perbaikan 100%, maka akan dieskalasi ke group ASP
  - ASP akan menerima tikat dan menganalis tiket tersebut (problem management)
  - ASP akan memberikan temporary solusi: patching data
  - ASP akan memberikan permanent solusi: perbaikan aplikasi (SDLC), jika tidak ada perubahan source maka akan dilakukan oleh ASP
- Knowledge management
- IOG dimonitoring oleh ASP terkait permasalahan di IT (tiket)

### Help Desk

- Pembicara: Yusuf Al Adana Haris
- ITKU untuk report issue (tiket)
- Issue akan disolve oleh help desk, jika tidak bisa akan dieskalasi ke IT Solution Management
- SLA per tiket beda-beda (dibedakan berdasarkan impact)
  - Critical: 3 jam: Global atau gangguan masal
  - High: 16 jam: Gangguan local berimpact tinggi. Satu lingkungan mati
  - Medium: 40 jam: Tidak ada impact ke banyak perangkat (satu PC mati)
  - Low: 112 jam: Tidak mengganggu operational dan cabang
- Total: 7 orang
- Sebagai first layer gangguan IT (pada aplikasi)
- Tiket akan closed saat tidak ada balasan selama 8 jam
- Jika tiket sudah closed, tidak dapat diopen kembali, harus membuat tiket baru
- Tidak ada spesialisasi per orang pada help desk, semua orang bisa menangani berbagai macam tiket

### Pinpad

- Pembicara: Admiral
- EDC punya kertas untuk bukti transaksi
- Pinpad (tanpa struck) untuk pembayaran juga. Tetapi untuk sekarang hanya digunakan untuk pin saja
- Pinpad: media untuk pembuatan pin. TCP/IP digunakan untuk connect ke Core Banking
- Terdapat pinpad berbasis android, menggunakan GSM untuk connect dengan core banking (intranet)
- Dibatasi hanya menggunakan filan 30
- Didalam pinpad terdapat master key (untuk enkripsi data), data kemudian akan dikirim ke switching
- Proses encripsi-descripsi akan diolah di HSM (Hardware Security Module)
- Yang dibaca oleh swtiching:
  - Terminal id: berdasarkan kode id cabang menggunakan TMS (terminal management system)
  - IP address
  - Master key
  - EDC serial number
- Switching: smartvista (sv)
- Brand: Ingenico & verifone
- Start date menggunakan 2 kartu
  - Otorisator: kartu teller untuk aktivitas harian (pada menu logon)
  - Supervisor: mengaktifkan pinpad
- Inisialisasi: 
  - Pastikan jaringan sudah konek dengan intranet (akan muncul `eth` pada pinpad)
  - Perubahan IP: pilih `#` pilih `0-telium manager`, pilih `1-ethernet setup`, pilih `2-ip address` (contoh `10.18.200.37`) pilih OK, ubah subnet `3-subnet` pilih `255.255.255.240`, Gateway `filan 30`, kemudian save.
  - Tekan `F *`, BSI Function `7978`, 

### IT Solution Management

- Pegang aplikasi juga tapi sebagai second layer
- Saat tim help desk tidak bisa memperbaiki, maka akan di lempar ke IT solution
- Menggunakan ITKU (jira)
- Gangguan perangkat kerja (laptop, pc, printer)

### Desktop & Peripheral

- Pengadaan desktop dan laptop (harus melalaui tiket)
- Standarisasi endpoint
  - Antivirus: trendmicro
  - Firewall: Global protect
  - Network endpoint: forescout
  - Trelix: backup data
  - Ivanti: remote desktop
  - Microsoft Intune: remote desktop
- Instalasi software melalui IOG dengan persetujuan CISO
  - Buat tiket di ITKU untuk installasi software melalui IOG
- Server campur (internal) dan server dmz
- Intune digunakan untuk remote access
- Terdapat tim intune
- Tim pinpad untuk maintenance ganti kartu dan pin pada EDC dan EXA
- Total: 18 organik



<!-- IMPLEMENTATION -->

## IT Implementation and Monitoring

- Dept. Head: Zaldy Suhatman
- Pembicara: Rafiati
- Handling deployment untuk production
- Punya room monitoring
- Punya 2 TL:
  - Rafiati
  - xxx
- Bertanggung jawab terhadap deployment di production, baik perubahan baru ataupun perbaikan
- Monitoring: pemantauan issue dan error di production

### Core Banking

- TL: Supriyono
- COB (Close of Bussiness): perhitungan transaksi per hari dan perubahan tanggal di jurnal nasabah, dilakukan di command center
- Tugas:
  - Proses COB (EOD, EOM, EOY)
  - Pengelolaan operasional harian atas sistem core banking sehingga berjalan stabil, cepat, tepat dan sesuai dengna SLA yang ditetapkan
  - Memastikan data dan program aplikasi telah dibackup (penting jika terjadi ransom)
- Core banking monitoring:
  - CBS (Core Banking System)
  - Disk max 70%
  - Response time browser T24
  - Response time TWS
  - Response time Jbase agent
  - Response time JSH
  - Response time tSS

### Non Core Banking

- TL: Nurman Slamet
- Aplikasi pembiayaan dan kepegawaian
- Tugas:
  - Operasional aplikasi non-core sesuai SLA
  - Menerapkan backup data
  - Monitoring layanan non-core

### E-Channel

- TL: Nurdiansyah
- Byond masuk ke dalam e-channel

### Change and Release

- TL: Dudi Royan Effendi & Rafiati
- Total: 3 orang
- Tugas:
  - Menindaklanjuti permintaan perubahan/deploy aplikasi ke server production sesuai dengan SDCL dan RCB (Release Control Board)
  - Melakukan uji coba DRP dan review pengambilan keputusan untuk dilakukan DRP (DRP melakukan pemindahan aplikasi dari DC ke DRC atau sebaliknya)
  - Menindaklanjuti audit di tingkat unit yang dilaksanakan sebagai tanggapan positif atas temuan audit
  - Melakukan pengecekan dokumen terhadap hal-hal yang berkaitan dengan request implementasi dan monitoring
  - Melakukan evaluasi terhadap aktivitas secara periodik. Evaluasi dilakukan saat masa freeze (22 - 5 setiap bulan)
- Bertanggung jawab terhadap perubahan dan release pada aplikasi & sistem
- DRP (Disaster Recovery Plan): perencanaan untuk mengatasi bencana
  - Regulasi dari BI
  - DRP akan dijalankan setiap 1 tahun sekali per aplikasi (terbatas untuk aplikasi critical)
  - DRP dibantu oleh BCM (Business Continuity Management)
  - Aplikasi yang dibuat sendiri untuk membuat aplikasi monitoring
- Command center berada di bawah Change and Release
  - Improvement dengan penambahan sirine
- Tools:
  - Dynatrace: alert problem
  - AppMon: BIFAST dan monitoring service
  - Malika: server production
- Flow: analisa -> eskalasi -> report
- Waktu kerja: 
  - Shift 1: 06.30 - 14.30
  - Shift 2: 14:00 - 22:00
  - Shift 3: 21:30 - 07.00
- Proses deployment:
  - Project => Tim implementasi ISG
  - Project issue => Tim ASP
  - Project (H-1) => Change release IOG
  - Deployment IOG
  - Report dan monitoring

<!-- END IMPLEMENTATION -->



## Data Center Management

### Data Center

- Jakarta (Rempoa), DCI (Data Center Indonesia) dan Surabaya

### Data Center Recovery

### Data Warehouse

- Seperti DDM. Pada IOG datanya secara live (data production)
- Housekeeping dan update data




<!-- IT INFRA/NETWORK MANAGEMENT -->

## IT Infrastructure/Network Management

- Job desc:
  - Menyediakan jalur agar semua di BSI dapat berkomunikasi
  - Secara hardware dan software (IP Address)

### Infrastructure Engineer

- Job desc:
  - Handle hardware
  - DCIM (Data Center Infra Management) proyek yang sedang berjalan
  - Utilisasi dan memastikan perangkat berjalan dengan baik
  - Ruang server (komunikasi data) harus 18 - 27 C

### Network Operation Center (NOC)

- Pembicara: Ota
- Job desc:
  - Melakukan monitoring jaringan (network)
  - Utilisasi jaringan server
  - Rekanan dengan provider dan memonitoring providernya
  - Menjaga kegiatan operasional berjalan dengan lancar
  - Pintu pelaporan lewat ITKU
    - Cabang tidak terkoneksi dengan intranet
    - Pinpad tidak connect
    - Ruang server bermasalah (kebakaran, kebanjiran)
  - Terlibat dalam relokasi cabang jika diperlukan
  - Ruang server pada cabang merupakan tanggung jawab
    - Perangkat tanggung jawab: switch, router, SDWAN (Software Defined Wide Area Network) (Paloalto), 2 provider yang dipakai
    - Memastikan perangkat konek dan dapat berkomunikasi dengan pusat
- Tools:
  - PRTG: monitoring jaringan Multiprotocol Label Switching (MPLS) seperti kinerja, bandwidth, dan statusnya
  - Paloalto: seperti CISCO
  - Strata: digunakan untuk monitoring paloalto (SDWAN) seperti kinerja, bandwidth, dan statusnya
- Provider:
  - Telkom
  - Sanatel

### Network Management

- Job desc:
  - Request IP
  - DRP (Disaster Recovery Plan)
  - 

- Penyedia IP untuk server

<!-- END OF IT INFRA/NETWORK MANAGEMENT -->




## IT Infrastructure Ops Management & Optimization

- Departemen yang menaungi IOG
- Bertindak sebagai PM untuk IOG
- Governance di IOG

## Cloud Infrastructure Technology

### Cloud Delivery Otomation

### Cloud Microservices & Application Platform

### Cloud Network & Load Balancer Support