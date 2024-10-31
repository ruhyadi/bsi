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
- 