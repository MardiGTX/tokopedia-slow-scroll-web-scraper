<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/>
<img src="https://img.shields.io/badge/BeautifulSoup-Web%20Scraping-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>

</p>

---

## 📌 Gambaran Proyek

Proyek ini bertujuan melakukan **web scraping data produk Tokopedia** menggunakan **Python, Selenium WebDriver, BeautifulSoup, dan Pandas**.

Proses scraping dilakukan menggunakan teknik **slow scroll (automated scrolling)** untuk mengambil data dari halaman Tokopedia yang memuat konten secara dinamis saat halaman digulir.

Data hasil scraping dapat digunakan untuk eksplorasi produk, observasi marketplace, analisis harga, maupun persiapan dataset untuk analisis lebih lanjut.

---

## 🎯 Tujuan Proyek

- Mengambil data produk dari hasil pencarian Tokopedia  
- Melakukan scraping pada halaman dengan konten dinamis menggunakan teknik **slow scroll**  
- Mengubah data mentah dari website menjadi dataset yang terstruktur  
- Menyusun data agar siap digunakan untuk analisis lebih lanjut  

---

## 🛠 Tech Stack

| Tools | Fungsi |
|--------|--------|
| Python | Bahasa pemrograman utama |
| Selenium WebDriver | Otomatisasi browser dan interaksi halaman dinamis |
| BeautifulSoup (bs4) | Parsing HTML dan ekstraksi data |
| Pandas | Pengolahan dan penyusunan data ke DataFrame |

---

## ⚙️ Alur Pengerjaan

1. Membuka halaman Tokopedia menggunakan **Selenium WebDriver**  
2. Melakukan **slow scroll (automated scrolling)** untuk memuat data produk secara dinamis  
3. Mengambil HTML halaman setelah konten selesai dimuat  
4. Melakukan parsing HTML menggunakan **BeautifulSoup**  
5. Mengekstrak informasi produk dari halaman web  
6. Menyimpan hasil scraping ke dalam **Pandas DataFrame**

---

## 📦 Data yang Dikumpulkan

Data yang berhasil diambil dari halaman Tokopedia meliputi:

| Data | Deskripsi |
|------|------------|
| Nama Produk | Nama produk |
| Harga | Harga produk |
| Penjual | Nama penjual/toko |
| Kota Toko | Kota/lokasi toko |
| Terjual | Banyak produk terjual |
| Rating | Rating produk |


## ▶️ Cara Menjalankan

1. Buka notebook menggunakan **Jupyter Notebook** atau **Google Colab**  
2. Jalankan setiap cell secara berurutan  
3. Selenium akan membuka browser secara otomatis  
4. Sistem melakukan **slow scroll** untuk memuat produk Tokopedia  
5. Data produk akan diekstrak dan disusun ke dalam **Pandas DataFrame**

---

## 📈 Contoh Penggunaan

Dataset hasil scraping dapat digunakan untuk:

- Analisis harga produk  
- Observasi marketplace Tokopedia  
- Monitoring produk dan toko  
- Persiapan dataset untuk analisis lanjutan  
- Eksplorasi tren produk

---

## 🔮 Pengembangan Selanjutnya

- Menyimpan hasil scraping ke format **CSV** atau **Excel**  
- Menambahkan fitur pembersihan data (*data cleaning*)  
- Menambahkan visualisasi data (*data visualization*)  
- Meningkatkan efisiensi scraping  
- Menambahkan exploratory data analysis (**EDA**)

---

## 👨‍💻 Author

**Mardi Wicaksana**  
Data Analyst Enthusiast | SQL | Python | Data Analysis | Web Scraping