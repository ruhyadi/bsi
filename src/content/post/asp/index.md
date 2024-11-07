---
title: "IT Application Support"
publishDate: "04 November 2024"
description: "Digital banking is the future of banking."
tags: ["digital"]
---

## Overview

- ASP group baru (2023 Oktober)
- Pecahan dari IDG
- IDG (70% development)
- ASP (70% analisa)
- Bug fixing, tuning dan troubleshooting (30% coding, ASP)
  - Tidak merubah bisnis proses (harus ke CR terlebih dahulu)
- Monitoring:
  - Production issue passive (Seconda Layer)
  - Memberikan solusi untuk improvement (short term dan long term)
- Setiap solution harus aline dengan management resiko
- Tugas:
  - Struktur ASP
  - Job Desk
  - SDLC di BSI apa saja
  - Arsitektur yang ada di BSI
  - Issue apa saja?
  - Solving bagaimana?
- Hari 1: IT core banking
- Hari 2: IT payment & integration services
- Hari 3: IT wholesale, IT digital banking, IT classic channel
- Hari 4: monitoring, testing
- Hari 5: IT financing

## IT Payment & Integration Services

- Middleware menggunakan SmartVista
  - SmartVista: middleware yang digunakan untuk menghubungkan aplikasi perbankan dengan jaringan kartu dan sistem pembayaran lainnya. Middleware ini memungkinkan aplikasi perbankan untuk berkomunikasi dengan sistem pembayaran eksternal, seperti ATM, EDC, dan sistem pembayaran lainnya.
  - ISO 8583: standar komunikasi yang digunakan oleh SmartVista untuk berkomunikasi dengan sistem pembayaran eksternal. Standar ini memungkinkan aplikasi perbankan untuk mengirim dan menerima pesan transaksi ke dan dari sistem pembayaran eksternal.
- Switching menggunakan SmartVista
  - Switching: proses yang digunakan untuk mengarahkan pesan transaksi dari aplikasi perbankan ke sistem pembayaran eksternal, seperti ATM, EDC, dan sistem pembayaran lainnya. Proses ini memungkinkan aplikasi perbankan untuk berkomunikasi dengan sistem pembayaran eksternal
- Fungsi switching:
  - Routing: proses yang digunakan untuk mengarahkan pesan transaksi dari aplikasi perbankan ke sistem pembayaran eksternal yang tepat. Proses ini memastikan bahwa pesan transaksi dikirim ke sistem pembayaran yang benar.
  - Authorization: proses yang digunakan untuk memvalidasi pesan transaksi dan menentukan apakah transaksi tersebut dapat dilakukan atau tidak. Proses ini memastikan bahwa transaksi yang dilakukan oleh nasabah adalah sah.
  - Clearing: proses yang digunakan untuk menyelesaikan transaksi antara bank pengirim dan bank penerima. Proses ini memastikan bahwa dana yang ditransfer antara bank pengirim dan bank penerima sesuai dengan transaksi yang dilakukan.
- Proses switching:
  - Issuer: bank pengguna
  - Acquire: middle
  - Destination: tujuan rekening
- Flow transfer:
  - Inqueri: menu konfirmasi
  - Transfer: menu transfer
- Bisnis proses:
  - Ticketing dari semua group BSI terkait problem dan incident
  - Memo
  - Menangani semua middleware dan switching
  - Jika tidak mampu/terlalu besar: akan di eskalasi ke IDG
  - Testing: di test oleh teman-teman testing (document QA needs)
  - Solve: mendaftarkan ke tim release untuk deploy ulang
  - IOG: deploy ulang aplikasi

## IT Core Banking

- Pembicara: Rendi
- 2007 BSM Data Center
- 2012 Application Support
- 2017 Development Core Banking Programmer
- 2022 Alamy
- 2023 Dept Head Application Support
- Garansi 3 bulan (jika ada masalah akan balik ke IDG)
- Stream/team:
  - Funding
  - Financing
  - Integration
  - Transaction
  - Operation
  - Wholesale
  - Report and Recon
  - Change Management