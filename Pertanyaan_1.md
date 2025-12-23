1. Apa yang dimaksud dengan fungsi rekursif?
2. Pada Percobaan1, apakah hasil yang diberikan fungsi faktorialRekursif() dan fungsi
faktorialIteratif() sama? Jelaskan perbedaan alur jalannya program pada penggunaan
fungsi rekursif dan fungsi iteratif!


jawab: 

1. Fungsi rekursif adalah sebuah fungsi yang terdapat perintah untuk memanggil
fungsi itu sendiri (dirinya sendiri). Dengan demikian, proses pemanggilan fungsi
akan terjadi secara berulang-ulang

2. Sama , perbedaan alur jalannya program antara fungsi rekursif dab fungsi iteratif adalah 

    a. Yang pertama, pada fungsi rekursif parameter yang ditampung di variabel n di validasi menggunakan condition berupa if else berupa jika n == 0 maka ,
    nilai yang dikembalikan adalah 0.  Sedangkan jika n !== 0 maka , recursion call dijalankan dengan n dikali dengan n-1 sampai dengan mendekati base case (n==0) 

    b. Yang kedua , pada fungsi iteratif terdapat deklarasi variabel faktor = 1 , dan parameter yang ditampung di variabel n kemudian di validdasi menggunakan perulangan pada fungsi ini , dengan i = n dan jika i lebih dari sama dengan 1 , kemudian variabel faktor tersebut dikalikan dengan i .  Kemudian hasil dari perklalian tersebut dikembalikan dengan keyword return faktor.