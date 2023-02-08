# Selection Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

1.[2,27,16,22,18,6] 
-> 1.Asama (En küçük eleman olan 2 en baştaki 22 ile yer değiştiriliyor)
2.[2,6,16,22,18,27] 
-> 2.Asama (2. en küçük eleman olan 6 ikinci sıradaki 27 ile yer değiştiriliyor)
3.[2,6,16,22,18,27] 
-> 3.Asama (3. en küçük eleman olan 16 üçüncü sırada olduğundan yerine dokunulmuyor)
4.[2,6,16,18,22,27] 
-> 4.Asama (4. en küçük eleman olan 18 dördüncü sıradaki 22 ile yer değiştiriliyor. Beşinci sıradaki 22 ile altıncı sıradaki 27 sayılarının yerleri doğru olduğundan dokunulmuyor)

Big-O = O(n^2)

18 sayısı Average Case kapsamına girer.

Soru 2:
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. işlem [2,3,5,8,7,9,4,15,6]
2. işlem [2,3,4,8,7,9,5,15,6]
3. işlem [2,3,4,5,7,9,8,15,6]
4. işlem [2,3,4,5,6,9,8,15,7]
