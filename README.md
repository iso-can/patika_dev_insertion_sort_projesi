# patika_dev_insertion_sort_projesi
  
Patika.dev'de veri yapıları kursu için yapılan proje  

#Proje 1
SORU-1) [22,27,16,2,18,6] -> Insertion Sort  
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1-) [22,27,16,2,18,6]  
2-) 22|,27,16,2,18,6  
3-) 22,27|,16,2,18,6  
4-) 16,22,27|,2,18,6  
5-) 2,16,22,27|,18,6  
6-) 2,16,18,22,27|,6  
7-) 2,6,16,18,22,27|  
  
Soru-2) Big-O gösterimini yazınız.  

O(N^2)  
  
Soru-3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.  

Worst Case:  
Küçükten büyüğe sıralanmak istenen bir dizinin tüm elemanlarının büyükten küçüğe sıralanmasıdır (reversed order).  
O(N x (N+1)) / 2 => O((N²+N)/2) => O(N²/2) => O(N²)  

Best Case:  
Küçükten büyüğe sıralamak istediğimiz bir dizinin elemanlarının zaten küçükten büyüğe sıralandığı durumdur.  
Dolayısıyla O(N)' dir.  

Average Case:  
O(N²) + O(N) in ortalaması olacağı için yine N² cinsinden bir sonuç olur. Average case = O(N²)  

[2,6,16,18,22,27]=> Sıralanmış dizi  

Cevap : Aradığımız sayı başta(Best Case) ve sonda(Worse Case) olmadığından beklenilen durum olarak Average Case'dir.  

Soru-4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.  


Soru -) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.  
7|,3,5,8,2,9,4,15,6  
3,7|,5,8,2,9,4,14,6  
3,5,7|,8,2,9,4,14,6  
3,5,7,8|,2,9,4,14,6  
