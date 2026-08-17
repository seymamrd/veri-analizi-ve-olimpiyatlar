# 🏅 Veri Analizi ve Olimpiyatlar Veri Seti Çalışması

Bu proje, Veri Bilimi (Data Science) sürecinin en temel ve kritik adımları olan **Veri Analizi (EDA)**, **Veri Temizleme (Data Cleaning)** ve **Veri Görselleştirme (Data Visualization)** konularında pratik yapmak amacıyla hazırlanmıştır.

Projede tarihi Olimpiyat Oyunları veri seti kullanılarak sporcular, branşlar, madalya dağılımları ve yaş/boy/kilo analizleri incelenmiştir.

---

## 📌 Öne Çıkan Özellikler ve Kazanımlar

### 1. 🧹 Veri Temizleme & Ön İşleme (Data Cleaning)
* Eksik veri (Missing Value) tespiti ve stratejik dolgu/silme işlemleri.
* Veri tiplerinin dönüştürülmesi ve gereksiz sütunların ayıklanması.
* Temizlenmiş verinin export edilerek analizlere hazır hale getirilmesi (`olimpiyatlar_temizlenmis.csv`).

### 2. 📊 Keşifçi Veri Analizi (EDA - Exploratory Data Analysis)
* Sporcuların fiziksel metriklerinin (boy, kilo, yaş) madalya kazanma oranları ile korelasyonu.
* Yıllara ve cinsiyete göre katılım oranlarının incelenmesi.
* Ülkelere ve branşlara göre madalya dağılım analizleri.

### 3. 🎨 Grafik ve Görselleştirme (Matplotlib & Seaborn)
* **Histogram & Boxplot:** Dağılım ve aykırı değer tespiti.
* **Scatter Plot:** Boy-kilo ilişkisi ve kümelenme analizleri.
* **Bar Chart & Line Plot:** Zaman içindeki değişim ve kategorik karşılaştırmalar.
* Özel grafik kaydetme ve aktarma çalışmaları (`benimfigur.png`).

---

## 🛠️ Kullanılan Teknolojiler

* **Python 3.x**
* **Pandas:** Veri manipülasyonu, filtreleme ve gruplama (`groupby`, `pivot_table`).
* **NumPy:** Vektörel işlemler ve sayısal analizler.
* **Matplotlib (Pyplot):** Özelleştirilmiş grafik mimarileri ve figür yönetimi.
* **Seaborn:** İstatistiksel veri görselleştirme.

---

## 📂 Dosya Yapısı

* `veribilimigiris.ipynb` — Veri analizi, pandas metotları ve veri temizleme adımlarını içeren ana notebook.
* `matplotlibdeneme.py` — Matplotlib kütüphanesi ile grafik çizim pratikleri.
* `athlete_events.csv` — Orijinal Olimpiyat veri seti.
* `olimpiyatlar_temizlenmis.csv` — Analize hazır hale getirilmiş temiz veri seti.
* `benimfigur.png` — Dışa aktarılan örnek grafik görseli.

---

## 🚀 Projeyi Yerelde Çalıştırma

1. Repoyu klonlayın:
   ```bash
   git clone [https://github.com/seymamrd/veri-analizi-ve-olimpiyatlar.git](https://github.com/seymamrd/veri-analizi-ve-olimpiyatlar.git)
   cd veri-analizi-ve-olimpiyatlar
