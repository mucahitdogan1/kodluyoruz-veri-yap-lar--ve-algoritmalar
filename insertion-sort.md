#### Insertion Sort Algoritması
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: 
   * Average case: Aradığımız sayının ortada olması,
    * Worst case: Aradığımız sayının sonda olması,
    * Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

------------
Hayali çizginin sol tarafı sıralanmış bir şekildedir. Sağ taraf ise sol ile karşılaştırılarak sol tarafta sıralamaya dahil edilir.

1.Insertion Sort
 * [22|27,16,2,18,6] 
 * [22,27|16,2,18,6]
 * [16,22,27|2,18,6] 
 * [2,16,22,27|18,6]
 * [2,16,18,22,27|6]
 * [2,6,16,18,22,27]

2.Big-O notation : O(n^2^)

3.Time Complexity: 
* Average case: O(n^2^)
* Worst case: O(n^2^)
* Best case: O(n)

4.Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

1.Adım [7|,3,5,8,2,9,4,15,6]
2.Adım [3,7|,5,8,2,9,4,15,6]
3.Adım [3,5,7|,8,2,9,4,15,6]
4.Adım [3,5,7,8|,2,9,4,15,6]
...

[patika.dev](https://www.patika.dev/tr)