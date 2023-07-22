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
