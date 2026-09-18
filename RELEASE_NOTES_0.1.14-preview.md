# Screen Awake 0.1.14-preview

## Русский

- Исправлен критический случай после удаления/переустановки: если системный тайм-аут телефона уже остался «Никогда», новая установка больше не считает это активным Screen Awake.
- Активность режима теперь определяется нашим собственным сохранённым состоянием, а не только значением системного тайм-аута.
- При отсутствии WRITE_SETTINGS приложение остаётся открытым и показывает внутренний экран помощи вместо автоматического перехода из приложения.
- В настройках отображается статус специального доступа и пошаговая инструкция.
- Переход в системные настройки выполняется только отдельной кнопкой пользователя.
- Если исходный тайм-аут уже был «Никогда», он сохраняется как исходное пользовательское значение и корректно восстанавливается после выключения режима.
- Сохранены безопасный Downloads-updater без REQUEST_INSTALL_PACKAGES и все функции предыдущих версий.

## English

- Fixed the critical reinstall case where a previously retained Never screen timeout was incorrectly treated as an active Screen Awake session.
- Mode activity is now determined by Screen Awake's own persisted state, not only by the system timeout value.
- When WRITE_SETTINGS is missing, the app stays visible and opens an internal help screen instead of automatically leaving the app.
- Settings shows the special-access state and manual steps.
- System settings are opened only after an explicit separate user action.
- If the original user timeout was already Never, it is preserved as the original value and restored correctly.
- Preserves the safe Downloads updater without REQUEST_INSTALL_PACKAGES and all existing features.
