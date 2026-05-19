<div align="center">

# 🔐 Washington'da Gerçekleşen Veri İhlallerinin Analizi

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>

> Washington eyaletinde bildirilen siber güvenlik ihlallerinin kapsamlı keşifsel veri analizi ve makine öğrenimi uygulaması.

</div>

---

## 📋 İçindekiler

- [Proje Hakkında](#-proje-hakkında)
- [Veri Seti](#-veri-seti)
- [Kullanılan Teknolojiler](#-kullanılan-teknolojiler)
- [Analizler](#-analizler)
- [Kurulum](#-kurulum)
- [Kullanım](#-kullanım)

---

## 🎯 Proje Hakkında

Bu proje, Washington eyaletinde resmi makamlar tarafından kayıt altına alınan veri ihlali vakalarını analiz etmektedir. Amaç; ihlallerin sektörel dağılımını, saldırı türlerini, etkilenen kişi sayılarını ve ihlallerin tespit/müdahale sürelerini anlamak ve bu verileri kullanarak tahminleyici modeller geliştirmektir.

---

## 📊 Veri Seti

**Dosya:** `WashıngtondaGerçekleşenVeriİhlalleri.csv`

| Sütun | Türkçe Karşılığı |
|---|---|
| `DateAware` | Fark Edilme Tarihi |
| `DateSubmitted` | Bildirim Tarihi |
| `DataBreachCause` | Veri İhlali Nedeni |
| `DateStart` | Başlangıç Tarihi |
| `DateEnd` | Bitiş Tarihi |
| `Name` | Kuruluş Adı |
| `CyberattackType` | Siber Saldırı Türü |
| `WashingtoniansAffected` | Etkilenen Kişi Sayısı |
| `IndustryType` | Sektör Türü |
| `DaysToContainBreach` | İhlali Kontrol Altına Alma Süresi (Gün) |
| `DaysToIdentifyBreach` | İhlali Belirleme Süresi (Gün) |
| `DaysOfExposure` | Maruz Kalma Süresi (Gün) |
| `DaysElapsedBeforeNotification` | Bildirimden Önce Geçen Süre (Gün) |
| `DiscoveredInProgress` | Devam Ederken Keşfedildi mi? |

---

## 🛠️ Kullanılan Teknolojiler

| Kütüphane | Kullanım Amacı |
|---|---|
| `pandas` | Veri işleme ve analiz |
| `numpy` | Sayısal hesaplamalar |
| `matplotlib` | Veri görselleştirme |
| `seaborn` | İstatistiksel görselleştirme |
| `scikit-learn` | Makine öğrenimi modelleri |

---

## 🔍 Analizler

### 📌 Keşifsel Veri Analizi (EDA)
- Veri setinin boyutu, temel istatistikleri ve eksik değer analizi
- Benzersiz değer dağılımları
- Sektörel bazda ihlal sayısı dağılımı

### 📈 Görselleştirmeler
- Siber saldırı türlerine göre etkilenen kişi dağılımı
- Sektörlere göre ihlal yoğunluğu
- İhlal tespit ve müdahale sürelerinin histogram analizi
- Yıllara göre ihlal trendleri

### 🤖 Makine Öğrenimi
- **Linear Regression** — Etkilenen kişi sayısı tahmini
- **Random Forest Regressor** — İhlali kontrol altına alma süresi tahmini
- Model performans metrikleri: MAE, RMSE, R²

---

## ⚙️ Kurulum

1. Repoyu klonlayın:
```bash
git clone https://github.com/yildirimyusuf79/guvenlik-ihlalleri-veri-analizi.git
cd guvenlik-ihlalleri-veri-analizi
```

2. Gerekli kütüphaneleri yükleyin:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## ▶️ Kullanım

```bash
jupyter notebook HiKodProjesi.ipynb
```

Notebook'u sırayla çalıştırarak analizleri takip edebilirsiniz.

---

<div align="center">

**Yusuf Yıldırım** · [GitHub](https://github.com/yildirimyusuf79)

</div>
