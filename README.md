Proyek Analisis Komparatif Aset Kripto: ETH vs. BNB vs. BNC

1. Gambaran Proyek (Project Overview)
 Proyek ini adalah analisis deskriptif yang mendalam terhadap harga historis tiga aset kripto utama: Ethereum (ETH), Binance Coin (BNB), dan BNC. Tujuannya adalah mengevaluasi kinerja risiko (volatilitas) dan imbal hasil (return) secara komparatif selama periode pengamatan yang spesifik. Output proyek ini memberikan rekomendasi strategis berdasarkan profil statistik masing-masing aset, ditujukan untuk membantu pengambilan keputusan investasi berbasis data.

2. Pertanyaan Analisis Kunci (Key Analytical Question)
 Berdasarkan analisis deskriptif pada data harga historis dari 05 Mei 2025 hingga 05 Agustus 2025, bagaimana perbandingan performa rata-rata return dan volatilitas (risiko) antara aset kripto ETH, BNB, dan BNC? Profil risiko-imbal hasil mana yang paling cocok untuk strategi investasi tertentu?

3. Metodologi dan Sumber Data

Sumber Data
 Platform: Kaggle
 Dataset: Digunakan data harga historis dari dataset [`crypto-price-pred-EDA`.](https://www.kaggle.com/code/aabdollahii/crypto-price-pred-eda/input)
 Periode Analisis: 05 Mei 2025 hingga 05 Agustus 2025

Teknik Analisis
1.  Analisis Deskriptif Mendalam: Perhitungan metrik utama (rata-rata return harian, median, dan Standar Deviasi sebagai indikator volatilitas) untuk periode 3 bulan.
2.  Analisis Korelasi: Mengukur hubungan pergerakan harga antaraset, terutama dengan BTC sebagai market leader.
3.  Visualisasi Tren: Pembuatan time series plot dan chart return untuk menganalisis perubahan harian.

4. Hasil Kunci dan Rekomendasi

Temuan Utama (Key Findings)
Berdasarkan metrik deskriptif dan observasi tren pasar:
 1. Ketergantungan pada BTC: Korelasi BTC-ETH mencapai R = 0,80, menunjukkan hubungan pergerakan harga yang sangat kuat. Pergerakan BTC berfungsi sebagai indikator utama untuk pengambilan keputusan pada aset lain.
 2. Pertumbuhan Agresif ETH: ETH memberikan return terbesar (mencapai 77%). Namun, volatilitasnya lebih tinggi dibanding BTC.
 3. Stabilitas BNB: BNB memiliki Standar Deviasi paling rendah di antara ketiganya, mengindikasikan aset ini paling stabil, sambil tetap memberikan return moderat.
 4. Volatilitas Kripto: Chart return menunjukkan perubahan harian yang cepat dan tajam, menegaskan pentingnya pengelolaan risiko.
 5. Tren Pasar Selama Pengamatan: Seluruh aset mengalami kenaikan harga yang stabil dengan frekuensi return positif yang dominan.

Rekomendasi Strategis Berdasarkan Profil Risiko
ETH bersifat agresif, Cocok untuk investor yang mencari peluang pertumbuhan tinggi dan siap menanggung fluktuasi yang lebih besar.
BNB bersifat konservatif/moderat, Cocok untuk investor yang memprioritaskan aset stabil namun tetap mengharapkan pertumbuhan moderat.

Implikasi Pasar Berdasarkan Tren
 BTC dan ETH berpotensi tetap bergerak searah (berdasarkan korelasi).
 Aset yang lebih volatil (seperti ETH) menawarkan peluang return yang lebih besar pada periode pasar bullish berikutnya.
 Kondisi pasar saat pengamatan sangat cocok untuk strategi Buy on Dips (membeli ketika terjadi koreksi harga minor).

5. Tools dan Teknologi
 Bahasa Pemrograman: Python
 Library Kunci: `Pandas` (manipulasi data), `NumPy` (perhitungan), `Matplotlib`/`Seaborn` (visualisasi).
 Lingkungan: Google Colab

6. Struktur Repository
 `notebooks/`: File kode utama (`crypto_analysis.ipynb`)
 `data/`: File data historis yang digunakan (`crypto_data.csv` atau `.xlsx`)
 `reports/`: Laporan visual/Presentasi (`Final_Crypto_Report.pdf`)
