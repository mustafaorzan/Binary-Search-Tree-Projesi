# Binary-Search-Tree-Projesi

patika.dev -> https://app.patika.dev/cataldirect

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


    ekle: 7 ->  7
    
    ekle: 5 ->  7
               /
              5
              
    ekle: 1 ->   5
               /   \
              1     7     
              
    
    ekle: 8 ->   5
               /   \
              1     7 
                     \
                      8
                      
     ekle: 3 ->    5
                 /   \
                3     7 
               /        \
              1          8     
              
              
     ekle: 6 ->     6
                 /      \
                3        7 
               /  \       \
              1    5       8
              

      ekle: 0 ->     6
                 /      \
                3        7 
               /  \       \
              1    5       8
             /
            0
            
      ekle: 9 ->     6
                 /      \
                3        8 
               /  \     /  \
              1    5   7    9
             /
            0
                  
      ekle: 4 ->    5
                    / \
                  /      \
                 3         6  
                /  \        \
               1    4        8 
              /             /  \
             0             7    9
             
 
 
       ekle: 2 ->    5
                    / \
                  /      \
                 3         6  
                /  \        \
               1    4        8 
              /  \          /  \
             0    2        7    9
          
