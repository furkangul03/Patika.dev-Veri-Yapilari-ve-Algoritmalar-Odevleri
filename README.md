# Insertion Sort Projesi

## 1. Odev

    [22,27,16,2,18,6] -> Insertion Sort
A.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

    1-[2,27,16,22,18,6]
    2-[2,6,16,22,18,27]
    3-[2,6,16,22,18,27] -->16 zaten en küçük değişiklik olmayacak.
    4-[2,6,16,18,22,27]
    5-[2,6,16,18,22,27] -->22 zaten en küçük değişiklik olmayacak.
---
B.Big-O gösterimini yazınız.

    n+(n-1)+(n-2)+...+1 den Big-O gösterimi O(n^2) olur.
---

C.Time Complexity: Average case: Aranan sayının ortada olması,Worst case: Aranan sayının sonda olması, Best case: Aranan sayının dizinin en başında olması.

Average case:n/2 işlem(3-4)
Worst Case:n tane işlem(6)
Best Case:1 işlem

---
D.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Avarage case kapsamına girer.

---
## 2. Odev

A. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1-[2,3,5,8,7,9,4,15,6]
2-[2,3,5,8,7,9,4,15,6] -->3 zaten en küçük değişiklik olmayacak.
3-[2,3,4,8,7,9,5,15,6] 
4-[2,3,4,5,7,9,8,15,6]

---