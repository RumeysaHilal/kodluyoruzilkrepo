# Binary Search Tree

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin aşamaları:

```
Root ilk baştaki sayı oolan 7'dir.

Yediden sonra gelen beş root'un solunda yer alır roottan küçük olduğu için.

Bir, hem beşten hem yediden küçük olduğu için en sol kısımda yer alır. 

Sekiz, roottan büyük olduğu için sağ tarafta yer alır.

Üç, yediden ve beşten küçük ancak birden büyük olduğu için bir düğümünün sağ tarafına yazılır.

Altı, yediden küçük beşten büyük olduğu için yedinin solunda beşin sağında yer alır. 

Sıfır, yediden, beşten ve birden küçük olduğu için en sola yazılır.

Dokuz, yediden ve sekizden büyük olduğu için en sağa yazılır.

Dört, yediden ve beşten küçük birden ve üçten büyük olduğu için üç düğümünün sağına yazılır.

İki, yediden, beşten küçük, birden büyük ve üçten küçük olduğu için üç düğümünün soluna yazılır.

                                    7
                                /       \
                               5         8
                            /     \        \
                           1       6        9
                        /     \
                       0       3
                             /    \
                            2      4                           

Şeklinde görünür.
```
