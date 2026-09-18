# Screen Awake 0.1.15-preview

## Русский

- Добавлена единая state machine состояния режима: READY / NEEDS_WRITE_SETTINGS / NEEDS_NOTIFICATIONS / ON_INFINITE / ON_TIMER / ON_CHARGING / RECOVERY_REQUIRED.
- Системный тайм-аут больше не используется как источник истины о состоянии Screen Awake.
- Добавлен отдельный «Центр разрешений»: WRITE_SETTINGS, уведомления, состояние QS-плитки и текущее состояние режима.
- Главный экран получил карточку «Готовность» со сводкой обязательных доступов.
- Добавлены редактируемые быстрые пресеты (2–6 значений, 0 = ∞). Они общие для QS-плитки и виджета.
- QS-плитка показывает выбранный пресет в выключенном состоянии, таймер/зарядку в активном и открывает Permission Center при нехватке доступа.
- Добавлен стандартный Android QS Tile Preferences — long-press плитки открывает настройки Screen Awake.
- Виджет расширен: состояние режима, выбранный пресет, отдельные кнопки включения/выключения и переключения пресета.
- Release-gate дополнен отдельным regression-тестом: чистая установка + старый MAX_INT + нет WRITE_SETTINGS/уведомлений → выдача доступа → автоматический старт → восстановление исходного MAX_INT.
- Full и Lite проверены на одновременную установку.
- Stop-on-screen-off намеренно не добавлен: Android не доставляет ACTION_SCREEN_OFF manifest receiver; надёжная фоновая реализация потребовала бы постоянного foreground service и дополнительных разрешений.

## English

- Added a canonical mode state machine: READY / NEEDS_WRITE_SETTINGS / NEEDS_NOTIFICATIONS / ON_INFINITE / ON_TIMER / ON_CHARGING / RECOVERY_REQUIRED.
- The Android screen timeout is no longer treated as the source of truth for Screen Awake state.
- Added a dedicated Permission Center for WRITE_SETTINGS, notifications, Quick Settings tile state and current mode state.
- Added a Readiness card to the main screen.
- Added editable quick presets (2–6 values, 0 = ∞), shared by Quick Settings and the widget.
- Quick Settings now shows the selected preset while idle, timer/charging state while active, and opens Permission Center when access is missing.
- Added standard Android QS Tile Preferences so long-press opens Screen Awake settings.
- Expanded the widget with mode state, selected preset, toggle and next-preset controls.
- Release gate now includes the stale-MAX_INT / missing-permissions state-machine regression.
- Full and Lite coexistence installation was verified.
- Stop-on-screen-off is intentionally not shipped because Android does not deliver ACTION_SCREEN_OFF to manifest receivers; reliable background support would require a persistent foreground service and extra permissions.
