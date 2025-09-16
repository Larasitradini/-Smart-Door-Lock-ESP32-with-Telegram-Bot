# -Smart-Door-Lock-ESP32-with-Telegram-Bot
# 🔐 Smart Door Lock ESP32 with Telegram Bot

Proyek ini adalah **sistem kontrol pintu otomatis** berbasis **ESP32** dan **Telegram Bot**.  
ESP32 akan menerima perintah melalui **Telegram** untuk membuka, menutup, atau mengecek status pintu.  
Servo digunakan sebagai aktuator pintu, sedangkan status dikirimkan kembali lewat chat Telegram.

🔗 **Live Simulation on Wokwi**  
👉 [Klik di sini untuk membuka proyek di Wokwi](https://wokwi.com/projects/420598687549376513)

---

## 🚀 Fitur Proyek
- Kontrol pintu jarak jauh lewat **Telegram Bot**.  
- Perintah tersedia:  
  - `/buka` → Membuka pintu.  
  - `/tutup` → Menutup pintu.  
  - `/status_pintu` → Mengecek kondisi pintu.  
- Respon balik otomatis di Telegram sesuai aksi.  
- Menggunakan **servo motor** untuk menggerakkan pintu.  
- Dapat digunakan untuk sistem **Smart Home**.  

---

## 🛠️ Hardware
- ESP32  
- Servo Motor (SG90 atau sejenis)  
- Push Button / Sensor untuk status pintu (opsional)  

---

## 📂 Struktur Project
