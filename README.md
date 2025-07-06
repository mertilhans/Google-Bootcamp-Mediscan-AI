# 💊 MediScan AI
![logo ](https://github.com/user-attachments/assets/bba31cc2-6c3a-4a7f-80db-3ae5dd9cd8e7)

MediScan AI, kullanıcıların ilaç kutularını, blisterlerini veya doğrudan ilaçların kendisini fotoğraflayarak ilaçlar hakkında sade, anlaşılır ve resmi bilgilere anında ulaşabildiği yapay zeka destekli bir sağlık teknolojisi platformudur.

---

## 🎯 Proje Amacı

Günümüzde milyonlarca insan ilaç prospektüslerindeki karmaşık tıbbi terimleri anlamakta zorluk çekiyor veya prospektüsleri kaybediyor. MediScan AI, bu sorunu çözmek için yapay zeka teknolojilerinden faydalanarak tıbbi bilgiyi herkesin anlayabileceği bir şekilde sunmayı amaçlar.

---

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
- Daily Scrums: Google Meet üzerinden gerçekleştirildi

### 📋 Backlog

- [[Trello Board Linki]](https://trello.com/b/Ef3v4hnH/bootcamp-183-grup)
- <img width="1349" alt="Screenshot 2025-07-06 at 23 19 48" src="https://github.com/user-attachments/assets/2b75088e-bc24-4751-9fc0-b989a336c8b8" />

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

> ℹ️ **Uyarı:** Bu platform tanı koymaz veya reçete vermez. Sadece bilgilendirme amacıyla kullanılır. Her zaman bir sağlık uzmanına danışınız.

