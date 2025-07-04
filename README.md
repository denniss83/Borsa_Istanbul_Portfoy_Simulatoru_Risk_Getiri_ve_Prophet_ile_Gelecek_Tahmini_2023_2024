# 📈 Borsa İstanbul Portföy Simülatörü: Risk, Getiri ve Prophet ile Gelecek Tahmini (2023–2024)

>## **⚠️ Uyarı**
>
>**❗️Bu çalışma python ile veri analizi kapsamında yalnızca eğitim ve öğrenim amaçlı hazırlanmıştır.**
**Hiçbir şekilde yatırım tavsiyesi içermez.**  
**Geleceğe dönük tahminler istatistiksel modellerle yapılmıştır ve garanti niteliği taşımaz.**

Bu projede, Borsa İstanbul’da (BIST) işlem gören şirketlerin 2023–2024 dönemine ait hisse fiyat verileri kullanılarak detaylı bir portföy analizi gerçekleştirilmiştir.

Amaç, farklı portföy stratejileri ile getirileri, riskleri ve ileriye dönük tahminleri karşılaştırmak ve yatırım karar süreçlerine veri analitiği perspektifi kazandırmaktır.

---

## 🔧 Kullanılan Veri ve Teknolojiler

- **Veri Kaynağı:** `yfinance` üzerinden BIST şirketlerinin günlük kapanış fiyatları  
- **Kapsam:** 2023-01-01 – 2024-12-31 dönemi  
- **Araçlar:** Python, Pandas, Matplotlib, Seaborn, Plotly, Facebook Prophet

---

## 📊 Yapılan Analizler

### 1. Genel Hisse Analizi
- Ortalama kapanış fiyatı, günlük getiri, volatilite
- En yüksek/negatif yıllık getirili hisseler
- Yüzde değişim (2023–2024 arası)

### 2. Korelasyon Matrisi
- Hisseler arası getirilerin korelasyon haritası (heatmap)
- Çeşitlendirme için uygun korelasyon analizi

### 3. Getiri – Risk Dağılımı
- Sharpe oranı (risksiz getiri %30 kabulüyle)
- Volatilite vs Yıllık Getiri grafik analizi

### 4. 4 Farklı Portföyün Performans Karşılaştırması
- Her biri 4 hisseden oluşan toplam 4 portföy
- Eşit ağırlıklı kümülatif getiriler (2x2 subplot grafiklerle)

### 5. Portföy Performans Özeti Tablosu
- Her portföy için yıllık getiri, volatilite ve Sharpe oranı

### 6. Prophet ile 180 Günlük Gelecek Tahmini
- Tüm portföyler için Prophet algoritmasıyla ileriye dönük kümülatif getiri tahmini
- Güven aralığıyla birlikte sunum


---

## ✍️ Hazırlayan

**Deniz Atabey**  
📍 İzmir, Türkiye   
📧 Email: [d-atabey@hotmail.com]

