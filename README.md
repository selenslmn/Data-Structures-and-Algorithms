# Insertion Sort Projesi

**Proje 1**

***[22,27,16,2,18,6] -> Insertion Sort***

*1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.*
> [2,27,16,22,18,6]
> [2,6,16,22,18,27]
> [2,6,16,18,22,27]

*2. Big-O gösterimini yazınız.*
> n = 6
> O(n^2) = O(6^2) = 36 işlem gerçekleşir.  

*3.Time Complexity:* 
> Average case: Aradığımız sayının ortada olması O(n^2)
> Worst case: Aradığımız sayının sonda olması O(n^2)
> Best case: Aradığımız sayının dizinin en başında olması O(n)

*4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.*
> Average case

*5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sorta göre ilk 4 adımını yazınız.*
     1. [2,3,5,8,7,9,4,15,6]
     2. [2,3,4,8,7,9,5,15,6]
     3. [2,3,4,5,7,9,8,15,6]
     4. [2,3,4,5,7,8,9,15,6]