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
- Pembicara: Imam, Farhan Dani
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

#### Waterfall

- Perlu memo untuk setiap penambahan fitur atau perubahan
- Memo akan diubah ke CR (costumer request)
- CR akan menjadi task yang akan dikerjakan
- Waterfall belum ada devops

#### Agile
