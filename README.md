# 🎨 TurkPhoto v2.0

**TurkPhoto**, PyQt6 ve NumPy altyapısı kullanılarak geliştirilmiş, Adobe Photoshop tarzı koyu temaya ve gelişmiş grafik düzenleme özelliklerine sahip bağımsız Windows masaüstü fotoğraf editörüdür.

![TurkPhoto Banner](Açılış.png)

---

## ✨ Öne Çıkan Özellikler

* **🎨 Photoshop Tarzı Koyu Arayüz:** Çift sütunlu sol araç çubuğu, sağ özellikler paneli, navigatör, geçmiş paneli ve geniş çalışma alanı (Canvas).
* **🚀 Yüksek Performans:** NumPy altyapısı sayesinde saliseler içinde çalışan resim filtreleri, katman karışımları (Blend Modes) ve efektler.
* **⚡ Hızlı Açılış:** Özel **Açılış Ekranı (Splash Screen)** ve çerçevesiz açılış deneyimi.
* **🌐 Çoklu Dil Desteği:** Türkçe ve İngilizce arayüz menü seçenekleri.
* **🖌️ Düzenleme Araçları:** Gelişmiş fırça, silgi, renk kovası (flood fill), seçim araçları, döndürme, aynalama ve yakınlaştırma (Zoom).
* **💾 Çoklu Format Desteği:** PNG, JPG, JPEG ve BMP formatlarında katmanlı dosya açma ve kaydetme.
* **📦 Bağımsız Çalışma:** Python veya ekstra hiçbir kütüphane kurulumu gerektirmeyen tek parça `.exe` yapısı.

---

## 🛠️ Kurulum ve Çalıştırma

TurkPhoto v2.0 tamamen taşınabilir (portable) ve bağımsız bir Windows uygulamasıdır.

### Yöntem 1: Doğrudan Çalıştırma (Tavsiye Edilen)
1. **[Releases](../../releases)** sayfasından en son **`TurkPhoto.exe`** (v2.0) dosyasını indirin.
2. Bilgisayarınızda **Python, PyQt6 veya NumPy yüklü olmasına gerek yoktur.**
3. İndirdiğiniz **`TurkPhoto.exe`** dosyasına çift tıklayarak uygulamayı doğrudan başlatın!

---

### Yöntem 2: Kaynak Koddan Çalıştırma (Geliştiriciler İçin)

Eğer kaynak kodu düzenlemek veya Python üzerinden çalıştırmak isterseniz:

```bash
# 1. Depoyu klonlayın
git clone [https://github.com/mucitemos/TurkPhoto.git](https://github.com/mucitemos/TurkPhoto.git)
cd TurkPhoto

# 2. Gerekli kütüphaneleri yükleyin
pip install PyQt6 numpy

# 3. Uygulamayı konsolsuz başlatın
pythonw main.pyw
