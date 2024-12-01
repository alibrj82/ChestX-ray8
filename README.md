ChestX-ray8 Görüntü İşleme Çalışması
Bu projede, ChestX-ray8 veri setindeki görüntüler üzerinde çeşitli görüntü işleme teknikleri uygulanarak, görsellerin kalitesini artırma, gürültü azaltma ve özelliklerini dönüştürme adımları gerçekleştirilmiştir. Amaç, görüntülerin analiz edilebilirliğini ve modelleme süreçlerinde kullanılabilirliğini artırmaktır. Çalışma şu başlıklar altında yürütülmüştür:

Görüntü Geliştirme: Görsellerde kontrast artırma, gamma düzeltmesi ve histogram eşitlemesi teknikleriyle görüntülerin dinamik aralığı ve detayları iyileştirilmiştir.

Gürültü Azaltma: Median Blur ve Gaussian Blur yöntemleri kullanılarak görüntülerdeki rastgele gürültüler temizlenmiştir. Median Blur keskin kenarların korunmasında, Gaussian Blur ise yumuşak geçişlerde etkili olmuştur.

Dönüşüm İşlemleri: Rastgele döndürme ve yatay çevirme gibi veri artırma yöntemleri, modelin farklı perspektifleri öğrenmesi için görüntülere uygulanmıştır.

Frekans Alanı Filtreleme: Fourier dönüşümü kullanılarak belirli frekansların filtrelenmesi ile görüntülerde önemli alanların öne çıkarılması sağlanmıştır.

Keskinleştirme ve Enterpolasyon: Unsharp mask yöntemi ile görüntülerdeki detaylar keskinleştirilmiş, bicubic enterpolasyon ile görüntü boyutu büyütülmüştür.

Görselleştirme: Her bir adımda elde edilen sonuçlar, orijinal ve işlenmiş görüntülerle birlikte görselleştirilerek sürecin etkileri net bir şekilde gözlemlenmiştir.
