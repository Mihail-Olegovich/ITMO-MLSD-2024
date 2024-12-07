## О проекте
text2sql analytical service - сервис для аналитической платформы, позволяющей сотрудникам компании получать оперативные данные и аналитику на основе запросов на естественном языке. Сервис использует большие языковые модели для генерации SQL-запросов, обработки ошибок и адаптации к контексту беседы. Он поддерживает широкий набор операций, включая фильтрацию, агрегирование, сортировку данных, а также работу с датами и периодами. Проект ориентирован на предоставление точных и персонализированных ответов, с проверкой прав доступа и подбором формата представления данных.

## Использование линтеров
В проекте используются: black, ruff

1.Установка pre-commit:
```bash
   pip install pre-commit
   ```
```bash
   pre-commit install
   ```
2.Проверка файлов
  ```bash
   pre-commit run --all-files
   ```