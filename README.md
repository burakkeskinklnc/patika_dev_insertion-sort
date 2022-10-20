# [Patika.dev](https://www.patika.dev/tr) Veri yapıları ve algoritmalar dersi, insertion sort projesi;
### [22,27,16,2,18,6] -> Insertion Sort
#### 1-)Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
-   1.aşama=> [2,27,16,22,18,6] Dizimizdeki en küçük sayının 2 olduğu belirlenir, 2 ila 22 yer değiştirir.
-   2.aşama=> [2,6,16,22,18,27] Devamında 2 haricinde en küçük sayı 6 olduğu için, 6 ve 27 yer değiştirir.
-   3.aşama=> [2,6,16,22,18,27] Bu aşamada 16 üçüncü en küçük sayımız olduğu için yer değiştirmez.
-   4.aşama=> [2,6,16,18,22,27] Dördüncü aşamaya geldiğimizde 18 ve 22 yer değiştirir.
-   5.aşama=> [2,6,16,18,22,27] Son olarak istenen sıralama bulunduğu için herhangi bir yer değiştirme olmaz.
#### 2-)Big-O gösterimini yazınız.
#####  =O(n²)
#### 3-) 1.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
-   Average Case:Aradığımız sayının ortada olması
-   Worst Case:Aradığımız sayının sonda olması
-   Best Case:Aradığımız sayının dizinin en başında olması
 #### 4-) 1. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
##### Cevap: Aradığımız sayı başta(Best Case) ve sonda(Worse Case) olmadığından beklenilen durum olarak Average Case'dir. 
 **[7,3,5,8,2,9,4,15,6**] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 
-   1.aşama=> (2,3,5,8,7,9,4,15,6)

-   2.aşama=> (2,3,5,8,7,9,4,15,6)

-   3.aşama=> (2,3,4,8,7,9,5,15,6)

-   4.aşama=> (2,3,4,5,7,9,8,15,6)
