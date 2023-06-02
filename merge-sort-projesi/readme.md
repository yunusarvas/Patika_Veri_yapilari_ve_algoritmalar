## PROJE-2 

**Soru-1** 

**[16,21,11,8,12,22] -> Merge Sort**

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

**Cevap-1** 

* Dizi ilk olarak 2 ye ayrılır ve bu işlem her iki tarafta da tek eleman kalıncaya kadar devam eder. 

* Adım-1:  ---**[16,21,11,8,12,22]** ---

               /          \
         [16,21,11]    [8,12,22]       
     
* Adım-2: **[16,21,11]**  -------------------**[8,12,22]**
            
          /       \               /    \
        [16]    [21,11]        [8]  [12,22]

* Adım-3: **[16]-----[21,11]**  -------------**[8]-----[12,22]**
            
           /       /    \          /    /   \
         [16]    [21] [11]        [8]  [12] [22]

* Adım-4: Tek elemanlı dizinler sıralama yaparak tekrar  gruplandırılr ve böylece sıralanmış dizin ortaya çıkar.

        [16]    [21] [11]        [8]  [12] [22] 
        
         /        \    /          /     \   /
         [16]    [11,21]        [8]    [12,22]
            \       /            \        /
           [11,16,21]            [8,12,22]
               \                     /
                    [8,11,12,16,22] sonucuna ulaşılır.
   
---

**Soru-2** 
* Big-O gösterimini yazınız.

**Cevap-2**

* 2^x=n = O(nlogn)

---