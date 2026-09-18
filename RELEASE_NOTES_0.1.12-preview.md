# Screen Awake 0.1.12-preview

## Русский

- Исправлено включение режима на реальных Samsung/Android 16, когда приложению ещё не разрешено изменение системных настроек.
- Кнопка больше не выглядит неработающей: при отсутствии WRITE_SETTINGS показывается явный диалог «Нужно разрешение».
- Добавлен устойчивый переход на специальный системный экран разрешения с резервными вариантами для vendor-прошивок.
- После выдачи разрешения и возврата в Screen Awake ожидаемое действие сохраняется и режим включается автоматически.
- Состояние WRITE_SETTINGS повторно проверяется при каждом возврате в приложение и отправляется в ESSENTIAL-диагностику.
- Сохранены безопасный Downloads-updater без REQUEST_INSTALL_PACKAGES и все функции 0.1.11-preview.

## English

- Fixed mode activation on real Samsung/Android 16 devices when Modify system settings has not yet been granted.
- The main button no longer appears unresponsive: a clear Permission required dialog is shown when WRITE_SETTINGS is missing.
- Added a robust special-access Settings handoff with vendor-safe fallbacks.
- The pending action survives activity recreation and automatically continues after permission is granted and the user returns.
- WRITE_SETTINGS state is re-checked on every resume and recorded in ESSENTIAL diagnostics.
- Preserves the safe Downloads updater without REQUEST_INSTALL_PACKAGES and all 0.1.11-preview features.
