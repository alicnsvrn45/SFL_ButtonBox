# ⚡ SFL ButtonBox — Akıllı & Adaptif Denetim Yazılımı
SFL ButtonBox, bilgisayarınız ile **SFL ButtonBox (Pro, Plus, Lite)** donanımları arasında kesintisiz, akıcı ve otonom bir köprü kuran yeni nesil bir mikser, makro ve kontrol yazılımıdır. 
Gelişmiş koyu tema arayüzü, 5 farklı dil desteği, zırhlı Over-The-Air (OTA) güncelleme motoru ve otonom oyun profili algılayıcısı ile donanımınızın potansiyelini zirveye çıkarır.
---
## ✨ Öne Çıkan Özellikler
### 🔌 1. Tak-Çalıştır ve Otonom Seri İletişim
- **Akıllı Port Keşfi**: COM portunu manuel seçmenize gerek yoktur. Donanım algılama motoru tüm seri portları tarar, cihazı bulur ve otonom el sıkışma (Handshake) protokolüyle saniyeler içinde bağlanır.
- **Kopma Toleransı**: Cihazın USB kablosu çıksa bile yazılım arka planda aramaya devam eder; geri takıldığında ayarlarınız bozulmadan saniyeler içinde otomatik olarak yeniden bağlanır.
- **Donanımsal Uyum**: Cihazınızın modeline göre (Pro, Plus, Lite) tüm buton şemasını ve fiziksel arayüzü (Örn: 3x3 veya 2x5 grid) anında otomatik olarak uyarlar.
### 🎛️ 2. Panel Ses Kontrolleri (Akıllı Mikser)
- **Kanal Atama**: Donanım üzerindeki potansiyometreleri istediğiniz uygulamaya (Spotify, Discord, Tarayıcı vb.) veya sistem ana sesine (`Master Volume`) atayabilirsiniz.
- **Aktif Program Odaklama (Auto-Focus)**: Düğmelerden birini "Aktif Program" moduna alarak, o an ekranda hangi pencere açıksa onun sesini otomatik olarak yönetebilirsiniz.
- **Ses Yumuşatma (Smoothing Filter)**: Donanımdaki potansiyometre aşınmalarını engelleyen ve ani ses zıplamalarını önleyen gelişmiş doğrusal filtreleme.
### ⌨️ 3. Adaptif Tuş Atamaları & Makro Stüdyosu (⚡)
- **Klavye Kısayolları**: Dilediğiniz butona klavyeden herhangi bir tuş kombinasyonunu (Örn: `Ctrl+C`, `F15`, `Ctrl+Shift+T`) atayabilirsiniz.
- **Uygulama Başlatma**: Tek tıkla bilgisayarınızdaki herhangi bir programı (`.exe`) butona atayarak anında açabilirsiniz.
- **Makro Kütüphanesi (Makro Stüdyosu)**: Zincirleme komutlar oluşturabilirsiniz (Örn: *"Kopyala → 100ms Bekle → Yeni Pencere Aç → Yapıştır"*).
- **Oyun Kumandası (Joystick) Modu**: Butonlara atama yapmadığınız sürece cihazınız oyunlarda standart DirectInput Gamepad tuşları olarak çalışır.
### 🎬 4. Canlı Yayıncı Entegrasyonu (OBS & Streamlabs)
- Sunucu adresi ve şifrenizle **OBS Studio** veya **Streamlabs Desktop** yazılımlarına doğrudan bağlanabilirsiniz.
- Tek tuşla sahne değiştirme, yayını/kaydı başlatıp durdurma, mikrofonu susturma (Mute) veya tekrar oynatma (Replay Buffer) tetiklemelerini gerçekleştirebilirsiniz.
### ⚡ 5. Sistem Ayarları & Otomasyon
- **Windows Başlangıcı**: Windows açıldığında ButtonBox arka planda hazır bekler.
- **Tepsiye Küçült**: Pencereyi kapatsanız dahi sistem saatinin yanında (System Tray) çalışmaya ve ses/makroları kontrol etmeye devam eder.
- **Otonom Profil Değiştirici (Auto-Profile)**: Oynadığınız aktif oyunu (Örn: ETS2, CS2, Assetto Corsa) otomatik algılar ve o oyuna ait tuş profilini anında devreye alır.
- **Kalibrasyon Sihirbazı**: Fiziksel aşınmalar nedeniyle 0'a veya 100'e ulaşamayan potansiyometreleri kalibre edebilmeniz için gelişmiş kalibrasyon stüdyosu.
---
## 🌎 5 Dil Desteği
Arayüz ve tüm kullanım rehberleri dil seçiminize göre anında adapte olur:
* 🇹🇷 Türkçe (TR)
* 🇬🇧 English (EN)
* 🇷🇺 Русский (RU)
* 🇩🇪 Deutsch (DE)
* 🇵🇱 Polski (PL)
---
## 📦 Kurulum ve Çalıştırma Kılavuzu
SFL ButtonBox'ı bilgisayarınıza kurup çalıştırmak son derece basittir:
### 📥 1. Adım: Kurulum Dosyasını İndirin
1. Bu GitHub deposunun ana sayfasında yer alan **`SFL_ButtonBox_v1.1.0_Setup.exe`** dosyasına tıklayın.
2. Sayfadaki **"Download"** butonuna basarak kurulum dosyasını bilgisayarınıza indirin.
### 🛠️ 2. Adım: Kurulumu Gerçekleştirin
1. İndirdiğiniz `SFL_ButtonBox_v1.1.0_Setup.exe` dosyasına çift tıklayarak çalıştırın (Yazılım kurulumu ve Windows kısayollarını otomatik hazırlar).
2. Kurulum sihirbazındaki yönergeleri takip ederek kurulumu tamamlayın.
3. Masaüstünde veya Başlat menüsünde oluşan **SFL ButtonBox** kısayoluna tıklayarak uygulamayı başlatın.
### 🔌 3. Adım: Cihazınızı Bağlayın
1. SFL ButtonBox donanımınızı USB kablosu ile bilgisayarınıza bağlayın.
2. Yazılım, cihazınızı otomatik olarak algılayacak, el sıkışmayı yapacak ve ekranın sol alt tarafında yeşil renkli **"Bağlantı Başarılı!"** uyarısı belirecektir.
3. *Not:* Eğer bilgisayarınız cihazı hiç algılamazsa, Ayarlar sekmesindeki **"Entegre Sürücüleri (CH340) Kur"** butonuna basarak gerekli USB seri port sürücüsünü saniyeler içinde yükleyebilirsiniz.
---

## 📷 Subakan 3D Design
Bu proje donanım ve kutu tasarımlarıyla **Subakan 3D Design** tarafından hayata geçirilmiştir. Güncel donanım modelleri ve 3D tasarımlar için resmi Instagram hesabımızı ziyaret edebilirsiniz:
👉 [subakan 3d design Instagram](https://www.instagram.com/subakan3ddesign/)
