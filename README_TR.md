# Birkan AI Mouse — ilk Android prototipi

Bu paket bir Android Studio/Gradle kaynak projesidir; **hazır APK değildir**.

## Bu prototipte olanlar
- Türkçe başlangıç ekranı
- USB klavyeden tuş olayı algılama (uygulama açıkken)
- USB modu ve dokunmatik mod ekranları
- M416, AKM, AUG, UMP45 ve Scar-L profili seçimi
- Kullanıcının girdiği dikey/yatay test değerlerinden basit hassasiyet önerisi

## Henüz olmayanlar
- PUBG Mobile üzerinde otomatik tuş eşleme veya dokunma enjeksiyonu
- Oyunun üstünde çalışan overlay
- Video/kamera görüntüsünden gerçek AI spray takibi
- Otomatik recoil kontrolü veya sıfır sekme

Bu işlevler Android/oyun izinleri ve oyun kuralları bakımından ayrıca değerlendirilmelidir. Bu uygulama hile, otomatik ateş veya recoil makrosu içermez.

## APK üretimi
`.github/workflows/build-apk.yml` GitHub Actions ile bulutta debug APK derlemek için eklenmiştir. Projeyi bir GitHub deposuna yükleyip Actions sekmesinden `Build Android APK` iş akışını çalıştırabilirsin. APK, başarılı derleme sonrası Artifacts bölümünden alınır.

## Gereksinimler
- Android SDK compileSdk 35
- JDK 17
- Android Gradle Plugin 8.7.3
