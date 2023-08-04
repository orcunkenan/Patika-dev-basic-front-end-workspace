# CSS Ders Notlarım

---

## CSS giriş

* Bu ders bir girizgah yapıldı.

---

## Birinci Ders Inline CSS

* Bir elementin içine style etiketi açarak inline css yani elementin içinde css komutları yazabiliriz.
* ```<h1 style="color:red"> Bu bir inline kod örneği </h1>```

---

## İkinci Ders İnline (Etikete Özel), İnternal (Aynı Dosyada), External (CSS Dosyasında) CSS Kullanımı

* CSS, web sitenizin ekranda nasıl görüneceğini belirleyen belirli stil kurallarına sahip dosyalardır. CSS kuralları, web sitenizin HTML dosyalarına çeşitli şekillerde ve yerlerde uygulanabilir. External yani harici bir stil sayfası, Internal yani dahili bir stil sayfası veya Inline yani satır içi stil kullanabilirsiniz. Her yöntemin belirli kullanımlara uygun avantajları vardır.

<br>

### External

* ***External*** stil sayfası, bir web sayfasından bağlanan bağımsız bir .css dosyasıdır. External stil sayfasının avantajı, bir kez oluşturulabilmesi ve birden çok web sayfasına uygulanabilmesidir. Site tasarımınızda geniş çaplı değişiklikler yapmanız gerekirse eğer, stil sayfasında tek bir değişiklik yapabilirsiniz ve bu değişiklik tüm bağlantılı sayfalara uygulanarak zamandan ve emekten tasarruf sağlar.

![Ikinci-ders-pic-1](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/css/inlineetikete-ozel%2C-internalayni-dosyada-ve-externalcss-dosyasinda-css-kullanimi/figures/css-yapisi.jpg)

<br>

### Internal

* ***Internal*** stil sayfası, HTML dosyasının <'head'> bölümünde sayfa için CSS kural kodlarını barındırır. Kural kodları yalnızca o sayfa için geçerlidir, ancak sayfa kodunda birden çok öğeye stil uygulamak için kullanılabilecek class ve id’leri yapılandırabilirsiniz. Yine, CSS kodunda yapılacak tek bir değişiklik, sayfadaki tüm etiketlenmiş öğelere uygulanacaktır.

![Ikinci-ders-pic-2](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/css/inlineetikete-ozel%2C-internalayni-dosyada-ve-externalcss-dosyasinda-css-kullanimi/figures/internal-css.png)

<br>

### Inline

* ***Inline***  stili, belirli bir sayfa öğesine stil vermek için, belirli bir HTML etiketi içinde kullanılır. Hızlı ve kalıcı değişiklikler için kullanışlıdırlar, ancak bir tasarım değişikliği yapmaya karar vermeniz durumunda, oluşturduğunuz her Inline stilin ayrı ayrı düzenlenmesi gerektiğinden, External ve Internal stil sayfalarından daha kullanışlı değildir ve diğerlerine göre çok fazla tercih edilmez.

![Ikinci-ders-pic-3](https://www.myprograming.com/wp-content/uploads/2021/03/inline-CSS.png)

<br>

## External CSS Kullanımı

* Yukarıda bahsettiğimiz gibi External CSS, normal HTML dosyanızdan bağımsız bir dosyadır ve .css uzantılıdır. CSS dosyanızı oluşturduktan sonra mutlaka HTML dosyanıza linklemeniz gerekir. Yoksa CSS dosyanız işlevsiz kalacak ve HTML sayfanızda yaptığınız değişiklikleri göremeyeceksiniz.

<br>

## Internal CSS Kullanımı

* Internal CSS, stil kodlarının direk HTML dosyasının içinde ```<head>``` bölümünde kullanıldığı bir yöntemdir. ```<head>``` bölümünün içinde bir ```<style>``` etiketi açtıktan sonra içine gerekli CSS kodlarını yazabilirsiniz.

<br>

## Inline CSS Kullanımı

* Inline yani satır içi stiller, doğrudan HTML kodunuzdaki herhangi bir öğeye uygulanır. Stil niteliği ve ardından normal CSS özellikleri bir HTML etiketi içinde belirtilir.

---

## Üçüncü Ders Genel Font Özellikleri

* **Serif** yazı tiplerinin her harfin kenarlarında küçük bir kontur vardır. Bir formalite ve zarafet duygusu yaratırlar.
* **Sans-serif** yazı tiplerinin temiz satırları vardır (küçük konturlar eklenmez). Modern ve minimalist bir görünüm yaratırlar.
* **Monospace** yazı tipleri burada tüm harfler aynı sabit genişliğe sahiptir. Mekanik bir görünüm yaratırlar.
* **Cursive** yazı insan el yazısı taklidi gibidir.
* **Fantasy** yazı tipleri dekoratif, eğlenceli yazı tipleridir.

<br>

* Tüm farklı yazı tipi adları, genel yazı tipi ailelerinden birine aittir.

<br>

* Not: Bilgisayar ekranlarında, sans-serif yazı tiplerinin serif yazı tiplerinden daha kolay okunabileceği kabul edilir.
<br>

### font-family

* bir metnin yazı tipini belirtmek için özelliği kullanırız.

### font-style

* çoğunlukla italik metnini belirtmek için kullanılır.
* **normal** Metin normal sekilde gosterilir
* **italic** Metin italik olarak gosterilir
* **oblique** Metin egimli gosterilir ama cok desteklenmiyor

### font-size

* font-size metnin boyutunu ayarlar.
* Metin boyutunu yönetebilmek web tasarımında önemlidir. Bununla birlikte, paragrafların başlık gibi veya başlıkların paragraflara benzemesi için yazı tipi boyutunu ayarlamalısınız. Bunun içinde font-size kullanılır.

* Not: Bir yazı tipi boyutu belirtmezseniz, paragraflar gibi normal metin için varsayılan boyut 16 pikseldir (16px = 1em).

#### Em ile Yazı Tipi Boyutunu Ayarla

* Kullanıcıların metni yeniden boyutlandırmasına izin vermek için (tarayıcı menüsünde), birçok geliştirici piksel yerine em kullanır.

* 1em, mevcut yazı tipi boyutuna eşittir. Tarayıcılarda varsayılan metin boyutu 16 pikseldir. Yani, 1em'in varsayılan boyutu 16 pikseldir.

---

## Dorduncu Ders Class ve Id Kullanimi

* Web sayfamızı oluştururken HTML elementlerimize bazı stil özellikleri eklemek isteriz. Bazı yazıların renkli, bazı resimlerin küçük veya bazı butonların farklı şekilde olması gerekebilir ve biz de bunun için CSS kullanırız.

### Class Kullanimi

* Class seçicisi, HTML üzerinde aynı class’a sahip elemana ulaşmamızı sağlar.
* Class seçicisi CSS’de . ile belirtilir.
* Bir class’ı birden fazla HTML elementi için kullanabiliriz.
* Eğer bir HTML elementinin birden fazla class özelliğine sahip olmasını istiyorsak aynı anda iki farklı class’ı kullanabiliriz. Bunun için sadece iki class arasına boşluk bırakmak yeterli olacaktır.
* Bir HTML elementi kendini kapsayan elementin (parent elementi) stil özelliklerine sahip olur.

### Id Kullanimi

* ID seçicisi, HTML üzerinde aynı id’ye sahip elemana ulaşmamızı sağlar.
* ID seçicisi CSS’de # ile belirtilir.
* ID seçicisinin kullanım amacı olarak class seçicisinden bir farkı yok diyebiliriz. İkisi de belirli HTML elementlerine CSS özellikleri eklemeye yöneliktir. Fakat id seçicisinin class seçicisinden bazı farkları vardır.
* Bir id’yi sadece bir HTML elementi üzerinde kullanabiliriz.
* Bir html elementinin sadece bir tane id’si olabilir.

---

