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
## 📝 Sprint 2 Notları

### 🎯 Sprint Hedefi  
**Tahmini Tamamlanacak Puan:** 100 Puan  
**Toplam Proje Puanı:** 300 Puan  

Sprint 2'de aşağıdaki hedeflere odaklanıldı:
- Veri setinin genişletilmesi  
- Veritabanı sistemlerinin production'a hazır hale getirilmesi  
- Frontend geliştirmeye başlanması  
- KVKK ve veri güvenliği üzerine araştırmalar yapılması  
- OCR ve görüntü işleme yöntemlerinin test edilmesi  
- Model tanıma testlerine başlanması  

---

### 📆 Daily Scrum  
- Takım üyeleri her gün **Google Meet** üzerinden çevrim içi toplantılar gerçekleştirdi.  
- **Görev dağılımları** ve **backlog** durumu günlük olarak takip edildi.  

---

### ✅ Sprint Review – Tamamlanan İşler  
- ✅ 50+ ilaç için yüksek kaliteli görsel veri seti oluşturuldu  
- ✅ Data augmentation ile veri seti 5 kat genişletildi (250+ görsel)  
- ✅ 100+ ilaç PDF’i başarıyla işlendi ve yapılandırıldı  
- ✅ PostgreSQL'de optimize edilmiş metadata sistemi kuruldu  
- ✅ ChromaDB RAG pipeline’ı başarıyla test edildi  
- ✅ React.js ile modern kullanıcı arayüzü geliştirildi  
- ✅ İlk model tanıma testleri %70+ doğruluk oranı gösterdi  
- ⏳ Gemini API entegrasyonu Sprint 3'e planlandı  

---

### 🧪 Demo Notları  
- Hybrid tanıma sistemi (**OCR + Görüntü İşleme**) ilk testlerde **umut verici sonuçlar** verdi.  

---

### 👥 Katılımcılar  
- Tüm takım üyeleri Sprint 2 sürecine aktif olarak katkı sağladı.

---

## 🔄 Sprint Retrospective  

### ✅ İyi Giden Noktalar
- PDF işleme hızı 10 kata kadar artırıldı  
- Docker kullanımı sayesinde deployment süreci kolaylaştı  
- Model ilk testlerde beklenen performansı gösterdi  
- Frontend-Backend mimari tasarımı sağlam temeller üzerine kuruldu  

---

### ⚠️ Geliştirilmesi Gereken Noktalar
- Model doğruluğu için daha fazla **edge case** verisine ihtiyaç var  
- ChromaDB’nin Türkçe embedding performansı geliştirilmeli  
- Bazı ilaç isimlerinde OCR hataları tespit edildi  

---

### 📌 Aksiyonlar (Sprint 3 için planlananlar)
- Model fine-tuning çalışmalarına başlanacak  
- Gemini API entegrasyonu öncelikli hedef olarak belirlendi  
- Kullanıcı test senaryoları hazırlanacak  
- İlaç veri seti 150+ görsel hedefine ulaştırılacak  

---

## 📋 Backlog & Takip Panosu

Sprint 2 sürecinde görevlerin planlanması ve takibi için **Trello** kullanıldı. Aşağıda aktif olarak kullanılan backlog bağlantısı yer almaktadır:

🔗 **Trello Sprint 2 Backlog Linki:** [Trello Panosunu Görüntüle](https://trello.com/b/y5EasA84/bootcamp-grup-183) 

> 📸
> ![bu1](https://github.com/user-attachments/assets/3aa0b34d-7f67-450b-b7fc-ea0e28f7d35b)
> ![bu2](https://github.com/user-attachments/assets/3ec29e68-0005-4be5-9335-f3a608bd66e6)
> ![trello](https://github.com/user-attachments/assets/27db1278-f417-4a95-8c7b-826643dd58ee)

> ℹ️ **Uyarı:** Bu platform tanı koymaz veya reçete vermez. Sadece bilgilendirme amacıyla kullanılır. Her zaman bir sağlık uzmanına danışınız.

