# Screen Awake Lite 0.1.4-preview

## Русский

- Исправлен неоткрывающийся системный экран разрешения на Samsung/Android 16.
- «Разрешить и включить» теперь без промежуточного диалога открывает общий раздел Android «Изменение системных настроек».
- В экран «Настройки» добавлены явный статус разрешения и резервная кнопка «Открыть системное разрешение».
- После выдачи доступа и возврата Lite автоматически продолжает включение режима.
- Package-specific intent используется только как запасной вариант, если общий системный экран недоступен.
- REQUEST_INSTALL_PACKAGES по-прежнему отсутствует; Play Protect-совместимый Downloads-updater сохранён.

## English

- Fixed the system permission screen not opening on Samsung/Android 16.
- Allow and turn on now opens Android's general Modify system settings screen directly, with no intermediate dialog.
- Settings now shows the permission status and provides a dedicated Open system permission fallback button.
- After access is granted and the user returns, Lite automatically continues enabling the mode.
- The package-specific intent is used only as a fallback if the general system screen is unavailable.
- REQUEST_INSTALL_PACKAGES remains absent and the Play Protect-friendly Downloads updater is preserved.
