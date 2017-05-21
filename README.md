# birthday-paradox

1.1)	The birthday paradox says that the probability that two people in a room will have the same birthday is more than half, provided n, the number of people in the room, is more than 23. This property is not really a paradox, but many people find it surprising. 
(from Goodrich and Tamassia)

a)C# method that generates a random birthdays between the two dates given such as 1996 and 1997 (01.01.1996 and 31.12.1997). 

b)C# method that generates n (read from the user) random birthdays.

c)C# program that can test this paradox by a series of experiments on randomly generated birthdays, which test this paradox for n = 100, 500, 1000 students in university (birthdays between 1996 and 1997). 

n’in her bir değeri için deneyleri 10’ar kere tekrarlayıp ortalama çakışma-eşleşme sayısını da tablo halinde yazdırıldı. Örnek olarak 50 kişilik bir sınıfta (ortalama) kaç çakışma vardır? İlgili deneyleri yapan metod yazılarak hesaplatıldı.

d)	Repeat the experiments “in 1.c)” for girls in themselves and boys in themselves assuming university consists of 25% girls and 75% boys. 

•	Çakışma: 2 kişinin doğum tarihi aynı güne geliyorsa 1 çakışma vardır. Bunun için doğum günü yanında doğum yılının da eşit olması gerekmektedir. 3 kişi aynı günde doğdularsa 2 çakışma vardır. 7 kişinin aynı doğum gününe sahip olmaları durumunda 6 çakışma vardır. 

i) Simülasyonlar yapılarak 10 deney için (günleri içeren düzensiz diziler ekrana basılmadan) sadece istatistiksel değerler (çakışma sayıları) 11 x 3’lük ayrı bir tablo olarak ekrana verilmiştir. n’in farklı değerleri (n = 100, 500, 1000 kişi) için 3 sütun, her deneydeki ortalama çakışma sayıları için 10 satır ve bu 10 değerin ortalaması için 11. satır yazdırılmıştır.
