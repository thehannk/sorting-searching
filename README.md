# sorting-searching

## Insertion Sort Project

#### [22,27,16,2,18,6] dizisinin intersertion sort türüne göre sıralaması: 
2,27,16,22,18,6 
2,6,16,22,18,27 
2,6,16,18,22,27

#### Big-O gösterimi : n.(n+1)/2 O(n^2) 18 sayısı Average case

#### [7,3,5,8,2,9,4,15,6] insertion sorta göre ilk 4 aşaması:

2,3,5,8,7,9,4,15,6

2,3,4,8,7,9,5,15,6

2,3,4,5,7,9,8,15,6

2,3,4,5,6,9,8,15,7


## Merge Sort Project

#### [16,21,11,8,12,22] dizisinin merge sort türüne göre sıralaması:
[16,21,11]-[8,12,22]

[16]-[21,11]-[8]-[12,22]

[16]-[21]-[11]-[8]-[12]-[22]

[16]-[21,11]-[8]-[12,22]

[11,16,21]-[8,12,22]

[8,11,12,16,21,22]

#### Big-O Gösterimi: 2^x=n logn O(nlogn)


## Binary Search Tree Project

#### [7,5,1,8,3,6,0,9,4,2] dizisinin binary search tree türüne göre sıralaması:
1.adım: Root:7 2.adım: 5 < 7

         7 
        /
       5
       
3.adım: 1 < 7

         7
        / 
       5
      /
     1
     
4.adım: 8 > 7

           7
          / \
         5   8
        /
      1
      
5.adım: 3 < 7

          7
         / \
        5   8
       /
      1
       \
        3
         
6.adım: 6 < 7

           7
          / \
         5   8
        / \
       1   6
       \
        3
         
7.adım: 0 < 7

           7
          / \
         5   8
        / \
       1   6
      / \
     0   3
     
8.adım: 9 > 7

            7
           / \
          5   8
         / \    \
        1   6    9
       / \
      0   3
      
9.adım: 4 < 7

             7
            / \
           5    8
          / \     \
         1   6     9
        / \
       0   3
            \
             4
             
10 .adım: 2 < 7

               7
              / \
             5   8
            / \    \
           1   6    9
          / \
         0   3
             / \
            2   4
            
