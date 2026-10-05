# DersTakip Android

Bu proje mevcut DersTakip web uygulamasını Android WebView içinde çalıştırır.

## Android Studio ile APK oluşturma
1. Android Studio'yu açın.
2. `DersTakip-Android` klasörünü Open ile açın.
3. Gradle Sync tamamlanmasını bekleyin.
4. `Build > Build APK(s)` seçin.
5. APK `app/build/outputs/apk/debug/app-debug.apk` altında oluşur.

Uygulama verileri WebView localStorage üzerinde cihazda tutulur. Dosya seçme alanları Android dosya seçicisini kullanır.

## Android Studio olmadan APK
GitHub Actions iş akışı `.github/workflows/build-apk.yml` ile otomatik APK derler. GitHub'da Actions sekmesinden workflow'u çalıştırıp Artifacts bölümünden APK'yı indirebilirsiniz.
