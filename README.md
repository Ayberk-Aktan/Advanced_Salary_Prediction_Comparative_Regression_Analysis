# 📈 Advanced Salary Prediction & Comparative Regression Analysis

![Python](https://img.shields.io/badge/Python-3.10.11-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Bu proje, çalışanların unvan seviyelerine göre maaş tahminlerinin yapılması ve farklı regresyon modellerinin performanslarının karşılaştırılması amacıyla geliştirilmiş bir veri analizi ve makine öğrenimi projesidir.

---

## 📌 Proje Özeti & Gerçekleştirilen Analizler

* **Veri Ön İşleme & Keşifsel Veri Analizi (EDA):** `maaslar_yeni.csv` veri seti incelenmiş; `UnvanSeviyesi`, `Kidem`, `Puan` ve `maas` değişkenleri arasındaki ilişkiler analiz edilmiştir.
* **Sabit Değişken Tespiti:** Veri setinde varyansı sıfır olan (her satırda aynı değere sahip) `Kidem` ve `Puan` gibi sabit sütunların korelasyon üzerindeki etkileri değerlendirilmiştir.
* **Model Karşılaştırmaları:** 
  * Ünvan seviyesi ile maaş arasındaki üstel/doğrusal olmayan ilişkiyi modellemek adına **Linear Regression** ve **Polynomial Regression** gibi regresyon yaklaşımları uygulanmıştır.
  * Modellerin başarı kriteri olarak $R^2$ (R-Kare / Belirtme Katsayısı) ve hata metrikleri incelenmiştir.
* **Görselleştirme:** Korelasyon matrisleri (`seaborn.heatmap`) ve model tahmin eğrileri `matplotlib` ile görselleştirilmiştir.

---

## 🛠️ Teknolojiler & Kütüphaneler

* **Python Sürümü:** 3.10.11
* **Veri İşleme:** `pandas`, `numpy`
* **Görselleştirme:** `matplotlib`, `seaborn`
* **Makine Öğrenimi:** `scikit-learn`

---

## 📂 Proje Dizin Yapısı

```text
.
├── maaslar_yeni.csv      # Veri seti
├── notebooks.ipynb       # Veri analizi, modelleme ve görselleştirme adımları
├── requirements.txt      # Proje bağımlılıkları
└── README.md             # Proje dokümantasyonu# 📈 Advanced Salary Prediction & Comparative Regression Analysis

![Python](https://img.shields.io/badge/Python-3.10.11-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Bu proje, çalışanların unvan seviyelerine göre maaş tahminlerinin yapılması ve farklı regresyon modellerinin performanslarının karşılaştırılması amacıyla geliştirilmiş bir veri analizi ve makine öğrenimi projesidir.

---

## 📌 Proje Özeti & Gerçekleştirilen Analizler

* **Veri Ön İşleme & Keşifsel Veri Analizi (EDA):** `maaslar_yeni.csv` veri seti incelenmiş; `UnvanSeviyesi`, `Kidem`, `Puan` ve `maas` değişkenleri arasındaki ilişkiler analiz edilmiştir.
* **Sabit Değişken Tespiti:** Veri setinde varyansı sıfır olan (her satırda aynı değere sahip) `Kidem` ve `Puan` gibi sabit sütunların korelasyon üzerindeki etkileri değerlendirilmiştir.
* **Model Karşılaştırmaları:** 
  * Ünvan seviyesi ile maaş arasındaki üstel/doğrusal olmayan ilişkiyi modellemek adına **Linear Regression** ve **Polynomial Regression** gibi regresyon yaklaşımları uygulanmıştır.
  * Modellerin başarı kriteri olarak $R^2$ (R-Kare / Belirtme Katsayısı) ve hata metrikleri incelenmiştir.
* **Görselleştirme:** Korelasyon matrisleri (`seaborn.heatmap`) ve model tahmin eğrileri `matplotlib` ile görselleştirilmiştir.

---

## 🛠️ Teknolojiler & Kütüphaneler

* **Python Sürümü:** 3.10.11
* **Veri İşleme:** `pandas`, `numpy`
* **Görselleştirme:** `matplotlib`, `seaborn`
* **Makine Öğrenimi:** `scikit-learn`

---

## 📂 Proje Dizin Yapısı

```text
.
├── maaslar_yeni.csv      # Veri seti
├── notebooks.ipynb       # Veri analizi, modelleme ve görselleştirme adımları
├── requirements.txt      # Proje bağımlılıkları
└── README.md             # Proje dokümantasyonu