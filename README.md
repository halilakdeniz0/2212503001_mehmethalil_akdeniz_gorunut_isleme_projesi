#  Car Damage Detection System (Araç Hasar Tespit Sistemi)

Bu proje, görüntü işleme ve derin öğrenme tekniklerini kullanarak araçlardaki hasarları (ezik, çizik, kırık cam vb.) otomatik olarak tespit eden yapay zeka tabanlı bir sistemdir.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![YOLOv8](https://img.shields.io/badge/Model-YOLOv8-green?logo=ultralytics)
![Gradio](https://img.shields.io/badge/Interface-Gradio-orange?logo=gradio)
![PyTorch](https://img.shields.io/badge/Framework-PyTorch-red?logo=pytorch)

## 📖 Proje Hakkında

**Car Damage Detection**, kullanıcıların araç fotoğraflarını yükleyerek araç üzerindeki hasarlı bölgeleri saniyeler içinde tespit etmelerini sağlar. Proje, nesne tespiti (Object Detection) için son teknoloji **YOLOv8** modelini kullanır ve kullanıcı dostu bir **Gradio** arayüzü ile sunulur.

### 🎯 Amaçlar
* Sigorta şirketleri için hasar tespit süreçlerini hızlandırmak.
* Araç kiralama şirketleri için giriş-çıkış kontrollerini otomatize etmek.
* Kullanıcıların araç hasar durumunu hızlıca analiz etmesini sağlamak.


## 📊 Model Eğitimi ve Performans

Model, **YOLOv8** mimarisi kullanılarak eğitilmiştir. Eğitim süreci `projebittikodu.ipynb` dosyasında detaylandırılmıştır.

* **Dataset:** [Dataset ismini veya kaynağını buraya yazabilirsin, örn: Roboflow Car Damage Dataset]
* **Epoch Sayısı:** [Notebook'taki epoch sayısını buraya yaz, örn: 50]
* **Başarı Oranı (mAP):** [Elde ettiğin mAP değerini buraya yazabilirsin]


## 🤝 Katkıda Bulunma

1.  Forklayın (Fork).
2.  Branch oluşturun (`git checkout -b feature/yeniozellik`).
3.  Değişikliklerinizi commit yapın (`git commit -am 'Yeni özellik eklendi'`).
4.  Branch'inizi pushlayın (`git push origin feature/yeniozellik`).
5.  Pull Request oluşturun.


Developed by Mehmet Halil Akdeniz
