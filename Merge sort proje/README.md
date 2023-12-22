MERGE SORT PROJE


Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

SORT AŞAMALARI : 1- Önce [16,21,11] ve [8,12,22] olarak iki eşit parçaya ayrılır.
2- Sonra [16,21] [11] ve [8,12] [22] olarak ayrılır.
3- Tekrar [16] [21] [11], [8] [12] [22] olarak tek tek olacak şekilde ayrılır. 
4- Şimdi ikişerli tekrar küçükten büyüğe sıralama yapılır. [16,21] [11], [8,12] [22] şeklinde olur.
5- [11,16,21] ve [8,12,22] olacak şekilde tekrar sıralama yapılır.
6- En son bu ikili ve sıralı grup karşılaştırılır ve küçükten büyüğe sıralanır. [8,11,12,16,21,22]

*Big O gösterimi O(n log n) olur.