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

## Dördüncü Ders
* Sıralı ve Sırasız listeler var genelde sırasız listeler kullanılıyor.
* Sıralı listeler için ol elementi kullanılıyor.
* Sırasız listeler için ul elementi kullanılıyor.
* sıralı veya sırasız listeler içerisinde sıralı veya sırasız listeler kullanabiliriz, liste içinde liste gibi.
* Sıralı listelerde type etiketini kullanarak sıralama seçeneğini değiştirebiliriz rakamdan roma alfabesine çevirmek gibi mesela.
* Sırasız listelerin başındaki simgeleri style etiketinin içinde list-style-type none diyerek yok edebiliriz.
* Sırasız listelerin başındaki simgeleri aynı zamanda style etiketini kullanarak list-style-type disc, square ya da circle değiştirebiliriz.

---

## Beşinci Ders