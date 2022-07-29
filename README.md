# Insertion-Sort-Projesi
## Proje 1
-[22,27,16,2,18,6] -> Insertion Sort

-Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
-Big-O gösterimini yazınız.
-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

-Insertion Sort Aşamaları
-[22,27,16,2,18,6] -(n)
-[2|,27,16,22,18,6] -(n-1)
-[2,6|,16,22,18,27] -(n-2)
-[2,16,16|,18,22,27] -(n-3)

-Big O Notation Gösterimi
-Worst Case : O(n2)=n(n-1)+(n+2)...+1

-Average Case: O(n2)
-Best Case: O(n)
Time Complexity
-Worst Case:[27,22,18,16,6,2] 
-Best Case:[2,6,16,18,22,27]
18 Case Durumu

-Dizi büyükten küçüğe sıralandığında [2,6,16,22,27] 18 sayısı bu dizinin ortanca değeridir. 18 sayısı bu konumda average casedir.

 -[7,3,5,8,2,9,4,15,6] Dizisi İlk 4 Adım
1. [7,3,5,8,2,9,4,15,6]
2. [2|,3,5,8,7,9,4,15,6] 
3. [2,3,4|,8,7,9,5,15,6] 
4. [2,3,4,5|,7,9,8,15,6]

  (https://app.patika.dev/)
