# Belajar Analisis Data untuk Pemula
Project Akhir course "Belajar Analisis Data untuk Pemula" by dicoding Menganalisis Bisnis Supermarket Indonesia

## Menganalisis Bisnis Supermarket Indonesia
Project Mandiri Anlisis Data<br>
Judul "Menganalisis Bisnis Supermarket Indonesia"<br>
Data: [Spreadsheet](https://docs.google.com/spreadsheets/d/1kAcBhvVvTxYVrEivmiBagRVlj1USuxnqEsJIYNNQzCw/copy)

## Studi Kasus
Bayangkan Anda adalah seorang analis data di sebuah perusahaan ritel (supermarket) terkemuka di Indonesia. Anda memegang dataset komprehensif yang mencatat setiap detail transaksi pelanggan, mulai dari waktu pembelian, metode dan waktu pengiriman, detail produk yang dibeli, hingga keuntungan yang diperoleh. Selain data transaksi, tersedia pula profil pelanggan seperti nama, lokasi asal, dan kode pos.<br>

Suatu hari, CEO perusahaan meminta bantuan Anda untuk menjawab beberapa pertanyaan strategis. Insight yang Anda hasilkan akan menjadi dasar pengambilan keputusan untuk menjawab tantangan bisnis saat ini maupun strategi di masa depan.<br>

Sebagai seseorang yang mencari pengetahuan di balik data, Anda akan bekerja dengan dataset yang sudah diberikan sebelumnya. Ada beberapa ketentuan yang harus Anda pahami untuk memenuhi seluruh kriteria submission. 

Pertama, dataset yang Anda terima masih dalam kondisi “kotor” dan memerlukan pra-pemrosesan sebelum dianalisis. Berikut adalah beberapa anomali data yang perlu Anda perbaiki.

Duplikasi data: Terdapat beberapa data yang duplikat, Anda wajib menanganinya dengan cara drop nilainya.

Konsistensi data: Beberapa kolom berikut memiliki tingkat inkonsistensi data yang tinggi dan perlu ditangani:

tanggal_pengiriman: Kolom ini memiliki nilai null atau kosong.

kode_pos: Kolom ini memiliki nilai null atau kosong.

kota: Kolom ini memiliki inkonsistensi format (misalnya, Jakarta dan JAKARTA) serta nilai null atau kosong. Oleh karena itu, dalam satu kolom clean_kota terbaru harus terdapat rumus yang menangani kedua permasalahannya. 

Membuat kolom baru bernama `clean_`: Setiap kolom yang Anda bersihkan wajib disimpan ke dalam kolom baru dengan awalan clean_ diikuti dengan nama kolomnya. Contoh, clean_kode_pos.

Kedua, untuk menerapkan pemahaman Anda tentang query SQL, kita akan menggunakan sintaks =QUERY() di Google Sheets. Oleh karena itu, Anda wajib memperhatikan setiap pertanyaan yang harus dijawab menggunakan SQL. Jika instruksi ini tidak diikuti, submission akan ditolak.

Ketiga, setiap jawaban wajib disimpan pada sheet dan subsheet yang telah ditentukan. Anda tidak diperbolehkan membuat sheet baru.

Untuk lebih detailnya, Anda dapat membaca dengan cermat poin-poin pada setiap kriterianya.

## Clean Data
Link Clean Data: [Clean Data](https://docs.google.com/spreadsheets/d/1hvxayeVmkll0JhXxbFSp-mjeTiAX0RmNx7uF1DzMCsw/edit?gid=1657195239#gid=1657195239)

## Google Data Studio
Link Visualisasi Data: [Data Studio](https://datastudio.google.com/reporting/990d2cf9-ad53-46f0-8bd2-410997248f67/page/txn9F)
