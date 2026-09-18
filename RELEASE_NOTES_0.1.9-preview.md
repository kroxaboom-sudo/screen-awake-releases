# Screen Awake 0.1.9-preview

## RU

- Проект разделён на две независимые редакции: Screen Awake и Screen Awake Lite.
- Основная редакция сохраняет Package ID `com.kroxaboom.screenawake` и обновляется поверх предыдущих версий.
- Общая логика удержания экрана, восстановления тайм-аута, уведомления, Quick Settings и безопасного обновления вынесена в единый собственный Core.
- Статистика, диагностика и анонимная телеметрия остаются только в основной редакции.
- Каналы обновлений Full и Lite разделены и могут развиваться независимо.
- Действия приложения теперь используют applicationId текущей редакции, поэтому Full и Lite могут быть установлены одновременно.
- Сторонние runtime-библиотеки не добавлены.

## EN

- The project is now split into two independently installable editions: Screen Awake and Screen Awake Lite.
- The main edition keeps package ID `com.kroxaboom.screenawake` and updates existing installations normally.
- Screen-awake control, timeout restoration, notification control, Quick Settings and the verified updater now share one first-party Core.
- Statistics, diagnostics and optional anonymous telemetry remain exclusive to the main edition.
- Full and Lite use independent update channels and can evolve separately.
- App actions now use the active edition applicationId, allowing Full and Lite to coexist on one device.
- No third-party runtime libraries were added.
