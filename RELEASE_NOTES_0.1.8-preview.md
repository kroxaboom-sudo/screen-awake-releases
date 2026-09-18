# Screen Awake 0.1.8-preview

## RU

- Механизм обновления приведён к проверенной схеме из Skazka Hub.
- Добавлен единый Download Core для загрузки APK: HTTPS, проверяемые перенаправления, повторы, прогресс, временный файл и безопасное завершение.
- Screen Awake теперь сам скачивает APK вместо перехода на GitHub для ручного скачивания.
- Перед установкой проверяются размер, SHA-256, package ID, versionCode/versionName, minSdk и сертификат подписи установленного приложения.
- После успешной проверки появляется отдельная кнопка «Установить обновление».
- Установка никогда не запускается автоматически: пользователь нажимает кнопку, после чего APK передаётся системному установщику Android.
- Если Android ещё не разрешил установку из Screen Awake, приложение открывает соответствующую системную настройку и просит пользователя вернуться и снова нажать «Установить обновление».
- PackageInstaller sessions и тихая/фоновая установка не используются.
- UpdateProvider закрыт от внешнего доступа и выдаёт системному установщику только один заранее проверенный APK.
- Сохранены локальная статистика и все функции 0.1.7-preview.
- Сторонние runtime-библиотеки не добавлены.

## EN

- The updater now follows the already proven Skazka Hub flow.
- Added a canonical Download Core for APK transfer: HTTPS, validated redirects, retries, progress, temporary files and safe completion.
- Screen Awake downloads the APK itself instead of sending the user to GitHub for manual download.
- Before installation, the app validates size, SHA-256, package ID, versionCode/versionName, minSdk compatibility and the installed-app signing certificate.
- After verification, a separate Install update button becomes available.
- Installation never starts automatically: the user taps Install, then Android's system installer takes over.
- If install-from-app permission is not yet granted, Screen Awake opens the relevant Android settings page and requires the user to return and tap Install again.
- No PackageInstaller sessions or silent/background installation are used.
- UpdateProvider is non-exported and exposes only the single verified APK to the system installer.
- Local statistics and all 0.1.7-preview functionality are retained.
- No third-party runtime libraries were added.
