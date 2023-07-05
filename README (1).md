
# Teori uas
Nama: ADILLA DINNI SAHRA_202131102

penjelasan:
OpenCV (cv2) untuk mengidentifikasi dan memisahkan buah-buahan (apel, mangga, dan jeruk) dalam gambar.
Import library yang diperlukan
Membaca gambar "buah.jpg"
Mengubah ruang warna gambar dari BGR (Blue-Green-Red) ke HSV (Hue-Saturation-Value)
Menentukan rentang nilai HSV untuk masing-masing buah (apel, mangga, jeruk)
Membuat mask menggunakan fungsi cv2.inRange() untuk mendapatkan bagian gambar yang memiliki warna dalam rentang yang ditentukan
Menerapkan operasi bitwise AND pada gambar asli dengan masker untuk mendapatkan hasil deteksi buah
Menerapkan operasi morfologi untuk membersihkan noise dalam mask menggunakan kernel berbentuk elips
Mencari kontur dalam mask yang telah dibersihkan menggunakan cv2.findContours()

Jurnal
Citra  /  gambar (image) merupakan  hal  yang  vital  dan  menjadi  bagian  integral  dari kehidupan sehari-hari. Pada  kepentingan tertentu, citra (gambar)  digunakan sebagai alat untuk mengungkapkan   pertimbangan (reason), interpretasi,   ilustrasi,   penggambaran (represent), ingatan (memorise), pendidikan,  komunikasi,  evaluasi,  navigasi,  survai,  hiburan,  dan  lain sebagainya.    Tetapi    kemudian    konsep    citra    dan    pengolahannya    dihubungkan    dengan pengubahan dan perbaikan citra (gambar) yang bertujuan antara lain : 
a.  memperbaiki kesalahan data sinyal gambar akibat transmisi dan selama akuisisi sinyal. b.   meningkatkan   penampakan   gambar   sehingga   dapat   'diterima'   oleh sistem   penglihatan manusia. Umumnya  pengolahan  citra  melibatkan  alat  bantu  komputer,  sehingga  muncul  istilah ‘computer vision’ yang selanjutnya dihubungkan dengan konsep komputasi dan elektronik dari dunia mesin sejalan dengan atribut penglihatan manusia. Aspek   komputer   adalah   sebuah   sistem   yang   berhubungan   dengan   elemen-elemen perangkat  keras  seperti  sensor  optik,  arsitektur  pengolahan  paralel  pada  komputer,  grafika komputer  dan alat penampil (display) serta  elemen-elemen perangkat  lunak seperti  manipulasi data  dan perhitungan  data  gambar. Sedangkan aspek penglihatan (vision) adalah bayangan dari sistem penglihatan manusia dan melingkupi aspek fungsional dari mata, saraf optik dan otak.  Secara  ideal,  mesin diharapkan mempunyai kemampuan  yang sama dengan kemampuan penglihatan   manusia.   Sehingga   suatu   pertimbangan   (misalnya   untuk   membedakan   obyek berdasarkan  permukaan,  warna,  cahaya  dan  lain-lain) dibuat  berdasarkan  karakteristik  sistem penglihatan manusia. Dalam kenyataannya, sistem penglihatan manusia sangat kompleks, yaitu dengan banyaknya tingkatan pengolahan pada mata dan jaringan saraf penglihatan di otak.