# MergeSortProjesi

                 PatikaDev MergeSort Projesi

                       [16,21,11,8,12,22] 

    Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
                   
                        16,21,11,8,12,22
                    
                  [16,21,11]      [8,12,22]       
              
             [16]    [21,11]      [8]    [12,22] 
              
           [16]  [21]   [11]      [8]   [12]   [22]
              
               [16]  [11,21]      [8]    [12,22] 
                  
                  [11,16,21]      [8,12,22]
                    
                      [8,11,12,16,21,22]

    
                
    Adım sayısı her defasında yarıya düştüğü için 2ˣ=n'den logn.
              

                  Big-O gösterimini >>> o(nlogn)
