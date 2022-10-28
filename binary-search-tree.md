#### Binary Search Tree Algoritması
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

-----
1.Adım : root 7'dir. root'un soluna 5 eklenir sağında bir sayı bulunmaz
2.Adım : 5'in soluna 1 eklenir
3.Adım : 7'nin sağına 8 eklenir.
4.Adım : 1'in sağına 3 eklenir.
5.Adım : 5'in sağına 6 eklenir.
6.Adım : 1'in soluna 0 eklenir.
7.Adım : 8'in sağına 9 eklenir.
8.Adım : 3'ün sağına 4 eklenir.
9.Adım : 3'ün soluna 2 eklenir.

Son görünüm aşağıdaki gibi olur

|     |     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|     |     |     |     |     |     | 7   |     |     |     |     |
|     |     |     |     |     | /   |     | \   |     |     |     |
|     |     |     |     | 5   |     |     |     | 8   |     |     |
|     |     |     | /   |     | \   |     |     |     | \   |     |
|     |     | 1   |     |     |     | 6   |     |     |     | 9   |
|     | /   |     | \   |     |     |     |     |     |     |     |
| 0   |     |     |     | 3   |     |     |     |     |     |     |
|     |     |     | /   |     | \   |     |     |     |     |     |
|     |     | 2   |     |     |     | 4   |     |     |     |     |
