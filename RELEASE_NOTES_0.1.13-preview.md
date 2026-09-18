# Screen Awake 0.1.13-preview

## Русский

- Исправлен vendor-specific переход к WRITE_SETTINGS на Samsung/Android 16.
- Кнопка «Разрешить и включить» теперь сразу открывает общий системный раздел «Изменение системных настроек» без промежуточного диалога.
- Package-specific переход оставлен только как резервный fallback.
- В «Настройки» добавлен отдельный статус «Изменение системных настроек: Разрешено / Не разрешено» и кнопка «Открыть системное разрешение».
- После выдачи доступа и возврата ожидаемое включение режима продолжается автоматически.
- Сохранены безопасный Downloads-updater, GLOBAL-OBS, таймеры, зарядка, battery guard, виджет и остальные функции.

## English

- Fixed vendor-specific WRITE_SETTINGS navigation on Samsung/Android 16.
- Allow and turn on now opens the general Modify system settings screen directly, without an intermediate dialog.
- Package-specific navigation is retained only as a fallback.
- Settings now includes an explicit Modify system settings: Allowed / Not allowed status and an Open system permission button.
- After permission is granted and the user returns, the pending enable action continues automatically.
- Preserves the safe Downloads updater, GLOBAL-OBS, timers, charging mode, battery guard, widget and all existing features.
