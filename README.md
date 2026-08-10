# 🏫 Matbu Veli Dilekçeleri Uygulaması

Okul idareleri ve veliler için tasarlanmış, kurulum veya sunucu gerektirmeyen (serverless), doğrudan tarayıcı üzerinden çalışan tek sayfalık (Single-Page) matbu dilekçe oluşturucu. 

Bu araç sayesinde veliler; Kayıt, Nakil, İsteğe Bağlı Kayıt, Kayıt Erteleme ve Sınıf Tekrarı gibi resmi dilekçeleri kolayca dijital ortamda doldurabilir ve tek tıkla A4 formatında kusursuz bir çıktı alabilirler.

## 🚀 Canlı Önizleme
Uygulamayı hemen kullanmaya başlamak için tıklayın:
👉 **[Veli Dilekçeleri - Canlı Demo](https://mhmtsk44.github.io/veli-dilekceleri/)**

## ✨ Öne Çıkan Özellikler

* **Tamamen İstemci Taraflı (Client-side):** Hiçbir veritabanı veya arka plan (backend) sunucusu kullanmaz. Girilen tüm T.C. Kimlik, adres ve telefon bilgileri yalnızca kullanıcının tarayıcısında kalır, %100 veri güvenliği sağlar.
* **Akıllı Doğrulama (Validation):** T.C. Kimlik numaraları resmi 11 haneli matematiksel algoritmaya göre anlık doğrulanır. Telefon numaraları otomatik olarak `05xx xxx xx xx` formatına çevrilir.
* **Baskı (Print) Optimizasyonu:** Ekranda kullanıcı dostu bir form olarak görünürken, yazdırıldığında (`Ctrl+P` veya Yazdır butonu) tüm arayüz elementleri (butonlar, sekmeler, renkler) gizlenir. Yerini MEB standartlarına uygun, A4 boyutuna tam oturan resmi bir evrak alır.
* **Veri Güdümlü Şablon (DRY Prensibi):** Dilekçe metinleri statik HTML yığını yerine, JavaScript tabanlı modüler bir mimariyle (`AYARLAR` ve `DILEKCELER` objeleri) oluşturulur.
* **Kalıcı İndirme Özelliği:** Kullanıcılar formu doldurduktan sonra, girilen verilerle birlikte tek bir `.html` dosyası olarak bilgisayarlarına veya telefonlarına kaydedebilirler.

## ⚙️ Kurulum ve MEB Sitelerine Entegrasyon

Herhangi bir sunucu kurulumuna gerek yoktur. `index.html` dosyasını tarayıcıda açmak yeterlidir. 

**Okul Web Sitelerinde (meb.k12.tr) Kullanımı:**
Güvenlik kısıtlamalarından dolayı bu kodu MEB paneline doğrudan metin olarak yapıştırmayın. Bunun yerine GitHub Pages linkini (yukarıdaki canlı önizleme linki) MEB sitenizin "Bağlantılar" veya "Duyurular" bölümüne dış link (URL) olarak ekleyebilirsiniz. Bu sayede iOS/iPhone cihazlardaki (QuickLook) JavaScript kısıtlamalarını da aşmış olursunuz.

## 💻 Teknolojiler

* HTML5
* CSS3 (CSS Variables, Flexbox, Print Media Queries)
* Vanilla JavaScript (ES6+)

---
*Mehmet IŞIK tarafından eğitim kurumlarının idari süreçlerini hızlandırmak amacıyla açık kaynak kodlu olarak geliştirilmiştir.*
