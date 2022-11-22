#Dataset-Narkotika_-319_308
*   [Dataset](https://github.com/n11bhq/Dataset-Narkotika_-319_308/tree/main/Dataset)
*   [Overview](https://github.com/n11bhq/Dataset-Narkotika_-319_308/tree/main/Overview)

# Term Frequency-Inverse Document Frequency (TF-IDF)
**Term frequency (tf)**, adalah model Bag of words, dilambangkan dengan nilai frekuensi setiap kata dalam dokumen particualr dan direpresentasikan di bawah ini sebagai.
![image](https://user-images.githubusercontent.com/8701464/130260732-31e928d5-0c4a-4915-a671-1b4564783c58.png)

Inverse document frecuency (idf) adalah kebalikan dari Term Frequency untuk setiap kata, membagi jumlah dokumen dengan frekuensi dokumen untuk setiap kata, operasi ini sedang diskalakan menggunakan logaritmik, rumusnya menambahkan 1 ke frekuensi dokumen untuk setiap kata untuk menyoroti bahwa ia juga memiliki satu dokumen lagi di korpus,  Ini juga addig 1 ke seluruh hasil untuk menghindari mengabaikan istilah yang bisa memiliki nol.

**df(word)** represents the number of documents in which the word w is present.

![image](https://user-images.githubusercontent.com/8701464/130260766-f5734ce8-6981-49d3-861b-97eec6c6a559.png)

# Euclidean Distance
Euclidean distance mengidentifikasi seberapa jauh dua vektor terpisah satu sama lain. Artinya dia melihat jarak kedekatan antara dua teks. Jika cosine similarity memperhatikan sudut antar vektor, euclidean distance lebih memperhatikan jarak antar vektor dalam euclidean space. Persamaan matematika dalam menghitung jaraknya adalah : 

![image](https://www.datavedas.com/wp-content/uploads/2018/04/image001-4-1080x191.png)

---
##Dataset
 Dataset yang digunakan diambil dari Direktori Putusan Mahkamah Agung Indonesia, yaitu direktori putusan PN Depok [bagian Pidana Khusus kasus Narkotika dan Psikotropika]( https://putusan3.mahkamahagung.go.id/direktori/index/pengadilan/pn-depok/kategori/narkotika-dan-psikotropika-1/page/52.html). Dataset berjumlah 50 file pdf yang disimpan dalam format .zip.
 
 ##Source Code
 Source Code pengerjaan search engine dapat diakses di [Google Colab](https://colab.research.google.com/drive/15i9GJ1Ac0AvqtrtWUcHrB-1lEtbWLtmA?usp=sharing).
