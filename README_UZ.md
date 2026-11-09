# ASADBEK CARAZERIA — Android loyiha v0.2

## Ushbu versiyada
- Kotlin asosidagi Android ilova.
- Telefon xotirasidan audio fayl tanlash va player ichida ijro etish.
- Qurilma qo‘llab-quvvatlasa Android Equalizer, BassBoost, Virtualizer va PresetReverb effektlari.
- STUDIO, POP, JAZZ, CLUB, CONCERT HALL va CHURCH presetlari.
- 31 chastota nuqtali boshqaruv interfeysi. Eslatma: Android qurilmasining haqiqiy Equalizer bandlari soni model/DSP ga bog‘liq; 31 nuqta mavjud bandlarga moslanadi, bu barcha telefonlarda haqiqiy 31 mustaqil DSP band bor degani emas.
- Animatsiyali delfinlar va CAR AUDIO vizual paneli.
- Samsung Galaxy A13 / Android 14 uchun mo‘ljallangan (qurilma DSP imkoniyatlari farq qilishi mumkin).

## Muhim cheklov
Oddiy Android ilovasi boshqa ilovalarning ovozini global tarzda o‘zgartira olmaydi. Bu versiya o‘z playeri ichida ijro etilayotgan musiqaga effekt beradi. SYSTEM SOUND rejimi uchun ishlab chiqaruvchi darajasidagi ruxsat yoki maxsus firmware/root integratsiyasi talab qilinishi mumkin.

## APK yig‘ish
1. Kompyuterga Android Studio o‘rnating.
2. ZIP arxivni oching va `AsadbekCarazeria` papkasini Android Studio orqali oching.
3. Gradle Sync tugashini kuting (internet kerak bo‘lishi mumkin).
4. `Build > Build Bundle(s) / APK(s) > Build APK(s)` ni tanlang.
5. APK: `app/build/outputs/apk/debug/app-debug.apk`.

`compileSdk 35`, `minSdk 23`, `targetSdk 35`; Gradle plugin 8.7.3 va Kotlin plugin 2.0.21.

## Kompyutersiz bulutda APK yig‘ish (GitHub Actions)
Loyihada `.github/workflows/android.yml` avtomatik build fayli ham bor. ZIPni GitHub'da yangi repositoryga yuklab, `Actions` bo‘limidan `Build ASADBEK CARAZERIA APK` ishini `Run workflow` bilan ishga tushirish mumkin. Build tugagach `ASADBEK-CARAZERIA-debug-apk` nomli Artifact ichidan APK olinadi. GitHub akkaunti va internet talab qilinadi.
