#### Merge Sort Algoritması
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

------

1. 
| Adımlar | Bölme Ve Birleştirme |
| --- | ----------- |
| 1.Bölme | [16,21,11] [8,12,22] |
| 2.Bölme | [16] [21,11] [8] [12,22] |
| 3.Bölme | [16] [21] [11] [8] [12] [22] |
| 1.Birleştirme | [16] [11,21] [8] [12,22] |
| 2.Birleştirme | [11,16,21] [8,12,22] |
| 3.Birleştirme | [8,11,12,16,21,22] |

2. O(nlogn)