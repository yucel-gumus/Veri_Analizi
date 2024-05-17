# Veri Analizi Projesi

Bu proje, [Kaggle Dünya Mutluluk Raporu Verisi](https://www.kaggle.com/datasets/unsdsn/world-happiness) kullanılarak dünya genelindeki mutluluğun ana etkenlerini analiz etmeyi amaçlamaktadır. Amacımız, insanların mutluluğunu belirleyen faktörleri keşfetmek ve ülkelerin vatandaşlarına nasıl daha mutlu bir yaşam sunabileceğini anlamaktır.

## Proje Adımları

### 1. Veri Yükleme ve Keşifsel Analiz

İlk olarak, CSV dosyamızı Kaggle'dan indirip veri setimizi yükledik. Ardından, verinin genel yapısını anlamak için keşifsel veri analizi (EDA) yaptık.

- Verinin başlıklarını ve ilk birkaç satırını görüntüledik.
- Verinin boyutunu ve temel istatistiksel özetini inceledik.
- Eksik ve boş verileri tespit ettik ve düzelttik.

### 2. Korelasyon Analizi

Veri temizlendikten sonra, değişkenler arasındaki ilişkileri anlamak için korelasyon analizi gerçekleştirdik. Bu analiz, mutluluğu etkileyen ana faktörleri belirlememize yardımcı oldu.

### 3. Görselleştirme

Veriyi daha iyi anlamak ve bulgularımızı daha anlaşılır kılmak için çeşitli görselleştirme teknikleri kullandık:

- Dağılım grafikleri (scatter plots)
- Kutu grafikleri (box plots)
- Isı haritaları (heatmaps)

### 4. Özellik Seçimi ve Mühendisliği

Mutluluğun asıl etkenlerini belirlemek için Recursive Feature Elimination (RFE) yöntemini kullanarak özellik seçimi yaptık. Ardından, özellik mühendisliği (feature engineering) ile verinin performansını artırmayı hedefledik.

### 5. Gelir ve Mutluluk İlişkisi

Bu işlemlerden sonra, kişisel gelir miktarının mutluluğa etkisini tekrar gözlemledik ve gelir ile mutluluk arasındaki ilişkiyi daha derinlemesine inceledik.


## Sonuçlar ve Bulgular

Bu proje kapsamında, kişisel gelir miktarının mutluluğa önemli bir etkisi olduğunu gözlemledik. Ancak, mutluluğun tek faktörü kişisel gelir değildir. Sağlık, sosyal destek, özgürlük gibi diğer faktörler de mutluluk üzerinde önemli bir etkiye sahiptir. Bu bulgular, ülkelerin politikalarını ve vatandaşlarına sundukları hizmetleri geliştirirken dikkate alabilecekleri önemli bilgiler sunmaktadır.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakın.
