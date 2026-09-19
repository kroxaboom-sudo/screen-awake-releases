# Screen Awake releases

Официальные сборки Screen Awake для Android 13+.

## Редакции

### Screen Awake

Основная редакция с общим Core, расширенной локальной диагностикой и статистикой, а также единым Observability Core.

<!-- FULL_CURRENT_START -->
**Full: 0.1.16-preview** (`versionCode 17`)  
APK: `Screen-Awake-0.1.16-preview.apk`
<!-- FULL_CURRENT_END -->

Package ID: `com.kroxaboom.screenawake`
Канал обновлений: `latest.json`

### Screen Awake Lite

Облегчённая редакция: общий Core, удержание экрана, восстановление тайм-аута, уведомление, Quick Settings, безопасные обновления и тот же обязательный Observability Core. Минимальная ESSENTIAL-диагностика работает по общим правилам приватности, EXTENDED управляется пользователем; Full-only экраны подробной диагностики и локальной статистики не включаются.

<!-- LITE_CURRENT_START -->
**Lite: 0.1.7-preview** (`versionCode 8`)  
APK: `Screen-Awake-Lite-0.1.7-preview.apk`
<!-- LITE_CURRENT_END -->

Package ID: `com.kroxaboom.screenawake.lite`
Канал обновлений: `latest-lite.json`

Обе редакции можно устанавливать одновременно. APK публикуются с SHA-256 и проходят Android Lint и smoke-матрицу Android 13 / 14 / 15 / 16.

## English

Screen Awake is distributed in two independently installable Android 13+ editions. Both use the shared first-party Core and the same mandatory Observability Core with ESSENTIAL diagnostics and user-controlled EXTENDED data. Full additionally includes detailed local diagnostics and usage statistics; Lite excludes those Full-only screens. Each edition has its own package ID, update feed, release tags and verified APKs.
