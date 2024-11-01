---
title: "Data Decision Management"
publishDate: "28 October 2024"
description: "Data decision management"
tags: ["digital"]
---

## Introduction

- You are a data driven company only if everyone uses data
- DDM sekarang under directorat digital
- Objektif:
  - Mencari nasabah potensial terkait pembiayaan

## Data Governance

### Strategi

- Pemenuhan policy data
- Pada tahun 2024, DG fokus pada data quality terkait penurunan CIF kotor dan ganda

### Fungsi Peran

- Policy maker
  - Membuat kebijakan terkait data governance
  - Menyusun SPO (Standar Prosedur Operasional) terkait data governance
  - Menyusun PTO (Prosedur Teknis Operasional) terkait data governance
- Quality assurance
  - Memastikan data yang digunakan oleh unit bisnis adalah data yang berkualitas
  - Memastikan data yang digunakan oleh unit bisnis adalah data yang valid
  - Memastikan tidak ada data raw yang duplikat
  - Fokus meningkatkan kualitas data BSI
    - Data CIF (Costumer Identification File) atau data nasabah
      - Kasus CIF kotor (kosong) dan ganda
      - CIF perorangan (28 field)
      - CIF non perorangan (35 field)
- Project manager
  - Mengelola proyek-proyek DDM
- Oversight data governance di BSI (bukan hanya DDM)
- Data policy & architect
  - Sebagai control tower
  - Building data policy foundation
    - Merancang SPO data management & PTO turunannya
    - SPO data management
      - PTO data leads & campaign
      - PTO CIF
      - PTO dataku
      - PTO big data
  - Initiating UU PDP implementation
  - Leading data governance body
  - Developing data governance tools
    - Metadata baru sampai table
    - Kedepannya metadata sampai field
  - Ketentuan pengolahan data
    - Data architecture
    - Data lifecycle management
    - Data integration & interoperability
    - Reference & master data management
    - Data warehouse & data mart
    - Data security
    - Data quality management

### Bisnis Proses

1. Menentukan tujuan data governance
2. Analisis prinsip tata kelola data
3. Menentukan indikator KPI dan tools
4. Evaluasi

### Keterkaitan

- Data management: menjaga kualitas data pada data warehouse DM
- SOR: sebagai pendamping dalam kegiatan risk assessment
- Dept DDM lain: sebagai policy maker dan quality assurance

### Ketentuan

- UU Perlindungan Data Pribadi
- SPO Data Management
- PTO CIF
- PTO Data Leads

### Kegiatan Operational

- Policy maker:
  - Membuat kebijakan SPO dan PTO
- Quality assurance
  - Data cleaning
  - Data validation (CIF ganda)
- Project manager
  - Planning
  - Budgeting
  - Koordinasi vendor

### Lain-lain

## Data Management

- The more you know, the more you can create. There's no end to imagination in the kicthen
- Pemilik big data (Claudera)
- Data warehouse (data yang sudah diolah)
  - Node: 16
  - Capacity: 300 TB
  - BSI total apps: 170
  - Big data not ready: 119
  - Big data ready: 51 (30%)
- Report realtime belum ada
- 3 Principles:
  - Otomasi proses
  - Cepat & efisiensi proses
  - Produktivitas meningkat
  - Pencapaian target meningkat
  - 1. KIS: Keep It Simple
    - ETL (Talend): menarik data dari source dan sink ke claudera
    - Data Lake (Claudera): menyimpan data mentah
    - Data Warehouse (Claudera): menyimpan data yang sudah diolah
    - Reverse ETL (Talend): menarik data dari claudera ke sink
  - 2. Access data should be like riding a bike:
    - Data mart: menyimpan data yang sudah diolah
  - 3. Build trust in your data:
    - Availability
    - Transparency
    - Reproducibility
    - Secure
  - Data upstream: merapikan data, data mart
  - Data downstream
- Single source of truth

### Strategi

- Pada tahun 2024, DM melakukan implementasi rencana pemulihan bencana, penyediaan inventaris sandbox, dan penyediaan data untuk advanced fraud detection
- Pada tahun 2025, DM menyediakan enterprise datamart dengan infrastruktur lebih maju
- Pada tahun 2026, DM menyediakan platform enterprise data dengan datamart yang kompleks

### Fungsi Peran

- Downstream
  - Proses penarikan data dari sumber data (aplikasi) ke data warehouse (Claudera)
  - Diawali dengan pembuatan memo akses database aplikasi (IDG/ASP/IOG)
- Upstream
  - Proses penarikan data dari data warehouse (Claudera) ke data mart atau sesuai kebutuhan user
- ETL
  - Proses extract, transform, load data dari sumber data ke data warehouse
  - Extract: menarik data dari sumber data
  - Transform: merapikan data
  - Load: menyimpan data ke data warehouse

### Bisnis Proses

1. Memo akses database aplikasi (IDG/ASP/IOG)
2. Pembuatan proses ETL
3. ETL data dari sumber data ke data warehouse
4. ETL data dari data warehouse ke data mart
5. Penyediaan data mart ke user

### Keterkaitan

- Data governance: sumber kebijakan terhadap data
- Dept DDM lain: sebagai sumber data raw dan data mart

### Ketentuan

- UU Perlindungan Data Pribadi
- SPO Data Management
- PTO CIF
- PTO Data Leads

### Kegiatan Oprational

- Downstream
- Pembuatan ETL
- Upstream

## Information Management

- Dashboard tableu & power BI
- Mirip dengan BI
- Orang pertama yang ditemui oleh user jika butuh data
- Tugas: mencari tahu kebutuhan user terkait data (availability)
- Data yang dikasih ke user bisa bermacam-macam
  - Project: minta data secara berkala (rutin) (dalam bentuk dashboard)
  - Ad hoc: sekali minta selesai (by request) (dalam bentuk excel)
- Permintaan data memerlukan memo
- Memberikan business service terkait kebutuhan user (yang belum tahu data apa yang dibutuhkan)
- Query ke data mart yang dibuat oleh Data Management
- Query data menggunakan claudera dan impala
- Visualisasi menggunakan PowerBI dan Tableu
- IM (DDM) langsung face to face dengan user tanpa ada perantara

### Strategi

- Pada tahun 2024, IM berfokus pada peran Business Analytics dan Intelligence
- Pada tahun 2025, IM memainkan peran utama dalam wawasan bisnis yang komprehensif

### Fungsi Peran

- Data visualization
  - Visualisasi data yang mudah dipahami oleh user untuk mendukung keputusan bisnis
- Data provider
  - Memberikan data yang dibutuhkan oleh user untuk mendukung keputusan bisnis
- Business analyst
  - Menganalisis kebutuhan bisnis user sehingga dapat disediakan visualisasi atau data yang sesuai

### Bisnis Proses

- Project based: data provide ke user secara rutin baik dalam bentuk dashboard atau laporan
- Ad hoc based: data provide ke user sesuai permintaan user
- Alur kerja:
  1. User meminta data melalui memo
  2. IM melakukan query data dari data mart
  3. IM melakukan visualisasi data menggunakan PowerBI atau Tableu
  4. IM memberikan dashboard atau laporan kepada user
  5. IM melakukan monitoring dan maintenance dashboard atau laporan

### Keterkaitan

- Data Management: sebagai sumber data yang digunakan oleh IM
- Unit bisnis (SRG, CM, CBG, CF1, CF2): sebagai user yang membutuhkan data

### Ketentuan

- UU Perlindungan Data Pribadi
- SPO Data Management
- PTO CIF
- PTO Data Leads"

### Kegiatan Operational

- Project based
- Ad hoc based
- Monitoring dan maintenance

### Lain-lain

## Data Analytics

- Python & Claudera
- Intinya: cari pattern dari data
- Membuat data mart sendiri
  - Membiasakan data sendiri agar dapat diotomatis
  - Memakai talend dan claudera
- Data exploration
  - Menggunakan python
  - CDSW (Cloudera Data Science Workbench)
- Membuat report dan visualisasi data
  - Membuat dashboard yang berisi analytics
- Tipe analytics yang digunakan:
  - Descriptive: apa yang terjadi
  - Diagnostic: mengapa terjadi
  - Predictive: apa yang akan terjadi
  - Prescriptive: apa yang harus dilakukan
- Hasil:
  - Analisa untuk strategi
  - Data leads
    - Kita mau jualan hasanah card tapi tidak tahu ke siapa?
    - Monitoring: sucess rate, cpa (cost per aquisition)
- Proses flow:
  - Initiatif
    - Naik ke GH
    - Naik ke product owner
    - Hasil perbandingan:
      - Success rate growth
      - Product volume growth
  - Request bussiness owner
    - Lebih banyak dari Angga
    - Menggunakan memo
    - Diskusi terkait kebutuhan
- Mikro dan SME
  - Pembicara: Alfian Prisma Yopiangga
  - Mencari nasabah mikro untuk upgrade ke SME
    - Harapan agar nasabah mikro dapat platform lebih tinggi
  - Mencari pattern kemudina implementasi
  - Wholesale value chain:
    - Supplier/distributor (SME, Mikro)
    - Koperasi (SME)
    - Payroll (Retail funding)
  - Skema:
    - By request
      - SLA: tidak ada
    - Propose ide
  - Task:
    - Query SQL di Hue
    - Python untuk analysis
    - Visualisasi di PowerBI
- Digital and E-Channel
  - Pembicara: Azarin
  - Mobile banking
  - Digital transaction
  - OOB
  - Net backing
  - ATM
  - Merchant QRIS
  - Merchant EDC
  - Fokus ke mobile banking:
    - Tujuan untuk meningkatkan user aktivasi (UREG) dan transaksi (USAK)
  - Tipe analytics bergantung kebutuhan bisnis dan user
  - Menggunakan machine learning untuk prediksi
- Non Digital
  - Pembicara: Anugrah
  - Digital financing
  - Digital funding
  - Konsumtif:
    - Hasanah card
  - Investment:
    - Emas
    - Deposito
  - Needs:
    - Griya
    - Oto
    - Mitraguna
    - Gadai
- Wholesale
- Hasanah Card
- Griya
- Cicil emas
- Implementasi AI:
  - Generative AI
  - NER (Named Entity Recognition)
- User:
  - Orang bisnis
  - Data dari DM (Data management)

### Strategi

- Sepanjang 2024, DA berfokus mengembangkan dan meningkatkan infrastruktur seperti Decision Support System
- Peningkatan penggunaan analytics predictive (machine learning, deep learning) untuk mendukung insight bisnis
- Penggunaan Generative AI (LLM, VLM) untuk memahami, merangkum, dan memprediksi data yang dapat dimanfaatkan oleh DA demi kebutuhan bisnis

### Fungsi Peran

- Data leads
  - Data nasabah potensial yang dapat dijadikan target marketing
  - Kriteria nasabah potensial yang dapat dijadikan target marketing
- Data analytics
  - Proses mencari pattern dari data yang dapat digunakan untuk strategi bisnis
- Monitoring
  - Success rate
  - CPA (Cost Per Aquisition)

### Bisnis Proses

- Inisiatif: Tim secara inisiatif melakukan analisis data yang dapat digunakan Tim secara inisiatif melakukan analisis data yang dapat digunakan untuk strategi bisnisuntuk strategi bisnis
- Request: Tim melakukan analisis data berdasarkan permintaan dari business owner
- General flow:
  1. Pendefinisian masalah bisnis
  2. Exploratori data analysis (EDA)
  3. Data preparation
  4. Model building
  5. Model evaluation
  6. Model deployment
  7. Monitoring
  8. Reporting
  9. Feedback
  10. Improvement

### Keterkaitan

- Unit bisnis (SRG, DPG, DAG): sebagai user yang membutuhkan analisis data
- Data Management: sebagai sumber data yang digunakan untuk analisis data

### Ketentuan

- UU Perlindungan Data Pribadi
- SPO Data Management
- PTO CIF
- PTO Data Leads

### Kegiatan Operational

- Inisiatif
- Request

### Lain-lain

## Campaign Management

- Membuat data leads (potensi nasabah yang akan berhasil jika ditawarin)
- Step: 
  - Determine campaign
  - Choose marketing platform
  - Lead generation
  - Campaign execution
  - Monitor & report campaign program
  - Review & evaluation
- Service:
  - Data lead distribution
  - Cashback
  - Personalize path notif
  - Personalize WAB (Whatsapp blast)
  - Personalize email
- Tools: semua tools di DDM digunakan
  - Talend
  - Dataku
- Tugas:
  - Membuat leads
  - Menjalankan campaign
  - Monitoring campaign
  - Salesnya DDM
- Dataku:
  - Menaruh data leads
  - Tujuan: convertion rate meningkat
  - Consumer leads collaboration
- Terbagi menjadi 2 unit:
  - Digital infrastruktur
  - Penetration
- CM mengambil data dari data mart yang dibuat oleh DM
- WA blast dan push notif direct ke nasabah

### Strategi

- Pada tahun 2024, CM menentukan titik fokus untuk membuat pengadaan dan mengembangkan beberapa tools

### Fungsi Peran

- Segmentasi user (leads): membagi user berdasarkan karakteristik tertentu. Data leads yang dihasilkan akan digunakan oleh CM atau unit bisnis lainnya
- PUblikasi campaign: mempublikasikan campaign ke user (Notification BSIM, WA Blast, Email Blast)
- Monitoring: memonitor efektifitas campaign yang telah dijalankan

### Bisnis Proses

- Determine campaign: menentukan campaign yang akan dijalankan
- Choose marketing platform: memilih platform marketing yang akan digunakan
- Lead generation: menghasilkan data leads
- Campaign execution: menjalankan campaign
- Monitor & report campaign program: memonitor dan melaporkan efektifitas campaign
- Review & evaluation: mengevaluasi campaign yang telah dijalankan

- Alur kerja:
  1. Membuat data leads dari data mart
  2. Koordinasi terkait konten campaign
  3. Blasting campaign ke user
  4. Monitoring campaign

### Keterkaitan

- Data Management: sebagai sumber data yang digunakan oleh CM
- Data Analis: sebagai sumber data lead atau analisis yang digunakan oleh CM
- Unit bisnis (SRG, CBG, CF1, CF2): sebagai user yang membutuhkan data leads untuk campaign

### Ketentuan

- UU Perlindungan Data Pribadi
- SPO Data Management
- PTO CIF
- PTO Data Leads

### Kegiatan Operational

- Determine campaign
- Choose marketing platform
- Lead generation
- Campaign execution
- Monitor & report campaign program
- Review & evaluation

### Lain-lain