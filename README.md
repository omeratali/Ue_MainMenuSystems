# Ue_MainMenuSystems 

Ue_MainMenuSystems, Unreal Engine projeleri için geliştirilmiş, modüler ve kolay entegre edilebilir bir Ana Menü sistemidir.

Bu proje, oyun geliştiricilerin sıfırdan bir menü sistemi yazmakla zaman kaybetmeden, oyunlarının temel arayüz ihtiyaçlarını (Başlat, Ayarlar, Çıkış vb.) hızlıca karşılamayı amaçlar.

#Özellikler

* **Ana Menü:** Oyuna Başla, Ayarlar, Jenerik (Credits) ve Çıkış butonları.
* **Ayarlar Menüsü:**
    * Grafik Ayarları: Çözünürlük, Kalite (Düşük/Orta/Yüksek), Pencere Modu.
    * ses Ayarları: Ana Ses, Müzik ve Efekt ses kontrolleri.
* Oyun İçi Durdurma (Pause) Menüsü: Oyuna geri dönme veya ana menüye dönme seçenekleri.
* Kolay Özelleştirme:** Widget Blueprint (UMG) tabanlıdır, renkler ve fontlar kolayca değiştirilebilir.


#Kurulum

1.  Bu repoyu bilgisayarınıza indirin veya `clone` yapın:
    ```bash
    git clone [https://github.com/omeratali/Ue_MainMenuSystems.git](https://github.com/omeratali/Ue_MainMenuSystems.git)
    ```
2.  Proje klasöründeki `Content` klasörünü kendi Unreal Engine projenizin `Content` klasörüne kopyalayın (Migrate işlemi de yapabilirsiniz).
3.  Unreal Engine editöründe `Project Settings > Maps & Modes` kısmına gidin.
4.  Varsayılan `GameInstance` ve `HUD` sınıflarını bu paketteki sınıflarla değiştirin.

# Kullanım

* Menüyü projenize dahil ettikten sonra `WBP_MainMenu` dosyasını açarak tasarımı kendi oyununuzun temasına göre düzenleyebilirsiniz.
* Butonların `OnClicked` eventlerini kendi oyun mantığınıza (örneğin "Level Aç") bağlamayı unutmayın.

#Gereksinimler

* **Unreal Engine Sürümü:** 5.3.2 ve üzeri (veya senin kullandığın sürüm neyse onu yaz)
* **Dil:** Blueprint


---
