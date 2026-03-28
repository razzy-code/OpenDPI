🚀 Genel Bakış

OpenDPI, gelişmiş Derin Paket İncelemesi (DPI) atlatma teknolojileri ile internet sansürünü aşmanıza ve ağ performansınızı optimize etmenize olanak tanıyan profesyonel bir ağ güvenlik yazılımıdır.

Temel Amacımız:

İnternet erişim özgürlüğünü korumak

Ağ performansını maksimuma çıkarmak

Kullanıcı gizliliğini garanti altına almak

Kararlı ve güvenilir bağlantı sağlamak

Erişim engeli olan sitelere güvenli bir şekilde girebilmek

⭐ Özellikler

Gelişmiş DPI Atlatma ve Ağ Güvenliği

Paket parçalama ve TTL manipülasyonu ile internet sansürünü aşın

Protokol taklidi ve özel paket oluşturma

Çok katmanlı şifreleme (256-bit SSL)

Yüksek Performans & Akıllı Optimizasyon

Gerçek zamanlı bağlantı analizi ve adaptif ağ ayarları

Otomatik en iyi atlatma metodunun seçimi

Minimum gecikme ve maksimum hız

Gizlilik ve Güvenlik

DNS ve IPv6 sızıntı koruması

Kill Switch ile bağlantı kesildiğinde veri sızıntısını engelleme

Log tutmayan gizlilik odaklı politika

Kolay Kullanım

Tek tıkla Discord ve diğer engellenmiş sitelere erişim

Kullanıcı dostu arayüz

🚀 Yeni: Nevo AI – Yeni Nesil Yapay Zeka DPI Motoru

Nevo AI, OpenDPI'ın gelecek nesil yapay zeka destekli DPI atlatma motorudur. Gelişmiş makine öğrenimi algoritmaları ile ISP'lerin DPI sistemlerini gerçek zamanlı analiz eder, en etkili atlatma stratejisini otomatik seçer ve sisteminizi arka planda sessizce korur.

Temel Özellikler:

Akıllı DPI Değiştirici: ISP’nizin DPI konfigürasyonunu milisaniyeler içinde analiz eder ve en etkili atlatma stratejisini uygular.

Sunucuyla Doğrudan Bağlantı: AES-256 şifreli bağlantı ile en güncel DPI imzalarını anlık olarak alır.

Arka Planda Sessiz Çalışma: nevo-ai.exe Windows servis olarak çalışır, CPU kullanımı %0.1’in altında.

Otomatik Veri Sızıntısı Engelleme: DNS, WebRTC ve IP sızıntılarını engeller, Kill Switch ile güvenlik sağlar.

Adaptif Performans Motoru: Ağ koşullarına göre MTU, TTL ve fragmentasyon stratejilerini otomatik ayarlar.

Sıfır Konfigürasyon: Kurulum sonrası hiçbir teknik ayar yapmaya gerek yoktur.

Teknik Detaylar:

OSI modeli 3., 4. ve 7. katmanlarda çok katmanlı analiz

Gerçek zamanlı model güncelleme ve ISP parmak izi tanıma

Milisaniye seviyesinde DPI atlatma tepkisi (<3ms)

Oturum bazlı öğrenme ve performans metrikleri toplama

Çalışma Mantığı:

OpenDPI açıldığında Nevo AI arka planda başlar ve OpenDPI sunucularına güvenli bağlantı kurar.

Güncel DPI imza veritabanı ve model parametrelerini indirir, ISP’ye özel model yükler.

Ağ trafiğini WinDivert ile yakalar, engellenen paketleri anlık olarak yeniden yapılandırır.

Anonim performans verilerini toplar ve sonraki oturumlarda modeli iyileştirir.

Gizlilik Taahhüdü:

Nevo AI sizi izlemez, kişisel veri toplamaz veya üçüncü taraflarla paylaşmaz.

Sadece DPI engellerini aşmak için çalışır, normal trafiğinize dokunmaz.

Trafiğiniz hiçbir üçüncü taraf sunucusuna gitmez.

🔑 Lisans Alma ve Etkinleştirme

Lisans Nasıl Alınır?

Admin ile iletişime geçin:

Instagram: @opendpi

E-posta: nebisaylancode@gmail.com

Lisans Nasıl Etkinleştirilir?

Lisans türünü belirleyin

Admin’den lisans anahtarınızı alın

OpenDPI’ı açın, anahtarı girerek etkinleştirin

💻 Sistem Gereksinimleri

Asgari Gereksinimler (Temel Çalışma)

OS: Windows 10/11 (64-bit)

İşlemci: 1 GHz veya daha hızlı

RAM: 700 MB (pluginler dahil)

Depolama: 600 MB – 1 GB boş alan

Ağ: İnternet bağlantısı

.NET Framework: 4.8 veya üzeri

Önerilen Gereksinimler (En İyi Performans)

OS: Windows 11 (64-bit)

İşlemci: 2 GHz çift çekirdek veya üzeri

RAM: 1 GB+

Depolama: 1 GB+ boş alan

Ağ: Stabil internet bağlantısı

.NET Framework: 4.8 veya üzeri

⚠️ Windows 7 ve 8/8.1 desteği kesilmiştir.

📥 Kurulum Rehberi

İndirin: OpenDPI-Setup.exe (≈800 MB)

Çalıştırın: Çift tıklayın, Windows SmartScreen uyarısına “Yine de çalıştır” deyin

Kurulum Sihirbazını Takip Edin: Adımları takip edin, gerekli izinleri onaylayın

Programı Başlatın: Masaüstü kısayolundan OpenDPI’ı açın

Program, otomatik olarak en uygun DPI atlatma metodunu seçer. Discord ve diğer engellenmiş sitelere erişim sağlanır.

🛡️ Antivirüs Uyarıları (False Positive)

OpenDPI bazı antivirüsler tarafından yanlışlıkla zararlı olarak algılanabilir.

Neden: Code signing sertifikası yok, WinDivert kütüphanesi ağ paketlerini yönlendiriyor, obfuscation kullanılmıştır.

VirusTotal Özet: 9/72 heuristik tespit, tümü false positive.

🗂️ OpenDPI Bileşenleri

OpenDPI.exe – Ana uygulama, tüm DPI ayarları ve DNS koruması

updater.exe – Otomatik güncelleme

nevo-ai.exe – Yeni  nesil  yapay zeka DPI motoru

opendpi-service.exe – Arka plan servis, DNS koruması

game.exe – Mini oyun (internet yokken eğlence)