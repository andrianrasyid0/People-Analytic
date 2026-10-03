# People Analytic
Menganalisis data karyawan untuk memahami faktor-faktor yang mempengaruhi kepuasan kerja dan memberikan rekomendasi berbasis data untuk meningkatkan kepuasan kerja tersebut, menggunakan data survei karyawan untuk melakukan eksplorasi, menganalisis faktor-faktor kepuasan kerja, dan membuat dashboard interaktif untuk menampilkan hasil analisis secara visual.

## Sumber Data
Data diberikan oleh dibimbing [Dataset](https://drive.google.com/file/d/1k08xUoWvXxenXfLDAUZNVKtGAN29P8Lv/view?usp=sharing)

## Business Problem
Di tahun 2026 sudah banyak  transisi ketika  bekerja  awalnya di office hingga work from home(WFH) atau Hybrid. Banyak pekerja yang bekerja tidak sesuai minat atau passion nya selain itu juga ada banyak faktor - faktor lain yang menyebabkan pekerja tidak puas ketika bekerja. Maka dari itu disini kita akan analisa apa saja variabel - variabel yang menyebabkan mereka tidak puas ketika bekerja seperti jam tidur yang kurang, beban kerja yang diterima dan juga lingkungan kerja mempengaruhi kepuasan saat bekerja.

## Dataset
Terdapat :

Jumlah data          : 2766

Kolom                : 23 

Missing Value        : Tidak ada

Data duplikat        : Tidak ada

Avg Job Satisfaction : 3.38

Skala Penilaian 1 -5 
Kolom wlb,work_env,workload,stress, dan Job satisfaction

## Preprocessing data

Data Cleaning
- Memeriksa data kosong (missing value)
-Memeriksa data yang duplikat

Data Transformation 
- Membuat kolom baru rentang  usia
  
Data Validation 
- Memeriksa apakah nilai yang dimasukkan sudah sesuai dengan rentang yang ditentukan
- Memastikan tidak ada kesalahan pada data
  
Data Preparation
- Data yang sudah bersih dan terstruktur kemudian digunakan untuk analisis

## Insight
- Resiko Burnout Tinggi di Departemen IT: IT mencatatkan kepuasan paling rendah (3.29) sekaligus akumulasi stres paling tinggi. Ini menunjukkan adanya masalah beban kerja atau alokasi sumber daya yang krusial.                
- Pemegang PhD: Karyawan berpendidikan PhD memiliki kepuasan terendah (2.93) dibanding jenjang lain. Hal ini mengindikasikan  kualifikasi berlebih yang tidak sebanding dengan peran/kompensasi atau ketidak sesuaian ekspektasi kerja.
- Beban Kerja Berbanding Terbalik dengan Kepuasan: Kepuasan merosot tajam dari 3.77 pada beban kerja level 1 menjadi 2.86 pada level 5. Nilai ambang batas ideal beban kerja berada di level 1–3.
  
- Pengaruh Fasilitas Komuter: Karyawan yang mengandalkan transportasi umum memiliki kepuasan lebih rendah dibanding yang membawa kendaraan pribadi, memperlihatkan dampak stres perjalanan (commute) terhadap kondisi kerja.

## Business Rekomendation
1. Lakukan Audit Kerja pada Departemen IT
Review alokasi proyek dan tambah personel atau efisiensikan workflow untuk menurunkan beban stres di IT.
Pertimbangkan skema kerja fleksibel (hybrid/remote) khusus tim IT untuk menjaga work life balance.
2. Evaluasi Jalur Karir & Peran Lulusan PhD
Sediakan ruang riset, proyek strategis, atau penyesuaian jalur karir yang lebih sesuai dengan kapasitas intelektual mereka.
3. Optimalisasi Beban Kerja (Workload Balancing)
Tetapkan batas toleransi beban kerja agar tidak menyentuh level 4 dan 5.
Redistribusi tugas antara anggota tim atau manfaatkan otomatisasi untuk tugas-tugas repetitif.
4. Dukungan Kesejahteraan & Transportasi Karyawan
Sediakan insentif/subsidi transportasi umum, atau sediakan armada jemputan kantor untuk mengurangi kelelahan akibat perjalanan ke tempat kerja.






