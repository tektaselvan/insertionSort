# insertionSort
[22,27,16,2,18,6] -> Insertion Sort
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
22* 27 26 2 18 16 n
22 27* 26 2 18 16 n-1
22 26 27* 2 18 16 n-2
2 22 26 27* 18 16 n-3
2 18 22 26 27* 18 n-4
[2 16 18 22 26 27] 1
Big-O gösterimini yazınız.
n+(n-1)+(n-2)+(n-3)+(n-4)+1= (n(n+1))/2= n^2
Big-O notasyonu: n^2
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1.Average case: Aradığımız sayının ortada olması

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
[2,3,4,5,6,7,8,15,9]
