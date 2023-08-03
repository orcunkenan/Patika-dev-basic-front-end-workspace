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