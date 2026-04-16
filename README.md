--Historical Olympic Performance Analysis (1896 - 2016)--

Bu proje, 1896'dan 2016'ya kadar olan modern Olimpiyat Oyunları verilerini kullanarak sporcuların demografik gelişimini, branş bazlı fiziksel farkları ve ülkelerin başarılarını inceleyen bir **Keşifçi Veri Analizi (EDA)** çalışmasıdır.

- Proje Özeti
Veri seti üzerinden Python'un veri analizi ve görselleştirme kütüphaneleri kullanılarak şu sorulara yanıt aranmıştır:
* Olimpiyatlara katılan sporcu sayısı yıllar içinde nasıl bir trend izledi?
* Madalya kazanan sporcuların yaş dağılımı nasıldır?
* Farklı spor branşları (Basketbol vs. Jimnastik) arasında fiziksel özellikler (Boy) açısından nasıl bir anomali/fark vardır?
* Tarih boyunca en çok madalya kazanan ilk 10 ülke hangisidir?

- Kullanılan Teknolojiler
* **Python 3.x**
* **Pandas:** Veri manipülasyonu ve temizleme.
* **Matplotlib:** Veri görselleştirme ve özelleştirilmiş grafik tasarımı.
* **Jupyter Notebook:** Analiz sürecinin dokümantasyonu.

-- Öne Çıkan Analizler ve Görselleştirmeler--

-- 1. Zaman Serisi Analizi--
Olimpiyatlara katılımın tarihsel gelişimi incelenmiş, özellikle dünya savaşları dönemindeki düşüşler ve modern dönemdeki artış gözlemlenmiştir.

-- 2. Branş Bazlı Kutu Grafiği (Box Plot)--
Basketbol ve Jimnastik branşları arasındaki boy farkları kutu grafiği ile analiz edilerek, verideki aykırı değerler (outliers) tespit edilmiştir.

-- 3. Ülke Başarı Sıralaması--
Tarih boyunca en çok madalya kazanan ülkeler, Pandas'ın gruplama yetenekleri kullanılarak sütun grafiklerinde görselleştirilmiştir.

-- 📂 Veri Seti--
Projede kullanılan veri seti Kaggle üzerinden temin edilmiştir:
[120 years of Olympic history: athletes and results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
*(Not: Veri dosyası boyutu nedeniyle repoya dahil edilmemiştir, yukarıdaki linkten indirilebilir.)*

-- Nasıl Çalıştırılır?--
1. Bu repoyu bilgisayarınıza clone'layın: `git clone https://github.com/IbrahimOgurlu/repository-ismin.git`
2. Gerekli kütüphaneleri yükleyin: `pip install pandas matplotlib`
3. Jupyter Notebook'u başlatın ve analiz dosyalarını inceleyin.

---
--Bu proje, veri görselleştirme tekniklerini ve veri bilimi metodolojilerini pekiştirmek amacıyla geliştirilmiştir.--
