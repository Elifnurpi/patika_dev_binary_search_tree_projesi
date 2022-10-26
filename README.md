# patika_dev_binary_search_tree_projesi,
[Patika.dev](https://www.patika.dev/tr)


    Proje 3
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

### İkili arama ağacı, her düğümün solundaki koldan ulaşılabilecek bütün verilerin düğümün değerinden küçük, sağ kolundan ulaşılabilecek verilerin değerinin o düğümün değerinden büyük olmasını şart koşar.

### root x=7'dir.

                    7                   (başlangıç)
                  / 
               5                        (5 sayısı 7'den küçük olduğu için 7'nin soluna yerleşti)
             /
           1                            (1 sayısı 5'ten ve 7'den küçük olduğu için 5'in soluna yerleşti)
           
           
           
                      7                   
                    /     \
                5           8            (8 sayısı 7'den büyük olduğundan 7'nin sağ koluna yerleşti)               
             /    
          1                       
            
       
          
           
                       7                   
                    /     \
                5           8                     
             /    
          1                       
            \
             3                       (3 sayısı 7'den ve 5'ten küçük olduğundan 7 ve 5'in soluna, 1'den büyük olduğundan 1'in sağına yerleşti)
                            
                  
                       7                   
                    /     \
                5           8                     
             /    \
          1        6                 (6 sayısı, 7'den küçük olduğu için 7'nin sol koluna; 5'ten büyük olduğu için 5'in sağ koluna yerleşti)
            \
             3  
                        
                        
                       7                   
                    /     \
                5            8                     
             /    \
          1        6                 
         /  \
        0     3                      (0 sayısı 7, 5 ve 1'den küçük olduğu için en sol tarafa yerleşti)
        
                       7                   
                    /     \
                5             8                     
             /    \             \
          1        6              9    (9 sayısı 7 ve 8'den büyük olduğundan 8'in sağ koluna yerleşti)
         /  \
        0     3
                          
                          
                       7                   
                    /      \
                5             8                     
             /    \             \
          1        6              9    
         /  \
        0     3
                \
                  4                     (4sayısı 7 ve 5'ten küçük olduğundan sola, 3'ten büyük olduğundan 3'ün sağına yerleşti)
                  
                  
                       7                   
                    /      \
                5             8                     
             /    \             \
          1        6              9    
         /  \
        0     3
             / \
           2     4                     
                                        (2 sayısı 7 ve 5'ten küçük olduğundan sola, 1'den büyük olduğudan 1'in sağına, 3'ten küçük olduğundan 3'ün sol koluna yerleşti)
        
