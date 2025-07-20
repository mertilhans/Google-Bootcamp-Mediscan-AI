# 💊 MediScan AI
![logo ](https://github.com/user-attachments/assets/bba31cc2-6c3a-4a7f-80db-3ae5dd9cd8e7)

MediScan AI, kullanıcıların ilaç kutularını, blisterlerini veya doğrudan ilaçların kendisini fotoğraflayarak ilaçlar hakkında sade, anlaşılır ve resmi bilgilere anında ulaşabildiği yapay zeka destekli bir sağlık teknolojisi platformudur.

---

## 🎯 Proje Amacı

Günümüzde milyonlarca insan ilaç prospektüslerindeki karmaşık tıbbi terimleri anlamakta zorluk çekiyor veya prospektüsleri kaybediyor. MediScan AI, bu sorunu çözmek için yapay zeka teknolojilerinden faydalanarak tıbbi bilgiyi herkesin anlayabileceği bir şekilde sunmayı amaçlar.

---
![logooo](https://github.com/user-attachments/assets/1bb2649d-832a-41f4-b72c-2b26cb41074c)

## 🔧 Özellikler

- **📸 İlaç Görüntü Tanıma:**
  - Kutu, blister veya doğrudan ilaç fotoğrafından tanıma.
  - Her tip için optimize edilmiş algoritmalar.

- **🧠 Hibrit Tanıma Sistemi:**
  - OCR ve görüntü işleme teknolojileri bir arada.
  - Sonuçlar birleştirilerek doğruluk artırılır.

- **📝 Akıllı Prospektüs Özetleme:**
  - Sağlık Bakanlığı verileri kullanılır.
  - Gemini API ile sade ve kişisel özetler sunulur.

- **❓ İnteraktif Soru-Cevap:**
  - Kullanıcılar sistem üzerinden sorular sorabilir.
  - Sistem, prospektüs verilerine dayalı yanıt üretir.

- **📷 Çoklu Fotoğraf Desteği:**
  - Aynı ilacın farklı açılardan fotoğrafları yüklenebilir.

- **🕵️ Anonim Kullanım:**
  - Hesap açmadan kullanılabilir.
  - Fotoğraflar geçici olarak işlenir ve saklanmaz.

- **🔁 Benzer İlaç Bilgisi:**
  - Aynı etken maddeye sahip alternatif ilaçlar gösterilir.

- **⚠️ Sorumluluk Reddi:**
  - Sunulan bilgiler tıbbi tavsiye değildir.

---

## 👥 Hedef Kitle

- Kronik hastalıkları olan bireyler
- 65 yaş üstü kullanıcılar
- Çocuklu aileler ve ebeveynler
- Görme problemi yaşayanlar
- Sağlık okuryazarlığı düşük bireyler
- Acil durumda ilaç bilgisine erişmek isteyenler
- Genç ve teknolojiye yatkın kullanıcılar
- Eczacılar ve sağlık çalışanları

---

## 🔮 Gelecek Sürümlerde Planlanan Özellikler

- Kullanıcı hesabı ve geçmiş arama kaydı
- Dozaj hatırlatıcı sistemi
- Favori ilaçlar listesi
- İlaç etkileşim kontrolü
- Eczane entegrasyonu ve stok bilgisi
- Mobil uygulama sürümü

---

## 👨‍💻 Proje Ekibi

| İsim                     | Görev             |
|--------------------------|------------------|
| Enes Muharrem Erdoğan    | Scrum Master     |
| Kezban Şevval İnci       | Product Owner    |
| Mert İlhan               | Developer        |
| Sevde Elif Hacıosmanoğlu | Developer        |
| Emirhan Yıldız           | Developer        |

---

## 🚧 Sprint 1 Notları

### 🔧 Teknik Kararlar

- Proje yönetimi için Trello kullanılmasına karar verildi
- UI/UX tasarımları için Figma kullanılacak
- Backend framework olarak FastAPI seçildi
- Görüntü işleme için OpenCV ve Pillow kütüphaneleri kullanılacak
- Model eğitimi için TensorFlow/Keras ve EfficientNet kullanılacak
- OCR işlemleri için Tesseract ve EasyOCR karşılaştırılacak
- Veritabanı olarak PostgreSQL (metadata) ve ChromaDB (vektör veritabanı) kullanılacak
- LLM entegrasyonu için Gemini API tercih edildi
- PDF işleme için PyPDF2 ve pdfplumber test edilecek

### 🎯 Sprint Hedefleri

- Hedeflenen puan: **100 Puan**
- Toplam 300 puanlık backlog, 3 sprint'e bölündü
- Daily Scrums: Google Meet üzerinden günlük gerçekleştirildi

### 📋 Backlog

- [[Trello Board Linki]](https://trello.com/b/Ef3v4hnH/bootcamp-183-grup)
![eklenecek1](https://github.com/user-attachments/assets/d691b13a-27ab-492c-ba03-aae4a96ddb84)
![eklenecek2](https://github.com/user-attachments/assets/ca0c2d6e-0a44-4a5b-98c9-231eaf225ce4)



### ✅ Sprint Review

- Literatür taraması ve rakip analizleri yapıldı
- İlk 20 ilaç için veri seti oluşturuldu
- 15.000 ilaç bilgisi PDF olarak toplandı
- PDF'lerden JSON test verileri üretildi
- GitHub repo ve klasör yapısı oluşturuldu
- Tech stack belirlendi ve belgelendi

**Katılımcılar:** Tüm takım üyeleri

![eklenecek1](https://github.com/user-attachments/assets/852a187c-7a92-4c95-9cf7-8f5ad00717fa)

### 🔁 Sprint Retrospective

- Fotoğraf çekimi beklenenden uzun sürdü, standartlaştırıldı
- PDF kütüphanelerinin çeşitliliği test edildi
- İkinci sprintte model eğitimi ve web geliştirme başlayacak
- OCR araştırması derinleştirilecek
- Görev dağılımı yeniden gözden geçirildi
- Mockup tasarımları ikinci sprintte tamamlanacak
- KVKK ve veri güvenliği üzerine araştırma yapılacak
- Proje ismi olarak "MediScan AI" kararlaştırıldı (geçici)

### 📝 Diğer Notlar

- Hibrit tanıma sistemi benimsenecek (OCR + Görüntü İşleme)
- Kullanıcı deneyimi öncelikli: hesap açmadan kullanım hedefleniyor
- Gelecekte kişiselleştirme ve kullanıcı hesabı özellikleri eklenecek

---
# 🚀 Sprint 2 Notları
  - Sprint İçinde Tamamlanması Tahmin Edilen Puan: 100 Puan
Puan Tamamlama Mantığı: Sprint 2'de veri setinin genişletilmesi, veritabanı sistemlerinin production'a hazır hale getirilmesi ve frontend geliştirmeye odaklanıldı. KVKK ve veri güvenliği üzerine araştırma yapıldı. Model tanıma testlerine başlandı, OCR ve görüntü işleme yöntemleri test edildi. Toplam 300 puanlık projenin ikinci 100 puanlık kısmı bu sprint'te tamamlanması hedeflendi.
Daily Scrum: Takım üyeleri Google Meet üzerinden günlük toplantılar gerçekleştirdi. Görev dağılımları ve backlog'lar günlük olarak takip edildi.
---

## 🎯 Tahmini Tamamlanacak İşler

- Veri setinin genişletilmesi  
- Veritabanı sistemlerinin production'a hazır hale getirilmesi  
- Frontend geliştirmeye başlanması  
- KVKK ve veri güvenliği üzerine araştırmalar yapılması  
- OCR ve görüntü işleme yöntemlerinin test edilmesi  
- Model tanıma testlerine başlanması  

**Toplam Proje Puanı:** 300  
**Sprint 2 Puanı (Tahmini):** 100  

---

## 📆 Daily Scrum

- Takım üyeleri(Enes Muharrem Erdoğan - Sevde Elif Hacıosmanoğlu - Şevval İnci - Mert İlhan)her gün **Google Meet** üzerinden online toplantılar gerçekleştirdi.  
- Görev dağılımları ve **backlog durumu** günlük olarak kontrol edildi ve güncellendi.
- ![bu2](https://github.com/user-attachments/assets/8937f582-6172-4613-bfe8-4d5a19b6c6d0)

---

## 📋 Backlog & Sprint Board

Sprint boyunca görevlerin takibi için **Trello** kullanıldı.  
🔗 [Trello Sprint 2 Backlog Linki](https://trello.com/b/y5EasA84/bootcamp-grup-183)

> 📸  
> ![trello](https://github.com/user-attachments/assets/27db1278-f417-4a95-8c7b-826643dd58ee)
![bu444](https://github.com/user-attachments/assets/11fdf9e1-3586-4ccd-9869-1ae19ba59a01)
---


## 💻 Arayüz ve Uygulama Geliştirme

- React.js ile modern kullanıcı arayüzü geliştirildi  
- Frontend ve Backend bileşenleri **sağlam mimari temeller** üzerine inşa edildi  
- Kullanıcı deneyimi önceliklendirildi: **Hesapsız kullanım** hedefleniyor  
- Gelecekte kişiselleştirme ve kullanıcı hesabı özellikleri planlandı  
![bu1](https://github.com/user-attachments/assets/bb30be78-9ab5-4520-afb4-fd3f9361ad53)


---

## ✅ Sprint Review – Tamamlanan İşler

- ✅ 50+ ilaç için yüksek kaliteli görseller toplandı  
- ✅ Data augmentation ile veri seti 250+ görsele genişletildi  
- ✅ 100+ ilaç PDF’i başarıyla işlendi ve yapılandırıldı  
- ✅ PostgreSQL ile optimize edilmiş metadata sistemi kuruldu  
- ✅ ChromaDB ile RAG pipeline başarıyla test edildi  
- ✅ İlk model tanıma testlerinde %70+ doğruluk elde edildi  
- ✅ Frontend geliştirme başladı  
- ⏳ Gemini API entegrasyonu bir sonraki sprint'e aktarıldı  

---

## 🧪 Demo Notları

- **Hibrit tanıma sistemi (OCR + Görüntü İşleme)** ilk testlerde umut verici sonuçlar verdi  
- PDF işleme süresi standartlaştırıldı ve performansı 10 kat artırıldı  

---

## 🔁 Sprint Retrospective

### ✅ İyi Giden Noktalar  
- PDF işleme süresi büyük ölçüde optimize edildi  
- Docker ile deployment süreçleri hız kazandı  
- İlk model testleri hedeflenen doğruluk seviyesine yaklaştı  
- Frontend-Backend entegrasyonu sorunsuz ilerledi  

### ⚠️ Geliştirilmesi Gerekenler  
- Model doğruluğu için **edge case** örneklerine ihtiyaç var  
- ChromaDB'nin **Türkçe metinlerdeki embedding kalitesi** artırılmalı  
- Bazı OCR çıktılarında ilaç adı tanıma hataları tespit edildi  

### 📌 Sprint 3 Aksiyonları  
- Model fine-tuning çalışmalarına başlanacak  
- Gemini API entegrasyonu yapılacak  
- Kullanıcı test senaryoları oluşturulacak  
- Görsel veri seti 150+ hedefiyle genişletilecek  

---

## 📝 Diğer Notlar

- **Fotoğraf çekimi** süreci standardize edildi  
- **PDF kütüphanelerinin** çeşitliliği test edildi  
- KVKK ve veri güvenliği araştırmaları devam edecek  
- **Mockup tasarımları** Sprint 3’e taşındı  
- Görev dağılımı yeniden gözden geçirildi  
- Proje adı olarak "**MediScan AI**" belirlendi *(geçici)*  
- Hibrit tanıma sistemi ve kullanıcı deneyimi ön planda tutuldu  
> ℹ️ **Uyarı:** Bu platform tanı koymaz veya reçete vermez. Sadece bilgilendirme amacıyla kullanılır. Her zaman bir sağlık uzmanına danışınız.

