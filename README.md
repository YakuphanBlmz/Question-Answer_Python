# Question-Answer_Python

**Soru 1 :** Aşağıdaki veri türlerinden hangilerinde sayısal ve metinsel ifadeler birlikte kullanılabilir?
   * Tuple
   * List
   * Dictionary

**Cevap :** Sayısal ve metinsel ifadelerin birlikte kullanılmasıyla ilgili olarak, Tuple, List ve Dictionary veri türleri uygun seçeneklerdir. Her üçü de Python'da farklı türlerdeki verileri içerebilir ve birlikte kullanılabilir. 

**EK:** Örnek olarak aşağıdaki kodları deneyebilirsiniz.
*   **Tuple** : Aşağıdaki örnekte Tuple içinde bir tamsayı (1), bir metin dizisi ("hello") ve bir ondalık sayı (3.14) bir arada bulunmaktadır.
 ```my_tuple = (1, "hello", 3.14)```

*   **List** :  Aşağıdaki örnekte Liste içerisinde bir tamsayı (42), bir metin dizisi ("world") ve bir ondalık sayı (3.14) bulunmaktadır.
```my_list = [42, "world", 3.14]```

*   **Dictionary** : Aşağıda ise Dictionary içinde bir metin dizisi ("isim"), bir tamsayı (yas) ve bir metin dizisi daha ("il") bulunmaktadır. Bu yapıda anahtarlar (keys) metinsel ifadeler olabilirken, değerler (values) herhangi bir veri türü olabilir.
```my_dict = {"isim": "Yakuphan", "yas": 21, "il": "Erzurum"}```

<br><br>

**Soru 2 :** Aşağıdaki programın ekran çıktısı hangisidir?<br>
```l1 = ["Süt", "Yumurta", "Kabartma Tozu"]```<br>
```l1.append("un")```<br>
```print(l1.pop())```<br><br>

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
```def get_coordinates():```
    ```return (10, 20)```

```x, y = get_coordinates()```
```print("x:", x)```
```print("y:", y)```








