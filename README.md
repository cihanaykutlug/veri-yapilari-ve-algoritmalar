# veri-yapilari-ve-algoritmalar
kodluyoruz eğitimleri kapsamında veri yapıları ve algoritmalar dersi proje ödevleri

# proje 1 
[22,27,16,2,18,6] -> Insertion Sort 
**Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

[22,27,16,2,18,6]
1. [**2**,27,16,22,18,6]
2. [**2**,**6**,16,22,18,27]
3. [**2**,**6**,**16**,22,18,27]
4. [**2**,**6**,**16**,**18**,22,27]
5. [**2**,**6**,**16**,**18**,**22**,27]
6. [**2**,**6**,**16**,**18**,**22**,**27**]

---
Big-O gösterimini yazınız. 
Insertion Sort'un Big-O gösterimi O(n^2)'dir.
---
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
- **Average case**: Aradığımız sayının ortada olması -> Bu durumda O(n/2) olduğundan average case O(n) olacaktır.
- **Average case**: Aradığımız sayının sonda olması -> Bu durumda O(n) olacaktır.
- **Average case**: Aradığımız sayının dizinin en başında olması -> Bu durumda O(1) olacaktır.
*Dolayısıyla, 18 sayısı sıralı bir dizide arandığı için Best Case (O(1)) durumuna girer.*

---
 [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] 
1. [**2**,3,5,8,7,9,4,15,6] 
2. [**2**,**3**,5,8,7,9,4,15,6] 
3. [**2**,**3**,**4**,8,7,9,5,15,6]
4. [**2**,**3**,**4**,**5**,7,9,8,15,6]

---
# Proje 2 
** [16,21,11,8,12,22] ** -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16,21,11,8,12,22]
1. [16,21,11] - [8,12,22]
2. [16,21] [11] - [8,12] [22]
3. [16] [21] [11] - [8] [12] [22]
4. [16,21] [11] - [8,12] [22]
5. [11,16,21] - [8,12,22]
6. [8,11,12,16,21,22]

Big-O gösterimini yazınız.
Merge Sort'un Big-O gösterimi O(n log n) şeklindedir.

---
# proje 3
 [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

**root = 7**
eklenecek : **5**
```
    7
   / 
  5
```
eklenecek : **1**
```
        7
       / 
      5
    /
   1
```
eklenecek : **8**
```
        7
       / \
      5   8
    /
   1
```
eklenecek :**3**
```
            7
           / \
          5   8
        /
       3
     /
   1
```
eklenecek :**6**
```
            7
           / \
          5   8
        /  \
       3    6
     /
   1
   ```
eklenecek :**0**
```
            7
           / \
          5   8
        /  \
       3    6
     /
   1
  /
 0
 ```
 eklenecek :**9**
 ```
            7
           / \
          5   8
        /  \   \
       3    6   9
     /
   1
  /
 0
 ```
eklenecek :**4**
```
                7
               / \
              5   8
             /  \   \
            4    6   9
           /
          3
         /
        1
       /
      0
```
eklenecek :**2**
```
                7
               / \
              5   8
             /  \   \
            4    6   9
           /
          3
         /
        1
       / \
      0   2
```