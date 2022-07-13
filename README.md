# Binary Tree Project solutios.

## Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Solutions. 

   7
  /
 5
 ---
      [7] 
     /
   [5]
   /
 [1]
 
---
 
      7
     /  \
    5    8
   /
  1
--- 
      7       3 added
     /  \
    5    8
   /
  1
   \
    3

      7       6 added
     /  \
    5    8
   / \
  1   6
   \
    3

      7       0 added
     /  \
    5    8
   / \
  1   6
 / \
0   3

      7       9 added
     /  \
    5    8
   / \    \
  1   6    9
 / \
0   3

      7       4 added
     /  \
    5    8
   / \    \
  1   6    9
 / \
0   3
     \
      4
      
       7      2 added
     /  \
    5    8
   / \    \
  1   6    9
 / \
0   3
   / \
  2    4
      
