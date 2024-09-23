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

## IT Implementation and Monitoring

- Handling deployment untuk production
- Punya room monitoring

### Core Banking

### Non Core Banking

### E-Channel

### Change and Release

## Data Center Management

### Data Center

- Jakarta (Rempoa), DCI (Data Center Indonesia) dan Surabaya

### Data Center Recovery

### Data Warehouse

- Seperti DDM. Pada IOG datanya secara live (data production)
- Housekeeping dan update data

## IT Infrastructure/Network Management

### Infrastructure Engineer

### Network Operation Center (NOC)

### Network Management

- Penyedia IP untuk server

## IT Infrastructure Ops Management & Optimization

- Departemen yang menaungi IOG
- Bertindak sebagai PM untuk IOG
- Governance di IOG

## Cloud Infrastructure Technology

### Cloud Delivery Otomation

### Cloud Microservices & Application Platform

### Cloud Network & Load Balancer Support