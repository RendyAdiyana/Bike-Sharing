# Bike-Sharing
This is a final project from Dicoding in the "Belajar Analisis Data Dengan Python" course to make analysis and create a dashboard from the bike sharing dataset. In the notebook file, I attached the way I did the analysis from Data Wrangling, Exploratory Data Analysis, and Data Visualization.

# 🚲 Capital Bikeshare: Bikesharing Analysis and Dashboard

## 📝 Analysis with Jupyter Notebook

🚧 See the detail of this analysis and visualization on the [notebook](https://github.com/RendyAdiyana/Bike-Sharing/blob/main/Bike_Sharing_Data%20Analysis.ipynb) 🚧

notebook.ipynb
Download this project.
Open your favorite IDE like Jupyter Notebook or Google Colaboratory (but in here I will use Google Colab).
Create a New Notebook.
Upload and select the file with .ipynb extension.
Connect to hosted runtime.
Lastly, run the code cells.

### Pertanyaan
1. Bagaimana trend peminjaman sepeda dalam 2 tahun kebelakang?
2. Apakah ada jam tertentu dimana peminjama sepeda naik?
3. Apa musim yang memiliki peminjam sepeda terbanyak?
4. Apakah ada korelasi antara suhu dan kelembaban dengan jumlah peminjaman sepeda?
5. Apakah cuaca mempengaruhi peminjaman sepeda?

### Insights and Findings
1. The number of bikeshare rides in 2012 was higher than in 2011. Both years showed the same trend and seasonality, with the number of rides increasing in the middle of the year and decreasing at the beginning and end of the year.

2. For registered users, the number of rides peaked at 8:00 AM and 5:00 PM, suggesting that they may have used the bikes to commute to work. For casual users, the number of rides started to increase during the day and decreased during the night.

3. Bikeshare rides were highest during the summer season and lowest during the winter season.

4. For registered users, the number of rides was higher during weekdays. This is consistent with the findings in question 2, suggesting that registered users likely used the bikes to commute to work. For casual users, the number of rides was higher on weekends than on weekdays, indicating that they used the bikes for leisure activities on weekends.

5. Yes, there is a moderate correlation between temperature and the number of bikeshare rides. The number of rides is lowest at colder temperatures, which occur during the winter, and starts to increase as the temperature increases, which happens in the summer. However, there is a "sweet spot" or temperature range when the number of rides is highest, which is between 20°C and 30°C. This temperature range typically occurs during the summer and fall seasons. On days with these temperature conditions, we can expect the number of bikeshare rides to be high.

6. Yes, the number of rides is significantly higher during clear weather than during more extreme weather conditions.

## 📊 Dashboard with Streamlit
### Streamlit Cloud
View the dashboard on streamlit could directly on this link: https://bike-sharing-rendy-adiyana-budiman.streamlit.app/
The dashboard shows the count of total rides across the year and season. It also shows the difference casual riders and registered riders use of the bikesharing service, based on hour and day of the week.

<p align="center">
  <img src="/image/streamlit_dashboard.png" />

### Run Streamlit on Local

#### Install Dependencies

Ikuti langkah di bawah ini untuk menjalankan file dashboard

```bash
pip install -r requirements.txt
```

#### Run Dashboard
```bash
cd dashboard
streamlit run dashboard.py
```

Thanks for visiting my project! 🔥
