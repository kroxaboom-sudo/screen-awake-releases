# Screen Awake 0.1.16-preview

## RU

- Внедрён канонический COMMON-UPDATER-01: после полной проверки APK обновление передаётся Android PackageInstaller.
- Перед установкой проверяются размер, SHA-256, package ID, versionCode/versionName, minSdk и сертификат подписи.
- Если для Screen Awake не разрешена установка из этого источника, приложение открывает системный экран разрешения и продолжает после возврата.
- Финальное подтверждение установки всегда выполняется системным интерфейсом Android; тихая установка не используется.
- Автопроверка обновлений включена по умолчанию. Автоскачивание и автоматический вызов системного подтверждения — отдельные opt-in настройки.
- Включение автоматического вызова установщика автоматически включает проверку и скачивание; повторные запросы ограничены cooldown.
- Системные «Загрузки» и ссылка «Открыть релизы» сохранены как резервные пути.
- Добавлена безопасная координация Full ↔ Lite: одновременно системным screen_off_timeout владеет только одна редакция.
- Coordination provider принимает команды только от APK с той же подписью Screen Awake.

## EN

- Added canonical COMMON-UPDATER-01: after full APK validation, updates are handed to Android PackageInstaller.
- APK size, SHA-256, package ID, versionCode/versionName, minSdk and signing certificate are verified before installation.
- If Screen Awake is not allowed to install from this source, the app opens Android's system permission screen and resumes after return.
- Final installation confirmation always stays in Android's system UI; silent installation is not used.
- Automatic update checks default On. Verified auto-download and automatic installer prompting are separate opt-in settings.
- Enabling installer prompting also enables checking and downloading; repeated prompts are cooldown-limited.
- System Downloads and the Open releases link remain available as fallback paths.
- Added safe Full ↔ Lite coordination so only one edition owns the system screen_off_timeout at a time.
- The coordination provider accepts commands only from APKs signed with the same Screen Awake certificate.
