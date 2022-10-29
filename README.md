[patika.dev adresim](https://app.patika.dev/harunbingol)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
root'un sağında kalanlar root değerinden büyük, solunda kalanlar ise root değerinden küçük değerler olmalıdır.
  - root : 7      
   # Adımlar : 
   ##### 1. ADIM : 5 sayısı root değerinden küçük olduğu için root değerinin sol tarafına yazıldı.
                             7
                            / \
                           5 
   ##### 2. ADIM : 1 sayısı root değerinden küçük olduğu için root değerinin sol tarafına, 5 değerinden küçük olduğu için 5'in sol tarafına yazıldı. 
                              7
                             / \
                            5                                               
                           / \
                          1 
   ##### 3. ADIM : 8 sayısı root değerinden büyük olduğu için root değerinin sağ tarafına yazıldı.
                              7                                                                                                        
                             / \
                           5     8                               
                          / \   / \
                         1         
                        / \ 
                          
   
   
   
   
   ##### 4. ADIM : 3 sayısı root değerinden küçük olduğu için root değerinin sol tarafına, 1 değerinden büyük olduğu için 1'in sağ tarafına yazıldı.
                              7  
                             / \
                           5     8                               
                          / \   / \
                         1         
                        / \ 
                            3
                           / \
                              
                    
   ##### 5. ADIM : 6 sayısı root değerinden küçük olduğu için root değerinin sol tarafına, 3 değerinden büyük olduğu için 3'ün sağ tarafına yazıldı.
                              7  
                             / \
                           5     8                               
                          / \   / \
                         1         
                        / \ 
                            3
                           / \
                               6
                              / \
                             
   
   
   ##### 6. ADIM : 0 sayısı root değerinden küçük olduğu için root değerinin sol tarafına, 6 değerinden küçük olduğu için 6'nın sol tarafına yazıldı.
                              7  
                             / \
                           5     8                               
                          / \   / \
                         1         
                        / \ 
                            3
                           / \
                               6
                              / \
                            0
                           / \
                             
   
   
   
   ##### 7. ADIM : 9 sayısı root değerinden büyük olduğu için root değerinin sağ tarafına, 8 değerinden büyük olduğu için 8'in sağ tarafına yazıldı.
                              7  
                             / \
                           5     8                               
                          / \   / \
                         1         9
                        / \ 
                            3
                           / \
                               6
                              / \
                            0
                           / \
                             
   
   
   ##### 8. ADIM : 4 sayısı root değerinden küçük olduğu için root değerinin sol tarafına, 0 değerinden büyük olduğu için 0'ın sağ tarafına yazıldı.
                                 7  
                             / \
                           5     8                               
                          / \   / \
                         1         9
                        / \ 
                            3
                           / \
                               6
                              / \
                            0
                           / \
                              4
                             / \
   
   
   ##### 9. ADIM : 2 sayısı root değerinden küçük olduğu için root değerinin sol tarafına, 4 değerinden küçük olduğu için 4'ün sol tarafına yazıldı.
   
                                  7  
                                 / \
                               5     8                               
                              / \   / \
                             1         9
                            / \ 
                                3
                               / \
                                   6
                                  / \
                                0
                               / \
                                  4
                                 / \
                                2   
                                
