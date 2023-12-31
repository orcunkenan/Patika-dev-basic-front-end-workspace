# Sık Kullanılan HTML Etiketleri

## H Etiketleri

H etiketleri başlık etiketleridir. Büyükten küçüğe doğru sırayla gider ve 6 da son bulur. 
*  h1 h2 h3 h4 h5 h6

```<h1> Bu bir başlık etiketidir. </h1>```

## P Etiketi

P etiketi paragraf etiketidir. Sayfa içerisinde oluşturacağımız metinleri p etiketi ile oluştururuz.

`<p> Bu bir paragraf etiketidir.</p>`


## BR Etiketi

br etiketi satırı atlama etiketidir ve kapatılmaya ihtiyaç duymaz.

```<p> Bu bir paragraftir <br> ve br etiketine örnek vermek için oluşturulmuştur</p>```
## A Etiketi

A etiketinin en önemli özelliği href özelliğidir. Bu etiket ile sayfaları linkleyebiliriz.

``` html
<a href="https://www.google.com.tr">Google</a>
```

## UL-OL-Li Etiketi

ul ve ol etiketleri liste oluşturma etiketleridir. Listeyi oluşturduktan sonra içeriğini oluşturmak için li etiketini kullanıyoruz.
```
<ul> = "unordered list" sırasız liste anlamına geliyor. </ul>
<ol> = "ordered list" sıralı liste anlamına geliyor. </ol> 
```

## Script Etiketi
script etiketi JavaScript kodlarını HTML içerisine yazabilmemizi sağlar.
```<script> document.write("kodluyoruz") </script>```

## Buton Etiketi
Buton etiketini buton oluşturmak için kullanırız. Buton üzerine yazmak istediğiniz içeriği etiketin içine yazmanız yeterlidir.

```<button> Buton </button>```

## IMG Etiketi
Resim eklemek için img etiketini kullanıyoruz. ```<img src=”resim.jpg” alt=”açıklama yazısı” />``` src="" kısmına eklemek istediğimiz görselin yolunu yani kaynağını yazmalıyız. Eğer görselimiz ve HTML dosyamız aynı klasörde ise görselin adını ve uzantısını yazmamız yeterlidir. alt="" kısmına görselin açıklamasını yazıyoruz fakat isterseniz boş bırakabilirsiniz. Bu etiket kapanmaya ihtiyaç duymaz.

```<img src=”görseller/kodluyoruz.jpg” alt=”Kodluyoruz Bootcamp” />```

## iframe Etiketi
Belge içinde belge gösterebilmemizi sağlayan etikettir. Genelde başka bir sitedeki belgeyi kendi sayfamızda göstermek için kullanırız. örn: Youtube'dan bir videoyu sayfamızda göstermek istersek ```<iframe>``` kodlarını sayfamıza eklememiz yeterli.(video üzerinde sağ tıklayıp yerleştirme kodunu kopyala diyerek iframe kodunu kopyalayabiliriz.)

```<iframe> burasi alinti link </iframe>```

---

## HTML ilk ders
Index.html dosyamı oluşturup, tarayıcıda görebileceğim bir kod yazdım.

---

## İkinci ders
Açıklama satırı öğrenildi.

---

## Üçüncü Ders
Başlıklar ve Paragraflar öğrenildi.

---

## Dördüncü Ders Listeler
* Sıralı ve Sırasız listeler var genelde sırasız listeler kullanılıyor.
* Sıralı listeler için ol elementi kullanılıyor.
* Sırasız listeler için ul elementi kullanılıyor.
* sıralı veya sırasız listeler içerisinde sıralı veya sırasız listeler kullanabiliriz, liste içinde liste gibi.
* Sıralı listelerde type etiketini kullanarak sıralama seçeneğini değiştirebiliriz rakamdan roma alfabesine çevirmek gibi mesela.
* Sırasız listelerin başındaki simgeleri style etiketinin içinde list-style-type none diyerek yok edebiliriz.
* Sırasız listelerin başındaki simgeleri aynı zamanda style etiketini kullanarak list-style-type disc, square ya da circle değiştirebiliriz.

---

## Beşinci Ders Emmet
* Etiket isimlerini direkt verebiliyoruz
* '+' ile kardeş bir element oluşturabiliriz tıpkı şu şekilde h1+h2 veya h1+p gibi.
* '>' ile bir elementin içine bir element oluşturabiliyoruz.  h1>p veya benzerleri.
* '^' içinde olduğumuz elementin dışına çıkarak bir element daha oluşturmamıza olanak tanır. div>h1^p gibi.
* '.' class oluştururken kullanıyoruz. .ilkdiv gibi.
* '#' id oluştururken kullanıyoruz. #ilkdiv gibi.
* '*' aynı elementten bir den fazla oluşturmak istediğimizde kullanırız. h1*3 gibi.

---

## Altıncı Ders Image
* HTML üzerinden local veya network üzerinden img elementini kullanarak imaj dosyası eklemeyi öğrendim.
* Picture etiketi ile sayfa boyutuna gore değişebilen resimler eklemeyi öğrendim.
* img dosyasına area ve map etiketi ile görselin içine özel linkleme etiketini öğrendim.

---

## Yedinci Ders Linkler
* HTML de a etiketi ile başka bir sayfaya veya siteye yönlendirme yapabiliyoruz
* a etiketinin içine img dosyası oluşturup linklenebilir bir img dosyası inşa edebiliyoruz.
* a etiketiyle navbar tasarımında sayfa içinde direkt olarak gidilecek yere yönlendirme yapabiliyoruz.
* mail veya telefon yönlendirmelerinde de kullanabiliyoruz.

---

## Sekizinci Ders Blok ve Inline elementler
* Bazı elementler content yani içeriği kadar yer kaplarken (İnline) Bazı elementler ise olduğu yerin genişliği olarak tamamını kaplar (Blok).
* İnline ve Blok olan elementlere dair bilgiler öğrendim.
* strong ve em yani kalın ve italik yapma elementlerini öğrendim
* br ve hr elementlerini öğrendim br bir alt satıra geçiyor hr ise bir alt satıra geçip araya çizgi çekiyor.

---

## Dokuzuncu Ders Class ve Id
* Class birden fazla yerde kullanılabilen ve kullanıldığı yerlerde aynı özelliği veren bir sınıftır.
* Id kimlik numarası gibi özel olarak kullandığımız bir sınıftır, bir elemente id tanımladığımızda sadece o elemente özel olmalıdır.

---

## ONUNCU DERS HTML İskeleti
* Bir HTML yapısı 3 ana başlıktan oluşur, ilk olarak html etiketi herşeyi içine alır daha sonra head ve body etiketleri gelir head üçüncü kullanıcının görmediği kısmı belirtir, body kısmı ise üçüncü kullanıcının göreceği herşeyin bütünüdür.
* Genel olarak bilgiler verildi.

---

## ON BIRINCI DERS Semantic etiketler ve kulllanımları
* Semantik, anlam veya anlamlandırma anlamı ifadesi taşımaktadır. O halde semantik elementler herhangi bir anlamı olan etiketler ifadesi taşımaktadır. Semantik olarak anlamlandırılmış bir element hem tarayıcıya hem geliştiriciye ne anlama geldiğini açık bir şekilde belirtir. ***div ve span*** gibi elementler ***semantik olmayan*** elementlerdir ve mevcut içeriğin hakkında bilgi vermezler. ***form, table ve img gibi elementler semantik elementlerdir*** ve içeriği açıkça belirtirler.
<br>
* ***header Elementi***
header elementi bir doküman veya bir <'section'> için bir başlık olduğunu belirtir. İçinde barındırdığı içeriği kapsayıcı olmalıdır. Bir dokümanda birden fazla kullanılabilir.
<br>
* ***nav Elementi***
nav elementi navigasyon bağlantıları büyük sayfalar için ortaya çıkarılmıştır. Fakat, sayfadaki tüm linkler bu element içinde olmak zorunda değildir.
<br>
* ***seciton Elementi***
section elementi bir dokuman icinde olan sadece bir kismi belirtir.
<br>
* ***figure Elementi***
İçeriğinde resim, gösterim, diyagram, kod listeleri vs. gibi nesnelerin olduğunu belirtir. Ana akış ile ilgili olsa da, konumu ana akıştan tamamen bağımsızdır. Çıkarılırsa dokümanın akışını engellemez.
<br>
* ***figcaption Elementi***
<'figcaption'> etiketi, <'figure'> elementinin belirttiği resme başlık koymaya yarar.
<br>
* ***aside Elementi***
<'aside'> elementi içerdiğinden farklı olarak daha başka bazı içerikleri tanımlar. İçeriği, üst içerik hakkında olmalıdır.
<br>
* ***article Elementi***
<'article'> elementi bir makale elementidir. Bir makale web sayfasının geri kalanından bağımsız olarak dağıtılabilmelidir.
Genelde bu elementin kullanabildiği yerler forum mesajları, blog gönderileri, haber metinleri, yorumlar gibi makale içeren metinlerdir.
<br>
* ***footer Elementi***
<'footer'> elementi bir doküman ya da kısım için alt bilgilerini belirtir. Bir <'footer'> genelde dokümanın yazarını, telif haklarını, kullanım gizliği, iletisim vs. gibi bilgileri içerir ve bir dokümanda bir kereden fazla kullanılabilir.

---

## ON IKINCI DERS Semantic olmayan etiketlere dair bilgilendirme yapildi.

---