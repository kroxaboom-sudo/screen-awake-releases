# Screen Awake 0.1.2-preview

## Русский

Исправление удержания экрана на реальных устройствах.

- Убран устаревший экранный wake lock как основной механизм.
- Режим теперь временно выставляет системный тайм-аут экрана в максимальное значение.
- При выключении Screen Awake прежний тайм-аут экрана автоматически восстанавливается.
- При первом включении Android попросит разрешить Screen Awake изменять системные настройки.
- Сохранены управление из постоянного уведомления и встроенное обновление приложения.
- Проверено параллельно на Android 13, 14, 15 и 16.

## English

Reliability fix for real devices.

- Removed the deprecated screen wake lock as the primary keep-awake mechanism.
- Active mode temporarily sets the system screen timeout to the maximum value.
- The previous screen timeout is restored automatically when Screen Awake is turned off.
- Android asks once for permission to let Screen Awake modify system settings.
- Persistent-notification controls and in-app updating remain available.
- Tested in parallel on Android 13, 14, 15, and 16.
