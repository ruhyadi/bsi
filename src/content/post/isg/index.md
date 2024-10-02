---
title: "ISG (IT Stategic Group)"
publishDate: "30 September 2024"
description: "OJT Umum"
tags: ["ojt"]
---

## Introduction

- Pembicara: Reza Mahendra (2020), beasiswa Glasgow (MBA)
- Lebih managing anggaran ketimbang manpower
- Strategi: teknologi apa yang harus kita miliki
- POJK MRTI: peraturan yang mengatur teknologi informasi di perbankan

## IT Strategic, Planning & Architecture

- Pembicara: Maurizka (IT Architecture)
- Proses bisnis:
  - Membuat dokumen analisa pre-ARF (IT Architecture)
  - Request CR, fitur-fitur, BIA (IT Architecture)
  - Forum arsitektur (PMO, BA, User)
  - Review dokumen
  - Drafting dokumen pre-ARF (Architecture Review Forum)
  - Request ticket ARF
- Total: 11 orang (3 TL, 8 staff)

### IT Architecture

- Menentukan kebutuhan arsitektur IT dari proyek yang akan dijalankan
  - Penentuan tech stack (sampe ke version)
  - Penentuan arsitektur aplikasi
- Kebanyak proyek-proyek besar dihandle oleh vendor
- ISG hanya incharge di awal (penentuan arsitektur) setelah proyek berjalan (development) dan maintenance dihandle oleh IDG atau vendor

## IT Infrastructure, Network & Security

## IT Project Management Officer

- Pembicara: Hamdan
- Dept Head: Reza Nur Abdul Hadi
- Total: 50 orang
- Tahapan IT PMO:
  - IT PMO dan BA sudah mulai dari TF (technical feasibility) meeting
    - Menentukan availability dan feasibility dari proyek
  - IT PMO mengikuti "join disccusion meeting" (meeting antara user dan IT)
    - Mirip dengan TF meeting
    - BA akan lebih mengeksplor terkait CR (Customer Requirement)
    - Timeline akan ditentukan pada tahap ini
    - Output berupa FSD (Functional Specification Document) dari IT BA
    - FSD digunakan tim developer untuk membuat aplikasi
  - Forum arsitektur
    - Untuk kebutuhan jika ada perubahan terkait arsitektur (server, db, dll)
    - Forum arsitektur dapat dilakukan sebelum join discussion meeting 
  - Development:
    - PMO melakukan checkpoint pada waktu yang disepakati
    - Provide kebutuhan saat development
    - Output berupa SDD (Sofware Development Document) dan source code
    - Pembuatan dokumen QA Need (Quality Assurance) di submit ke TMP (Testing Management Plan) pada ASP (Application Support)
  - Testing Management Plan (TMP)
    - Dilaksanakan di ASP, akan mengundang IT PMO dan developer
    - Membahas terkait skenario yang akan dilakukan terkait pengetestan aplikasi
      - Dilakukan pentest atau tidak (Tim CISO)
      - Dilakukan performance test atau tidak (Tim ASP)
    - Output berupa dokumen kebutuhan SAT, UAT, Performance Test, Security Test
    - Dijelaskan kebutuhan QA testernya
    - Estimasi waktu testing dan dokumentasi
  - Testing
    - Dilakukan secara series (SAT -> UAT)
    - SIT: System Integration Testing. Output SIT report
    - UAT: User Acceptance Testing. Output berita acara UAT
    - Security Testing: penetration testing (berkaitan dengan aplikasi ke internet)
    - Performance Testing
  - RCB (Release Control Board)
    - Berupa meeting dengan komite untuk dilakukan deployment dan implementasi
    - Dihandle di ASP
    - Tim PMO: mengumpulkan semua dokumentasi yang dibutuhkan untuk RCB
      - SDD: Software Development Document
      - BASIT: Berita acara Business Acceptance Test
      - BAUAT: Berita acara User Acceptance Test
      - SCC: Security Compliance Check
      - Strategi implementasi (dibuat oleh PM IT) (di ttd oleh Dept. Head IT dan ASP SME (Subject Matter Expert))
        - Strategi deployment
        - Strategi rollback
        - Backup plan yang dilakukan
      - Source code
      - PMO mengajukan ke RCB
      - Output: MOM RCB dari Tim ASP
        - Mengajukan jadwal deploy
      - Level:
        - C: level DH (Dept Head). Review dokumen RCB
        - B: level GH (Group Head). Bisa ada putusan untuk eskalasi
        - A: level Direksi. Jika ada putusan, maka ada jadwal deploy
      - Koordinasi pendaftaran deployment oleh "IT Project Implementation"
      - Tim implementasi akan melakukan arrangement dengan IOG
    - PTR (Production Trial Run)
      - Dilakukan oleh user di environment PTR
      - Dilakukan pengetesan oleh ASP
      - Output: berita acara PTR (diminta oleh PMO)
        - Digunakan sebagai berita acara untuk go live
    - Go Live:
      - Di deploy di env produksi

### IT Project Management Officer

- Menjadi pemegang proyek yang mengkoordinasi anara user dengan grup IT lainnya
- Sebagai pemegang proyek, PMO harus mengerti seluruh proses SDLC
- Tidak menghandle detail terkait teknis
- Arrange meeting terkait proyek
- Menjembatani kebutuhan user dan developer

### IT Business Analyst

### IT Project Implementation

## IT Policy & Governance

- Pembicara: Naufal & Atikah
- Drafting PTO (Prosedur Teknis Operasional)
- Fungsi:
  - IT policy and governance
    - IT policy: pembagian tugas terkait kebijakan apa saja yang berkaitan dengan IT
    - IT security: terkait kebijakan yang berkaitan dengan group security (CISO, IOG, ISG)
  - IT awareness
  - IT audit: sebagai liason untuk tim audit internal atau eksternal
  - IT regulatori: pelaporan-pelaporan ke regulator (OJK, BI)
- Jobdesc:
  - Membuat kebijakan yang akan dipatuhi oleh group-group dan SME yang ada di BSI
  - Membuat SOP (Standar Prosedur Operasional)
  - Membuat PTO (Petunjuk Teknis Operasional)
  - In line dengan peraturan regulator
- Kebijakan akan di review dalam 1 tahun sekali
- Semua proses yang ada di IT harus tertuang di PTO
- Melakukan sosialisasi terkait SOP dan PTO

### Security Policy & Awareness

- Merancang dan menyusun kebijakan dan regulasi seperti SPO (Standar Prosedur Operasional) dan Petunjuk Teknis Operasional (PTO) terkait IT
- Meningkatkan awareness IT security ke cabang dan kantor pusat
- Memberikan kesadaran (awareness) ke pegawai dan nasabah
  - Nasabah: sebagai advisory (penasehat)
  - Pegawai: melalui email, teams, secretary, memo
  - Dalam bentuk quiz per bulan
  - Dalam bentuk webminar untuk pegawai cabang baik offline dan online
- Sharing informasi terkait security dan kesadaran

### IT Infrastructure & Network Governance

- Yang diatur:
  - Deploy aplikasi dan IT operation

## IT Asset & Vendor Management

- Pengaturan asset IT (laptop, tv, printer, dll)
- Mengelola vendor (outsourcing)

### IT Asset Management

- Pembicara: Muhammad Saefudin
- Asset owner
  - Server, Endpoint: IOG
  - Security: CISO
  - Source code: IDG
  - Aplikasi: ASP
  - ATM: DBO
  - Masing-masing asset owner melakukan pencatatan asset
  - IT Asset management hanya melakukan accountable (verifikasi) dari sisi asset
- Asset terbagi menjadi 2:
  - R1: infra yang ada di data center
    - Server
    - Network
    - Firewall
  - R3: infra yang diluar data center
    - Endpoint
    - ATM
    - Network cabang
- Pencatatan masih dilakukan secara manual
  - Sedang diadakan implementasi tools asset management
- Assessment (review) pengadaan:
  - Dalam pengajuan harus dilakukan review berdasarkan kebutuhan
  - Yang melakukan pengadaan adalah asset owner-nya
  - Jika barang baru, maka harus dilakukan assessment berdasarkan kebutuhan
  - Jika dilakukan penambahan, harus cek dengan asset existingnya
- Baseline-nya adalah kebutuhan bukan anggaran
- Pengadaan dilakukan pada JPS (Join Planning Session)
  - Incharge review pada sesi JPS terkait pengadaan asset
- IT steering comitee (ITSC) akan melakukan penyetujuan terkait pengadaan asset berdasarkan budget yang dimiliki
- Memastikan perangkat yang digunakan masih dalam kondisi support life cycle product
  - Fokus pada end-of-support, jangan menggunakan perangkat yang sudah obsolute
  - Jika sudah end-of-support, maka harus dilakukan upgrade
  - Terdapat resiko kepatuhan jika memakai perangkat yang sudah end-of-support
  - Akan merambat ke resiko operasional, maka akan ditemukan celah keamanan dan impact ke stabilitas dan operational
  - Resiko operasional akan impact ke resiko reputasi
- Disposal asset yang sudah end-of-support
  - Secara accounting masih ada barangnya
  - Disposal dapat berupa:
    - Hibah
    - Lelang
    - Dihancurkan
  - Disposal akan dilakukan oleh PFA (Procurement Fixed Asset)
  - IT asset akan memastikan bahwa disposal berjalan dengan baik
    - Data sudah dihapus
    - Dismantel: harus berkoordinasi dengan PFA terkait dismantel
- Support ITSM (IT service management) process
  - Request management: instalasi software
  - Insident management: server tidak bisa diakses
  - Change and release management: perubahan configurasi dari sisi server
  - Support terhadap proses-proses tersebut
- CMDB (Configuration Management Database)
  - Relationship dari assets

### IT Vendor Management

- Pembicara: Adli
- Dept. Head: Rino Nurahmat
- TL: Lis
- Total: 10 orang
- Jobdesc:
  - Monitoring PKS (perjanjian kerja sama) (Capex dan Opex)
  - Procurement di bagian SDLC
  - Monitoring MSA (Master Service Aggrement)
    - Pegawai yang baseline nya project based
  - Banyak berurusan dengan third-party atau vendor sehingga mengarah ke pengadaan
  - Monthly: purchase order (PO) MSA yang ada di ISG (untuk saat ini)
  - Belum ada tools yang digunakan tetapi sudah ada rencana untuk di develop
  - Setiap 6 bulan terdapat form evaluasi kinerja vendor

## IT Business Partner

- Sebagai jembatan utama antara bisnis dan IT

### IT Business Partner 1

### IT Business Partner 2

### IT Business Partner 3

- Pembicara: Raisa
- Fokus pada proyek-proyek:
  - IT directorate
  - CEO directorate (digital)
- Dalam SDLC hanya mengawal pada:
  - Inisiatif:
    - Join planning session (JPS)
    - Finalisasi DAD
    - Finalisasi CR
    - Working group
  - Enhancement:
    - Finalisasi DAD
    - Finalisasi CR
    - Technical Feasibility (TF) meeting
- Tahapan proyek enchancement:
  - CR masuk dan akan direview
  - Assessment dan followup terkait CR dengan user dan developer (IDG/vendor eksternal)
    - Seberapa besar effortnya
    - Possible tidak
    - Timeline pengembangan
  - Pembuatan DAD sebagai acuan untuk vendor
  - CR dikirim ke IFG untuk perhitungan risk
  - Mendaftarkan proyek ke forum TF meeting
    - Merupakan forum go or no-go proyek
    - Merupakan ranah IT strategic planning (Reza Mahendra)
    - User akan present di TF meeting
    - IT planning/strategic akan assessment CR
  - Setelah lulus TF meeting
  - Pemilihan vendor jika ingin dikembangakan ke vendor
  - Join discussion meeting (fix-in dari sisi teknis)

### SDLC

- Tahap:
  1. Tahap perencanaan
     - Join planning session (JPS) (grooming dengan IDG, IOG, SOR)
       - Group dapat mengusulkan proyek-proyek inisiatif yang akan dijalankan
     - Finalisasi DAD (Demand Analysis Document)
     - Finalisasi CR (Customer Requirement) dan FS budget
     - Working group
       - pendiskusian CR
     - Melakukan TF (Technical Feasibility) meeting
     - Menghasilkan dokumen:
       - DAD: Demand Analysis Document
       - FS (Feasibility Study) Anggaran
       - CR: Customer Requirement
  2. Tahap pendefinisian
     - ITSC (steering comitee)
     - Penyusunan project carter
       - Timeline
       - Scope
       - Resiko
       - Dibikin oleh user
       - Dikawal oleh PMO
     - Join discussion meeting
     - Forum arsitektur
     - Menghasilkan dokumen:
       - AAD: Architecture Analysis Document
       - FSD: Functional Specification Document
  3. Tahap pengembangan
  4. Tahap testing plan
  5. Tahap implementasi
  6. Tahap PIR (Post Implementation Review)
- Project di ISG:
  - Inisiatif
    - Melibatkan strategic planning sehingga tanpa TF meeting
  - Enhancement
    - Terdapat TF meeting
- Kategori CR (Customer Requirement):
  - Regulatory: CR yang muncul karena temuan audit atau regulasi
  - Security: CR yang muncul karena kebutuhan keamanan
  - Stabilitas Sistem: CR yang muncul karena kebutuhan stabilitas sistem