##Proje 2
[16,21,11,8,12,22] -> Merge Sort

**1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**
merge sort un ne olduğuna dair küçük bir hatırlatma; ilk önce ikiye ayırıyoruz ve en küçük yapıtaşına ayırdıktan sonra birleştirip sıralayarak devam ediyoruz.

[16,21,11,8,12,22]
[16,21,11] [8,12,22]
[16,21] [11] [8,12] [22]
[16] [21] [11] [8] [12] [22] --> şimdi hem birleştirip hem de sıralıyoruz.
[16,21] [8,11] [12,22]
[8,11,12,16,21,22]

**2- Big-O gösterimini yazınız.**

2^x=n --> logn