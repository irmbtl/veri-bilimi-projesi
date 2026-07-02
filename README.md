# veri-bilimi-projesi

# Öğrenci Bilgileri
1306240084
İrem Betül Kocaman

# İstanbul Raylı Sistemler Veri Analizi ve Tahmin Modeli

Bu proje, İstanbul Büyükşehir Belediyesi (İBB) raylı sistem ağındaki istasyon bazlı günlük yolcu ve geçiş sayılarını inceleyen, keşifçi veri analizi (EDA) ve çoklu doğrusal regresyon (Multiple Linear Regression) tabanlı bir makine öğrenmesi tahminlemesi içeren bir veri bilimi çalışmasıdır.

## Veri Kaynağı ve Lisans Bilgileri

- **Veri Seti Adı:** 2025 Yılı Raylı Sistemler İstasyon Bazlı Yolcu ve Yolculuk Sayıları
- **Beklenen Dosya Adı:** `2025-yl-rayl-sistemler-istasyon-bazl-yolcu-ve-yolculuk-saylar.csv`
- **Kaynak:** [İBB Açık Veri Portalı](https://data.ibb.gov.tr/)
- **Lisans:** Creative Commons Attribution 4.0 International (CC BY 4.0) / İBB Açık Veri Lisansı

*Not: Projeyi çalıştırabilmek için ilgili veri setinin İBB Açık Veri Portalı'ndan indirilip, notebook (.ipynb) dosyası ile aynı çalışma dizinine yerleştirilmesi gerekmektedir.*

## Kullanılan Kütüphaneler ve Teknolojiler

Projenin çalıştırılabilmesi için veri işleme, görselleştirme ve makine öğrenmesi odaklı aşağıdaki Python kütüphaneleri kullanılmıştır:

- **Python 3.8+**
- **Pandas:** Veri işleme, temizleme ve analiz
- **NumPy:** Sayısal hesaplamalar ve matris işlemleri
- **Matplotlib & Seaborn:** Verilerin ve keşifçi analizin (EDA) görselleştirilmesi
- **Scikit-Learn (sklearn):** Makine öğrenmesi işlemleri (Model kurulumu, eğitim/test veri bölmesi, Label Encoding, metrik hesaplamaları - MAE, RMSE, R²)
- **Jupyter Notebook / JupyterLab:** Kod geliştirme ve interaktif sunum ortamı

## Projeyi Çalıştırma Talimatları

Proje dosyalarını (örneğin indirdiğiniz `Untitled.ipynb` dosyasını) bilgisayarınızda boş bir klasöre alın.

Terminal (Command Prompt) veya sisteminizin komut satırı arayüzünü açın. Python ortamınızda gerekli kütüphanelerin yüklü olduğundan emin olmak için şu komutu çalıştırın:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
