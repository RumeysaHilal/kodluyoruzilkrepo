# Merge Sort

### [16,21,11,8,12,22] Aşamaları:

```
Dizi öncelikle ikiye bölünür.
Birinci dizi: 16,21,11
İkinci dizi: 8,12,22
Bu diziler de kendi içlerinde bölünür ve sıralama yapılır. Sıralama sonrası diziler:
Birinci dizi: 11,16,21
İkinci dizi: 8,12,22
Bu diziler de en küçüklerden başlayarak karşılaştırma yapılarak sıralanır.
İlk önce 8 ve 11 karşılaştırılır. 8,11 olur. 2den sonra gelen 11 ile karşılştırılır ve 8,11,12 elde edilir.
Bu şekilde diziler sadece bir sonraki ile karşılaştırılır.

Sorted List: 8,11,12,16,21,22
```

### Big-O Gösterimi:
Best, Average, Worst Case :  O(nlogn)
