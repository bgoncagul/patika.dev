1.1)Insertion Sort Aşamaları
1.[22,27,16,2,18,6] -> Insertion Sort

2. [22,27,16,2,18,6] -> mevcut en küçük elemanı bulmak için dizi taranır. en küçük eleman ile ilk sıradaki elemanın yeri değiştirilir.	

3. [2,27,16,22,18,6] -> ilk eleman sabit tutulur ve 2. elemandan başlanarak aynı işlem uygulanır.
 
4. [2,6,16,22,18,27] -> ilk 2 eleman sabit tutulur ve 3. elemandan başlanarak aynı işlem uygulanır.
 
5. [2,6,16,22,18,27] -> dizinin 3. elemanı olması gerektiği yerde olduğu için 4. elemandan başlayarak en küçük eleman bulunur ve 4. eleman ile yer değiştirilir.
 
6. [2,6,16,18,22,27] -> insertion sort tamamlanmıştır.

1.2)Big O Gösterimi
n+(n-1)+(n-2)+(n-3)...+1(1 den n'e kadar ardışık sayıların toplam formülü) n*(n+1)/2 =n^2+n/2 dominant fonksiyon x^2 olduğunda,O(n^2)dir.

1.3)Time Complexity

Best Case: [2,27,16,22,18,6] O(n)

Average Case:  [2,6,16,18,22,27] O(n)

Worst Case: [22,27,16,18,6,2] O(n^2)

1.4)Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.[22,27,16,18,6,2]

2)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. adım ->[2,3,5,8,7,9,4,15,6]
2. adım ->[2,3,4,8,7,9,5,15,6]
3. adım ->[2,3,4,5,7,9,8,15,6]
4. adım ->[2,3,4,5,6,9,8,15,7]
