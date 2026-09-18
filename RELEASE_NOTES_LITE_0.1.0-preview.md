# Screen Awake Lite 0.1.0-preview

## RU

- Первый отдельный preview-релиз облегчённой редакции Screen Awake.
- Package ID: `com.kroxaboom.screenawake.lite`; Lite можно установить рядом с основной версией.
- Оставлены только базовые функции: удержание экрана, безопасное восстановление исходного тайм-аута, управление из уведомления и Quick Settings.
- Сохранён безопасный двухшаговый механизм обновления: приложение скачивает и проверяет APK, а установку пользователь подтверждает в системном установщике Android.
- Статистика использования, экран диагностики и анонимная телеметрия в Lite отсутствуют.
- Используется тот же собственный Core, что и в основной редакции, без копирования общей логики.
- Сторонние runtime-библиотеки отсутствуют.

## EN

- First standalone preview release of the lightweight Screen Awake edition.
- Package ID is `com.kroxaboom.screenawake.lite`, so Lite can be installed alongside the main edition.
- Lite contains only the core features: keep-awake mode, safe original-timeout restoration, notification control and Quick Settings control.
- The verified two-step updater is retained: the app downloads and validates the APK while Android's system installer handles user-confirmed installation.
- Usage statistics, diagnostics UI and anonymous telemetry are not included in Lite.
- Lite shares the same first-party Core as the main edition instead of duplicating the common implementation.
- No third-party runtime libraries are included.
