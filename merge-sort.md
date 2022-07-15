Proje 2
[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.

1. Diziyi tek eleman kalana kadar 2'ye bölüyoruz
[16,21,11,8,12,22]
[16,21,11] - [8,12,22]
[16,21] - [11] - [8,12] - [22]
[16] - [21] - [11] - [8] - [12] - [22]
   Tek elemanlı dizilerimizi sıralayarak birleştiriyoruz
[16] - [21] - [11] - [8] - [12] - [22]
[16,21] - [11] - [8,12] - [22]
[11,16,21]- [8,12,22]
[8,11,12,16,21,22]

2. 
Big-O gösterimi: O(nlogn)
