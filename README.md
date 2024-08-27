# AkakceTestCalismasi

Akakçe Test Çalışması için iletilen pdf'te 2. madde olan "Test Otomasyonu UI" ve 5. madde olan "API Testi için Rest Assured Test otomasyonu" için çalışmalar repository içinde Akakce.zip dokümanı içinde bulunmaktadır.

Test Otomasyonu UI kapsamında, "AkakceUITest" çalışması yapılmıştır. Elementlerin tanımlanasını xpath aracılığıyla yapmak istememe karşın çalıştırdığım her farklı gün ürüne ait xpath değiştiğinden mecburen cssSelector kullandım.
Her bir test adımına yorum ekledim.


API Testi için Rest Assured Test otomasyonu kapsamında yapılan "APIOtomasyon" çalışmasında, olabildiğince tüm adımlarda yaptıklarımı yorum şeklinde yazmaya çalıştım. Allure reports ve benzeri raporlama yöntemlerini kullanmak istesem de sürekli bir hata ile karşılaştım. Çalışmayı bitirmek için zamanım azaldığından yalnızca console ekranlarına test sonuçlarını yazdırdım. Benden istendiği gibi 5 adet test yazdım. Bu testlere aşağıda açıklamalarıyla birlikte yer verilmiştir.

• statuKoduTesti -> StatusCode 200 dönmesi durumunun kontrolü için yazılmıştıur. URL'den statusCode 200 döndüğünde başarılı olacaktır.

• jsonYapisiDogrulama -> statusCode 200 döndüğünde, JSON yapısında userId, id , title, body alanlarından bulunduğunun kontrolü ile test başarılı olacaktır.

• belirliBirDegerinDogrulanmasi -> id nin 1 olduğu durumda title için örnek body de verilen değerin eşleşmesi durumunda test başarılı olacaktır.

• listeUzunlukKontrolu -> verilen liste için liste uzunluğunun en az 10 olması durumunda test başarılı olacaktır.

• dinamikVeriKontrolleri -> bu test için ise ide değerinin boş olmaması ve 0'dan büyük sayı olması durumunda test başarılı olacaktır.

-TEST SONUÇLARI-

UI ve API otomasyonları için yazılan testler başarılı olup, herhangi bir bulgu ile karşılaşılmamıştır.
