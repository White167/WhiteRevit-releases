# WhiteRevit — выпуски

WhiteRevit — форк [RevitCortex](https://github.com/LuDattilo/RevitCortex): MCP-плагин, который даёт Claude работать с моделью Autodesk Revit 2025. Форк доработан под промышленные здания (раздел АР, позже КР/КМ) и русскую локаль Revit.

Здесь лежат только готовые установщики. Исходный код хранится отдельно.

## Установка

1. Откройте [последний выпуск](../../releases/latest) и скачайте `WhiteRevit-Setup-….exe`.
2. Закройте Revit и Claude Desktop (из трея: правый клик → Quit).
3. Запустите установщик. Права администратора и PowerShell не нужны.
4. Запустите Claude Desktop, затем Revit 2025. На вкладке «Надстройки» → панель WhiteRevit нажмите «Cortex Switch».

Что нужно на компьютере: Windows 10/11 (x64), Revit 2025, [Claude Desktop](https://claude.ai/download).

Проверка: в Claude Desktop → Настройки → Developer должен быть сервер `revitcortex` в состоянии «running». В чате попросите «вызови say_hello в Revit».

## Удаление

«Параметры Windows» → «Приложения» → WhiteRevit (Revit 2025) → «Удалить».

## Лицензия

MIT. Основано на RevitCortex © 2026 Luigi Dattilo — см. [LICENSE](LICENSE).
