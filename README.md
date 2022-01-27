# python_koşullu_durumlar
--------------------------
## Mantıksal Değerler ve Karşılaştırma Operatörleri :
------------------------------------------------------
Bu konuda, koşullu durumları incelemeden önce bilmemiz gereken mantıksal değerleri ve karşılaştırma operatörlerini öğrenmeye çalışacağız.
### Mantıksal Değerler (Boolean) : 
------------------------------------
Mantıksal değerler ya da ingilizce ismiyle boolean değerler aslında Pythonda bir veri tipidir ve iki değere sahiplerdir: True ve False. 


!! not :Pythonda bir sayı değeri eğer 0'dan farklıysa True, 0 ise False olarak anlam kazanır. Bunu bool() fonksiyonuyla dönüştürme yaparak görebiliriz.Ayrıca Pythonda eğer bir değişkenin değerini sonradan belirlemek isterseniz geçici olarak bu değişken None (atanmamış anlamında) değerine eşitleyebilirsiniz.

### Karşılaştırma Operatörleri :
-------------------------------
== : İki değer birbirine eşitse True, değilse False değer döner.
!= : İki değer birbirine eşit değilse True, diğer durumda False döner.	
<  : Soldaki değer sağdaki değerden küçükse True, değilse False döner
>  : Soldaki değer sağdaki değerden büyükse True, değilse False döner.	
>= : Soldaki değer sağdaki değerden büyükse veya sağdaki değere eşitse True, değilse False döner.	
<= : Soldaki değer sağdaki değerden küçükse veya sağdaki değere eşitse True, değilse False döner.	
-----------------------------------------------------------------------------------------------------------------------------
## Mantıksal Bağlaçlar :
-----------------------
Mantıksal bağlaçlar daha çok karşılaştırma işlemini kontrol ettiğimiz zamanlarda kullanılır. Bu konuda bunları öğrenmeye çalışacağız.

### and Operatörü :
------------------
Bu mantıksal bağlaç, bütün karşılaştırma işlemlerinin sonucunun True olmasına bakar. Bağlanan karşılaştırma işlemlerinin hepsinin kendi içinde sonucu True ise genel sonuç True , diğer durumlarda ise sonuç False çıkar.İşlemlerin birinin bile sonucu False ise genel işlemin sonucu False çıkmaktadır.
### or operatörü :
--------------------
Bu mantıksal bağlaç, bütün karşılaştırma işlemlerinin sonuçlarından en az birinin True olmasına bakar. Bağlanan karşılaştırma işlemlerinin en az birinin True olmasında genel sonuç True , diğer durumlarda ise sonuç False çıkar.
### not operatörü :
------------------
not operatörü aslında bir mantıksal bağlaç değildir. Bu operatör sadece bir mantıksal değeri veya karşılaştırma işlemininin tam tersi sonuca çevirir. Yani, not operatörü True olan bir sonucu False , False olan bir sonucu True sonucuna çevirir. Ku

!! not : Opertörler tek tek kullanabildiğimiz gibi birlikte de kullanabiliriz.
örneğin ;
1)not (2.14 > 3.49 or ( 2 != 2 and "Murat" == "Murat"))
                               |
                               |
                       bu ifade false çıkar
                       
2) not(2.14 > 3.49 or(false))
         |
         |
 bu ifade true çıkar

3) true or false
4) cevap true çıkar
---------------------------------------------------------------------------------------------------------------------------
## Koşullu Durumlar - if-else koşullu durumları :
------------------------------------------------
### Python Programlarının çalışma mantığı :
---------------------------------------------
Python programları çalışmaya başladığı zaman kodlarımız yukardan başlayarak teker teker çalıştırılır ve çalıştıracak kod kalmayınca programımız sona erer.


### Koşullu Durumlar
---------------------
Artık Pythonda bizi bir ileri seviyeye taşıyacak koşullu durumları öğrenmenin vakti geldi.

Koşullu durumlar aslında günlük yaşamda sürekli karşılaştığımız durumlardır. Örneğin havanın yağmurlu olma koşuluna göre şemsiyemizi alırız veya uykumuzun gelme koşuluna göre uyuruz. Aslında programlamada da birçok koşullu durumla karşılaşırız. Örneğin , belli koşullara göre belli işlemleri yaparız , belli koşullara göre yapmayız. İşte bunlar koşullu durumların temeli oluşturur. İsterseniz koşullu durumları yazmaya if blokları ile başlayalım.

### Koşullu Durumlar
---------------------
if bloğu programımızın içinde herhangi bir yerde belli bir koşulu kontrol edecek isek kullanılan bloklardır.Yazımı şu şekildedir;

       if (koşul): 
           # if bloğu - Koşul sağlanınca (True) çalışır. Bu hizadaki her işlem bu if bloğuna ait.
           # if bloğu - Girintiyle oluşturulur.
           Yapılacak İşlemler

if bloğu eğer koşul sağlanırsa anlamı taşır. Eğer if kalıbındaki koşul sağlanırsa (True) if bloğu çalıştırılır, koşul sağlanmazsa (False) if bloğu çalıştırılmaz.

Burada istediğimizi elde edemedik çünkü 2. print işlemi herhangi bir koşula bağlı değil. O yüzden 2.print işlemi her durumda çalışıyor. Peki if koşulu sağlanmadığında belli bir işlemin çalışmasını nasıl sağlayacağız ? Bunun için sıradaki kalıbımızı öğrenelim.
### else Bloğu
----------------
else blokları if koşulu sağlanmadığı zaman (False) çalışan bloklardır. Kullanımı şu şekildedir;

       else:
           # else bloğu - Yukarısındaki herhangi bir if bloğu (veya ilerde göreceğimiz elif bloğu) çalışmadığı
           # zaman çalışır. 
           # else bloğu - Girintiyle oluşturulur.
               Yapılacak İşlemler

































