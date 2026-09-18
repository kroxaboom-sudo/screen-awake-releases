# Screen Awake Lite 0.1.3-preview

## Русский

- Исправлена кнопка «Включить» на Samsung/Android 16 при отсутствии специального доступа «Изменение системных настроек».
- Теперь вместо ощущения «кнопка не работает» показывается понятный диалог и кнопка «Открыть настройку».
- После выдачи разрешения и возврата Lite автоматически продолжает включение режима.
- Добавлены резервные переходы для прошивок, где прямой экран WRITE_SETTINGS недоступен.
- Статус специального разрешения теперь виден сразу на главном экране.
- Play Protect-совместимый механизм обновления через системные «Загрузки» сохранён; REQUEST_INSTALL_PACKAGES по-прежнему отсутствует.

## English

- Fixed the Turn on button on Samsung/Android 16 when Modify system settings special access is missing.
- A clear permission dialog and Open setting action now replace the previously confusing no-op experience.
- After permission is granted and the user returns, Lite automatically continues enabling the mode.
- Added vendor-safe Settings fallbacks when the direct WRITE_SETTINGS screen is unavailable.
- The special-access state is now visible immediately on the main screen.
- The Play Protect-friendly Downloads update flow remains; REQUEST_INSTALL_PACKAGES is still absent.
