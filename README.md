# Proje 1 Sorusu
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Insertion Sort:

Dizi = [7,3,5,8,2,9,4,15,6]
    1. [22,27,16,2,18,6]
    2. [22,27,16,2,18,6]
    3. [16,22,27,2,18,6]
    4. [2,16,22,27,18,6]
    5. [2,16,18,22,27,6]
    6. [2,6,16,18,22,27]

 Insertion sort algoritmasında O(n^2) olur. Sıralama yaparken daha fazla zaman harcamış oluruz.
 Dizi sıralandıktan sonra 18 sayısının Time Complexity: Average case olur.

## Selection Sort:
Dizi = [7,3,5,8,2,9,4,15,6]

    1. [2,3,5,8,7,9,4,15,6]
    2. [2,3,4,8,7,9,5,15,6]
    3. [2,3,4,5,7,9,8,15,6]
    4. [2,3,4,5,6,9,8,15,7]

# Proje 2 Sorusu

## Merge Sort
        [16,21,11,8,12,22]

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
-

        [16,21,11,8,12,22]

       [16,21,11] [8,12,22]

      [16,21] [11] [8] [12,22]

    [16] [21] [11] [8] [12] [22]

      [16,21] [11] [8,12] [22]

       [16,11,21] [8,12,22]

        [8,11,12,16,21,22]

Merge sort algoritması diziyi parçalara bölüp kendi içerisinde Insertion sort algoritması gibi önce kendi içerisinde daha sonra diğer parçaları arasında sıralama yapıyor bu şekilde Insertion sort algorimasından daha hızlıdır. Big-O gösterimi O(nlogn) formulü ile gösterilir.

# Proje 3 Sorusu

## Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Root: 7

             7
            / \
           5   8
          / \   \
         1   6   9
        / \ 
       0   3
          / \
         2   4

- 5 < 7 küçük root'un soluna
- 1 < 7 ve 1 < 5'in soluna
- 8 > 7 sağına
- 3 < 7'den soluna ve 3 < 5'ten ve 3 > 1'den 1'in sağına
- 6 < 7'den soluna 6 > 5'ten sağına
- 0 < 7'den soluna 0 < 5'ten soluna 0 < 1'den soluna
- 9 > 7'den sağına 9 > 8'den sağına
- 4 < 7'den soluna 4 < 5'ten soluna 4 > 1'den sağına 4 > 3'ten sağına
- 2 < 7'den soluna 2 < 5'ten soluna 2 > 1'den sağına 2 < 3'ten soluna
