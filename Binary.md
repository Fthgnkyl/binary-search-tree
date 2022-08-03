# Proje 3

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1.  [0, 1, 2, 3, 4, 5, 6, 7, 8, 9] düzgün bir sıralama için dizi rootu 5 olsun
2.                          5
3.                    3           7
4.                 2    4       6   8
5.              0                      9
6.               1
    **_iyi bir sıralama için dizim bu şekilde olur._**

kötü bir sıralama için root 8 olursa.

1. sağında 9 solunda 7
2. 7 için solunda 6
3. 6 için solunda 5
4. 5 için solunda 4
5. 4 için solunda 3
6. 3 için solunda 2
7. 2 için solunda 1
8. 1 için solunda 0

_şeklinde kötü bir şekilde sıralanabilir._
