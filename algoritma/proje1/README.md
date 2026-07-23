# Proje 1: Insertion Sort ve Selection Sort 

Insertion (Araya Ekleme) Sort, diziyi sanki elinde iskambil kağıtlarını sıraya diziyormuşsun gibi soldan sağa doğru okuyup, her elemanı solundaki sayılarla karşılaştırarak araya sokuşturma işlemidir

## Soru 1: [22, 27, 16, 2, 18, 6] dizisinin Insertion Sort aşamaları 

* **Başlangıç:** [22, 27, 16, 2, 18, 6] 
* **1. Adım:** İkinci eleman (27), 22'den büyük olduğu için yeri değişmez. [22, 27, 16, 2, 18, 6] 
* **2. Adım:** Üçüncü eleman (16), 27 ve 22'den küçüktür[cite: 633]. İkisinin de soluna, yani en başa geçer. [16, 22, 27, 2, 18, 6]
* **3. Adım:** Dördüncü eleman (2), tüm sıralı gruptan (16, 22, 27) küçüktür[cite: 635]. En başa yerleşir. [2, 16, 22, 27, 18, 6] 
* **4. Adım:** Beşinci eleman (18), 16'dan büyük, 22 ve 27'den küçüktür[cite: 636]. 16 ile 22 arasına girer. [2, 16, 18, 22, 27, 6] 
* **5. Adım (Son):** Altıncı eleman (6), 2'den büyük, 16'dan küçüktür[cite: 637]. [cite_start]2 ile 16 arasına girer. **Sıralanmış Hali:** [2, 6, 16, 18, 22, 27] 

## Soru 2: Big-O Gösterimi

[cite_start]Insertion sort algoritmasında elemanlar tek tek taranıp her biri için tekrar geriye dönük karşılaştırma yapıldığı için "n çarpı n" işlemi yapılır[cite: 639].
* [cite_start]**Cevap:** $O(n^2)$ [cite: 640]

## Soru 3: Time Complexity (18 sayısı hangi case kapsamına girer?)

[cite_start]Sıralanmış dizimiz: [2, 6, 16, 18, 22, 27] [cite: 640]
[cite_start]Aradığımız 18 sayısı dizinin en başında (Best case) veya en sonunda (Worst case) değil, ortalarındadır[cite: 640].
* **Cevap:** Average case (Beklenen durum)[cite: 641].

## Soru 4: [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımı

Selection Sort tüm dizideki en küçük elemanı bulup, sıradaki indeks ile yer değiştirmeye dayanır[cite: 641].
* [cite_start]**Başlangıç:** [7, 3, 5, 8, 2, 9, 4, 15, 6] [cite: 642]
* **1. [cite_start]Adım:** Dizideki en küçük sayı 2'dir[cite: 642]. [cite_start]En baştaki 7 ile yer değiştirir: [2, 3, 5, 8, 7, 9, 4, 15, 6] [cite: 642, 643]
* **2. [cite_start]Adım:** Geri kalanlar arasındaki en küçük sayı 3'tür[cite: 643]. [cite_start]Zaten ikinci sırada olduğu için yeri değişmez: [2, 3, 5, 8, 7, 9, 4, 15, 6] [cite: 643, 644]
* **3. [cite_start]Adım:** Geri kalanlar arasındaki en küçük sayı 4'tür[cite: 644]. [cite_start]Üçüncü sıradaki 5 ile yer değiştirir: [2, 3, 4, 8, 7, 9, 5, 15, 6] [cite: 644, 645]
* **4. [cite_start]Adım:** Geri kalanlar arasındaki en küçük sayı 5'tir[cite: 645]. [cite_start]Dördüncü sıradaki 8 ile yer değiştirir: [2, 3, 4, 5, 7, 9, 8, 15, 6] [cite: 645, 646]

---
