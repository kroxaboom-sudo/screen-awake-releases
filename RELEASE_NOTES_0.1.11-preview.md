# Screen Awake 0.1.11-preview

## Русский

- Убран REQUEST_INSTALL_PACKAGES и прямой запуск системного установщика из приложения.
- Обновление теперь скачивается и полностью проверяется внутри Screen Awake, после чего проверенный APK сохраняется в системные «Загрузки». Установка начинается только когда пользователь сам выбирает APK в системном файловом менеджере.
- Добавлены пресеты длительности: до отключения, 15/30/60/120 минут и своё время от 1 до 1440 минут.
- Добавлен режим «не выключать экран во время зарядки» с автоматическим возвратом обычного тайм-аута после отключения питания.
- Добавлена защита при низком заряде: 5/10/15/20%.
- Постоянное уведомление показывает длительность/обратный отсчёт и позволяет добавить 30 минут.
- Quick Settings использует выбранный по умолчанию пресет и показывает активный режим.
- Добавлен простой виджет для быстрого включения/выключения.
- Добавлен компактный экран настроек.
- Сохранены единый GLOBAL-OBS Core, двухступенчатая проверка обновлений, Android 13+ и отсутствие сторонних runtime-зависимостей.

## English

- Removed REQUEST_INSTALL_PACKAGES and direct installer launching from the app.
- Updates are downloaded and fully verified inside Screen Awake, then the verified APK is saved to system Downloads. Installation starts only when the user selects the APK in the system file manager.
- Added default duration presets: until disabled, 15/30/60/120 minutes, plus a custom 1–1440 minute duration.
- Added keep-awake-while-charging with automatic timeout restoration after power is disconnected.
- Added low-battery protection at 5/10/15/20%.
- The persistent notification now shows elapsed/countdown state and offers +30 minutes.
- Quick Settings uses the selected default preset and shows the active mode.
- Added a simple home-screen widget for quick toggle.
- Added a compact Settings screen.
- Preserved the unified GLOBAL-OBS Core, update verification, Android 13+ baseline and zero third-party runtime dependencies.
