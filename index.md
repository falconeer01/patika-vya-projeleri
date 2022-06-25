# Veri Yapıları ve Algoritmalar Ödevleri

1. ## Insertion Sort Projesi
    ### Proje 1
    [22,27,16,2,18,6] -> Insertion Sort
    - 1.adım: [2,27,16,22,18,6]
    - 2.adım: [2,6,16,22,18,27]
    - 3.adım: [2,6,16,18,22,27]
    - Big-0 = O(n^2)
    - 18 sayısı average case kapsamına girer.

    [7,3,5,8,2,9,4,15,6]
    - 1.adım: [2,3,5,8,7,9,4,15,6]
    - 2.adım: [2,3,4,8,7,9,5,15,6]
    - 3.adım: [2,3,4,5,7,9,8,15,6]
    - 4.adım: [2,3,4,5,6,9,8,15,7]
---
2. ## Merge Sort Projesi
    ### Proje 2
    [16,21,11,8,12,22] -> Merge Sort
    - [16,21,11]   [8,12,22]
    - [16] [21,11] [8] [12,22]
    - [16] [21] [11] [8] [12] [22]
    - [16] [11,21]   [8] [12,22]
    - [11,16,21]   [8,12,22]
    - [8,11,12,16,21,22]
    - Big-0 = O(nlogn)
---
3. ## Binary Search Tree Projesi
    ### Proje 3
    [7,5,1,8,3,6,0,9,4,2] -> Binary Search Tree
    - 7 Roottur. Root'un sağında 8, solunda 5 bulunur.
    - 8'in sağında 9 bulunur. Solu boştur.
    - 5'in sağında 6, solunda 1 bulunur.
    - 1'in solunda 0, sağında 3 bulunur.
    - 3'ün solunda 2, sağında 4 bulunur.