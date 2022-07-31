# MERGE SORT
---
[16,21,11,8,12,22] -> Merge Sort  
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
[16,21,11,8,12,22]  dizinin elemanları yalnız kalana kadar diziyi sağ ve sol olarak 2’ye ayırıyoruz.  
[16,21,11]- [8,12,22] ->1. Aşama   
[16]-[21,11]    [8]-[12,22] ->2. Aşama  
[16]  [21]-[11]   [8]  [12]-[22]->3. Aşama (teker teker ayırdığımız sayıları kendi grupları içerisinde sırayla birleştirerek bir bütün haline getiriyoruz.)  
[16]-[11,21]    [8]-[12,22] ->4. Aşama   
[11,16,21]- [8,12,22]->5. Aşama   
[8,11,12,16,21,22]->6. Aşamada merge sort tamamlandı.  
---
Big-O gösterimi: O(nlog(n))

