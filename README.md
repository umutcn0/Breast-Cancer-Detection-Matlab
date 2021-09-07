# Amaç
Bu çalışmada 32 farklı girdi (özellik) ile 569 tane örneği makine öğrenmesi tekniği kullanarak yapay zekamıza %96 öğrenme başarısı ile öğrettik. Bu da demek oluyor ki herhangi bir uzmana ya da insana gerek kalmadan, hastaya ait girdiğimiz verilerle hücrenin iyi huylu veya kötü huylu olup olmadığını bir bilgisayar yardımıyla saptayabiliyoruz. Ve sistem bizim de verdiğimiz geri dönüşlerle kendini her seferinde geliştirmeye, hatalarını düzeltmeye, yeni şeyler öğrenmeye devam ediyor. Bu da demek oluyor ki sistemin hata yapma şansı git gide sıfıra yaklaşıyor.

## Gereklilikler
- Matlab

## Kullanılan Metod
Kaggle’dan aldığımız veritabanı ile Matlab uygulamasında Fitting App – Marquardt Algoritması kullanarak yakaladığımız en yüksek öğrenme yüzdesi olan %96 öğrenme yüzdesi ile yapay zekamızı 32 farklı girdi ve 569 örnek ile eğittik. Sisteme hastada gözüken belirtileri girdiğimizde bize sonuç olarak hücrenin iyi huylu veya kötü huylu olduğu bilgisini veriyor. Yapay zeka girilen bilgiler ve aldığımız sonuçlara verdiğimiz geri dönüşlerle kendini yenilemeye, geliştirmeye ve öğrenmeye devam ediyor.

![image](https://user-images.githubusercontent.com/54486428/132333679-f7399ef6-ea85-48aa-96a7-9f82aa58ec17.png)


## Özet ve sonuç
Göğüs kanserinde erken tanı çok önemlidir. Özellikle kadınların ölüm sebeplerinden biridir. Bu kanser türü her sekiz kadından birinde yaşamları boyunca etkili olmakta, erkeklerde ise nadiren görülmektedir. Bilim adamları, göğüs kanserinin gelişmesine yardımcı olan yaşlanma, genetik risk faktörü, aile geçmişi, çocuk sahibi olamama, obezite ve benzeri birçok etkeni bilmelerine rağmen henüz bu etkenlerin etkilerini tamamen ortadan kaldırabilecek çözümlere ulaşamamışlardır. Erken dönemde tespiti ve tümörün lokalizasyonu, ölüm oranını azaltmak için tek yoldur. Göğüs kanseri tespiti için xışını mamografisi kanser taramasında en çok kullanılan tanı aracıdır. Ancak göğüs kanseri tespiti için xışınının kullanımında önemli derecede sınırlamalar vardır. Bu yüzden hastada görülen belirtilerin tam anlamıyla düzgün bir şekilde kaydedilip yapay zekaya bilgilerin girilmesiyle hem hastaya zararlı ışın uygulamadan tespiti rahatça yapılabilir hem de herhangi bir uzmanın yorumuna gerek kalmadan yapay zeka bize sonucu kolaylıkla verir.

Bu çalışmada edinilen veri tabanı kullanılarak yapay sinir ağları ile göğüs kanserinin teşhisine yönelik bir tahmin mekanizması oluşturulmuştur. Veri tabanındaki her bir örneğe ait öznitelik değerleri oluşturulan yapay sinir ağının girişlerine verilmiş ve hata oranı belli bir seviyenin altına inene kadar geri besleme yaparak ağ eğitilmiştir. Eğitim sırasında 569 örneğin 560 tanesi kullanılmıştır. Geriye kalan 9 tanesi test aşamasında kullanılmıştır. Ağın öğrenme başarısı %96’dır.

### Girdiler
- id
- teshis
- yarıcap_ort
- doku_ort
- cevre_ort
- alan_ort
- purusuzluk_ort
- kompaktlık_ort
- icbukeylık_ort
- ıcbukey_puan_ort
- simetri_ort
- fraktal_boyut
- fraktal_boyut_ort
- yarıcap_se
- doku_se
- cevre_se
- alan_se
- purusuzluk_se
- kompaktlık_se
- ıcbukeylik_se
- ıcbukey_noktalar_se
- simetri_se
- fraktal_boyut_se
- yarıcap_worst
- doku_worst
- cevre_worst
- alan_worst
- purusuzluk_worst
- kompaktlık_worst
- icbukeylık_worst
- icbukey_puan_worst
- simetri_worst
- fraktal_boyut_worst

### Çıktılar
- M: Kötü Huylu:1
- B: İyi Huylu:0
