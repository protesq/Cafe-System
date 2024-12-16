# Kafe Yönetim Sistemi

## 📝 Proje Açıklaması
Bu proje, kafe işletmelerinde sipariş ve masa yönetimini kolaylaştırmak amacıyla geliştirilmiş bir **Kafe Yönetim Sistemi**dir. Yönetici ve garsonların iş süreçlerini kolaylaştırmak için kullanıcı dostu bir arayüz sunar.

---

## 📦 Özellikler
- **Kullanıcı Rolleri:**
  - Yönetici ve garson girişi
  - Yönetici paneli ile garson ve ürün yönetimi
- **Masa Yönetimi:**
  - Masa durumlarının görüntülenmesi ve güncellenmesi
  - Masa birleştirme ve yeni masa ekleme
- **Ürün ve Kategori Yönetimi:**
  - Yeni ürün ekleme ve düzenleme
  - Kategori yönetimi (ekleme, silme)
- **Sipariş Yönetimi:**
  - Sipariş ekleme, güncelleme ve iptal etme
  - Masa durumunun siparişe göre otomatik güncellenmesi
- **Raporlama:**
  - Günlük, aylık ve yıllık raporlar (Word dosyası olarak)

---

## 💻 Kullanılan Teknolojiler
- **Python** (3.8 ve üzeri)
- **Tkinter:** Kullanıcı arayüzü geliştirme
- **SQLite3:** Veritabanı yönetimi
- **python-docx:** Word dosyası oluşturma

---

## 🚀 Başlangıç

### Gereksinimler
- Python 3.8 veya üzeri sürüm
- Aşağıdaki kütüphanelerin yüklü olması:
  ```bash
  pip install python-docx
  ```

### Çalıştırma Adımları
1. Proje dosyalarını indirin veya klonlayın:
   ```bash
   git clone https://github.com/protesq/kafe-yonetim-sistemi.git
   cd kafe-yonetim-sistemi
   ```
2. Python gereksinimlerini yükleyin:
   ```bash
   pip install python-docx
   ```
3. Uygulamayı başlatın:
   ```bash
   python main.py
   ```

---

## 📂 Proje Dosya Yapısı
- **main.py:** Uygulamanın ana dosyası
- **kafe_sistemi.db:** SQLite veritabanı dosyası
- **README.md:** Proje açıklaması ve kurulum rehberi
