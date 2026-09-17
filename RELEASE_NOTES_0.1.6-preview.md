# Screen Awake 0.1.6-preview

## RU

- Диагностика стала понятнее для проверки на Samsung/One UI.
- Сохраняется исходный тайм-аут последнего сеанса даже после выключения режима.
- Отдельно показываются последнее включение и последнее выключение режима с фактическим изменением тайм-аута.
- Усилена проверка обновлений: повторные обращения к `latest.json` без кэша уменьшают влияние задержек GitHub Raw.
- Релизный процесс теперь ждёт, пока публичный `latest.json` действительно начнёт отдавать новую версию.
- Новых разрешений, installer-возможностей и сторонних runtime-зависимостей нет.

## EN

- Diagnostics are clearer for Samsung/One UI validation.
- The original timeout from the last session remains visible even after the mode is disabled.
- Last enable and last disable are shown separately with the actual timeout transition.
- Update checks retry the no-cache `latest.json` feed to reduce GitHub Raw propagation-delay false negatives.
- The release pipeline now waits until the public `latest.json` actually exposes the new version.
- No new permissions, installer capabilities, or third-party runtime dependencies.