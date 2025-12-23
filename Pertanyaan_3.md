Pertanyaan
1. Pada Percobaan3, sebutkan blok kode program manakah yang merupakan “base case”
dan “recursion call”!

2. Jabarkan trace fase ekspansi dan fase subtitusi algoritma perhitungan laba di atas jika
diberikan nilai hitungLaba(100000,3)

jawab:

1.  kode program base case:
     if (tahun == 0 ) {
            return (saldo);
        }
    
    kode program recursion call : 
    hitungLaba(saldo, tahun - 1)

2. Fase Ekspansi 
    hitungLaba(100000, 3) = 1.11 * ( hitungLaba(100000, 2))
                          = 1.11 * ( hitungLaba(111000, 1))
                          = 1.11 * ( hitungLaba(123.210, 0))
                          
    
    Fase substitusi
    = 1.11 * 10000 
    = 1.11 * 111000 
    = 1.11 * 123.210 
    = 136.763