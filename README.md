📊 Analisis Nilai Siswa Menggunakan Python

Program ini digunakan untuk menganalisis data nilai siswa berdasarkan mata pelajaran dengan bantuan Python dan beberapa pustaka analisis data seperti pandas, matplotlib, dan seaborn.
Kode ini cocok dijalankan di Google Colab karena mendukung fitur unggah file langsung.

🧩 Fitur Utama

Upload File CSV

Mengunggah file nilai siswa secara langsung melalui files.upload() di Google Colab.

File CSV harus memiliki delimiter ; (titik koma).

Pembersihan & Persiapan Data

Mengubah semua nama kolom menjadi huruf kecil agar konsisten.

Mengecek apakah kolom yang dibutuhkan (matpel dan nilai) tersedia.

Statistik Dasar

Menghitung rata-rata, median, dan modus dari seluruh nilai siswa.

Filter Data Berdasarkan Mata Pelajaran

Menampilkan data khusus untuk:

Bahasa Indonesia

Bahasa Inggris

Matematika

Analisis Nilai Maksimum & Minimum

Menampilkan nilai tertinggi dan terendah untuk setiap mata pelajaran.

Visualisasi Data

Bar Chart: menampilkan rata-rata nilai per mata pelajaran dengan tampilan rapi dan label horizontal.

Boxplot: menunjukkan sebaran nilai tiap mata pelajaran untuk melihat variasi dan persebarannya.

🧠 Library yang Digunakan
Library	Fungsi
pandas	Membaca dan mengolah data CSV
matplotlib.pyplot	Membuat grafik batang (bar chart)
seaborn	Membuat grafik boxplot yang menarik
google.colab.files	Mengunggah file dari komputer ke Google Colab
io	Membaca file yang diunggah ke memori
📂 Format Data CSV

Pastikan file CSV kamu memiliki kolom berikut:

matpel	nilai
Bahasa Indonesia	85
Bahasa Inggris	90
Matematika	88
Fisika	92
Produktif	80

Gunakan delimiter “;” jika file berasal dari Excel atau sistem dengan pemisah titik koma.

🚀 Cara Menjalankan di Google Colab

Buka Google Colab
.

Salin seluruh kode Python ini ke dalam satu cell.

Jalankan cell.

Ketika muncul prompt upload, pilih file CSV kamu.

Tunggu hingga hasil analisis dan grafik muncul.

📈 Contoh Output
🔹 Statistik Dasar
Rata-rata: 87.5  
Median: 88.0  
Modus: 85  

🔹 Visualisasi

Bar Chart – Rata-rata Nilai per Mata Pelajaran

Boxplot – Sebaran Nilai per Mata Pelajaran

<img width="709" height="689" alt="Screenshot 2025-11-10 111844" src="https://github.com/user-attachments/assets/58423319-4a1b-4d36-acc5-1914f6f977ab" />

📚 Lisensi

Kode ini bersifat bebas digunakan untuk keperluan belajar dan penelitian.
Silakan modifikasi atau kembangkan sesuai kebutuhanmu.
