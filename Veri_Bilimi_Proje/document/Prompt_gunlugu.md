1.Jupyterlab'da veri setini okutmaya çalışırken FileNotFoundError: \[Errno 2] No such file or directory hatası alıyorum. Dosya aynı klasörde görünmesine rağmen bu hatayı veriyor, nasıl düzeltebilirim?



2\. İBB Açık Veri Portalı üzerinden aldığım Raylı Sistemler İstasyon Bazlı Yolcu ve Yolculuk Sayıları isimli veri seti üzerinde çalışıyorum. Veri setindeki sütun isimleri şunlar: transaction\_year    transaction\_month    transaction\_day    line    station\_name    station\_number    town    longitude    latitude    passage\_cnt    passanger\_cnt

Öncelikle pandas kullanarak bu veriyi yükleyen, eksik değerleri (NaN) tespit eden ve veri tiplerini dönüştüren bir Python kodu yaz.



3.Veri setimdeki eksik değerleri silmek için df.dropna() komutunu kullandım Kod hatasız çalıştı. Ama daha sonra df.head() veya df.isnull().sum() ile kontrol ettiğimde eksik (NaN) değerlerin hala yerinde durduğunu görüyorum. Silme işlemi neden kalıcı olmadı ve bunu nasıl çözerim?



4.Bu kodun çıktısında veriler neden sütun halinde görünüyor, bunu nasıl düzeltebilirim?



5.Ayın hangi günlerinde yolcu sayısı en yüksektir? Veri setimde passenger\_cnt ve transaction\_day sütunları var. `seaborn` ve `matplotlib` kullanarak x ekseninde günlerin, y ekseninde ortalama yolcu sayısının olduğu şık bir çizgi grafik oluştur. Başlık ve eksen isimleri türkçe ve okunaklı olsun.



6.En çok kullanılan ilk 10 ulaşım hattı hangileridir? Veri setimde line ve passenger\_cnt sütunları var. Önce veriyi `groupby` ile hat koduna göre grupla, toplam yolcu sayılarını hesapla ve büyükten küçüğe sıralayarak ilk 10 hattı seç. Ardından bu veriyi yatay bir çubuk grafik olarak görselleştir. Kod en yüksek değere sahip çubuğu farklı bir renkle vurgulasın.



7.Yolcu yoğunluğunun ilçeler ve günler arasındaki ilişkisinin bir matris olarak gösterilmesi. Veri setimde towns ve transaction\_day sütunları var.  Önce `groupby` kullanarak bir ekseni Ayın günleri, diğer ekseni İlçeler / İstasyonlar olan ve hücrelerinde toplam yolcu sayısının yer aldığı bir özet tablo oluştur. Ardından bu tabloyu bir Heatmap şeklinde görselleştir.



8.Farklı hatların yolcu sayıları arasındaki dağılımı ve varyansı karşılaştırmak ve ekstrem yoğun günlerin tespit edilmesi. Veri setimde line ve passenger\_cnt sürunları var X ekseninde Hat Adı, Y ekseninde ise Yolcu Sayısı olacak şekilde bir box plot kodu yaz.



9.Bir raylı sistem hattındaki istasyonların saatlik yolcu giriş-çıkış verilerini analiz ediyorum. Belirli bir saatteki toplam yolcu sayısını tahmin etmek istiyorum. Scikit-learn kullanarak temel bir Lineer Regresyon modeli oluştur. Verideki kategorik değişkenleri  encode eden, modeli eğiten  eksiksiz bir kod bloğu ver. Kod anlaşılır olsun ve çıktısı türkçe olsun.



10.Yazdığın lineer regresyon modeli çalıştı ama R^2 skoru çok düşük geldi. Sanırım veri setinde çok fazla aykırı değer var. Modelin tahmin gücünü artırmak için ekstrem yoğun günleri veriden temizleyen ve modeli tekrar eğiten bir kod bloğu ver.

