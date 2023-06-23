# PROJE3
# SORU:
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.   
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Çözüm:   
Root elemandan küçük elemanları root elemanın soluna, büyük elemanları sağına yazacağız.  
Adım1 -> Baştaki elemanı(7) root olarak alırız.  
Adım2 -> 5, 7'den küçük olduğu için 7'nin sol çocuğu olur.  
Adım3 -> 1, 5'den küçük olduğu için 5'in sol çocuğu olur.  
Adım4 -> 8, 7'den büyük olduğu için 7'nin sağ çocuğu olur.  
Adım5 -> 3, 7'nin sol çocuğu, 5'in sol çocuğu ve 1'in sağ çocuğu olur.  
Adım6 -> 6, 7'nin sol çocuğu, 5'in sağ çocuğu olur.  
Adım7 -> 0, 7'nin sol çocuğu, 5'in sol çocuğu, 1'in sol çocuğu olur.  
Adım8 -> 9, 7'nin sağ çocuğu, 8'in sağ çocuğu olur.  
Adım9 -> 4, 7'nin sol çocuğu, 5'in sol çocuğu, 1'in sağ çocuğu, 3'ün sağ çocuğu olur.  
Adım10 -> 2, 7'nin sol çocuğu, 5'in sol çocuğu, 1'in sağ çocuğu, 3'ün sol çocuğu olur.  
```
           7
          / \
        5     8
       / \     \
      1   6     9
    /   \
   0     3
        / \
       2   4
