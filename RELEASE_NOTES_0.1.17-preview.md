# Screen Awake 0.1.17-preview

## RU

- Observability переведён на канонический транспорт Skazka: `/v1/observability` и `/v1/observability-policy`.
- Клиент теперь использует заголовок `X-Skazka-Client`; старый `X-Grouple-Client` из APK удалён.
- Release-сборки помечают технические события как `environment=production`.
- Debug/CI-сборки помечают события как `environment=ci`, поэтому сервер исключает их из production-статистики.
- Сохранены ESSENTIAL/EXTENDED правила приватности: ESSENTIAL минимален, EXTENDED остаётся пользовательским opt-in.
- Сервер сохраняет совместимый bridge для уже выпущенных версий Screen Awake, поэтому обновление с 0.1.16 не требует промежуточной сборки.
- Функции режима экрана, Full ↔ Lite coordination и COMMON-UPDATER-01 не изменены.

## EN

- Observability now uses the canonical Skazka transport: `/v1/observability` and `/v1/observability-policy`.
- The client now sends `X-Skazka-Client`; legacy `X-Grouple-Client` is removed from the APK.
- Release builds mark technical events as `environment=production`.
- Debug/CI builds mark events as `environment=ci`, so the server excludes them from production statistics.
- ESSENTIAL/EXTENDED privacy rules are preserved: ESSENTIAL stays minimal and EXTENDED remains a user opt-in.
- The server keeps a compatibility bridge for already released Screen Awake versions, so 0.1.16 can update directly.
- Screen-awake behavior, Full ↔ Lite coordination and COMMON-UPDATER-01 are unchanged.
