# 🚗 AutoTrend Analytics: Semantik Arama ve Kelime Yerleştirmeleri

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Gensim](https://img.shields.io/badge/Gensim-red?style=for-the-badge)

---

## 📌 Proje Özeti
[cite_start]Bu çalışma, **Auto Trend Analytics** firması için hazırlanan bir metin analiz sistemidir[cite: 34]. [cite_start]Manuel anahtar kelime aramalarının yetersizliğini çözmek amacıyla geliştirilmiştir [cite: 38-43].

### 🎯 Çözülen Problemler
* [cite_start]**Sınırlı Semantik Bakış:** Birbirine yakın kelimelerin (örneğin: ekonomik, pratik) ilişkisiz görünmesi sorunu çözüldü [cite: 39-40].
* [cite_start]**Görselleştirme Eksikliği:** Statik tablolar yerine etkileşimli kelime haritaları oluşturuldu[cite: 42].

---

## 🛠️ Teknik Altyapı
Proje kapsamında aşağıdaki kütüphaneler kullanılarak bir boru hattı (pipeline) oluşturulmuştur:
* [cite_start]**Gensim:** Word2Vec model eğitimi için[cite: 56, 188].
* [cite_start]**Matplotlib:** Veri görselleştirme için[cite: 56, 190].
* [cite_start]**Scikit-learn:** PCA ve t-SNE algoritmaları için[cite: 189, 191].

---

## 🚀 Analiz Süreci

### 1. Model Eğitimi
[cite_start]Model, müşterilerin bütçe dostu ve lüks araçları tanımlarken kullandığı kelime setleri (corpus) ile eğitilmiştir [cite: 46, 263-274].

### 2. Boyut İndirgeme (Dimensionality Reduction)
[cite_start]Projede iki ana teknik uygulanmıştır [cite: 12-13, 27]:
1. [cite_start]**PCA:** Genel veri yapısını görmek için kullanıldı ancak kümelemede zayıf kaldı [cite: 498-499].
2. [cite_start]**t-SNE:** Kelime kümelerini daha net ayırmak ve yüksek performanslı görselleştirme elde etmek için kullanıldı [cite: 791-793].

---

## 📊 Sonuç
[cite_start]Yapılan optimizasyonlar sonucunda, müşteri tercihlerini temsil eden anlamsal kelime grupları (cluster) başarıyla ayrıştırılmıştır[cite: 843].

---

