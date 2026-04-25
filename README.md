# streamlit-analisis-data
project analisis data
🚲 Bike Sharing Data Analysis Dashboard

Dashboard ini dibuat untuk menganalisis pola penyewaan sepeda berdasarkan kondisi cuaca, hari, dan musim menggunakan dataset Bike Sharing.

📊 Fitur Dashboard
Analisis pengaruh cuaca terhadap penyewaan sepeda
Analisis pola penyewaan berdasarkan hari dan musim
Ringkasan statistik (total, rata-rata, maksimum)
Filter interaktif berdasarkan musim dan kondisi cuaca
Visualisasi data menggunakan Seaborn & Matplotlib
🛠️ Setup Environment
🔹 Menggunakan Anaconda
conda create --name bike-ds python=3.9
conda activate bike-ds
pip install -r requirements.txt
🔹 Menggunakan Shell/Terminal
mkdir bike_sharing_dashboard
cd bike_sharing_dashboard
pipenv install
pipenv shell
pip install -r requirements.txt
▶️ Menjalankan Dashboard

Pastikan posisi berada di folder submission, lalu jalankan:

streamlit run dashboard/dashboard.py
