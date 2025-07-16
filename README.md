# 📊 Analisis Sosial Media Twitter
Repositori ini berisi dua studi analisis jaringan sosial berbasis data Twitter. Penelitian ini menggunakan pendekatan Social Network Analysis (SNA) untuk mengungkap aktor berpengaruh dan struktur komunitas dalam percakapan daring mengenai isu sosial dan politik.

## 1. Analisis Centralitas Twitter: "Boikot"

Tujuan: Mengidentifikasi akun paling berpengaruh dalam diskusi bertema “boikot” di Twitter, terkait isu Palestina-Israel.

Metode:
1. Crawling data dengan kata kunci “boikot”
2. Membangun graph mention antar pengguna
3. Menggunakan tiga metrik centralitas:
   - Degree Centrality
   - Closeness Centrality
   - Betweenness Centrality

Hasil Singkat:
- Akun @tanyarlfes memiliki degree tertinggi (paling banyak disebut)
- Akun @tanyakanrl memiliki closeness dan betweenness tertinggi (paling efisien menghubungkan antar pengguna)


## 2. Deteksi Komunitas Twitter: "Debat Capres"

Tujuan: Mengidentifikasi komunitas pengguna Twitter yang terbentuk selama percakapan seputar “debat capres”.

Metode:
1. Crawling tweet dengan kata kunci “debat capres”
2. Pembentukan graph mention antar pengguna
3. Deteksi komunitas menggunakan algoritma Louvain

Hasil Singkat:
- Terbentuk 500 komunitas dari 1944 node
- Komunitas terbesar terdiri dari akun-akun seperti @PartaiSocmed, @aniesbaswedan, dan @Mdy_Asmara1701
- Visualisasi menunjukkan kedekatan antar pendukung berdasarkan interaksi
