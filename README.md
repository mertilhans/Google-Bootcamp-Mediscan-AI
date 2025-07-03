
# 🧠 İlaç Bilgi Sistemi (Akıllı Tanıma & Bilgilendirme Platformu)

İlaç kutusunun fotoğrafını çekerek, **kullanıcıya kişiselleştirilmiş, güvenilir ve açıklayıcı ilaç bilgisi** sunmayı amaçlayan yapay zeka destekli bir platform.

---

## 🚀 Proje Amacı

- 📷 Görüntü tanıma ile ilaç tespiti  
- 📄 Kullanma Talimatı (KT) ve Kısa Ürün Bilgisi (KÜB) verilerinden zengin içerik  
- 🧠 AI ile sadeleştirilmiş hasta bilgisi veya profesyonel detay  
- 💬 API & Konuşma yönetimi ile etkileşimli bilgi akışı  
- ✅ KVKK uyumlu, güvenli, kişisel veri saklamayan yapı

---

## 🏗️ Sistem Mimarisi

```
📦 Görüntü → OCR → Metin Tanıma → SQL Sorgu
       ↓
🔍 Eşleşme → ChromaDB vektör arama → Gemini ile cevap üretimi
       ↓
🧠 Kullanıcıya göre özet ya da detay bilgi
```

---

## 📊 Ana Bileşenler

### 1. 🧾 Veri Hazırlama
- Kullanma Talimatı & KÜB PDF analizleri
- JSON çıktılar & kritik bilgi çıkarımı

### 2. 🗃️ Veritabanı & Vektör Arama
- PostgreSQL: İlaç ana veri deposu
- ChromaDB: KT & KÜB bilgi arama (embedding)

### 3. 🔤 OCR & Görüntü İşleme
- Tesseract OCR ile metin çıkarımı
- İlaç kutusu algılama modelleri

### 4. 🤖 AI Destekli Bilgi Servisi
- Prompt engineering (Gemini)
- Farklı seviyelerde bilgi üretimi (hasta / uzman)

### 5. 🔐 Güvenlik & Uyumluluk
- KVKK uyumlu geçici session yapısı
- Sorumluluk reddi & kritik bilgi önceliği

---

## 🧪 API Örnekleri

```http
POST /api/ilac/tani
→ Görüntü yükle, OCR yap, eşleşme bul

GET /api/ilac/{id}/ozet
→ Hasta için sade bilgi

POST /api/ilac/{id}/soru
→ Detaylı AI yanıtı (Gemini ile)

GET /api/ilac/{id}/detay
→ Teknik veriler (KÜB dahil)
```

---

## ⚙️ Teknoloji Stack

| Alan              | Teknoloji                          |
|-------------------|------------------------------------|
| Backend           | FastAPI / Django                   |
| Veritabanı        | PostgreSQL                         |
| Vektör DB         | ChromaDB                           |
| OCR               | Tesseract                          |
| AI/LLM            | Google Gemini                      |
| Caching           | Redis                              |
| Kuyruklama        | Celery + RabbitMQ                  |
| Monitoring        | Prometheus + Grafana               |

---

## 📅 Yol Haritası

| Zaman Aralığı | Hedefler |
|---------------|----------|
| **1-2 Gün**   | JSON çıktılarının iyileştirilmesi, eksik alanların tespiti |
| **1 Hafta**   | PostgreSQL & ChromaDB kurulumu, veri yükleme, ilk API uçları |
| **2-3 Hafta** | OCR & Gemini entegrasyonu, basit frontend prototipi |
| **1-2 Ay**    | Üretim ortamı kurulumu, A/B testleri, performans optimizasyonu |

---

## ✅ Başarı Kriterleri

- 🔍 **Tanıma Doğruluğu**: %95+
- ⚡ **Yanıt Süresi**: < 2 saniye
- ❤️ **Kullanıcı Memnuniyeti**: %90+
- ❗ **Kritik Bilgi Atlama Oranı**: %0

---

## 👥 Proje Ekibi

| Rol                  | İsim                             |
|----------------------|----------------------------------|
| 🧭 Scrum Master       | Enes Muharrem Erdoğan             |
| 🎯 Product Owner      | Kezban Şevval İnci                |
| 👨‍💻 Developer          | Mert İlhan                       |
| 👩‍💻 Developer          | Sevde Elif Hacıosmanoğlu          |
| 👨‍💻 Developer          | Emirhan Yıldız                   |

---

## 📄 Lisans ve Sorumluluk

Bu proje sadece **eğitim ve araştırma** amaçlıdır. Verilen bilgiler gerçek tıbbi tavsiye yerine geçmez. Uygulama hiçbir şekilde kullanıcı verisi tutmaz veya kişisel veri işlemez.

---

## 📌 Not

Proje geliştirme süreci aktif olarak devam etmektedir. Katkı sunmak isteyenler için `issues`, `pull request` ve `contributing.md` bölümleri yakında eklenecektir.
