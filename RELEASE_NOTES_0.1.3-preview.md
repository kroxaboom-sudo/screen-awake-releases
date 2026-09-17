# Screen Awake 0.1.3-preview

## Русский

- Восстановление активного режима и уведомления после перезагрузки телефона.
- Восстановление состояния после обновления приложения поверх установленной версии.
- Автоматическая сверка сохранённого состояния с реальным системным тайм-аутом.
- Плитка Screen Awake для быстрых настроек Android: включение и выключение одним нажатием.
- Кнопка добавления плитки прямо из приложения.
- Убрана зависимость режима от постоянно работающего foreground service: активное состояние хранится в системном тайм-ауте и переживает завершение процесса приложения.
- При выключении восстанавливается исходный тайм-аут экрана.
- Сохранено безопасное обновление из приложения с проверкой SHA-256 и сертификата подписи.
- Проверено параллельно на Android 13, 14, 15 и 16, включая реальную перезагрузку эмуляторов и обновление APK поверх активного режима.

## English

- Restores active mode and its notification after device reboot.
- Restores state after an in-place app update.
- Reconciles persisted state with the real system screen timeout.
- Adds a Screen Awake Quick Settings tile for one-tap on/off control.
- Adds an in-app button for requesting Quick Settings tile placement.
- Removes the need for a continuously running foreground service; the active state is maintained by the system screen timeout and survives app process death.
- Restores the original screen timeout when the mode is disabled.
- Keeps secure in-app updates with SHA-256 and signing-certificate verification.
- Tested in parallel on Android 13, 14, 15, and 16, including real emulator reboots and in-place APK replacement while active.
