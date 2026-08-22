<h1 align="center">🎯 Müşteri Segmentasyonu (K-Means Clustering)</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
</p>

## 🎓 Proje Hakkında
Bu proje, **Huawei & Türkiye Yapay Zeka Akademisi Data Science Bootcamp** bitirme çalışması olarak geliştirilmiştir. K-Means makine öğrenmesi algoritması kullanılarak, müşterilerin harcama alışkanlıklarındaki gizli örüntüler keşfedilmiş ve veri odaklı pazarlama stratejileri için segmentasyon yapılmıştır.

🔗 **[Medium Makalemi Oku: Verinin Gücüyle Müşterileri Tanımak]https://medium.com/@nidazbey/verinin-g%C3%BCc%C3%BCyle-m%C3%BC%C5%9Fterileri-tan%C4%B1mak-k-means-ile-m%C3%BC%C5%9Fteri-segmentasyonu-78314b4104bf)**
🏆 **[Bootcamp Sertifikamı Görüntüle](bootcamp_sertifikasi.png)**

---

## ⚙️ Proje Adımları

1. **Veri Ön İşleme:** Eksik (NaN) ve aykırı (Outlier) değerlerin temizlenmesi.
2. **Özellik Mühendisliği:** Parçalı harcama verilerinin `Total_Spend` olarak tek bir anlamlı değişkene dönüştürülmesi.
3. **Ölçeklendirme:** Algoritmanın doğru çalışması için `StandardScaler` uygulanması.
4. **Kümeleme:** Optimum küme sayısının **Dirsek (Elbow) Yöntemi** ile belirlenmesi ve modelin eğitilmesi.

---

## 📊 Görselleştirmeler ve Analiz

### 1. Dirsek (Elbow) Yöntemi ile K Değerinin Bulunması
Modelin en yüksek performansı göstereceği küme sayısını belirlemek için inersiya (inertia) grafiği çizdirildi. Grafikteki kırılma noktasına göre en uygun küme sayısı **K=3** olarak belirlendi.

<p align="center">
  <img src="images/elbow_method.png" width="650" alt="Elbow Method Analizi">
</p>

### 2. K-Means Kümelerinin Dağılımı
Müşteriler, algoritma sonucunda gelir ve harcama durumlarına göre 3 farklı segmente ayrıldı:

<p align="center">
  <img src="images/cluster_scatter.png" width="650" alt="K-Means Cluster Dağılımı">
</p>

---

## 🚀 Müşteri Segmentleri (Sonuçlar)

| Segment | Profil Özeti | Strateji Önerisi |
| :--- | :--- | :--- |
| 🥇 **Grup 1 (Yüksek Gelir/Harcama)** | Platformun en değerli, premium kitlesi. | VIP hizmetler, özel ayrıcalıklar ve lüks kampanyalar sunulmalı. |
| 🥈 **Grup 2 (Orta Gelir/Harcama)** | Düzenli alışveriş yapan, sadık kitle. | Sadakat programları ve çapraz satış (cross-sell) stratejileri uygulanmalı. |
| 🥉 **Grup 3 (Düşük Gelir/Harcama)** | Fiyat duyarlılığı yüksek, fırsat arayan kitle. | İndirim kuponları, 1 alana 1 bedava gibi agresif kampanyalar düzenlenmeli. |

---
<p align="center">
  <i>Geliştirici: Nida Özbey | Bilgisayar Mühendisliği Öğrencisi</i>
</p>
