![icon@2x](https://github.com/YakuphanBlmz/Question-Answer_Python/assets/106194461/1e146c2d-6719-4405-8130-c6a4ce9dc937)# Question-Answer_Python

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

**Soru 3 :** Aşağıdaki programın ekran çıktısı nedir?<br>
```
a = [1,2,3,4,5]
print(a.index(3))
```

**Cevap :** Cevabımız *2* sayısıdır. Nedeni ise bu kodu çalıştırdığımızda, *a* listesinde bulunan *index()* yöntemi çağrılır. Bu yöntem, **belirtilen öğenin indeksini döndürür.** Kodun **çıktısı ise 2** olacaktır. Çünkü **3 öğesi a listesinde 2. indekste** bulunmaktadır.

<br><br>

**Soru 4 :** Aşağıdaki programın ekran çıktısı nedir?<br>
```
a = [1,2,3]
a.reverse()
print(a[-1])
```

**Cevap :** Cevabımız *1* sayısıdır. Nedeni ise bu kodu çalıştırdığımızda, önce *a* listesi ters çevrilir *(reverse() yöntemi kullanılarak)*. Sonrasında, *print(a[-1])* ifadesiyle **listenin son öğesi ekrana** yazdırılır. **Ters çevrildikten sonra listenin son öğesi, başlangıçta listenin ilk öğesiydi**, yani 1. Dolayısıyla çıktı 1 olacaktır.


<br><br>

**Soru 5 :** Aşağıdaki ifadelerin hangisinde/hangilerinde liste oluşturma satırı doğru olarak yazılmıştır?<br>
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
