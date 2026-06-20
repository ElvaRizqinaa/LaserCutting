# LaserCutting
Proses desain untuk laser cutting menggunakan CorelDraw X6, sekaligus cara praktis mengoperasikan mesin laser cutter.

# Praktikum Laser Cutting: Dari CorelDraw X6 ke Wujud Nyata
Repository ini mendokumentasikan keseluruhan alur kerja (*workflow*) pembuatan produk fisik menggunakan teknologi pemotongan laser pada material akrilik. 
Proyek ini merupakan bagian dari pemenuhan tugas mata kuliah **Praktikum CAD CAM**, program studi **Teknologi Rekayasa Otomasi, Sekolah Vokasi Universitas Diponegoro**.

## Tentang Proyek Ini
Tujuan utama dari proyek ini adalah mendemonstrasikan bagaimana desain vektor 2D digital dapat dieksekusi menjadi bentuk fisik yang akurat. Mulai dari perancangan geometri sederhana hingga bentuk fungsional seperti dudukan LCD, proyek ini mencakup dua fase utama: perancangan di perangkat lunak dan eksekusi di perangkat keras mesin.

## Fase 1: Desain (CorelDraw X6)
Semua perancangan dilakukan menggunakan perangkat lunak CorelDraw X6 dengan mengedepankan presisi dimensi. Proses meliputi:
* **Penentuan Skala:** Penyesuaian satuan ukur (inci, cm, mm) untuk memastikan ukuran aktual.
* **Geometri Dasar & Fungsional:** Perancangan persegi panjang dan lingkaran untuk membuat komponen presisi seperti dudukan (*mounting*) LCD.
* **Bentuk Kreatif:** Penggunaan *ellipse tool, rectangle tool, two-point line tool,* dan *shape tool* untuk merancang objek kustom (gantungan kunci, angka, awan, hati, dan bintang).
* **Konversi Teks:** Mengubah elemen *font* menjadi *outline* (kurva) agar jalur potong (*cutting path*) dapat dibaca oleh mesin laser.

## Fase 2: Eksekusi (Laser Cutter)
Tahap manufaktur menggunakan mesin *laser cutter* dengan material dasar lembaran akrilik. Parameter dan langkah operasi yang dilakukan:
* **Transfer Data:** Mengirim desain dari PC ke *software* bawaan mesin menggunakan kabel USB.
* **Kalibrasi Area:** Menyelaraskan posisi akrilik dan menggunakan fitur *Preview* (simulasi) untuk memastikan pergerakan laser tidak keluar dari material.
* **Parameter Pemotongan (*Cutting*):**
  * **Power (Kekuatan Laser):** `30`
  * **Speed (Laju Pergerakan):** `10`
* **Proses Akhir:** Eksekusi pemotongan dan prosedur aman mematikan mesin.
