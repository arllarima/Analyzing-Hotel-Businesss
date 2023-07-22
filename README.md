# Analyzing-Hotel-Businesss
**Dataset** : Provided by Rakamin Academy <br>
**Programming Language** : Python <br>
**Libraries** : Pandas, NumPy

## Overview
Sangat penting bagi perusahaan untuk selalu menganalisis kinerja bisnisnya. Analisis kinerja bisnis dapat membantu mengidentifikasi masalah dan kemudian menerapkan strategi untuk mengatasi masalah tersebut sehingga perusahaan dapat mencapai potensi optimalnya. <br>
Kali ini saya akan mendalami industri perhotelan untuk mencari tahu. Fokus saya adalah menganalisis perilaku pelanggan selama reservasi hotel dan faktor apa yang memengaruhi tingkat pembatalan reservasi. Hasil insight yang saya temukan nantinya akan disajikan melalui visualisasi untuk pemahaman yang lebih baik. <br>

## Data Pre-Processing
Beberapa tahapan yang dilakukan pada pre-processing:
1. Mengatasi missing values pada beberapa kolom dengan cara mengisi missing values dan ada beberapa yang di drop.
2. Mengganti beberapa nilai yang tidak sesuai pada data.
3. Mengganti beberapa tipe data, supaya pemrosesan ke depannya menjadi lebih mudah.
4. Menghapus data-data yang tidak di perlukan, seperti total tamu dan stay duration yang berjumlah 0.

## Data Analysis and Visualization
### 1. Monthly Hotel Booking Analysis Based on Hotel Type
Analisis ini akan dilakukan untuk melihat dan menganalisis pada bulan apa (atau musim apa) terjadi kenaikan dan penurunan dari jumlah pemesanan hotel untuk setiap jenis hotel. <br>

<p align="center">
  <kbd><img src="additional/visualisasi tren.png" width=600px> </kbd> <br>
  Gambar 1. Visualisasi Tren City Hotel dan Resort Hotel
</p>

Dari visualisasi data diatas, dapat kita analisa bahwa: <br>
1. Hotel memiliki dua kali masa peak season, yaitu pada bulan Mei-Juli dan bulan November-Desember. Pada bulan Mei-Juli kemungkinan karena libur semester bagi mahasiswa Indonesia dan pada bulan November-Desember kemungkinan karena libur Natal dan Tahun Baru. <br>
2. Pada bulan Januari-Maret tingkat reservasi hotel menjadi yang terendah. Hal ini mungkin karena sedikitnya hari libur nasional dan saat ini adalah awal tahun ajaran baru bagi siswa dan bukan waktu untuk perjalanan bisnis yang sibuk karena masih awal tahun. <br>
3. Untuk mengoptimalkan resource hotel di luar peak season, dapat dilakukan dengan menawarkan promo holiday deals di awal tahun. <br>
<br>
### 2. Impact Analysis of Stay Duration on Hotel Bookings CancelLation Rate
Analisis ini akan dilakukan untuk mencari tahu bagaimana korelasi antara durasi menginap terhadap tingkat pembatalan pemesanan hotel. <br>

<p align="center">
  <kbd><img src="additional/cancelation rate.png" width=600px> </kbd> <br>
  Gambar 2. Persentase Cancellation Rate terhadap Stay Duration
</p>

Dari visualisasi data diatas, dapat kita analisa bahwa: <br>
1. Tingkat pembatalan yang tinggi di kedua hotel tergantung pada lamanya waktu pemesanan. Hal ini kemungkinan terjadi karena semakin lama menginap, semakin tinggi tagihan hotel. Pelanggan dapat memeriksa opsi lain seperti perbandingan harga, yang mengarah pada pembatalan reservasi hotel. <br>
2. Ke depannya pihak hotel bisa menerapkan kebijakan pembatalan untuk mengurangi tingkat pembatalan. Semakin lama periode pemesanan, semakin tinggi biaya pembatalannya. <br>
<br>
### 3. Impact Analysis of Lead Time on Hotel Bookings CancelLation Rate
Analisis ini akan dilakukan untuk mencari tahu bagaimana korelasi antara jarak waktu pemesanan hotel (lead time) terhadap tingkat pembatalan pemesanan hotel. <br>

<p align="center">
  <kbd><img src="additional/lead time cancelation rate.png" width=600px> </kbd> <br>
  Gambar 2. Persentase Cancellation Rate terhadap Lead Time
</p>

Dari visualisasi data diatas, dapat kita analisa bahwa: <br>
1. Tingkat pembatalan tertinggi ada pada City Hotel dengan lead time 10 bulan hingga 1 tahun, sementara Resort Hotel memiliki tingkat pembatalan stabil sekitar 40%. <br>
2. City Hotel yang terletak di pusat kota dan sering digunakan untuk acara atau bisnis cenderung rentan terhadap pembatalan karena perubahan jadwal atau penawaran lebih baik di tempat lain. Di sisi lain, Resort Hotel yang lebih ditujukan untuk liburan atau rekreasi memiliki pelanggan yang lebih terikat pada jadwal mereka. <br>
3. Tingkat pembatalan lebih tinggi ketika lead time hampir satu tahun, dan lead time kurang dari 1 bulan memiliki tingkat pembatalan terendah. Perusahaan dapat membuat batasan pemesanan maksimum dan mempertimbangkan syarat deposit untuk mengurangi peluang pembatalan.

## Recommendations:
Dari analisis yang telah dilakukan, terdapat beberapa rekomendasi yang dapat dilakukan sebagai tindak lanjut: <br>
1. Untuk mengoptimalkan resource hotel di luar peak season, dapat dilakukan dengan menawarkan promo holiday deals di awal tahun.<br>
2. Ke depannya pihak hotel bisa menerapkan kebijakan pembatalan untuk mengurangi tingkat pembatalan. Semakin lama periode pemesanan, semakin tinggi biaya pembatalannya. <br>
3. Tingkat pembatalan lebih tinggi ketika lead time hampir satu tahun, dan lead time kurang dari 1 bulan memiliki tingkat pembatalan terendah. Pihak hotel dapat membuat batasan durasi pemesanan maksimum dan mempertimbangkan syarat deposit untuk mengurangi peluang pembatalan.
