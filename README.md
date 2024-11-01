# TransjakartaTransaction
Public Transportation Transaction Transjakarta
# **Latar Belakang**
Sebagai penyedia layanan Jasa transportasi Bus Rapid Transit (BRT) di indonesia, Pemerintah provinsi DKI Jakarta menginginkan masukan dari Data analyst untuk meningkatkan performa pelayanan yang lebih baik.
Menurut Data yang disediakan di BPS, terjadi peningkatan jumlah penumpang dari Tahun 2023-2024 sebesar 6,83% dibandingkan tahun sebelumnya. 
Peningkatan jumlah penumpang ini diiringi oleh perkembangan jumlah bus yang melayani yakni sebanyak 4.400 unit bus pada Januari 2024. Sementara itu, pada Januari 2023, jumlah bus yang melayani penumpang baru mencapai 3.850 unit. [_berita terkait_](https://www.antaranews.com/berita/3992097/jumlah-penumpang-transjakarta-januari-2024-capai-30-juta)

## Pernyataan Masalah
Pemerintah DKI Jakarta ingin mendapatkan solusi dari data yg diamati seperti :
- Mengurangi durasi perjalanan yg lama dari 1 ke koridor tujuan tertentu,
- Jumlah kartu yang digunakan pengguna berdasarkan rentang umur dan perilaku perjalanan, 
- Efisiensi penggunaan rute (waktu tempuh),
- Ketersediaan jumlah Bis di Rute Tersibuk,
- Total pendapatan per rute,
- Prediksi jam-jam tersibuk setiap hari.

Sehingga dengan analisa yg tepat, Transjakarta sebagai penyedia bisnis jasa dapat berkembang menjadi lebih baik dan meningkatkan pelayanan nya

# **Tentang Dataset Transjakarta**
Dataset terdiri dari 22 kolom, dataset berdasarkan data perjalanan bulan april 2023 dimana ada 1 unik ID dan kolom-kolom lain untuk dianalisa

Berikut daftar isi Dataset yang sudah di siapkan
1.	transID: ID transaksi unik untuk setiap transaksi
2.	payCardID: Pengidentifikasi utama pelanggan. Kartu yang digunakan pelanggan sebagai tiket masuk dan keluar.
3.	payCardBank: Nama bank penerbit kartu pelanggan
4.	payCardName: Nama pelanggan yang disematkan di kartu.
5.	payCardSex: Jenis kelamin pelanggan
6.	payCardBirthDate: Tahun lahir pelanggan
7.	corridorID: ID Koridor / ID Rute sebagai kunci untuk pengelompokan rute.
8.	corridorName: Nama Koridor / Nama Rute berisi Awal dan Akhir untuk setiap rute.
9.	direction: 0 untuk Pergi, 1 untuk Kembali. Arah rute.
10.	tapInStops: Tap In (entrance) Stops ID for identifying stops name
11.	tapInStopsName: ID Perhentian Tap In (pintu masuk) untuk mengidentifikasi nama perhentian
12.	tapInStopsLat: Latitude perhentian tap in
13.	tapInStopsLon: Longitude perhentian tap in
14.	stopStartSeq: Urutan pemberhentian, pemberhentian pertama, pemberhentian kedua, dst. Terkait dengan arah.
15.	tapInTime: Waktu tap in. Tanggal dan waktu
16.	tapOutStops: ID pemberhentian Tap Out (Keluar) untuk mengidentifikasi nama pemberhentian
17.	tapOutStopsName: Nama pemberhentian Tap out (keluar) tempat pelanggan melakukan tap out.
18.	tapOutStopsLat: Latitude perhentian tap out
19.	tapOutStopsLon: Longitude perhentian tap out
20.	stopEndSeq: Urutan pemberhentian, pemberhentian pertama, pemberhentian kedua, dst. Terkait dengan arah.
21.	tapOutTime: Waktu tap out. Tanggal dan waktu
22.	payAmount: Jumlah yang dibayarkan pelanggan. Sebagian gratis. Sebagian tidak.
