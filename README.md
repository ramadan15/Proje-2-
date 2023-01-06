# Proje-2-
Merge Sort sıralama algoritmasıyla veri dizisindeki elemanları her seferinde ikiye bölerek küçükten büyüğe sıralayabiliriz. 
                              [16,21,11,8,12,22]
                              [16,21]  [11]     [8,12]  [22]
                            [16]   [21]  [11]   [8]  [12]    [22]
                            [11,16,21]            [8,12,22]
                                      [8,11,12,16,21,22]
     Sayı dizisini her seferinde 2'ye böldüğümüzden time complexity = 2 üzeri X = n ve n-1 defa bu işlemi yaptığımızdan dolayı time complexity= nlogn
