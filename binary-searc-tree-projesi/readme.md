## PROJE-3

**Soru-1** 

**[7,5,1,8,3,6,0,9,4,22]**

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

**Cevap-1** 

* İlk olarak 7 rakamından başlayıp, bunun Kök Boğum(Root Node) olduğunu düşünerek en başa yerleştirelim. Ardınan ikinci rakama geçelim. İkinci rakam, ilk rakam olan 7' ye bağlı olmak durumda. Bir başka deyişle onun alt boğumu/çocuk boğumu(Child Node) olacak. 5, 7' den küçük bir rakam. Bu sebepten onu sol alt tarafa alalım. Ve bundan sonra gelen tüm sayıları da aynı kurala göre dizelim.Büyük olanı sağ, küçük olanı sola koyalım.

                         7
                        / \
                       5   8
                      / \   \
                     1   6   9
                    /  \      
                   0    3      
                       / \
                      2   4


