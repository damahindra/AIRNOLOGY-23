# Airnology 2023 Objective Quest Tahap Penyisihan - Prediksi Curah Hujan

![](https://bccfilkom.net/static/assets/images/BCC-Logo.svg)
# BCC Freya

#### Problem Domain
Prediksi curah hujan memiliki relevansi yang sangat penting dalam berbagai aspek kehidupan, termasuk pertanian, mitigasi bencana, pengelolaan sumber daya air, dan perencanaan infrastruktur. Dengan memiliki informasi yang akurat tentang kapan, seberapa banyak, dan di mana hujan akan terjadi, kita dapat mengoptimalkan penggunaan sumber daya pertanian, menghindari kerugian akibat banjir, mengatur pasokan air yang efisien, dan merencanakan pembangunan kota yang tahan cuaca. Dalam konteks pemindahan ibu kota baru Indonesia, prediksi curah hujan yang baik akan membantu dalam perencanaan dan pengaturan jadwal proyek, mengurangi risiko penundaan, dan memastikan kelancaran proyek infrastruktur yang sangat penting tersebut.
#### Diagram Alir Metodologi
![workflow](https://i.imgur.com/FgvkD2a.png)

Proses dimulai dengan pemerolehan data dari Kaggle yang telah disiapkan oleh panitia. Selanjutnya, data tersebut akan mengalami ekstraksi fitur agar nilai-nilainya dapat digunakan. Langkah berikutnya adalah melakukan EDA untuk mendapatkan wawasan dan ide-ide potensial untuk feature engineering. Setelah itu, akan dilakukan tiga skenario feature engineering secara paralel. Setiap skenario akan menghasilkan fitur-fitur yang berbeda untuk meningkatkan ketepatan prediksi. Setelah proses feature engineering selesai, model fitting dan pelatihan akan dilakukan pada masing-masing skenario. Evaluasi model akan dilakukan dengan membagi dataset menjadi data pelatihan dan data validasi menggunakan data split, serta dengan menggunakan cross-validation untuk memastikan keandalan model. Hasil prediksi akan disubmit ke Kaggle untuk pengujian. Score terbaik akan dicatat dan dimasukkan ke dalam suatu knowledge base yang berisi kumpulan ide-ide feature engineering yang telah terbukti efektif dalam menurunkan Root Mean Square Error (RMSE). Proses ini akan berjalan secara berkelanjutan, diulang, dan diperbaiki seiring berjalannya waktu untuk terus meningkatkan kualitas prediksi curah hujan.
