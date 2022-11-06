[Patika.dev](https://www.patika.dev/tr)
# Binary-Search-Tree-Projesi
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

 1. Root 7'dir.
 2. 5, 7'den küçüktür. 7'nin soluna yazılır
 3. 1, 7'den ve 5'ten küçüktür. 5'in soluna yazılır.
 4. 8, 7'den büyüktür. 7'nin soluna yazılır.
 5. 3, 7'den ve 5'ten küçüktür ama 1'den büyüktür. 1'in soluna yazılır.
 6. 6, 7'den küçüktür fakat 5'ten büyüktür. 5'in sağına yazılır.
 7. 0, 7'den 5'ten ve 1'den küçüktür. 1'in soluna yazılır.
 8. 9, 7'den ve 8'den büyüktür. 8'in sağına yazılır.
 9. 4, 7'den ve 5'ten küçüktür ama 1'den ve 3'ten büyüktür. 3'ün sağına yazılır.
10. 2, 7'den ve 5'ten küçüktür ama 1'den büyüktür. 3'ten küçüktür, 3'ün soluna yazılır.


      
                    7
                   /  \
                  5    8
                 / \     \
                1   6     9
               / \         
              0   3         
                 / \  
                2   4
