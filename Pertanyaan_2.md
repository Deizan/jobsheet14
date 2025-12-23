Pertanyaan

1. Pada Percobaan2, terdapat pemanggilan fungsi rekursif hitungPangkat(bilangan,
pangkat) pada fungsi main, kemudian dilakukan pemanggilan fungsi hitungPangkat()
secara berulangkali. Jelaskan sampai kapan proses pemanggilan fungsi tersebut akan
dijalankan!

2. Tambahkan kode program untuk mencetak deret perhitungan pangkatnya. Contoh:
hitungPangkat(2,5) dicetak 2x2x2x2x2x1 = 32

Jawab: 

1. Proses pemanggilan fungsi tersebut dijalankan sampai base case atau nilai batas terpenuhi atau sampai y==0

2. Sudah , ada di kode di bawah ini :

     String tampilan_1 = "hitungPangkat" + "(" + bilangan + "," + pangkat + ")" + " " + "dicetak" + " ";
       String tampilan_2 = "1" + "" + " = "+ hasilFungsi;

        System.out.print(tampilan_1);
       for (int i = 0; i < pangkat ; i++) {
           System.out.print( bilangan + " x ");
       }
        System.out.print(tampilan_2);