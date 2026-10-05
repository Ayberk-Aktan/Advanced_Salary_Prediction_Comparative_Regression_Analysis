# 📈 Advanced Salary Prediction & Comparative Regression Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Bu proje, unvan seviyeleri ve çalışan metriklerine dayalı olarak **maaş tahmini** yapmak amacıyla geliştirilmiş kapsamlı bir makine öğrenimi ve istatistiksel analiz çalışmasıdır. Doğrusal ve doğrusal olmayan regresyon modellerinin performansları ($R^2$, MSE vb.) karşılaştırılmış ve veri seti üzerindeki istatistiksel ilişkiler analiz edilmiştir.

---

## 📌 Proje Özeti & Öne Çıkanlar

* **Veri Analizi & Korelasyon:** Değişkenler arasındaki korelasyon ilişkileri incelemeli ve sabit (varyansı 0 olan) metriklerin analize etkisi ayıklanmıştır.
* **Eğrisel / Üstel İlişki Tespiti:** Unvan seviyesi arttıkça maaşın üstel bir şekilde artması nedeniyle, standart Doğrusal Regresyon (Linear Regression) yerine Polinomiyal Regresyon ve Logaritmik Dönüşüm yaklaşımlarının başarısı karşılaştırılmıştır.
* **İstatistiksel Analiz (ANOVA):** Kategorik değişkenlerin maaş üzerindeki anlamlılığı ANOVA ($F$-Testi) ve p-değeri analizleri ile değerlendirilmiştir.

---

## 🛠️ Kullanılan Teknolojiler & Kütüphaneler

* **Dil:** Python 3.8+
* **Veri İşleme & Analiz:** `pandas`, `numpy`
* **Görselleştirme:** `matplotlib`, `seaborn`
* **Makine Öğrenimi:** `scikit-learn`
* **İstatistiksel Modeller:** `statsmodels`

---

## 📂 Proje Yapısı

```text
Advanced_Salary_Prediction_Comparative_Regression_Analysis/
│
├── data/
│   └── salary_data.csv          # Veri seti
│
├── notebooks / scripts/
│   └── main_analysis.py          # Veri analizi, modelleme ve görselleştirme kodları
│
├── requirements.txt             # Gerekli Python paketleri
├── README.md                    # Proje dokümantasyonu
└── .gitignore                   # Git tarafından izlenmeyecek dosyalar