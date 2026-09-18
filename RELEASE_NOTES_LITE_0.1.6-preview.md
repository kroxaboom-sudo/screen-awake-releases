# Screen Awake Lite 0.1.6-preview

## Русский

- Добавлена строгая state machine вместо косвенного определения режима по screen_off_timeout.
- Добавлен «Центр разрешений» с понятными статусами WRITE_SETTINGS, уведомлений, QS-плитки и режима.
- На главном экране появилась карточка «Готовность».
- Быстрые пресеты теперь редактируются: 2–6 значений, 0 означает ∞. Один набор используется QS-плиткой и виджетом.
- QS-плитка показывает выбранный пресет, активный таймер/зарядку и ведёт в Permission Center при нехватке доступа.
- Long-press QS-плитки открывает настройки Screen Awake через стандартный Android Tile Preferences.
- Виджет стал крупнее и функциональнее: состояние, пресет, включение/выключение и «Следующий пресет».
- Добавлен постоянный release regression для чистой установки со старым MAX_INT и отсутствующими разрешениями.
- Lite сохраняет минимальный набор разрешений и не получает foreground service только ради отслеживания блокировки экрана.
- REQUEST_INSTALL_PACKAGES по-прежнему отсутствует.

## English

- Added a strict state machine instead of inferring mode state from screen_off_timeout.
- Added Permission Center with clear WRITE_SETTINGS, notification, QS tile and mode-state statuses.
- Added a Readiness card to the main screen.
- Quick presets are now editable: 2–6 values, with 0 meaning ∞. The same list is shared by Quick Settings and the widget.
- Quick Settings shows the selected preset, active timer/charging state and routes missing access to Permission Center.
- Long-press on the QS tile opens Screen Awake settings through standard Android Tile Preferences.
- The widget is now larger and more useful: state, preset, toggle and next-preset actions.
- Added a permanent stale-MAX_INT / missing-permissions release regression.
- Lite keeps its minimal permission model and does not add a foreground service just to watch screen-lock events.
- REQUEST_INSTALL_PACKAGES remains absent.
