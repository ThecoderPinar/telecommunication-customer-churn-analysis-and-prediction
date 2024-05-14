# 🚀 Telecom Customer Churn Prediction Project

Bu proje, telekomünikasyon müşterilerinin ayrılma durumlarını tahmin etmek ve müşteri kaybını azaltmaya yönelik stratejiler geliştirmek amacıyla gerçekleştirilmiştir.

## 🎯 Amaç ve Hedef

Projemizin temel hedefleri şunlardır:

1. Müşteri kaybını anlamak ve etkileyen faktörleri belirlemek.
2. Doğru ve güvenilir bir model oluşturarak müşteri churnünü tahmin etmek.
3. Müşteri kaybını azaltmaya yönelik stratejiler geliştirmek.

## 📋 Veri Seti Tanımı

Veri seti, telekomünikasyon müşterileriyle ilgili çeşitli öznitelikleri içerir. Toplamda 7043 satır ve 21 sütun içermektedir.

## 📊 Veri Keşfi ve Ön İşleme

1. **Veri Seti İncelemesi**: Yapısal analiz gerçekleştirildi.
2. **Eksik Veri Kontrolü**: Eksik veriler işlendi.
3. **Veri Türleri ve Dağılımları**: Veri tipleri incelendi ve dağılımlar görselleştirildi.
4. **Aykırı Değerlerin İncelenmesi**: Aykırı değerler tespit edildi ve işlendi.
5. **Özellik Mühendisliği**: Yeni özellikler türetildi.

## 📈 Veri Analizi ve Keşif (EDA)

1. **Değişkenler Arası İlişkiler**: Görselleştirmelerle ilişkiler analiz edildi.
2. **Churn Dağılımı**: Müşteri kaybının dağılımı incelendi.
3. **Demografik Analiz**: Cinsiyet, yaş gibi faktörlerle ilişkiler araştırıldı.
4. **Hizmet Kullanımı Analizi**: Hizmet kullanımı ile churn arasındaki ilişki incelendi.
5. **Müşteri Memnuniyeti ve Sadakati**: Müşteri memnuniyeti ile churn arasındaki ilişki değerlendirildi.

## 📈 Sonuçlar ve Tahminler

### 📊 Model Performansı

- En iyi model %92.42 doğruluk ve 0.2144 kayıp değeri ile elde edildi.
- Tenure, InternetService, OnlineSecurity gibi özellikler tahminlerde en etkili faktörler olarak belirlendi.

### 📉 Müşteri Kaybı Analizi

- Demografik faktörlerin (yaş, partner, bağımlılık), hizmet kullanımı ve müşteri memnuniyetinin churn üzerinde etkili olduğu görüldü.

### 💡 Stratejiler ve Öneriler

1. Müşteri deneyimini iyileştirme.
2. Sadakat programları ve özel teklifler sunma.
3. Müşteri geri kazanma stratejileri geliştirme.

Bu stratejilerin uygulanması, müşteri churnünü azaltabilir ve şirketin başarısını artırabilir.

## 📄 Dosya Yapısı

- **Random_Forest_Classifier_Model.pkl**: Random Forest algoritması kullanılarak eğitilen bu model, müşterilerin ayrılma olasılığını tahmin etmek için müşteri verilerini kullanır.
- **neural_network_models.json**: Derin öğrenme modelinin yapısal bilgileri.
- **neural_network_models.h5**: Derin öğrenme modelinin ağırlıkları.

## 🚀 Başlarken

Proje dosyalarını çalıştırmak ve modelleri tekrar eğitmek için aşağıdaki adımları izleyebilirsiniz:

1. Repoyu klonlayın: `git clone https://github.com/ThecoderPinar/telecommunication-customer-churn-analysis-and-prediction.git`
2. Gerekli kütüphaneleri yükleyin: `pip install -r requirements.txt`
3. Jupyter Notebook dosyasını çalıştırın: `jupyter notebook`

## 📝 Lisans

Bu proje, MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.
