#Efsun💜✨
---
Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

2. [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
---
1. Proje: Insertion Sort Analizi
Dizi: [22, 27, 16, 2, 18, 6]

Insertion Sort (Ekleme Sıralaması), her adımda diziden bir eleman seçip, bu elemanı kendinden önceki sıralı alt 
dizi içindeki doğru konuma "yerleştirerek" ilerler ✨

Aşamalar:
1. [22], 27, 16, 2, 18, 6 | İlk eleman (22) sıralı kabul edilir. İkinci eleman 27, 22 ile kıyaslanır. 27 > 22 olduğu için yerinde kalır
2. [22, 27], 16, 2, 18, 6 | 16 elemanı seçilir. 27 ve 22 ile kıyaslanır. İkisinden de küçük olduğu için en başa alınır
3. [16, 22, 27], 2, 18, 6 | 2 elemanı seçilir. Sıralı bloktaki (16, 22, 27) tüm elemanlardan küçük olduğu için en başa taşınır
4. [2, 16, 22, 27], 18, 6 | 18 elemanı seçilir. 27 ve 22'den küçük, 16'dan büyüktür. 16 ile 22 arasına yerleşir
5. [2, 16, 18, 22, 27], 6 | 6 elemanı seçilir. 2'den büyük, 16'dan küçüktür. 2 ile 16 arasına yerleşir
6. [2, 6, 16, 18, 22, 27] | Dizi sıralanmıştır


Big-O Gösterimi:
Insertion Sort'un karmaşıklığı, iç içe iki döngü yapısından dolayı hesaplanır:
> Worst Case (En Kötü Durum): Dizi tamamen ters sıralıysa O(n^2)
> Average Case (Ortalama Durum): O(n^2)
> Best Case (En İyi Durum): Dizi zaten sıralıysa sadece O(n)


Time Complexity ve 18 Sayısının Durumu:
Dizi sıralandıktan sonraki hali: [2, 6, 16, 18, 22, 27]
> 18 Sayısı: Sıralanmış dizide orta bölgede yer almaktadır
> Case: Average Case kapsamına girer. Çünkü aradığımız sayı ne en başta (Best) ne de en sondadır (Worst); beklenen değer olarak ortalardadır

---

2. [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

---
Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]
Selection Sort, dizideki en küçük elemanı bulup o anki iterasyonun başındaki elemanla "yer değiştirme" mantığına dayanır.

1.	Adım:
Tüm dizi taranır. En küçük eleman 2 olarak bulunur
En baştaki 7 ile 2 yer değiştirir

Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]

2.	Adım:
İkinci elemandan itibaren (3'ten başlayarak) tarama yapılır. En küçük eleman 3'tür
3 zaten doğru yerdedir (kendisiyle yer değiştirir veya işlem yapılmaz)

Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]

3.	Adım:
Üçüncü elemandan itibaren (5'ten başlayarak) tarama yapılır. En küçük eleman 4 olarak bulunur
5 ile 4 yer değiştirir

Dizi: [2, 3, 4, 8, 7, 9, 5, 15, 6]

4.	Adım:
Dördüncü elemandan itibaren (8'den başlayarak) tarama yapılır. En küçük eleman 5 olarak bulunur
8 ile 5 yer değiştirir

Dizi: [2, 3, 4, 5, 7, 9, 8, 15, 6]

---
