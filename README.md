# Scduler-time

# 🔔 Smart Alarm with Arduino + DFPlayer + RTC + LCD

Proyek ini adalah alarm otomatis yang bisa memutar suara tertentu pada jam yang sudah ditentukan. Ditampilkan juga waktu, tanggal, hari, dan bonus **kalimat motivasi random** di LCD! Cocok untuk dijadikan sebagai **desk accessory** atau pengingat ibadah harian.

> 🎧 Suara alarm bisa kamu ganti sendiri!  
> 📅 Alarm berjalan otomatis berdasarkan hari & jam  
> 💡 Dilengkapi quote random buat nemenin kamu ngoding!

---

## 📦 Komponen yang Digunakan

| No | Komponen                | Keterangan                        |
|----|-------------------------|------------------------------------|
| 1  | Arduino Uno R3          | Otak dari sistem                   |
| 2  | LCD I2C (20x4 / 16x2)   | Menampilkan waktu & motivasi       |
| 3  | RTC Module (DS3231)     | Menyimpan waktu & tanggal          |
| 4  | DFPlayer Mini           | Memutar suara dari file .mp3       |
| 5  | Micro SD Card           | Media penyimpanan suara            |
| 6  | Speaker                 | Output suara alarm                 |
| 7  | Proto Shield            | Alternatif breadboard (lebih rapi) |
| 8  | Jumper Wire             | Penghubung antar komponen          |

---

## 🛠️ Cara Pasang Hardware (Wiring)

**LCD & RTC** (pakai I2C, bisa sharing pin):  
- SDA → A4  
- SCL → A5  
- VCC → 5V  
- GND → GND

**DFPlayer Mini**:  
- TX → pin 2  
- RX → pin 3  
- VCC → 5V  
- GND → GND  
- Speaker → SPK_1 & SPK_2  
- SDCard → Format FAT32, file: `0001.mp3`, `0002.mp3`, dll.

---

