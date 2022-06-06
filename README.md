# MergeSortProject
https://patika.dev 'in Merge Sort Projesi


**1) [16,21,11,8,12,22]
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**

[16,21,11]--------[8,12,22] (Dizinin elemanları her adımda parçalara ayrılıp, tek eleman kalıncaya kadar yazılır.)
[16]---[21,11]-----[8]---[12,22]
[16]---[21]---[11]---[8]---[12]---[22] (Dizi elemanları tek kaldıktan sonra sıralama ve birleştirme işlemi yapılır.)
[16]---[11,21]----[8]---[12,22]
[11,16,21]-------[8,12,22]
[8,11,12,16,21,22] (Dizi en sonunda sıralanmış hale getirilir.)


**2)Big-O gösterimini yazınız.**
 O(nlogn)
