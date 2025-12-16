# 🚗 Makine Öğrenmesi ile Araç Satış Fiyatı Tahmini

## 📌 Proje Hakkında
Bu projede, makine öğrenmesi modelleri kullanılarak ikinci el araçların
satış fiyatlarının tahmin edilmesi amaçlanmıştır. 
Proje, önce **Spyder** kullanılarak hazırlanmış ardından **Jupyter Notebook** ile rapor haline getirilmiştir.

## 📊 Veri Seti
Veri seti; araç markası, model, yıl, kilometre, yakıt türü gibi özellikleri
içermektedir. Hedef değişken araç satış fiyatıdır.

## 🤖 Kullanılan Modeller
- Lineer Regresyon
- Log Dönüşümlü Lineer Regresyon
- Ridge Regresyon
- Lasso Regresyon
- Random Forest

## ⚙️ Kullanılan Python Kütüphaneleri
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- SciPy
- Statsmodels

## 📈 Sonuç
Farklı makine öğrenmesi modelleri karşılaştırılmış ve en iyi performansı
gösteren model belirlenmiştir.

## 📁 Dosyalar
- `Car_Price.csv` : Veri seti
- `Araç_Fiyat_Tahmin.ipynb` : Veri analizi, modelleme ve sonuçlar


> Not: Bu notebook rapor formatında hazırlanmış olup tüm analizler, çıktılar ve görseller çalıştırılmış şekilde sunulmaktadır. Projeyi incelemek için yeniden çalıştırılması zorunlu değildir.  
> Dileyen kullanıcılar projeyi kendi ortamlarında çalıştırmak isterse:
> - **Lokal ortamda:** Bilgisayarında Python (Anaconda önerilir) kurulu olmalıdır. Repo indirildikten sonra Anaconda Navigator üzerinden Jupyter Notebook açılarak `Araç_Fiyat_Tahmin.ipynb` dosyası `Restart & Run All` ile çalıştırılabilir.
> - **Web üzerinden:** Proje, Google Colab veya benzeri çevrim içi Jupyter ortamlarına yüklenerek de çalıştırılabilir. Bu durumda veri dosyasının `data/` klasörü altında bulunmasına dikkat edilmelidir.
