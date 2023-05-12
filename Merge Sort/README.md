Soru1:[16,21,11,8,12,22] -> Merge Sort

A) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.


[16,21,11,8,12,22]

[16,21,11] | [8,12,22]
[16] | [21,11] | [8] [12,22]
[16] | [21] | [11] | [8] | [12] | [22]
[16] | [11,21] | [8] [12,22]
[11,16,21] | [8,12,22]
[8,11,12,16,21,21]

Soru2:B) Big-O gösterimini yazınız.

 2^x=n
 
 x=logn 
 
 0(n) Her Bölme İşlemi 
 
 Big-O = O(nlogn)
