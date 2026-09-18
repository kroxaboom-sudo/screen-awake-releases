# Screen Awake Lite 0.1.1-preview

## Русский

- Lite переведён на тот же обязательный Observability Core, что и Full — без урезаний правил приватности, диагностики или согласия.
- Добавлен экран «Данные и диагностика»: ESSENTIAL, EXTENDED Да/Нет, состояние очереди и последней отправки.
- EXTENDED по умолчанию выключен и не может быть удалённо включён сервером.
- Добавлена минимальная диагностика запуска, crash/ANR, разрешений, восстановления режима и update funnel.
- Сохранены все общие функции Core: уведомление, Quick Settings, восстановление после reboot/package replace и безопасное двухшаговое обновление.
- Full-only Diagnostics/Statistics/legacy Telemetry классы физически не включены в Lite APK.
- Сторонние runtime-библиотеки и telemetry SDK не используются.

## English

- Lite now uses the same mandatory Observability Core as Full, with no reduced privacy, diagnostics or consent rules.
- Added Data and diagnostics with ESSENTIAL transparency, EXTENDED Yes/No, queue state and last-delivery status.
- EXTENDED is Off by default and cannot be remotely enabled by the server.
- Added minimal startup, crash/ANR, permission, recovery and update-funnel diagnostics.
- All shared Core functions remain: notification control, Quick Settings, reboot/package-replace recovery and secure two-step updates.
- Full-only Diagnostics/Statistics/legacy Telemetry classes remain physically absent from the Lite APK.
- No third-party runtime libraries or telemetry SDKs are included.
