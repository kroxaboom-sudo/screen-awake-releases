# Screen Awake 0.1.10-preview

## Русский

- Внедрён единый собственный Observability Core по правилам GLOBAL-OBS-01…04.
- Full и Lite используют одинаковые ESSENTIAL/EXTENDED, локальную ограниченную очередь, Privacy allowlist, удалённый kill-switch и единый HOSTKEY endpoint.
- Добавлен общий экран «Данные и диагностика» с прозрачным описанием ESSENTIAL, переключателем расширенной диагностики и состоянием очереди/доставки.
- EXTENDED по умолчанию выключен; удалённая конфигурация не может включить его вместо пользователя. При выключении неотправленные EXTENDED-события удаляются.
- Добавлена минимальная диагностика запуска, crash/ANR предыдущего процесса, разрешений, восстановления режима и полного update funnel.
- Обновления по-прежнему устанавливаются только после явного действия пользователя через системный установщик Android.
- Сервер автоматически агрегирует события, группирует ошибки, применяет TTL, формирует сводки и регрессионные предупреждения для Control Panel/Telegram.
- Старый параллельный `/api/screen-awake-usage` удалён: Full и Lite теперь используют только единый Observability Core.
- Сторонние runtime-библиотеки и telemetry SDK не используются.

## English

- Added the first-party unified Observability Core under GLOBAL-OBS-01…04.
- Full and Lite now use the same ESSENTIAL/EXTENDED model, bounded local queue, privacy allowlist, remote kill switch and HOSTKEY ingest endpoint.
- Added the shared Data and diagnostics screen with ESSENTIAL transparency, an Extended diagnostics toggle and queue/delivery state.
- EXTENDED is Off by default; remote configuration cannot opt a user in. Disabling it removes unsent EXTENDED events.
- Added minimal diagnostics for startup, previous-process crash/ANR, required permissions, recovery and the complete update funnel.
- Update installation still requires an explicit user action through the Android system installer.
- Server-side processing aggregates events, fingerprints errors, applies retention, produces summaries and detects regressions for Control Panel/Telegram.
- The old parallel `/api/screen-awake-usage` transport was removed: Full and Lite now use only the unified Observability Core.
- No third-party runtime libraries or telemetry SDKs are included.
