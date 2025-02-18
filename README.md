# Hisse Senetlerinin Sektörel Benzerlik Analizi ve Sınıflandırma Modeli

## Proje Tanımı
Bu proje, hisse senetlerinin zaman serisi verilerini kullanarak sektörel benzerliklerini analiz etmeyi ve sınıflandırmayı amaçlamaktadır. Veri yoğun uygulamalar kapsamında geliştirilen bu model, yatırım stratejilerine yönelik öngörüler sunmayı hedeflemektedir.

## Kurulum
Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### Bağımlılıkları Yükleme
```bash
pip install -r requirements.txt
```

## Veri Kaynakları
Proje, aşağıdaki veri kaynaklarından veri toplamaktadır:
- **yfinance** (Yahoo Finance)
- **investpy** (Investing.com)
- **quandl** (Ekonomik ve finansal veriler)

## Veri İşleme ve Özellik Çıkarma
- **TSFRESH** kütüphanesi kullanılarak zaman serisi özellikleri çıkarılmaktadır.
- Momentum, volatilite, RSI ve MACD gibi faktör hesaplamaları yapılmaktadır.

## Model Eğitimi
- **Makine Öğrenmesi Modelleri:** Random Forest, XGBoost, CatBoost
- **Hiperparametre Optimizasyonu:** GridSearchCV ve RandomizedSearchCV
- **Değerlendirme Metriğleri:** Accuracy, F1-score, ROC-AUC

## Sonuçlar ve Değerlendirme
Model performansı, yukarıdaki metrikler ile değerlendirilmiş ve sonuçlar yatırım stratejileri için yorumlanmıştır.

## Kullanım Senaryoları
Bu model, finans sektöründe şu alanlarda kullanılabilir:
- Yatırım portföyleri oluşturma
- Sektörel analiz ve hisse sınıflandırma
- Risk değerlendirme

## Lisans
Bu proje, akademik ve araştırma amaçlı kullanım için açıktır.

---
Projeye dair geliştirme önerileriniz varsa lütfen bizimle iletişime geçin!

