---
{"dg-publish":true,"permalink":"/skenario/sample-skenario/"}
---

***Decision Support System (DSS)***

Tujuan Sistem Decision Support System (DSS) ini dirancang untuk mendukung manajemen Ayam Chicken UMKM dalam pengambilan keputusan yang efektif dan efisien. Sistem ini memungkinkan pengelolaan stok bahan baku, penyesuaian produksi, pengaturan tenaga kerja, perencanaan strategi penjualan, pengawasan arus kas, serta pembuatan laporan keuangan. Dengan DSS, keputusan terkait pesanan harian maupun pesanan besar seperti catering dapat diambil secara cepat, tepat, dan berbasis data.

1.      Struktur Organisasi, Divisi Operasional, & Divisi Produksi bekerja berdasarkan stok dari gudang untuk memastikan seluruh menu harian dan pesanan catering dapat diproduksi sesuai standar kualitas. Divisi Finance mengawasi pengeluaran dan laba untuk menjaga kesehatan keuangan UMKM. Divisi SDM mengatur jadwal kerja karyawan agar operasi berjalan lancar. Divisi Marketing memanfaatkan data tren penjualan untuk merancang strategi promosi. Pemilik UMKM dapat memantau seluruh aktivitas dan mengambil keputusan strategis melalui dashboard DSS.

|Divisi|Fungsi Utama|Tanggung Jawab|Output DSS|
|---|---|---|---|
|Produksi & Dapur|Memasak ayam geprek, fried chicken, sambal, dan nasi|Menjaga kualitas dan kuantitas produk|Data output harian|
|Gudang & Logistik|Mengelola stok bahan baku dan pengiriman|Menjamin ketersediaan bahan secara kontinu|Laporan stok dan notifikasi restock|
|Penjualan & Marketing|Mengatur penjualan outlet, online, dan catering|Mencapai target penjualan serta merencanakan promosi|Data tren penjualan|
|Finance|Mengelola arus kas, biaya, dan laba rugi|Memastikan pengendalian keuangan dan profitabilitas|Laporan keuangan|
|SDM / HRD|Mengatur jadwal dan kinerja karyawan|Memastikan tenaga kerja digunakan secara efisien|Data jam kerja dan produktivitas|
|Owner / Manajemen|Mengambil keputusan strategis|Memantau kinerja seluruh divisi|Dashboard DSS|

2.      Data Stok Gudang (Awal Minggu) Gudang bertugas memastikan seluruh bahan baku tersedia sesuai kebutuhan produksi harian dan catering. Divisi Produksi menggunakan stok ini untuk merencanakan produksi. Divisi Finance memantau biaya pembelian bahan baku untuk menjaga profitabilitas. Sistem DSS memberikan peringatan otomatis jika stok ayam atau minyak mendekati batas minimum.

|Bahan Baku|Satuan|Stok Awal|Kebutuhan Harian|Batas Minimum|Supplier|Harga Beli|
|---|---|---|---|---|---|---|
|Ayam Potongan (mix: dada, paha, sayap)|kg|30|18|10|PT Ayam Segar Sejahtera|Rp40.000/kg|
|Tepung Krispi|kg|10|5|3|UD Bumbu Jaya|Rp15.000/kg|
|Minyak Goreng|liter|25|10|5|PT Minyak Abadi|Rp18.000/liter|
|Sambal Bakar|kg|3|1|0.5|Produksi sendiri|Rp30.000/kg|
|Sambal Bumbu Hitam|kg|3|1|0.5|Produksi sendiri|Rp32.000/kg|
|Hot Lava Sauce|kg|2.5|0.8|0.4|Produksi sendiri|Rp35.000/kg|
|Keju Parut|kg|2|0.6|0.3|Distributor Lokal|Rp85.000/kg|
|Nasi Putih|kg|30|15|10|Supplier Beras Harum|Rp13.000/kg|

3.      Menu & Harga Jual Terbaru Divisi Produksi menyiapkan menu sesuai pesanan harian maupun catering. Finance menghitung biaya produksi tiap menu untuk memastikan margin tetap sehat. Divisi Marketing dapat merancang promosi atau paket bundling berdasarkan menu yang tersedia. Divisi SDM mengatur jadwal kerja dapur agar semua pesanan dapat diselesaikan tepat waktu.

|Menu|Harga|
|---|---|
|Paket Nasi Ayam Geprek Sambal Bakar|Rp18.000|
|Paket Nasi Ayam Geprek Bumbu Hitam|Rp18.000|
|Paket Nasi Ayam Geprek Fire Lava Cheese|Rp20.000|
|Ayam Geprek saja (tanpa nasi)|Rp14.000|
|Ayam Fried Chicken saja (tanpa sambal & nasi)|Rp11.000|
|Nasi Putih saja|Rp5.000|

4.      Data Penjualan Rata-Rata (Outlet & Online) Data penjualan ini menunjukkan menu yang paling diminati pelanggan. Divisi Marketing dapat memanfaatkan informasi ini untuk menyusun strategi promosi. Divisi Produksi menyesuaikan kapasitas masak agar stok menu tersedia sesuai permintaan. Divisi Finance mencatat pendapatan harian dan melakukan analisis margin.

|Menu|Penjualan / Hari|Pendapatan / Hari|Kontribusi ke Total|
|---|---|---|---|
|Paket Nasi Ayam Geprek Sambal Bakar|35 porsi|Rp630.000|30%|
|Paket Nasi Ayam Geprek Bumbu Hitam|25 porsi|Rp450.000|21%|
|Paket Nasi Ayam Geprek Fire Lava Cheese|20 porsi|Rp400.000|19%|
|Ayam Geprek saja|10 porsi|Rp140.000|7%|
|Ayam Fried Chicken saja|5 porsi|Rp55.000|3%|
|Nasi Putih saja|10 porsi|Rp50.000|5%|
|Total|105 porsi|Rp1.725.000|100%|

5.      Pesanan Catering Khusus (100 Porsi Campur) Pesanan catering memerlukan perencanaan stok dan produksi tambahan. DSS menghitung kebutuhan bahan baku tambahan berdasarkan jumlah porsi catering. Divisi Produksi menyesuaikan jadwal memasak, SDM mengatur jam kerja dan lembur, Finance memantau biaya tambahan, dan Logistik menyiapkan pengiriman bahan.

|Rincian|Jumlah|Harga|Total|
|---|---|---|---|
|Catering Campur (25x4 varian)|100 porsi|Rp18.000|Rp1.800.000|

6.      Dampak Operasional dari Catering Peningkatan jumlah pesanan catering berdampak langsung pada kebutuhan bahan baku dan kapasitas produksi. DSS menghitung kebutuhan tambahan untuk setiap bahan.

| Aspek         | Sebelum Catering | Tambahan Catering | Total Kebutuhan |
| ------------- | ---------------- | ----------------- | --------------- |
| Ayam Potongan | 18 kg            | +22 kg            | 40 kg           |
| Tepung Krispi | 5 kg             | +6 kg             | 11 kg           |
| Minyak Goreng | 10 liter         | +8 liter          | 18 liter        |
| Sambal Campur | 2.8 kg           | +3.5 kg           | 6.3 kg          |
| Keju          | 0.6 kg           | +1.5 kg           | 2.1 kg          |
| Nasi          | 15 kg            | +10 kg            | 25 kg           |
7.      Sistem Keuangan (Finance) Finance mengelola seluruh aliran kas dan memantau biaya tambahan akibat catering. DSS menghasilkan laporan mingguan otomatis.

|Jenis Transaksi|Sebelum Catering|Setelah Catering|Keterangan|
|---|---|---|---|
|Pendapatan Penjualan|Rp12.950.000|Rp14.650.000|Termasuk 100 porsi catering|
|Biaya Produksi|Rp7.200.000|Rp8.400.000|Biaya tambahan catering|
|Laba Kotor|Rp5.750.000|Rp6.250.000|Margin tetap stabil|
|Biaya Operasional (gaji, listrik, sewa)|Rp2.000.000|Rp2.200.000|Tambahan lembur dan transport|
|Laba Bersih Mingguan|Rp3.750.000|Rp4.050.000|Kenaikan Rp300.000|

Rasio Keuangan: Margin kotor 43%, margin bersih 27%, ROI 15% per bulan, perputaran persediaan 4x/minggu.
