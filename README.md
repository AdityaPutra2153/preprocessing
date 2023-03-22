# preprocessing
Latihan preprocessing data dengan Python pada mata kuliah Data Mining

Pada preprocessing data pada dataset Flipkart.csv, saya menggunakan 4 library yaitu 

"numpy" untuk memudahkan kita melakukan perhitungan saintifik seperti matriks, aljabar, statistik, dan sebagainya. yang kedua 
"matpotlib.pyplot" untuk memvisualisaikan data melalui grafik atau diagram 
"pandas" berguna untuk memproses data, mulai pembersihan data, manipulasi data, hingga melakukan analisis data.
"sklearn" yang berguna untuk menyediakan berbagai fungsi dan algoritma untuk pemrosesan data, preprocessing data, feature engineering, pemilihan model, pelatihan model, evaluasi model, dan validasi model.
Hal pertama yang saya lakukan yaitu mengidentifikasi atribut mana yang memiliki missing values. Dan pada adataset yang saya gunakan terdapat 3 atribut yang memiliki 3 missing values yaiitu Memory, Storage dan Rating. Kemudian kita lakukan pembersihan data atau sering disebut Data Cleaning. Namun sebelum kita melakukan data cleaning, kita analisis terlebih dahulu jenis data dari atribut tersebut merupakan data numerik atau non numerik. Dikarenakan atribut Memory dan Storage merupakan data yang bersifat non numerik maka saya menggunakan metode imputasi Most-Frequent atau MODUS yang mana metode ini akan mengambil data yang muncul paling banyak pada dataset. Sedangakan atribut Rating termasuk ke jenis data yang numerik maka saya menggunakan metode imputasi MEAN atau Rata Rata dari data pada atribut yang memiliki missing values.

Kemudian setelah dilakukannya pembersihan data/Data Cleaning, selanjutnya saya melakukan encoding untuk mengubah data kategorikal menjadi numerikal sehingga dapat diolah oleh model machine learning. pada tahap ini saya menggunakan 2 metode yang berbeda. Untuk proses encoding pada atribut saya menggunakan one-hot encoding dan pada proses encoding pada class saya menggunakan labelEncoder. Kemudian setelah dilakukannya Encode, langkah selanjutnya yaitu melakukan  pembagian dataset ke dalam training set dan test set. Hal ini berguna untuk mengukur kemampuan model untuk melakukan prediksi yang akurat pada data yang belum pernah dilihat sebelumnya. Dan langkah terakhir yaitu melakukan Feature Scaling yaitu untuk untuk mengubah skala data sehingga nilai-nilai variabel numerik berada dalam rentang yang sama atau memiliki skala yang relatif sama.

Dataset Flipkart merupakan dataset yang berisi mengenai data penjualan berbagai merk Handphone.
Dengan dilakukannya preprocessing ini pada dataset flipkart.csv yang sebelumnya memiliki missing values, maka dataset ini dapat diperbaiki atau dilengkapi datanya sehingga dapat digunakan secara optimal pada machine learning.
