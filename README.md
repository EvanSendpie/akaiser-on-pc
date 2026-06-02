# Panduan Memainkan Animal Kaiser di PC dengan Emulator Play!

Panduan ini menjelaskan cara mengatur dan memainkan *Animal Kaiser* (game arcade klasik) di PC menggunakan emulator PlayStation 2, **Play!**.

## Persyaratan Sistem
* **Emulator:** [Play! Emulator](https://purei.org/) (Unduh versi terbaru untuk sistem operasi Anda).
* **File Game:** File ISO game *Animal Kaiser*.
* **Kontroler:** Disarankan menggunakan gamepad (Xbox, PlayStation, atau USB Controller lainnya) untuk pengalaman bermain yang lebih baik, tapi keyboard juga gapapa.

## Langkah-langkah Instalasi & Konfigurasi

### 1. Persiapan Emulator
1.  Unduh emulator Play! dari situs resmi [purei.org](https://purei.org/). Atau bisa pada kolom "Release" repo ini.
2.  Ekstrak file emulator ke folder yang diinginkan di PC Anda.
3.  Jalankan file `Play.exe` (untuk Windows).
4.  Sesuaikan setting di emulator Play! Seperti gambar di bawah ini:
   
    <img width="310" height="228.5" alt="image" src="https://github.com/user-attachments/assets/95497b21-2e30-45c2-94e9-1a135cdf3123" />

6.  Untuk settingan grafis, bisa menyesuaikan denga spesifikasi perangkat masing-masing, namun untuk GS Handler, saya sangat merekomendasikan menggunakan Vulkan supaya tidak muncul kotak-kotak aneh saat bermain.
    <img width="311" height="230" alt="image" src="https://github.com/user-attachments/assets/fe2a3cdb-3270-4437-b92e-c3940890bbc5" />

8.  Jika dirasa sudah seleasi, bisa klik close.

### 2. Memuat Game
1.  Ekstrak file ROM yang sudah saya bagikan dengan nama file ```KP012B_AnimalKaiserNAND```, yang kemudian setelah di ekstrak muncul file ```kp012b_k9k8g08u0b.ic31```.
2.  Pindahkan file ROM tersebut ke ```C:\Users\(nama user)\Documents\Play Data Files\arcaderoms\``` dan buat folder baru bernama akaiser.
3.  Buka emulator Play!.
4.  Klik menu **File** > **Open** atau **Load**.
5.  Cari file ISO game *Animal Kaiser* yang sudah Anda miliki di direktori komputer Anda, saya meletakkan di ```C:\Users\Stefanus Evan\Documents\Play Data Files\arcaderoms\akaiser```.
6.  Game akan mulai berjalan secara otomatis.

### 3. Konfigurasi Kontroler
1.  Masuk ke menu **Settings** atau **Input** pada emulator.
2.  Petakan tombol (*mapping*) sesuai dengan kenyamanan Anda:
    * **D-Pad/Analog:** Untuk pergerakan.
    * **Tombol Aksi (X, O, Segitiga, Kotak):** Untuk memilih kartu atau menyerang.
    * **Start/Select:** Untuk menu dan pause.
  
### 4. Ketika Bermain
1. Buka emulator Play!
2. Pilih **Animal Kaiser Evolution 8**
3. Jika muncul gambar seperti di bawah, jangan panik. Saya berikan troublesshootnya.
   <img width="478" height="283.5" alt="image" src="https://github.com/user-attachments/assets/b2840955-c258-4888-a86a-5427bc88cc78" />

4. Tahan tombol 1 maka akan memunculkan Menu, pilih ke **COIN OPTIONS** dengan menekan "Z" tanpa melepas tombol 1.
5. Kemudian pada opsi free play, ganti menjadi **ON**.
6. Setelah itu pilih exit dengan mennekan tombol "Z".
7. Pilih **GAME OPTIONS** dengan menekan tombol "Z".
8. Sesuaikan dengan setting saya ini, terutama pada setting **"CARD DISPENSER ENABLE"** wajib di-OFFkan.
   <img width="465" height="285" alt="image" src="https://github.com/user-attachments/assets/e963e738-66c1-4048-aeef-6c4ada1e24ef" />

10. Untuk settingan lainnya siilahkan menyesuaikan masing masing.
11. Lepas angka 1 maka akan langsung masuk ke gamenya. Have fun!
   <img width="478" height="290" alt="image" src="https://github.com/user-attachments/assets/f77a7134-a51d-4588-8ff8-ade2ca9269c7" />


## Tips Bermain
* **Simpan Game (Save State):** Gunakan fitur *Save State* emulator untuk menyimpan progres kapan saja, karena *Animal Kaiser* adalah game yang sangat bergantung pada waktu respon.
* **Performa:** Jika game terasa lambat (*lag*), cek pengaturan **Graphics** di dalam emulator dan turunkan resolusi internal (jika tersedia).
* **Koneksi Kontroler:** Pastikan kontroler terhubung sebelum emulator dibuka agar terdeteksi dengan benar.

## Pemecahan Masalah (Troubleshooting)
* **Game Tidak Terbaca:** Pastikan file ISO tidak korup. Coba unduh ulang atau buat ulang *dump* ISO dari kaset asli.
* **Emulator Crash:** Pastikan *driver* kartu grafis PC Anda sudah versi terbaru.
* **Input Tidak Berfungsi:** Coba atur ulang *mapping* tombol di menu input dan pastikan kontroler sudah terdeteksi di *Device Manager* Windows.

---
