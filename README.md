#### BİLECİK ÜNİVERSİTESİ - University_Exam_Question_Answers_Data_Structures_Lesson

**Soru 1 :** Aşağıdaki veri türlerinden hangilerinde sayısal ve metinsel ifadeler birlikte kullanılabilir?
   * Tuple
   * List
   * Dictionary

**Cevap :** Sayısal ve metinsel ifadelerin birlikte kullanılmasıyla ilgili olarak, Tuple, List ve Dictionary veri türleri uygun seçeneklerdir. Her üçü de Python'da farklı türlerdeki verileri içerebilir ve birlikte kullanılabilir. 

**EK:** Örnek olarak aşağıdaki kodları deneyebilirsiniz.
*   **Tuple** : Aşağıdaki örnekte Tuple içinde bir tamsayı (1), bir metin dizisi ("hello") ve bir ondalık sayı (3.14) bir arada bulunmaktadır.<br>
 ```my_tuple = (1, "hello", 3.14)```

*   **List** :  Aşağıdaki örnekte Liste içerisinde bir tamsayı (42), bir metin dizisi ("world") ve bir ondalık sayı (3.14) bulunmaktadır.<br>
```my_list = [42, "world", 3.14]```

*   **Dictionary** : Aşağıda ise Dictionary içinde bir metin dizisi ("isim"), bir tamsayı (yas) ve bir metin dizisi daha ("il") bulunmaktadır. Bu yapıda anahtarlar (keys) metinsel ifadeler olabilirken, değerler (values) herhangi bir veri türü olabilir.<br>
```my_dict = {"isim": "Yakuphan", "yas": 21, "il": "Erzurum"}```

<br><br>

**Soru 2 :** Aşağıdaki programın ekran çıktısı hangisidir?<br>
```
l1 = ["Süt", "Yumurta", "Kabartma Tozu"]
l1.append("un")
print(l1.pop())
```

**Cevap :** Çıktı şu şekilde olacaktır : **```un```**<br>
*  İlk olarak, *l1* adında bir liste oluşturulmuştur: ```["Süt", "Yumurta", "Kabartma Tozu"]```
*  append() yöntemi kullanılarak listenin sonuna *"un"* öğesi eklenmiştir.
*  pop() yöntemi çağrılmış ve listenin son öğesi olan "un" öğesi çıkarılmıştır ve ekrana yazdırılmıştır.

<br><br>

**Soru 3 :** Aşağıdaki verinin türü nedir?
```Haftaİçi = ("Pazartesi")```

**Cevap :** *Tuple*

**EK:** Tuple, Python'da kullanılan bir veri türüdür. Liste gibi sıralı ve değiştirilebilir veri yapılarından farklı olarak, tuple'lar sıralı ve değiştirilemez (immutable) veri yapılarıdır. Bu, bir kere oluşturulduktan sonra içeriğinin değiştirilemeyeceği anlamına gelir. 
* Tuple'lar parantez içinde ve virgülle ayrılmış öğelerden oluşur. Örneğin:  <br>
```my_tuple = (1, 2, 3, 4, 5)```
*  Tuple'lar genellikle farklı veri tiplerinden öğeler içerebilir ve karışık veri yapılarında kullanılabilirler. Örneğin: <br>
```mixed_tuple = ("apple", 3, True, 2.5)```
* Tuple'lar genellikle sabit veri koleksiyonları için kullanılır ve verilerin değiştirilemezliği nedeniyle, programların güvenli ve tutarlı çalışmasını sağlarlar. Tuple'lar ayrıca işlevlerden birden fazla değer döndürmek için de kullanılır. Örneğin: <br>
```
def get_coordinates():
    return (10, 20)

x, y = get_coordinates()
print("x:", x)
print("y:", y)
```
<br><br>

**Soru 4 :** Aşağıdaki programın ekran çıktısı nedir?<br>
```
a = [1,2,3,4,5]
print(a.index(3))
```

**Cevap :** Cevabımız *2* sayısıdır. Nedeni ise bu kodu çalıştırdığımızda, *a* listesinde bulunan *index()* yöntemi çağrılır. Bu yöntem, **belirtilen öğenin indeksini döndürür.** Kodun **çıktısı ise 2** olacaktır. Çünkü **3 öğesi a listesinde 2. indekste** bulunmaktadır.

<br><br>

**Soru 5 :** Aşağıdaki programın ekran çıktısı nedir?<br>
```
a = [1,2,3]
a.reverse()
print(a[-1])
```

**Cevap :** Cevabımız *1* sayısıdır. Nedeni ise bu kodu çalıştırdığımızda, önce *a* listesi ters çevrilir *(reverse() yöntemi kullanılarak)*. Sonrasında, *print(a[-1])* ifadesiyle **listenin son öğesi ekrana** yazdırılır. **Ters çevrildikten sonra listenin son öğesi, başlangıçta listenin ilk öğesiydi**, yani 1. Dolayısıyla çıktı 1 olacaktır.


<br><br>

**Soru 6 :** Aşağıdaki ifadelerin hangisinde/hangilerinde liste oluşturma satırı doğru olarak yazılmıştır?<br>
```
isimListesi1 = ("Yakuphan","Enes","Muhammed","Gürkan","Furkan")

isimListesi2 = [Yakuphan,Enes,Muhammed,Gürkan,Furkan]

isimListesi3 = ["Yakuphan","Enes","Muhammed","Gürkan","Furkan"]

isimListesi4 = Yakuphan,Enes,Muhammed,Gürkan,Furkan

isimListesi5 = "Yakuphan","Enes","Muhammed","Gürkan","Furkan"
```


**Cevap :** Cevap **isimListesi3**'tür. Bu satır, listenin öğelerini " " (çift tırnak) içine alır ve virgülle ayrılarak bir liste oluşturur. Peki diğer ifadeler nedir?
*  **isimListesi1** : Bir tuple oluşturur.
*  **isimListesi2** : İçindeki isimlerin tırnak işaretleri olmadığı için geçerli bir Python ifadesi değildir.
*  **isimListesi4** : Bir tuple oluşturur, ancak içindeki isimlerin tırnak işaretleri olmadığı için geçerli bir Python ifadesi değildir.
*  **isimListesi5** : Öğeleri çift tırnak işaretleri içinde virgülle ayrılarak bir tuple oluşturur. Bu da geçerli bir Python ifadesidir, ancak özellikle bir liste oluşturmak için kullanılmamıştır, tuple oluşturmuştur.

Eğer sizde kendi ortamınızda kodları deneyip görmek isterseniz aşağıdan kopyalayıp yapıştırarak bakabilirsiniz :
```
isimListesi1 = ("Yakuphan","Enes","Muhammed","Gürkan","Furkan")
print(type(isimListesi1))

isimListesi2 = [Yakuphan,Enes,Muhammed,Gürkan,Furkan]
print(type(isimListesi2))

isimListesi3 = ["Yakuphan","Enes","Muhammed","Gürkan","Furkan"]
print(type(isimListesi3))

isimListesi4 = Yakuphan,Enes,Muhammed,Gürkan,Furkan
print(type(isimListesi4))

isimListesi5 = "Yakuphan","Enes","Muhammed","Gürkan","Furkan"
print(type(isimListesi5))
```

<br><br>

**Soru 7 :** Aşağıdaki kodun ekran çıktısı nedir?
```
a = 5
b = 3.14
c = [a,b,True]
print(c[1])
```

**Cevap :** Bu kodu çalıştırıldığında, c listesinin **indeksi 1 olan** öğesi ekrana yazdırılacaktır. Bu öğe, **b değişkeninin değeridir, yani 3.14 olacaktır.** Dolayısıyla çıktı 3.14 olacaktır.

<br><br>

**Soru 8 :** Aşağıdaki programın ekran çıktısı nedir?
```
a = [1,2,3,4,5]
print(a.count(3))
```

**Cevap :**  Bu kodu çalıştırıldığında, a listesinde bulunan *count()* yöntemi çağrılacaktır. Bu yöntem, listenin içinde belirtilen öğenin kaç kez geçtiğini sayar. **Çünkü 3, a listesinde bir kez geçmektedir**, bu nedenle **çıktı 1 olacaktır.**


<br><br>

**Soru 9 :** Aşağıdaki program çıktısında, 0-3 arası rakamları alt alta ekrana yazdığına göre **XXX** olan kısıma ne gelmelidir?
```
satır = 4
for i in XXX(satır) :
  print(i)
```


**Cevap :** Doğru ifade *range(satır)* olmalıdır. Bu durumda, 0'dan başlayarak satır - 1'e kadar (yani 3'e kadar) olan sayılar alt alta ekrana yazdırılır. 

<br><br>

**Soru 10 :** Aşağıdaki verinin türü nedir?
```
anket = {"Anadili" : "Türkçe" , "Yaşı" : 21 , "YabancıDil" : "Türkçe"}
```

**Cevap :** Veri türü, **anket** değişkenine atanan değerin bir sözlük (dictionary) olduğunu belirtir. 


<br><br>


**Soru 11 :** Aşağıdakilerden hangisi primitif (basit) olmayan bir veri türüdür.
*  List
*  String
*  Integer
*  Float

**Cevap :** Listenin, primitif olmayan (basit olmayan) bir veri türüdür. Liste, birden çok öğeyi içerebilen ve değiştirilebilen bir veri yapısıdır, bu nedenle diğer seçeneklerden farklıdır.

**"Primitif"** terimi genellikle basit veya temel anlamına gelir. Programlama bağlamında, "primitif veri türleri" temel veri tiplerini ifade eder. Bu veri tipleri, dilin temel yapısını oluşturan ve daha karmaşık veri yapıları ve nesnelerin yapı taşları olan veri tipleridir.

Örneğin, bir dilin primitif veri tipleri genellikle şunlardır:

* **Integer (Tam Sayı):** Tamsayıları temsil eder. Örneğin, -3, 0, 42 gibi.
* **Float (Ondalık Sayı):** Ondalık sayıları temsil eder. Örneğin, 3.14, -0.001 gibi.
* **String (Metin):** Metin veya karakter dizilerini temsil eder. Örneğin, "hello", "world" gibi.
* **Boolean (Mantıksal Değer):** Sadece iki değere sahip olan, genellikle "True" ve "False" olarak ifade edilen mantıksal değerleri temsil eder.

Primitif veri tipleri, genellikle dilin temel sözdizimine dahil edilmiş ve doğrudan kullanılabilen veri türleridir. Diğer veri yapıları ve nesneler, bu primitif veri tipleri üzerinde inşa edilmiştir.

<br><br>

**Soru 12 :** Aşağıdaki programın çıktısı nediir?
```
tureng = {
    'kitap' : 'book',
    'sayfa' : 'page',
}

a = list(tureng.items())
print(a[0][1])
```

**Cevap :** *Book*

Bu kodu çalıştırdığımızda, *tureng* sözlüğünün öğeleri bir liste olarak dönüştürülür *(list(tureng.items())).* Bu liste, (anahtar, değer) çiftlerini içerir. print(a[0][1]) ifadesi, bu **listenin ilk öğesinin değerini (yani, ilk çiftin değerini)** yazdırır.

*a[0] ifadesi listenin ilk öğesini* (yani, ilk çifti) verir. **a[0][1] ifadesi ise listenin ilk öğesinin ikinci öğesine** (yani, ilk çiftin değerine) karşılık gelir.

Dolayısıyla, çıktı **"book"** olacaktır.

<br><br>

**Soru 13 :** Aşağadaki programın çıktısı nedir?
```
adres = 'Bilecik'
for sokak in adres :
  print(adres)
```

**Cevap :** Ekrana **7 kez Bilecik** yazısını yazdırır. 

Bu kod parçası, **"adres"** değişkeninin her bir karakterini sokak değişkenine atayarak bir döngü oluşturur ve her döngü adımında "adres" değişkenini ekrana yazdırır. Ancak, "adres" değişkeni döngü içinde herhangi bir değişikliğe uğramaz, dolayısıyla her döngü adımında aynı şeyi ekrana yazdırır.<br>

Yani, bu kod parçasını çalıştırdığımızda "Bilecik" string'i 7 kez alt alta yazdırılır. Her satırda "Bilecik" string'i aynı kalır çünkü döngü her bir karakter üzerinde dönse de "adres" değişkeni değişmez.<br>

Eğer "adres" değişkeninin uzunluğu, yani içindeki karakterlerin sayısı 7 ise, döngü 7 kez çalışacak ve "Bilecik" string'i 7 kez alt alta yazdırılacaktır. Dolayısıyla, "adres" değişkeninin uzunluğu kadar, yani 7 kez yazdırır.<br>

<br><br>

**Soru 14 :** Aşağıdaki programın çıktısı nedir?
```
tureng = {
    'kitap' : 'book',
    'sayfa' : 'page',
}

print(tureng.get('book','yakuphan'))
```

**Cevap :** Bu kod parçası, *'book'* anahtarına sahip bir değer olup olmadığını kontrol eder. Eğer 'book' anahtarı varsa, bu anahtarın değerini döndürür. Ancak, 'book' anahtarı yoksa, varsayılan olarak 'yakuphan' değerini döndürür.

Ancak, **'tureng' sözlüğünde 'book' anahtarı bulunmamaktadır.** Bu nedenle, tureng.get('book','yakuphan') ifadesi 'book' anahtarına karşılık gelen bir değer olmadığı için varsayılan değeri olan 'yakuphan'ı döndürecektir. Dolayısıyla, **çıktı "yakuphan"** olacaktır.

<br><br>

**Soru 15 :** Hangi veri yapısının eleman değerleri değiştirilemez?
*  List
*  Dictionary
*  Tuple
*  Array


**Cevap :**  Eleman değerleri değiştirilemez olan veri yapısı, **"Tuple"** olarak adlandırılan veri yapısıdır. 


<br><br>


**Soru 16 :** Aşağıdaki programın çıktısı nedir?
```
a = [2,1,-2,5]
a.sort()
print(a[1])
```

**Cevap :** Bu programda, a listesini sıralanır ve ardından listenin ikinci en küçük elemanını ekrana yazdırılır.

İlk olarak, a listesi *[2, 1, -2, 5]* olarak tanımlanır. Sonra a.sort() metodu kullanılarak liste sıralanır ve **yeni liste [ -2, 1, 2, 5]** olur. Ardından, print(a[1]) ifadesi ile listenin **ikinci elemanı** ekrana yazdırılır. Listenin ikinci elemanı 1 olduğu için **çıktı 1** olacaktır.


<br><br>

**Soru 17 :** Aşağıdakilerden hangisi Python'da varsayılan olarak bulunmaz?
*  Object
*  Tuple
*  Strcut
*  List


**Cevap :** Python'da varsayılan olarak bulunmayan veri yapısı **"Strcut"tur.** Diğer seçenekler, yalnızca "Strcut" değil, Python'da bulunan veri yapılarıdır.

Python'da struct yerine genellikle veri yapısı oluşturmak için **class** kullanılır. Bir sınıf tanımlayarak özel bir veri yapısı oluşturabilir ve bu sınıfın örneklerini kullanarak veri yapılarını temsil edebilirsiniz. Sınıflar, veriye sahip özellikler (attributes) ve bu özellikler üzerinde işlem yapabilen yöntemler (methods) içerebilir. 

Python'da **struct modülü**, veri yapısı oluşturmak için kullanılabilir ancak bu, **varsayılan bir veri yapısı değildir.** struct modülü, Python'un standart kütüphanesinin bir parçasıdır ve veri yapılarını temsil etmek için kullanılabilir, ancak dilin temel veri tipleri olan **list, tuple, dict, str** gibi yapılar kadar yaygın değildir. Bu nedenle, Python'da varsayılan olarak bulunan veri yapıları arasında struct bulunmaz.

<br><br>

**Soru 18 :** Aşağıdaki programın çıktısı ne olur?
```
adres = 'Python'
for i in range(len(adres)//2) : 
  print(adres[i])
```


**Cevap :** Programda, 'adres' değişkeninin yarısına kadar (taban tabana) bir aralıkta döngü oluşturur ve her döngü adımında 'adres' değişkeninin indekslerini ekrana yazdırır.

İlk olarak, 'adres' değişkeni "Python" olarak tanımlanır. Sonra, **len(adres)//2 ifadesi kullanılarak 'adres' değişkeninin uzunluğunun yarısı alınır** ve bu değer range() fonksiyonuna iletilir. Bu, 'adres' değişkeninin yarısı kadar bir aralık elde edilir.

Döngü her bir indeks üzerinde döner ve her döngü adımında 'adres' değişkeninin ilgili indeksi ekrana yazdırılır.

Bu durumda, **'adres' değişkeninin yarısı 3 olduğu için**, döngü 0, 1 ve 2 indekslerinde dönecektir. Dolayısıyla, çıktı şu olacaktır:

```
P
y
t
```

<br><br> 

**TEŞEKKÜRLER** 
















