# Insertion Sort
### [22,27,16,2,18,6] Dizisinin aşamaları:

```
Eleman: 22
 Sıralama: 22,27,16,2,18,18,6
Eleman: 16 (22 ve 27 sıralaması yapıldığından dağılmaması için bir sonraki elemana geçildi)
  Sıralama: 16,22,27,2,18,6
Eleman: 2
  Sıralama: 2,16,22,27,18,6
Eleman: 18
  Sıralama: 2,16,18,22,27,6
Eleman: 6
  Sıralama 2,6,16,18,22,27
  
Sorted List: 2,6,16,18,22,27
```

### Big-O Gösterimi: 

Best Case --> O(n)

Average Case --> O(n<sup>2</sup>)

Worst Case --> O(n<sup>2</sup>)

### Dizi sıralandıktan sonra 18 sayısı Average kapsamına girer.

***

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı:

```
Birinci Adım: Eleman: 7 
  Sıralama: 3,5,7,8,2,9,4,15,6
İkinci Adım: Eleman: 2
  Sıralama: 2,3,5,7,8,9,4,15,6
Üçüncü Adım: Eleman: 9
  Sıralama: 2,3,5,7,8,9,4,15,6
Dördüncü Adım: Eleman: 4
  Sıralama: 2,3,4,5,7,8,9,15,6
```
