## PROJE-1 

**Soru-1** 

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


**Cevap-1** 

* **Adım-1** -> Verilen örüntü içindeki en küçük ifade bulunur ve en baştaki sayı ile yer değiştirir. Bunun için tüm ifadeler ile kıyaslama yapılarak ( **n** ) adet işlem yapılır. Bu işlem sonucunda ortaya çıkan örüntü: [**2**,27,16,**22**,18,6] şeklini alır.

* **Adım-2** -> Sol taraftaki sayı artık en küçük olduğu için soldan ikinci ifade de aynı işleme tabi tutulur. Bunun için gereken kıyaslama adedi ise (**n-1**) olacaktır. Bu işlem sonucunda ortaya çıkan örüntü: [2,**6**,16,22,18,**27**] şeklini alır.

* **Adım-3**-> Sol taraftaki 2 sayı (2,6) sayıları örüntü içerisinde artık en küçük olduğu için işleme bunların yanında ki sayı (16) ile devam edilir ve işlem basamakları tekrarlanır. Bu kıyaslama için yapılması gerekn işlem adedi ise (**n-2**) dir.Bu işlem sonucunda ortaya çıkan örüntü: [2,6,**16**,22,18,27] şeklini alır.

* **Adım-4**-> Sol taraftaki 3 sayı (2,6,16) sayıları örüntü içerisinde artık en küçük olduğu için işleme bunların yanında ki sayı (22) ile devam edilir ve işlem basamakları tekrarlanır. Bu kıyaslama için yapılması gereken işlem adedi ise (**n-3**) dür.Bu işlem sonucunda ortaya çıkan örüntü: [2,6,16,**18**,**22**,27] şeklini alır.

* **Adım-5**-> Sol taraftaki 4 sayı küçükten büyüğe sıranlamış olduğu için son olarak örüntünün son basamağında bulunan sayılar (22,27) arasında kıyas yapılır ve en küçük olan sola büyük olan ise örüntü sonuna yazılarak işlem tamamlanır.Bunun için yapılması gerekn işlem adeti ise 1 'dir. Bu işlem sonucunda ortaya çıkan örüntünün son hali: [2,6,16,18,22,27] şeklini alır. 
---

**Soru-2**

Big-O gösterimini yazınız.

**Cevap-2** 
* Toplam işlem adeti: n+ (n-1)+ (n-2)+(n-3)+1 olur.
* **Toplam**: **|nx(n+1)|/2** -> **|n^2+n|/2** sonucuna ulaşılabilir. Burada dominant olan ifade ise n^2 olduğu için **Big-O** -> **O(n^2)** şeklinde ifade edilir. 

---

**Soru-3**

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

1. **Average case:** Aradığımız sayının ortada olması
2. **Worst case:** Aradığımız sayının sonda olması
3. **Best case:** Aradığımız sayının dizinin en başında olması.

**Cevap-3** 

**18** sayısı dizinin ortasında yer alması sebebiyle **Average case**  kapsamına girmektedir.

---

**Soru-4**

**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

**Cevap-4** 

* **Adım-1** ->[**2**,3,5,8,**7**,9,4,15,6]
* **Adım-2** ->[2,**3**,5,8,7,9,4,15,6]
* **Adım-3** ->[2,3,**4**,8,7,9,**5**,15,6]
* **Adım-4** ->[2,3,4,**5**,7,9,**8**,15,6]
* **Adım-5** ->[2,3,4,5,**6**,9,8,15,**7**]
* **Adım-6** ->[2,3,4,5,6,**7**,8,15,**9**]
* **Adım-7** ->[2,3,4,5,6,7,**8**,15,9]
* **Adım-8** ->[2,3,4,5,6,7,8,**9**,**15**]





### NOT: Yer değiştiren ifadeler daha  kalın olarak ifade edilmiştir.


