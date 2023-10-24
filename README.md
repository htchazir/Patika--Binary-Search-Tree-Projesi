# Patika--Binary-Search-Tree-Projesi
Verilen diziyi bir Binary Search Tree (BST) yapısına dönüştürmek ve aşamalarını yazmak için aşağıdaki adımları izleyebiliriz:

Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

İlk elemanı kök (root) olarak belirle: root 7'dir.
Dizi sırasıyla elemanları kontrol ederek BST'yi oluştur:
5, root'un solunda yer alır: root'un solunda 5 bulunur.
1, root'un solunda yer alır: root'un solunda 5'in solunda 1 bulunur.
8, root'un sağındadır: root'un sağına 8 eklenir.
3, 5'in sağındadır: 5'in sağına 3 eklenir.
6, 5'in sağındadır: 5'in sağına 6 eklenir.
0, 1'in solundadır: 1'in soluna 0 eklenir.
9, 8'in sağındadır: 8'in sağına 9 eklenir.
4, 3'ün sağındadır: 3'ün sağına 4 eklenir.
2, 1'in sağındadır: 1'in sağına 2 eklenir.
BST yapısı şu şekildedir:

markdown
Copy code
       7
     /   \
    5     8
   / \     \
  1   6     9
 /     \
0       3
         \
          4
           \
            2
Bu şekilde verilen diziyi bir BST'ye dönüştürmüş olduk.

