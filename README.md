# 🚗 Hasar Dosyası Açma Asistanı

[![Canlı Önizleme](https://img.shields.io/badge/Canlı_Önizleme-Tıklayın-blue?style=for-the-badge&logo=github)](https://efekanerdogan.github.io/sigortaasistan/)

Kaporta servisleri, sigorta acenteleri ve eksperler için tasarlanmış, manuel veri girişi hamallığını ortadan kaldıran ve operasyonel hızı artıran dinamik hasar dosyası yönetim aracı.

Şu anki versiyon, hızlı kullanım ve yerel veri güvenliği (Local Storage) odaklı bir MVP (Minimum Viable Product) olarak çalışmaktadır.

## ⚡ Özellikler

* **Dinamik Form Yönetimi:** Mağdur, vuran ve sigorta detaylarının tek bir ekranda, birbirine entegre (örn. Sürücü ile Ruhsat Sahibi aynıysa otomatik doldurma) şekilde yönetimi.
* **İnteraktif Hasar Çizimi:** Araç üzerindeki hasarlı bölgelerin (kaput, tavan, kapılar vb.) SVG tabanlı interaktif bir harita üzerinde tıklanarak işaretlenmesi.
* **Gelişmiş Dashboard & Analitik:** Kayıtlı dosyaların finansal hacmi, aylık/yıllık bazda filtreleme ve sigorta/eksper dağılımı gibi metriklerin anlık takibi.
* **Hızlı Arama ve Filtreleme:** Plaka, dosya no veya isim üzerinden saniyeler içinde eski kayıtlara ulaşma.
* **PDF Çıktı & Yedekleme:** Profesyonel rapor görünümüyle PDF yazdırma ve verileri istenildiğinde JSON formatında dışa/içe aktarma.

## 🛠 Kullanılan Teknolojiler

* **HTML5 & CSS3:** Semantik yapı ve modern tasarım prensipleri.
* **Tailwind CSS:** Hızlı, mobil uyumlu ve modern arayüz (UI) inşası.
* **Vanilla JavaScript (ES6+):** Herhangi bir kütüphaneye bağlı kalmadan saf ve yüksek performanslı DOM manipülasyonu, form doğrulama ve state yönetimi.
* **SVG (Scalable Vector Graphics):** Çözünürlükten bağımsız, tıklanabilir interaktif araç hasar haritası.
* **LocalStorage API:** Veritabanı maliyeti olmadan tarayıcı tabanlı hızlı veri kalıcılığı.

## 🚀 Kurulum ve Kullanım

Herhangi bir sunucu kurulumuna, npm paketine veya derleme işlemine ihtiyaç yoktur. Sıfır bağımlılık prensibiyle çalışır.

1.  Projeyi bilgisayarınıza klonlayın:
```bash
    git clone [https://github.com/efekanerdogan/sigortaasistan.git](https://github.com/efekanerdogan/sigortaasistan.git)
    ```
2.  Klasörün içindeki `index.html` dosyasını tercih ettiğiniz bir modern tarayıcıda (Chrome, Safari, Edge vb.) açın.
3.  Uygulama hemen kullanıma hazırdır. (Veya doğrudan [canlı önizleme](https://efekanerdogan.github.io/sigortaasistan/) linki üzerinden projeyi test edebilirsiniz.)

## 🗺 Yol Haritası (Gelecek Vizyonu)

Bu proje, gelecekte bir B2B SaaS (Hizmet Olarak Yazılım) ürününe dönüşmek üzere ölçeklenebilir bir temelde inşa edilmektedir. Planlanan güncellemeler:

- [ ] **Backend Entegrasyonu:** Supabase/Firebase ile bulut tabanlı, çoklu kullanıcı destekli (Auth) veri yönetimi.
- [ ] **OCR Otomasyonu:** Ehliyet ve ruhsat fotoğraflarından optik karakter tanıma ile formların saniyeler içinde otomatik doldurulması.
- [ ] **Plaka & Araç API:** Plaka girildiğinde marka/model/yıl bilgilerinin devlet veya sigorta servislerinden anlık çekilmesi.
