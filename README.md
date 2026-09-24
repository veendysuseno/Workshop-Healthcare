# 🏥 Workshop-Healthcare

## IoT Microcontroller: Healthcare Monitoring System

Workshop **Mikrokontroler (Healthcare)** yang mempelajari penggunaan **WeMos ESP8266** sebagai perangkat utama dalam membangun sistem **Healthcare Monitoring berbasis Internet of Things (IoT)**.

Workshop ini mencakup pengenalan perangkat mikrokontroler, pemrograman IoT, cara kerja sensor medis, serta implementasi sistem monitoring menggunakan **Arduino IDE** dan **ThingSpeak**.

---

## 🎯 Objectives

Workshop ini bertujuan agar peserta mampu:

1. Memahami **pin-pin yang tersedia pada IoT MCU (WeMos ESP8266)**.
2. Memahami dasar-dasar **pemrograman IoT MCU**.
3. Mempelajari fungsi dan aplikasi dari **IoT MCU**.
4. Memahami prinsip kerja **sensor medis/healthcare**.
5. Memahami pemrograman dan implementasi **teknologi IoT**.
6. Mengimplementasikan sistem monitoring data kesehatan secara real-time melalui internet.

---

## 🧠 Workshop Topics

Materi yang dipelajari dalam workshop meliputi:

- Pengenalan **WeMos ESP8266**
- Pengenalan pin dan GPIO
- Dasar-dasar pemrograman mikrokontroler
- Penggunaan **Arduino IDE**
- Konsep dasar **Internet of Things (IoT)**
- Cara kerja sensor medis
- Pembacaan data dari sensor
- Pengiriman data sensor melalui jaringan Wi-Fi
- Monitoring data menggunakan **ThingSpeak**
- Implementasi **Healthcare Monitoring System**

---

## 🛠️ Hardware

Perangkat yang digunakan dalam workshop antara lain:

- **WeMos ESP8266**
- Sensor kesehatan/medis
- Kabel USB
- Breadboard
- Jumper wires
- Komputer/Laptop
- Wi-Fi / Internet

> Jenis sensor dapat disesuaikan dengan modul praktikum yang digunakan.

---

## 💻 Software & Platform

| Software / Platform | Fungsi |
|---|---|
| **Arduino IDE** | Pemrograman dan upload program ke WeMos ESP8266 |
| **ThingSpeak** | Monitoring dan visualisasi data IoT |
| **ESP8266 Board Package** | Dukungan board ESP8266 pada Arduino IDE |
| **Wi-Fi** | Komunikasi data antara perangkat dan internet |

---

## 🔌 System Overview

Secara umum, sistem **Healthcare Monitoring System** bekerja dengan alur berikut:

```text
┌─────────────────┐
│  Medical Sensor │
└────────┬────────┘
         │
         │ Sensor Data
         ▼
┌─────────────────┐
│ WeMos ESP8266   │
│   IoT MCU       │
└────────┬────────┘
         │
         │ Wi-Fi
         ▼
┌─────────────────┐
│    Internet     │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│   ThingSpeak    │
│ Data Monitoring │
└─────────────────┘

