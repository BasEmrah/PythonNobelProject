# Nobel Ödülleri Veri Analizi Projesi

Bu proje, Nobel Ödülleri veri seti kullanılarak çeşitli analizler ve görselleştirmeler içermektedir. Projenin amacı, Nobel Ödülleri ile ilgili bazı önemli soruları cevaplamak ve bu süreçte elde edilen içgörüleri paylaşmaktır.

## İçindekiler
1. [Veri Seti Hakkında](#veri-seti-hakkında)
2. [Sütun Adlarının Açıklamaları](#sütun-adlarının-açıklamaları)
3. [Analizler](#analizler)
    1. [Nobel Ödüllerini En Çok Kazanan İlk On Ülke](#nobel-ödüllerini-en-çok-kazanan-ilk-on-ülke)
    2. [Nobel Ödüllerini Kazanan İlk Kadınlar](#nobel-ödüllerini-kazanan-ilk-kadınlar)
    3. [Nobel Ödüllerini Kazanan İlk Erkekler](#nobel-ödüllerini-kazanan-ilk-erkekler)
    4. [Nobel Ödülünü En Çok Kazanan Ülkenin Hakimiyeti](#nobel-ödülünü-en-çok-kazanan-ülkenin-hakimiyeti)
    5. [Nobel Ödülü Kazananların Cinsiyet, Yaş, Kategori ve Yıllara Göre Görselleştirilmesi](#nobel-ödülü-kazananların-cinsiyet-yaş-kategori-ve-yıllara-göre-görselleştirilmesi)
    6. [1938-1945 Yılları Arasında Nobel Ödülü Kazananların Kategorileri ve Ülkeleri](#1938-1945-yılları-arasında-nobel-ödülü-kazananların-kategorileri-ve-ülkeleri)
    7. [1947-1991 Yılları Arasında Nobel Ödülü Kazananların Kategorileri ve Ülkeleri](#1947-1991-yılları-arasında-nobel-ödülü-kazananların-kategorileri-ve-ülkeleri)
    8. [2000 Sonrası Nobel Ödülü Kazananların Ülkeleri ve Yaşları](#2000-sonrası-nobel-ödülü-kazananların-ülkeleri-ve-yaşları)
4. [Dosyalar](#dosyalar)
5. [Sonuçlar ve İçgörüler](#sonuçlar-ve-içgörüler)

## Veri Seti Hakkında
Bu proje için kullanılan veri seti Nobel Ödülleri verilerini içermektedir.

## Sütun Adlarının Açıklamaları
- `year`: Nobel Ödülü'nün verildiği yıl.
- `category`: Nobel Ödülü'nün kategorisi (Fizik, Kimya, Barış, Edebiyat, Tıp vb.).
- `prize`: Ödülün adı.
- `motivation`: Ödül gerekçesi.
- `prize_share`: Ödülün payı (Ödül birden fazla kişiye verilmişse).
- `laureate_id`: Ödül sahibinin kimlik numarası.
- `laureate_type`: Ödül sahibinin tipi (Kişi veya Organizasyon).
- `full_name`: Ödül sahibinin tam adı.
- `birth_date`: Ödül sahibinin doğum tarihi.
- `birth_city`: Ödül sahibinin doğduğu şehir.
- `birth_country`: Ödül sahibinin doğduğu ülke.
- `sex`: Ödül sahibinin cinsiyeti.
- `organization_name`: Ödül sahibinin çalıştığı organizasyonun adı.
- `organization_city`: Ödül sahibinin çalıştığı organizasyonun bulunduğu şehir.
- `organization_country`: Ödül sahibinin çalıştığı organizasyonun bulunduğu ülke.
- `death_date`: Ödül sahibinin ölüm tarihi (varsa).
- `death_city`: Ödül sahibinin öldüğü şehir (varsa).
- `death_country`: Ödül sahibinin öldüğü ülke (varsa).

## Analizler

### Nobel Ödüllerini En Çok Kazanan İlk On Ülke
Nobel Ödüllerini en çok kazanan ilk on ülke analiz edilmiştir.

### Nobel Ödüllerini Kazanan İlk Kadınlar
Nobel Ödüllerini kazanan ilk kadınlar listelenmiştir.

### Nobel Ödüllerini Kazanan İlk Erkekler
Nobel Ödüllerini kazanan ilk erkekler listelenmiştir.

### Nobel Ödülünü En Çok Kazanan Ülkenin Hakimiyeti
En çok Nobel Ödülü kazanan ülkenin hangi yıldan itibaren hakimiyet sağladığı görselleştirilmiş ve bu hakimiyette rol oynayan faktörler analiz edilmiştir.

### Nobel Ödülü Kazananların Cinsiyet, Yaş, Kategori ve Yıllara Göre Görselleştirilmesi
Nobel Ödülü kazananların cinsiyetlerini, yaşlarını, ödül kategorisi ve yılları kullanarak görselleştirilmiştir. Her bir ödül kategorisi için ayrı grafikler oluşturulmuştur.

### 1938-1945 Yılları Arasında Nobel Ödülü Kazananların Kategorileri ve Ülkeleri
1938-1945 yılları arasında Nobel Ödülü kazananların kategorileri ve ülkeleri görselleştirilmiş ve analiz edilmiştir.

### 1947-1991 Yılları Arasında Nobel Ödülü Kazananların Kategorileri ve Ülkeleri
1947-1991 yılları arasında Nobel Ödülü kazananların kategorileri ve ülkeleri görselleştirilmiştir. Her kategori için ayrı grafikler oluşturulmuştur.

### 2000 Sonrası Nobel Ödülü Kazananların Ülkeleri ve Yaşları
Kimya, Edebiyat, Barış, Fizik ve Tıp kategorilerindeki 2000 sonrası Nobel Ödülü kazananların ülkeleri ve yaşları görselleştirilmiştir. Her bir kategori için ayrı görselleştirmeler yapılmıştır.

## Dosyalar
- `EmrahBasPythonProje.ipynb`: Projenin Jupyter Notebook dosyası.
- `Emrah_Bas_Python_Proje_6.png`: 6 numaralı proje sorusunun analizlerini ve içgörülerini içeren görsel.
- `README.md`: Projenin açıklamalarını içeren bu dosya.

## Sonuçlar ve İçgörüler
Projenin her bir aşamasında elde edilen sonuçlar ve içgörüler detaylı olarak incelenmiştir. Özellikle Nobel Ödüllerini kazanan ilk kadınlar ve erkekler ile ilgili önemli bulgular paylaşılmıştır. Ayrıca, en çok Nobel Ödülü kazanan ülkenin hangi yıldan itibaren hakimiyet sağladığı ve bu hakimiyette rol oynayan faktörler derinlemesine analiz edilmiştir. Görselleştirmeler, veriyi anlamamıza yardımcı olmuş ve çeşitli kategorilerdeki Nobel Ödülü kazananların demografik özellikleri hakkında değerli bilgiler sunmuştur.

Bu README dosyası, proje hakkında genel bir bilgi ve içerik sunmaktadır. Proje dosyalarının detaylı açıklamaları ve analiz sonuçları için `EmrahBasPythonProje.ipynb` dosyasına bakabilirsiniz.
