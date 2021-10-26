# Machine-Learning

<img width="1920" alt="7" src="https://user-images.githubusercontent.com/44236850/116789295-6212f700-aad8-11eb-8f55-9d8c93f85903.png">
<p>
<p>

Secara garis besar ada tiga tipe algoritma utama Machine Learning:

- <h4>Supervised Learning<h4>
- <h4>Unsupervised Learning<h4>
- <h4>Reinforcement Learning<h4>
<br>
<p>
<p>
<h3>1. Supervised Learning</h3><br>
Supervised Learning adalah algoritma machine learning yang dalam proses belajarnya membutuhkan serangkaian contoh input-output yang benar, sebagai supervisor (pengawas/pelatih).<br>
Contoh kasus pada Iris classification, kita memiliki sejumlah dataset sampel input berupa data panjang dan lebar sepal dan petal. Masing-masing sampel tersebut sudah memiliki output yang benar (memiliki label). Serangkaian sampel input-output ini kemudian digunakan untuk menge-train (melatih) algoritma kita, agar kelak dapat menghasilkan output (label) yang sesuai ketika diberikan masukan data baru. <br>
Algoritma Supervised Learning ini sendiri juga dibagi lagi menjadi beberapa jenis algoritma tergantung dari task/tujuan dibentuknya algoritma, antara lain:

- Klasifikasi: Logistik Regression, Decision Trees, Random Forest, KNN, SVM, Neural Networks, Naïve Bayes, dll
- Prediksi Numerik/Regresi: Linear Regression, Decision Trees, Neural Networks, SVM, Trees, dll
<p>
<h3>2. Unsupervised Learning</h3> <br>
Unsupervised learning adalah algoritma machine learning yang dalam proses belajarnya, algoritma hanya diberikan sejumlah sampel masukan tanpa label (output yang benar). Sehingga pada algoritma ini, tidak ada supervisor/pelatih yang membantu dalam menentukan apakah kinerja dan output yang dihasilkan benar atau salah. <br>
Contoh penggunaan algoritma ini adalah untuk segmentasi pasar. Misalkan suatu perusahaan X memiliki data usia, gender, pekerjaan, tempat tinggal, frekuensi pembelian, dan kuantitas pembelian dari pembeli produknya selama dua tahun terakhir. Data ini bisa digunakan oleh perusahaan X untuk melakukan segmentasi pasar berdasarkan data-data tadi. Dengan algoritma Unsupervised Learning, kita tidak perlu men-declare atau menetapkan ‘label’ atau ‘output yang benar’. Kita tidak perlu melabeli pembeli dengan usia, gender, dan kriteria tertentu ke dalam kelompok tertentu. Kita tidak perlu menentukan jumlah kelas/kelompok dan kriteria tiap kelompok. Di sini algoritma machine learning akan melihat dan mempelajari pola-pola dari karakteristik tiap data yang ada dan melakukan pengelompokan pembeli secara mandiri. <br>
Untuk macam-macam algoritma unsupervised sendiri antara lain berdasarkan task/tujuan algoritmanya: <br>

- Klustering: K-Means Clustering, Hierarchical Clustering
- Association: Association Rules
<p>
<h3>3. Reinforcement Learning</h3><br>
Pada reinforcement learning, terdapat dua komponen utama yaitu agent dan environment. Di algoritma pembelajaran ini, agent ‘dipaksa’ untuk dengan sendirinya mempelajari bagaimana ia harus bertindak menghadapi environment-nya untuk mencapai tujuannya. Di sini tidak ada kumpulan dataset yang diberikan seperti pada Supervised Learning dan Unsupervised Learning. <br>
Contohnya misal kita hendak membuat sebuah machine yang dapat bermain catur melawan Magnus Carlsen, sang Juara Catur Dunia. Tujuan dari machine ini adalah memenangkan pertandingan. Dengan Reinforcement Learning, machine bertindak sebagai agent. Bagaimana cara bermain catur, aturan mainnya, dan trik yang biasa digunakan Magnus Carlsen adalah environment, yang tentunya harus ia pelajari sendiri. Sehingga dalam kasus ini, si machine pokoknya harus bisa belajar dengan sendirinya meraba-raba environment yang ada biar menang. Titik. <br>
Dalam proses belajarnya sendiri ia akan belajar dari pengalaman-pengalaman yang ia peroleh ketika bermain (tanpa kita ajarkan). Misalkan pengalaman ketika ia mendapatkan skak dari lawan ataupun pengalaman ketika ia berhasil memakan benteng lawan. Dari pengalaman-pengalaman ini, ia dipaksa belajar untuk memahami apa yang harus dan tidak boleh ia lakukan dalam menghadapi lawan dan membuat strateginya sendiri agar menang.

