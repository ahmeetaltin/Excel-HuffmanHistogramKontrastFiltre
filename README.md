# goruntuIsleme-Excell
4. Sınıf Görüntü İşleme "Huffman-Histogram-Kontrast-Filtre-UzunlukHesaplayıcı" Çözücü Excell

-Huffman-
Verilen a1,a2,a3,a4,a5,a6 olasılıklarını tablodaki sarı ile işaretlenmiş hücrelere yazıp "1 butonu"na bastığımızda gerekli hesaplamaları yapıyor.
Ardından soruda verilen yüksek bit 0 yada 1 şeklindeki bilgiye göre sağ taraftaki sarı hücreleri üsttekine 0 alttakine 1 şeklinde doldurduktan sonra "3 butonu"na basıp programımızın hesaplamasını bitiriyoruz.
Sonuç olarak kırmızı hücreleri baz alabiliriz.

-Açma Kapama-
Buradaki şekiller sadece konuyu anlatmaktadır herhangi bir çözüm işlemi yapmamaktadır.

-Histogram-
Verilen piksel sayısını 64 64 şeklinde B3  ve C3 hücrelerine yazıyoruz, ardından Bit sayısını (4 tane n varsa 2, 8 tane n varsa 3,16 tane n varsa 4) yazıp hemen sağında bulunan beyaz dağıt düğmesine basıyoruz. Daha sonrasında soruda verilen değerlere göre nk sütununun sarı hücrelerini dolduruyoruz ve sıfır olan yerleri değiştirmiyoruz. Kontrol etmek için aşşağıdaki kırmızı hücreleri ve alt tarafındaki uyarıları kontrol ediyoruz.Eğer herşey doğruysa sonrasında 3. kısım hesaplamasını yapmak için sağ üstte bulunan "= yani hesapla butonu"na basıp makromuzu çalıştırıyoruz. Sonuç olarak 3. kısımdan istenilen sütunu yazabiliriz.

-Kontrast Germe ve Uzunluk Hesaplama-
Soruda verilen r1,s1,r2,s2,r ve top değerini(en üstteki sayı 255 olarak alınır) tabloya girdikten sonra r değerine karşılık gelen s değerini tablomuz bize hesaplıyor.

-Uzaklık Hesaplama-
x,y,s,t değerlerini yani 2 farklı noktanın x y koordinatlarını girdikten sonra bu iki noktanın arasındaki 3 farklı uzaklık tipini hesaplıyor.

-Filtreler (Laplace4komşu,Laplace8komşu,Ortalama,Medyan,Mean,Sobel,pozitif4lü,negatif4lü,pozitif8li,negatif8li)-
Bize verilen 3x3lük tabloyu sarı hücrelere gelecek şekilde doldurduktan sonra sonuçlarımızı kırmızı hücrelerden alabiliriz.
