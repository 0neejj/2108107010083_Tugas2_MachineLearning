**Klasifikasi & Regresi menggunakan Support Vector Machine (SVM)**

1. Klasifikasi : ***https://www.kaggle.com/datasets/mrsimple07/obesity-prediction/data***
   
    Pada klasifikasi saya menggunakan data obesitas. Data ini memberikan informasi kategori dari obesitas. dataset ini terdapat 1000sample dengan 6 kolom atribut yaitu umur, jenis kelamin, tinggi badan, berat badan, BMI(Indeks Massa Tubuh), Tingkat aktivitas fisik dan 1 label dimana label akan terbagi kedalam 4 kelas(normal, underweight, overweight, obesitas).
    Untuk menjalankan code pada klasifikasi hal pertama yang perlu dilakukan adalah mengimport beberapa library yang diperlukan seperti sns, numpy, pandas, matplotlib. selanjutnya adalah prepocessing data. Data yang digunakan masih dalam bentuk kategori sehingga akan dilakukan encoding label agar data berubah menjadi numerik, pemilihan fitur dan target(label), setelah membagi datanya makan akan dibagi data menjadi data latih dan data uji, kemudian dataset akan dilakukan normalisai agar data akan menghasilkan model yang lebih stabil. karena fitur lebih dari 1 maka akan dilakukan reduksi menggunakan PCA. Dengan PCA akan mereduksi fitur-fitur menjadi dua komponen utama.
	Membuat model dengan kernel linear dan RBF. model tersebut akan dilatih menggunakan data latih yang teah direduksi. selanjutnya adalah mengevaluasi model dengna menggunakan model yang telah dilatih diatas untuk memprediksi label dari data uji, didapatkan hasil akurasi pada evaluasi model adalah 0,92. Dan dilakukan visualisasi untuk melihat hasil dari model dalam bentuk plot dengan dua dimensi.


2. Regresi : ***https://www.kaggle.com/datasets/fayejavad/marketing-linear-multiple-regression/data***
   
    Dataset ini memberikan informasi tentang percobaan periklanan antara anggaran media sosial dan penjualan(dalam ribuan$). Pada data ini terdapat 172 sampel dengan 4 kolom yaitu youtube, facebook, newspaper dan sales. sales akan menjadi label pada data ini(x) dan kolom lainnya akan menjadi data(y).
    Hampir sama dengan data klasifikasi, unutk menjalankannya lakukan terlebih dahulu prepocessing data. Karena data sudah dilakukan prepocessing maka tidak lagi dilakukan prepocessing. kemudian dibuat model regresi linear untuk memprediksi sales. pada data ini fitur yang paling berpengaruh terhadap target adalah Youtube sehingga saya menggunakan youtube untuk membangun model dan visualisasinya. setelah memilih fitur yang akan digunakan maka data akan dibagi menjadi data trainin dan data testing, sebelum membuat model maka akan dilakukan normalisasi agar model yang dibuat lebih baik dan stabil. Hasil evaluasi model yang dihasilkan adalah dalam bentuk linear.
   
   ** HOW TO RUN**
   
-git clone ***https://github.com/0neejj/2108107010083_Tugas2_MachineLearning.git***

-python3 -m venv env

-source env/bin/activate

-python3 pip install -r requirements.txt

-run code 2108107010083_SVMclassification.ipynb dan 2108107010083_SVMRegression.ipynb
