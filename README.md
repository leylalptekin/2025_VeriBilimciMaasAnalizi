<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/c6fcb862-1a1f-4ae6-897a-95ada5654c1a" />
# 📊 EDA on Data Science Salaries

Bu proje, veri bilimi alanında çalışan profesyonellerin maaş verileri üzerinde Keşifsel Veri Analizi (EDA) uygulayarak içgörü elde etmeyi amaçlamaktadır.

## 🔍 Proje Hakkında

Bu çalışma, [Data Science Salaries Dataset](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries) veri seti kullanılarak gerçekleştirilmiştir. Veriler, 2020-2024 yılları arasında dünya genelinde veri bilimi ile ilgili işlerde çalışan bireylerin maaş bilgilerini içermektedir.

Analiz kapsamında şu sorulara yanıt aranmıştır:

- Hangi ülke ve sektörlerde maaşlar daha yüksek?
- Uzak çalışma (remote) maaşları nasıl etkiliyor?
- Kıdem (experience level) maaşlara nasıl yansıyor?
- En yüksek maaşlar hangi rollerde?

## 📁 Proje İçeriği

Aşağıdaki dosyalar bu repoda yer almaktadır:

- `eda_on_data_science_salaries.ipynb`: Keşifsel veri analizini içeren Jupyter Notebook dosyası.
- `data_science_salaries.csv`: Analizde kullanılan veri seti.
- `README.md`: Projeye ait açıklayıcı bilgiler.
- `Grafikler/`: Grafikleri içeren klasör.

## 🧰 Kullanılan Kütüphaneler

Projede kullanılan başlıca Python kütüphaneleri:

- pandas
- numpy
- matplotlib
- seaborn
- plotly (opsiyonel)
- warnings

> Grafikler hem statik (seaborn, matplotlib) hem de interaktif (plotly) araçlarla görselleştirilmiştir.

## 📈 Elde Edilen Bazı Bulgular

- **Uzaktan çalışma**, ortalama maaşı artırmaktadır.
- **Kıdem** seviyesi yükseldikçe maaşta ciddi artış gözlemlenmektedir.
- **Amerika Birleşik Devletleri**, maaş düzeyinde öne çıkan ülkelerden biridir.
- **Machine Learning Engineer** ve **Data Architect** gibi pozisyonlar en yüksek maaş alan rollerdendir.

## 🛠 Nasıl Çalıştırılır?

1. Repoyu klonlayın:
   ```bash
   git clone https://github.com/kullanici-adi/data-science-salaries-eda.git
   cd data-science-salaries-eda
