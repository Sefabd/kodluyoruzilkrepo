# Proje 3: Binary Search Tree (İkili Arama Ağacı)  

Binary Search Tree kuralı basittir: İlk gelen eleman en tepeye (Root) oturur]Sonra gelen her sayı Root'tan küçükse sola, büyükse sağa doğru dal açarEğer orada da bir sayı varsa aynı kurala göre ondan da sağa veya sola ayrılır.

## Dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 

* **Root 7'dir.** 
* **5:** 7'den küçüktür. 7'nin solunda bulunur
* **1:** 7'den küçük, 5'ten küçüktür.5'in solunda bulunur.
* **8:** 7'den büyüktür. 7'nin sağında bulunur.
* **3:** 7'den küçük, 5'ten küçük, 1'den büyüktür1'in sağında bulunur
* **6:** 7'den küçük, 5'ten büyüktür. 5'in sağında bulunur.
* **0:** 7'den küçük, 5'ten küçük, 1'den küçüktür1'in solunda bulunur.
* **9:** 7'den büyük, 8'den büyüktür. 8'in sağında bulunur.
* **4:** 7'den küçük, 5'ten küçük, 1'den büyük, 3'ten büyüktür3'ün sağında bulunur.
* **2:** 7'den küçük, 5'ten küçük, 1'den büyük, 3'ten küçüktür. 3'ün solunda bulunur.
