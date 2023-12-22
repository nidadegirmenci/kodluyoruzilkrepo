[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Cevap: Root 9 dur. Bu durumda bir sonraki sayı 6 alırsak, 7 yi ele alırsak sağına almak zorundayız. Sola 5 verebiliriz. 5 i ele aldığımızda 8 verirsek, sağına almak durumundayız. Soluna diğer küçük seçeneklerden birini alırız. 3 ü aldığımız ihtimalde soluna 1 koyabiliriz. Sağa 3 den büyük bir sayı koyup devam edelim. 1 in soluna artık ondan küçük sayı olarak tek seçenek olarak 0 gelir ve sağına 1 den büyük olan elimizde kalan 2 yi yazarız.
                    
                    Root = 9 
                    
                      9                        
                    /
                   6
                 / \
                5   7
                /  \
               3     8
                /  \
                1   4
                /  \
               0    2

