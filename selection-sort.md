#### Selection Sort Algoritması
[22,27,16,2,18,6] -> Selection Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: 
   * Average case: Aradığımız sayının ortada olması,
    * Worst case: Aradığımız sayının sonda olması,
    * Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

------------

1.Selection Sort
 * [22,27,16,2,18,6] swap(22,2)
 * [2,27,16,22,18,6] swap(27,6)
 * [2,6,16,22,18,27] swap(22,18)
 * [2,6,16,18,22,27]

2.Big-O notation : O(n^2^)

3.Time Complexity: 
* Average case: O(n^2^)
* Worst case: O(n^2^)
* Best case: O(n^2^)

4.Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı

1.Adım [**7**,3,5,8,**2**,9,4,15,6] swap(7,2)
2.Adım [2,3,**5**,8,7,9,**4**,15,6] swap(5,4)
3.Adım [2,3,4,**8**,7,9,**5**,15,6] swap(8,5) 
4.Adım [2,3,4,5,7,9,8,15,6]
...

[patika.dev](https://www.patika.dev/tr)