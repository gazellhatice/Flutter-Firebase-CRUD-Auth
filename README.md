# Flutter Firebase CRUD Auth

Bu proje, Flutter ve Firebase kullanılarak geliştirilmiş bir mobil uygulamadır. Uygulama kullanıcı kimlik doğrulama işlemlerini (kayıt, giriş) ve Firebase Firestore üzerinde CRUD (Create, Read, Update, Delete) işlemlerini gerçekleştirebilmektedir.

## 🚀 Özellikler

- Firebase Authentication ile kullanıcı kayıt ve giriş
- Firestore veritabanı ile veri ekleme, okuma, güncelleme ve silme
- Kullanıcı dostu ve modern Flutter arayüzü
- Gerçek zamanlı veri takibi
- Responsive tasarım

## 🛠️ Kurulum Adımları

1. Bu repoyu klonlayın:
   ```bash
   git clone https://github.com/gazellhatice/Flutter-Firebase-CRUD-Auth.git
   ```

2. Proje dizinine girin:
   ```bash
   cd Flutter-Firebase-CRUD-Auth
   ```

3. Gerekli Flutter paketlerini yükleyin:
   ```bash
   flutter pub get
   ```

4. Firebase kurulumunu yapın:
   - Firebase Console üzerinden bir proje oluşturun.
   - Android için: `google-services.json` dosyasını `android/app/` klasörüne yerleştirin.
   - iOS için: `GoogleService-Info.plist` dosyasını `ios/Runner/` klasörüne ekleyin.
   - `android/build.gradle` ve `android/app/build.gradle` dosyalarında Firebase yapılandırmalarını tamamlayın.

5. Uygulamayı çalıştırın:
   ```bash
   flutter run
   ```

## 📁 Proje Yapısı

```
lib/
├── models/
├── services/
├── screens/
├── widgets/
├── main.dart
```

## 📸 Ekran Görüntüleri

Uygulama arayüzüne ait ekran görüntüleri `Assets/Images/` klasöründe yer almaktadır.

## 🧩 Kullanılan Teknolojiler

- Flutter
- Firebase Authentication
- Firebase Firestore
- Dart

## 📝 Lisans

Bu proje [Apache License 2.0](LICENSE) ile lisanslanmıştır.

---

👩‍💻 Geliştirici: Hatice Gazel  
📫 GitHub: [@gazellhatice](https://github.com/gazellhatice)
