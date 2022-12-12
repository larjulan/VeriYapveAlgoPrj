# Veri Yapıları ve Algoritmalar - Projeler Bölümü
Aşağıda patika.dev üzerinde yer alan Veri Yapıları ve Algoritmalar eğitiminin projeler bölümündeki soruların çözümleri yer almaktadır.  

- Selection Sort Projesi
- Merge Sort Projesi
- Binary Search Tree Projesi

# Proje 1 - Selection Sort  

## Soru 1:
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması  
Worst case: Aradığımız sayının sonda olması  
Best case: Aradığımız sayının dizinin en başında olması.  

## Çözüm:
Aşamalar;
1) Dizideki en küçük değer saptanarak ilk değer ile yer değiştirilir: [2,27,16,22,18,6]
2) İkinci değerden itibaren en küçük değer saptanarak ikinci değerle yer değiştirilir: [2,6,16,22,18,27]
3) Üçüncü değerden itibaren en küçük değer hali hazırda üçüncü değerdedir, bu aşamada herhangi bir değişiklik olmaz: [2,6,16,22,18,27]
4) Dördüncü değerden itibaren en küçük değer saptanarak dördüncü değerle yer değiştirilir: [2,6,16,18,22,27]  
Bu noktada dizi sıralanmış olduğu için işlemin devam etmesine gerek yoktur.

Big-O:  O(n^2)

Time Comlexity: Average Case

## Soru 2:  
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.  

## Çözüm:
Aşamalar;
1) En küçük değer sapta, ilk değer ile yer değiş: [2,3,5,8,7,9,4,15,6]
2) İkinci değerden itibaren en küçük değer zaten ikinci değerde, bu aşamada değişiklik olmaz: [2,3,5,8,7,9,4,15,6]
3) Üçüncü değerden itibaren en küçük değer ile üçüncü değer yer değiş: [2,3,4,8,7,9,5,15,6]
4) Dördüncü değerden itibaren en küçük değer ile dördüncü değer yer değiş: [2,3,4,5,7,9,8,15,6]  
# Proje 2 - Merge Sort  
## Soru 1:  
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
Big-O gösterimini yazınız.  
## Çözüm:

1) [16,21,11,8,12,22]
2) [16,21,11] - [8,12,22]
3) [16,21] - [11] - [8,12] - [22]
4) [16] - [21] - [11] - [8] - [12] - [22]
5) [16,21] - [11] - [8,12] - [22]
6) [11,16,21] - [8,12,22]
7) [8,11,12,16,21,22]  

Big-O:  O(nlogn)  

# Proje 3 - Binary Search Tree  
## Soru 1:  
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.  
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.  
## Çözüm:  
Root 5.  
5'in sağından 7 bulunur,  
7'nin solundan 6 bulunur (leaf), sağından 8 bulunur,  
8'in sağından 9 bulunur (leaf).  
5'in solundan 2 bulunur,  
2'nin sağından 3 bulunur, solundan 1 bulunur,  
3'ün sağından 4 bulunur (leaf),  
1'in solundan 0 bulunur (leaf).  

![OlaylıGörsel](https://lh3.googleusercontent.com/pw/AL9nZEUCMjkBsGCfa32V_ls-CEG-F3OLJmLs03Gz0Ehc_QdCkGA4YFEgKkcM6C2foALjS_9b82i0w4J5uGAiMYLToQOwRiePeiTp7ORSk_i2BIlR9b2BQFGOCd3rGYz81W-0w5wk3Ka-QGVjAKDuNLLhJ0aQ=w311-h214-no)


Herkese benden çay.