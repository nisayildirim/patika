##Proje 1


*Çözümlere başlamadan önce, ilk olarak Insertion Sort'un ne olduğunu hatırlayalım. Verilen örüntüye göre en küçük elemanın en başa geçip, en baştaki elemanın ise onun yerine geçmesiyle tekrarlanan bir sıralama tekniğidir.

**[22,27,16,2,18,6] -> Insertion Sort**

**1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**
1. [2,27,16,22,18,6]
2. [2,6,16,22,18,27]
3. [2,6,16,22,18,27]
4. [2,6,16,18,22,27]
5. [2,6,16,18,22,27]
**2. Big-O gösterimini yazınız.**
n=6
[22,27,16,2,18,6] --> n(6)
[2|27,16,22,18,6] --> 6-1
[2,6|16,22,18,27] --> 6-2
[2,6,16|22,18,27] --> 6-3
[2,6,16,18|22,27] --> 6-4
[2,6,16,18,22|27] --> 6-5

açıklama: yani 6'dan (n'den) 1 e kadar sayıların toplamı => ( n*(n-1) ) / 2 => n^2(O) 


**3. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**
*Kısa bir hatırlatma*
Time Complexity: Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.


[2,6,16,**18**,22,27]
Sıralanmış haldeyken *18* ortada olduğu için *average case* kapsamına girer.


**4. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**


1.Adım: Dizideki en küçük eleman "2" ile, en baştaki elemanın yer değiştirmesi.

[2,3,5,8,7,9,4,15,6]

2.Adım: ikinci en küçük eleman "3" ile, ikinci elemanın yer değiştirmesi.

[2,3,5,8,7,9,4,15,6]

3.Adım: üçüncü en küçük eleman "3" ile, üçüncü elemanın yer değiştirmesi.

[2,3,4,8,7,9,5,15,6]

4.Adım: dördüncü en küçük eleman "3" ile, dördüncü elemanın yer değiştirmesi.

[2,3,4,5,7,9,8,15,6]