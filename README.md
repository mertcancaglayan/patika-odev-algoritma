Insertion Sort Aşamaları:
Verilen dizi: [22, 27, 16, 2, 18, 6]

Adım 1: [22, 27, 16, 2, 18, 6] (22 doğru konumda)
Adım 2: [22, 27, 16, 2, 18, 6] (27 doğru konumda)
Adım 3: [16, 22, 27, 2, 18, 6] (16 doğru konuma geldi)
Adım 4: [2, 16, 22, 27, 18, 6] (2 doğru konuma geldi)
Adım 5: [2, 16, 18, 22, 27, 6] (18 doğru konuma geldi)
Adım 6: [2, 6, 16, 18, 22, 27] (6 doğru konuma geldi, dizi sıralanmış durumda)


Big-O Gösterimi:
Insertion Sort'un Big-O gösterimi O(n^2) olur. En kötü durumda, her elemanı doğru konuma taşımak için tüm diziyi kontrol etmek zorunda kalabiliriz, bu da zaman karmaşıklığını O(n^2) yapıyor.

Time Complexity:
Dizi sıralandıktan sonra 18 sayısı, "Average case"e (ortalama durum) girer. Çünkü Insertion Sort, verilen dizinin neredeyse sıralı olduğu durumlarda daha iyi performans gösterir. 18, bu dizide yarıdan daha küçük bir değer olduğu için ortalama durumu temsil eder.

Selection Sort Aşamaları:

Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Adım 1: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Adım 2: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Adım 3: [2, 3, 4, 8, 7, 9, 5, 15, 6]
Adım 4: [2, 3, 4, 5, 7, 9, 8, 15, 6]
