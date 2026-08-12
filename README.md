# 🏫 Matbu Veli Dilekçeleri Uygulaması

Okul idareleri ve veliler için tasarlanmış, kurulum veya sunucu gerektirmeyen (serverless), e-Okul süreçleriyle uyumlu ve doğrudan tarayıcı üzerinden çalışan tek sayfalık (Single-Page) matbu dilekçe oluşturucu. 

Bu araç sayesinde veliler; Kayıt, Nakil, İsteğe Bağlı Kayıt, Kayıt Erteleme ve Sınıf Tekrarı gibi resmi dilekçeleri kolayca dijital ortamda doldurabilir ve tek tıkla A4 formatında kusursuz bir çıktı alabilirler. İster bilgisayarda ister mobil cihazlarda (iOS/Android) yerel bir dosya olarak internetsiz dahi çalıştırılabilir.

## 🚀 Canlı Önizleme
Uygulamayı hemen kullanmaya başlamak için tıklayın:
👉 **[Veli Dilekçeleri - Canlı Demo](https://mhmtsk44.github.io/veli-dilekceleri/)**

## ✨ Öne Çıkan Özellikler

* **Tamamen İstemci Taraflı ve Çevrimdışı (Offline):** Hiçbir veritabanı veya arka plan (backend) sunucusu kullanmaz. İnternet bağlantısı olmasa bile tüm formül ve algoritmalar tarayıcınızda lokal olarak çalışır.
* **KVKK Uyumlu Temiz Şablon Kaydetme:** Kullanıcılar kendi okullarının adını girip "Kaydet" butonuna bastığında; sistem formdaki T.C. Kimlik, telefon ve isim gibi kişisel verileri **otomatik olarak temizler** ve bilgisayara/telefona kişiselleştirilmiş ancak veriden arındırılmış temiz bir şablon (`.html`) indirir.
* **Akıllı Doğrulama ve QR Kod Entegrasyonu:** T.C. Kimlik numaraları resmi 11 haneli matematiksel algoritmaya göre anlık doğrulanır ve geçerli bir numara girildiğinde anında sayfanın köşesine bir **Karekod (QR Code)** üretilir. Telefon numaraları otomatik olarak `05xx xxx xx xx` formatına çevrilir.
* **Baskı (Print) Optimizasyonu:** Ekranda kullanıcı dostu bir form olarak görünürken, yazdırıldığında (`Ctrl+P` veya Yazdır butonu) tüm arayüz elementleri (butonlar, sekmeler, renkler, geçersiz uyarıları) gizlenir. Yerini MEB standartlarına uygun, A4 boyutuna tam oturan resmi bir evrak alır.
* **Veri Güdümlü Şablon (DRY Prensibi):** Dilekçe metinleri statik HTML yığını yerine, JavaScript tabanlı modüler bir mimariyle (`AYARLAR` ve `DILEKCELER` objeleri) oluşturulur. Gelecek eğitim-öğretim yıllarında tarihleri güncellemek sadece birkaç saniye sürer.

## 💻 Teknolojiler

* HTML5
* CSS3 (CSS Variables, Flexbox, Print Media Queries)
* Vanilla JavaScript (ES6+)
* QRious (Açık kaynaklı, yerel QR kod üretici)

---
*Mehmet IŞIK tarafından eğitim kurumlarının idari süreçlerini hızlandırmak amacıyla açık kaynak kodlu olarak geliştirilmiştir.*
