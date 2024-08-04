## **Bank Marketing Campaign**

**Context**

Jenis produk keuangan yang digunakan oleh publik semakin bervariasi. Salah satu produk keuangan yang dikenal luas oleh masyarakat adalah deposito berjangka. Mekanisme deposito berjangka adalah nasabah menyetorkan sejumlah uang di bank atau lembaga keuangan, dan uang tersebut hanya bisa ditarik setelah jangka waktu tertentu. Sebagai kompensasi, nasabah akan diberikan bunga tetap sesuai dengan jumlah uang yang disetorkan.

Namun, sebagai entitas bisnis dengan produk keuangan dan pelanggan masing-masing, bank tetap harus bersaing agar tidak kehilangan pelanggan. Salah satu cara untuk memperoleh pelanggan baru adalah dengan melakukan kampanye pemasaran.

Target :

0 : Tidak melakukan deposito

1 : Melakukan deposito

**Problem Statement**

Bank perlu menarik nasabah baru dan mempertahankan yang sudah ada untuk produk deposito berjangka mereka. Dengan berbagai produk keuangan yang tersedia, persaingan antar bank sangat ketat. Untuk mengatasi tantangan ini, bank bertujuan untuk mengadakan kampanye pemasaran untuk mempromosikan penawaran deposito berjangka. Tujuannya adalah mengidentifikasi profil nasabah dan strategi pemasaran yang menghasilkan pembukaan rekening deposito berjangka yang sukses.

**Goals**

Bank ingin mempunyai kemampuan untuk mengidentifikasi profil nasabah berdasarkan faktor-faktor apa saja yang mempengaruhi nasabah yang akan membuka rekening deposito dan yang tidak akan, guna membuat strategi pemasaran yang menghasilkan tingkat konversi yang lebih tinggi atau tepat sasaran.

**Stakeholder**
- Bank Marketing Manager
- Bank Marketing Team
- Pimpinan kepala cabang pembantu

**Analytic Approach**

Jadi kita akan menganalisis output model untuk mengidentifikasi faktor-faktor utama yang mempengaruhi langganan deposito berjangka.

Kemudian kita akan membangun model klasifikasi yang akan membantu untuk memberikan wawasan dan rekomendasi yang dapat ditindaklanjuti untuk mengoptimalkan kampanye pemasaran di masa depan.

**Evaluation Metrics**

Type 1 error : False Positive

Kondisi: Nasabah terdeteksi berkeinginan membuka rekening deposito, padahal sebenarnya tidak tertarik untuk melakukannya.

Konsekuensi: Kampanye yang dilakukan cenderung sia-sia.

Type 2 error : False Negative

Kondisi: Nasabah terdeteksi tidak berkeinginan membuka rekening deposito, padahal sebenarnya tertarik untuk melakukannya.

Konsekuensi: Kehilangan calon nasabah potensial.

Berdasarkan konsekuensinya, tujuan utamanya adalah menciptakan model yang dapat mengurangi biaya kampanye bagi bank tanpa mengurangi jumlah calon nasabah potensial. Kita ingin mendapatkan sebanyak mungkin prediksi kelas positif yang benar, sambil meminimalkan prediksi yang salah positif (False Positive). Oleh karena itu, metric utama yang akan kita gunakan adalah F1-Score.
