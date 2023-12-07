**Grup 7 AI**

**Presented by :**

**1. M. Farhan Aryo Lazuardi  (5311421016)**

**2. M. Muhtar Allawi         (5311421027)**

**3. M. Firman Ardianto       (5311421035)**

**Parkinson Disease**

**> Selection**

Metode yang digunakan dalam fungsi **selection** di atas adalah "Selection by Rank" atau "Rank-Based Selection." Pada metode ini, individu-individu dalam populasi diurutkan berdasarkan nilai fitness mereka, dan kemudian sejumlah tertentu dari individu dengan peringkat terbaik dipilih untuk membentuk populasi berikutnya. Dalam hal ini, sejumlah **n_parents** individu dengan peringkat tertinggi dipilih untuk menjadi bagian dari populasi berikutnya.

Metode ini sering digunakan dalam algoritma genetika untuk memastikan bahwa individu-individu dengan fitness yang lebih tinggi memiliki peluang yang lebih besar untuk ditransfer ke generasi berikutnya, sehingga meningkatkan kualitas keseluruhan populasi dari generasi ke generasi.

**> Crossover**

Metode yang digunakan dalam fungsi crossover di gunakan adalah One-Point Crossover. Dalam One-Point Crossover, sejumlah individu dari populasi yang dipilih secara berpasangan dipotong pada titik tertentu, dan bagian-bagian sebelah kiri dan kanan dari titik potong tersebut dipertukarkan antara dua individu tersebut untuk menghasilkan dua anak baru.

**> Mutation**

Metode yang digunakan dalam fungsi **mutation** di gunakan adalah **Mutasi Bitwise**. Mutasi ini dilakukan dengan mengubah nilai bit acak dalam kromosom, yaitu dengan meng-invert (mengganti dari 0 menjadi 1 atau sebaliknya) nilai bit pada posisi tertentu. Hal ini dilakukan dengan probabilitas tertentu (dikontrol oleh **mutation_rate**).
