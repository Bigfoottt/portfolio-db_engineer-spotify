# portfolio-db_engineer-spotify


Berikut adalah contoh soal untuk tema "Popular Spotify Songs" dalam format Jupyter Notebook:

#1 Statistik Data Popular Spotify Songs
1. Buatlah sebuah DataFrame dari file CSV yang berisi data tentang lagu-lagu populer di Spotify.
2. Tampilkan lima baris pertama dari DataFrame tersebut.
3. Berapa jumlah total lagu dalam dataset?
4. Berapa jumlah kolom dalam dataset?
5. Tampilkan ringkasan statistik deskriptif dari kolom 'popularity' (kepopuleran lagu) dalam dataset.
6. Berapa rata-rata kepopuleran lagu dalam dataset?
7. Berapa lagu dengan kepopuleran tertinggi dalam dataset?
8. Berapa lagu dengan kepopuleran terendah dalam dataset?
9. Tampilkan 10 lagu dengan jumlah 'followers' (pengikut) terbanyak dari kolom 'artists' (artis) dalam dataset.
10. Visualisasikan distribusi kepopuleran lagu dalam bentuk histogram.

#2 Analisis Artis dalam Popular Spotify Songs
1. Hitunglah jumlah lagu yang dimiliki oleh masing-masing artis dalam dataset.
2. Tampilkan 10 artis dengan jumlah lagu terbanyak.
3. Hitunglah rata-rata kepopuleran lagu yang dimiliki oleh masing-masing artis.
4. Tampilkan 10 artis dengan rata-rata kepopuleran lagu tertinggi.

#3 Korelasi antara Fitur Lagu
1. Hitung korelasi antara fitur 'danceability' (kemampuan untuk menari) dan 'energy' (energi) dari lagu.
2. Hitung korelasi antara fitur 'valence' (kesenangan) dan 'loudness' (kenyaringan) dari lagu.
3. Apakah ada korelasi yang signifikan antara fitur-fitur tersebut? Jelaskan.
4. Soal 4: Analisis Waktu Rilis Lagu
5. Ubah kolom 'release_date' (tanggal rilis) menjadi tipe data datetime.
6. Buat kolom baru 'year' (tahun) yang berisi tahun rilis dari lagu.
6. Hitung jumlah lagu yang dirilis pada setiap tahun.
7. Visualisasikan jumlah lagu yang dirilis pada setiap tahun dalam bentuk diagram batang.

Soal 5: Analisis Genre Lagu (Opsional)
1. Jika dataset Anda menyertakan informasi tentang genre lagu, hitung jumlah lagu dalam setiap genre.
2. Tampilkan 10 genre dengan jumlah lagu terbanyak.
3. Hitung rata-rata kepopuleran lagu dalam setiap genre.
4. Tampilkan 10 genre dengan rata-rata kepopuleran lagu tertinggi.

Panduan Penyelesaian
1.  Baca dataset dari file CSV ke dalam DataFrame menggunakan Pandas.
2. Gunakan fungsi-fungsi Pandas seperti head(), info(), describe(), value_counts(), dan lainnya untuk menjawab pertanyaan-pertanyaan yang diberikan.
3.Untuk visualisasi, Anda dapat menggunakan pustaka Matplotlib atau Seaborn.

==Selamat mengerjakan!==