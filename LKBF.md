
# **SOP Penggunaan Teleskop**
## **1. Persiapan Awal**
### **a. Membuka Ruangan**

1. Buka pintu rumah teleskop dan kaitkan pintu agar tidak tertutup atau mengayun karena angin.
![Image](https://github.com/zak-kya/SOP-teleskop/blob/images/1748936753938.jpg)
2. Periksa kondisi dalam ruangan:
    - Pastikan tidak ada kebocoran air atau area yang basah.
    - Amati kondisi sekitar untuk memastikan tidak ada hal yang tidak normal (bau terbakar, kabel terlepas, dll.).
### **b. Pengisian Logbook**
1. Segera setelah tiba, isi **logbook fisik** yang tersedia di meja:
    - Tanggal
    - Nama pengguna
    - Waktu mulai aktivitas
![Image](https://github.com/zak-kya/SOP-teleskop/blob/images/1748936753560.jpg)
![Image](https://github.com/zak-kya/SOP-teleskop/blob/images/1748936753543.jpg)
2. Baca entri terakhir dalam logbook:
    - Perhatikan catatan masalah sebelumnya, terutama terkait listrik atau perangkat.
    - Pastikan tidak ada kerusakan atau keganjilan sebelum memulai.
3. Setelah selesai:
    - Catat waktu selesai
    - Rincian aktivitas
    - Objek yang diamati atau peristiwa menarik
    - **Catat semua masalah atau gangguan**, sekecil apa pun.
4. Bila mengalami masalah yang menghambat observasi:
    - Hubungi kontak darurat yang tertera di halaman depan logbook.
    - Jika lewat tengah malam, hanya hubungi jika **masalah bersifat kritis**, seperti atap tidak bisa ditutup atau teleskop rusak parah.
    - Untuk masalah umum, catat di logbook dan kirim email ke: [m.yusuf@itb.ac.id](mailto:m.yusuf@itb.ac.id)
## **2. Persiapan Teleskop**
### **a. Membuka Penutup Teleskop**
1. Lepaskan pengunci arah teleskop (altitude dan azimuth).
2. Arahkan teleskop ke posisi **aman**:
    - **Altitude: 0°**, **Azimuth: 180°** (posisi mendatar ke selatan).
3. Buka penutup bagian-bagian teleskop secara berurutan:
    - Cermin sekunder
    - Baffle (tabung pelindung cahaya)
    - Cermin primer
### **b. Membuka Atap (Rumah Teleskop)**
**‼ WAJIB dilakukan sebelum membuka atap:**
1. **Cek kondisi cuaca terlebih dahulu** melalui situs cuaca lokal observatorium:
    🔗 [http://167.205.7.36](http://167.205.7.36)
2. **JANGAN membuka atap dalam kondisi berikut:**
    - **Hujan**
    - **Kabut tebal**
    - **Angin kencang** (lebih dari **25 km/jam**)
3. **Jangan langsung membuka atap setelah hujan berhenti.**    
    Pastikan atap dan udara sekitar cukup kering dan aman untuk pengoperasian peralatan optik dan elektronik.
4. Setelah memastikan kondisi **aman dan stabil**, lakukan langkah pembukaan atap seperti berikut:
	1. Buka pengunci geser atap.
	2. Pastikan **tidak ada orang atau benda** di luar garis batas merah.
	3. Periksa kembali bahwa teleskop sudah dalam posisi aman.
	4. Geser atap ke arah **selatan** hingga tanda merah segaris.
	5. Kunci kembali posisi atap setelah terbuka penuh.
## **3. Menyalakan Sistem Elektronik**
### **a. Menyambungkan Daya**
1. Sambungkan **UPS** (Uninterruptible Power Supply) ke sumber listrik utama.
2. Sambungkan kabel perangkat ke UPS sesuai label:
    - L350
    - AC40404
    - SC4
3. Sambungkan kabel **LAN** ke komputer.
### **b. Mengaktifkan Sistem**
1. Tekan tombol power untuk menyalakan **UPS**.
2. Nyalakan:
    - Power EFA (Electronic Focuser Adapter)
    - Dew Heater (pemanas embun)
    - Pemanas kamera pengintai
	- Power mount
3. Nyalakan komputer pengendali.
## 4. Koneksi Kendali Jarak Jauh Komputer
Jika Anda perlu mengakses komputer pengendali dari jarak jauh:
1. Pastikan komputer pengendali telah terhubung ke jaringan LAN dan internet.
2. Gunakan perangkat Anda (laptop/PC) untuk membuka aplikasi RustDesk.
3. Masukkan ID dan Password yang tercantum di logbook pengamatan.
4. Setelah berhasil tersambung, Anda bisa mengoperasikan komputer pengendali secara penuh dari jarak jauh.


### Catatan Keamanan:
- Jangan membagikan ID dan password RustDesk ke pihak yang tidak berwenang.
- Gunakan koneksi ini hanya untuk keperluan pemantauan dan pengoperasian perangkat lunak astronomi.

## **5. Menjalankan Perangkat Lunak**
### **a. PWI4**
1. Buka perangkat lunak **PWI4**.
2. Mount (teleskop), EFA, dan Dew Heater akan **terhubung secara otomatis**.
### **b. MaximDL6 (To be changed)**
1. Jalankan **MaximDL6**.
2. Hubungkan kamera ke perangkat lunak.
3. Aktifkan sistem pendingin kamera (**Cooler ON**).
### **c. PHD2**
1. Jalankan **PHD2** (guiding software).
2. Hubungkan semua perangkat yang dibutuhkan untuk auto-guiding (kamera, mount, dll.).

## **6. Prosedur Penutupan**
Sebelum meninggalkan rumah teleskkop, **pastikan semua prosedur penutupan dilakukan secara lengkap dan berurutan**. Lakukan seluruh **prosedur start-up secara terbalik**, meliputi:
1. **Panaskan kamera ke temperatur ambien.**
2. **Tutup seluruh perangkat lunak** (PHD2, MaximDL6, PWI4) sesuai urutan yang benar.
3. **Matikan sistem komputer dan semua perangkat keras**:
    - Komputer
    - Pemanas kamera
    - Dew Heater
    - EFA
    - Mount
    - UPS (jika aman untuk dimatikan)
    - Cabut kabel LAN
4. **Tutup penutup teleskop**:
    - Cermin primer
    - Baffle
    - Cermin sekunder
5. **Kembalikan teleskop ke posisi aman** jika belum dilakukan.
6. **Tutup atap rumah teleskop**:
    - Buka pengunci geser
    - Geser atap kembali ke posisi semula
    - Pastikan semua garis merah sejajar dan tidak ada benda di lintasan
    - Kunci kembali atap rumah teleskop
    
7. **Periksa kembali seluruh kondisi rumah teleskop**:
    - Tidak ada kabel tersisa terhubung
    - Semua alat dalam kondisi mati
    - Area bersih dan tertutup rapi
    

### **PENTING!**
**Telah dipasang checklist penutupan di pintu rumah teleskop.**
Sebelum meninggalkan observatorium:
- **Periksa satu per satu isi checklist tersebut.**
- Pastikan setiap langkah telah dilakukan dan dicek.
- **Selalu bawa kunci rumah di tangan Anda sebelum menutup pintu!**
