---
title: "IT Application Support"
publishDate: "04 November 2024"
description: "Digital banking is the future of banking."
tags: ["digital"]
---

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