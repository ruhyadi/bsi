---
title: "Data Decision Management"
publishDate: "28 October 2024"
description: "Data decision management"
tags: ["digital"]
---

## Introduction

- You are a data driven company only if everyone uses data
- DDM sekarang under directorat digital

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

## Campaign Management

- Membuat data leads (potensi nasabah yang akan berhasil jika ditawarin)
