# Bike-Sharing
Berikut ini adalah Final Project dari Dicoding "Belajar Analisis Data Dengan Python" . Pada file Notebook saya telah melampirkan keseluruhan analisa data yang telah saya lakukan mulai dari Data Wrangling, Data Cleaning, Exploitary Data Analysis dan Data Visualization

## Analysis with Jupyter Notebook

Keseluruhan Detail dan juga Hasil pekerjaan dapat dilihat pada: https://github.com/RendyAdiyana/Bike-Sharing/blob/main/Bike_Sharing_Data%20Analysis.ipynb 
Untuk dapat running Notebook anda dapat mengikuti langkah- langkah berikut:

Download project ini.
Buka file IDE seperti VS Code, Jupyter Notebook, atau Google Colaboratory
Install requirement
Buka file yang telah di download
Jalankan coding tersebut

### Pertanyaan
1. Bagaimana trend peminjaman sepeda dalam 2 tahun kebelakang?
2. Apakah ada jam tertentu dimana peminjama sepeda naik?
3. Apa musim yang memiliki peminjam sepeda terbanyak?
4. Apakah ada korelasi antara suhu dan kelembaban dengan jumlah peminjaman sepeda?
5. Apakah cuaca mempengaruhi peminjaman sepeda?

### Insights and Findings
1.Jumlah perjalanan bikeshare pada tahun 2012 lebih tinggi dibandingkan tahun 2011. Kedua tahun tersebut menunjukkan tren dan musim yang sama, dengan jumlah perjalanan meningkat pada pertengahan tahun dan menurun pada awal dan akhir tahun.
2. Pada registered users, jumlah perjalanan mencapai puncaknya pada pukul 08.00 dan 17.00, yang menunjukkan bahwa mereka mungkin menggunakan sepeda untuk berangkat kerja. Sedangkan casual users, jumlah perjalanan mulai meningkat pada siang hari dan menurun pada malam hari.
3.Jumlah perjalanan bikeshare tertinggi terjadi pada musim panas dan terendah pada musim dingin.
4. Terdapat korelasi antara suhu dan jumlah perjalanan bikeshare dimana seiring peningkatan suhu peminjam sepeda meningkat. Jumlah peminjaman paling sedikit terjadi pada suhu yang lebih dingin, yang terjadi selama musim dingin, dan mulai meningkat seiring dengan peningkatan suhu, yang terjadi pada musim panas. Namun, ada "sweet spot" atau kisaran suhu saat jumlah peminjam paling banyak, yaitu antara 20°C dan 30°C. Kisaran suhu ini biasanya terjadi pada musim panas dan musim gugur. Sedangkan untuk kelembaban/humidity terlihat bahwa peminjam paling banyak di antara 40-80 dan seiring peningkatan kelembaban peminjam sepeda semakin berkurang
5. Jumlah peminjaman jauh lebih tinggi saat cuaca cerah dibandingkan saat kondisi cuaca lebih ekstrem.

## Dashboard with Streamlit
### Streamlit Cloud
Anda dapat melihat Dashboard Streamlit melalui Link berikut: https://bike-sharing-rendy-adiyana-budiman.streamlit.app/

Dashboard terrsebut menunjukan jumlah peminjaan sepeda sepanjang tahun dan musim, pada dashboard tersebut juga menunjukan perbedaan antara Casual dan Registered User dalam peminjaman sepeda berdasarkan jam, suhu, dan kelembaban

<p align="center">
  <img src="/Images/Streamlit_DB 1.png" />
<p align="center">
  <img src="/Images/Streamlit_DB 2.png" />
<p align="center">
  <img src="/Images/Streamlit_DB 3.png" />
<p align="center">
  <img src="/Images/Streamlit_DB 4.png" />
  
### Run Streamlit on Local

#### Install Dependencies

Ikuti langkah di bawah ini untuk menjalankan file dashboard
#### Aktifkan virtual environtment : (Pada project ini menggunakan Anaconda)
```bash
conda create --name main-ds python=3.11
conda activate main-ds
```

#### Install file requirement
```bash
pip install -r requirements.txt
```
#### Buka file Dashboard_bike_sharing pada VS Code

#### Run Dashboard
```bash
streamlit run [Dashboard_bike_sharing.py]
```
#### Reminder: Pastikan path dashboard tersebut sesuai dengan tempat anda menyimpan file tersebut

Thanks for visiting my project! 🔥
