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
**Big-O gösterimini yazınız.**
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