# Screen Awake Lite 0.1.7-preview

## RU

- Lite получает тот же канонический COMMON-UPDATER-01, что и Full: проверенный APK передаётся Android PackageInstaller.
- До установки проверяются размер, SHA-256, package ID, версия, minSdk и сертификат подписи.
- Разрешение «установка из этого источника» открывается через системный экран Android; финальное подтверждение установки всегда остаётся действием пользователя.
- Автопроверка включена по умолчанию; автоскачивание и автоматический вызов системного подтверждения включаются отдельно.
- Системные «Загрузки» остаются резервным путём.
- Добавлена координация с Full: одновременно системным тайм-аутом владеет только одна редакция, а команды принимаются только от APK с нашей подписью.

## EN

- Lite now uses the same canonical COMMON-UPDATER-01 as Full: a verified APK is handed to Android PackageInstaller.
- Size, SHA-256, package ID, version, minSdk and signing certificate are validated before installation.
- Install-from-this-source permission is handled through Android system settings; final installation confirmation always remains a user action.
- Automatic checks default On; verified auto-download and automatic installer prompting are separate opt-ins.
- System Downloads remains available as a fallback path.
- Full/Lite coordination is included so only one edition owns the system timeout at a time, and commands are accepted only from APKs signed with our certificate.
